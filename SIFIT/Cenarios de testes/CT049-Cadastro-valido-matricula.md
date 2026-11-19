# CT049 - Cadastro válido de matrícula

## Objetivo
Verificar se o sistema permite cadastrar uma matrícula com dados válidos.

## Pré-condições
- Usuário autenticado no SIFIT.
- Acesso ao módulo Matrículas.
- Cliente ativo cadastrado (ex.: 434 - QA Felipe Cadastro Valido).

## Passos para execução
1. Acessar Matrículas > "Cadastrar Matrícula" e selecionar um cliente sem matrícula pela lupa.
2. Escolher a modalidade "Treino Livre", Tipo Pagamento "Pix", Dia Vencimento "10" e preencher a Taxa Matrícula; clicar em "Salvar" e depois em "Escolher".
3. Na pergunta de pagamento, clicar em "Cancelar".

## Resultado esperado
A matrícula deve ser salva e o sistema deve voltar à listagem sem erros.

## Resultado obtido
A matrícula foi salva (mensagem "Matrícula salva!"). Ao clicar em "Cancelar" na pergunta de pagamento com a Taxa Matrícula preenchida, o sistema exibiu "Erro no servidor - Erro interno inesperado." e a janela "Quantidade Parcelas" ficou travada na tela. Na gravação, o Jam registrou que a requisição que cria a conta a receber (cadastrar-conta-receber) falhou com erro HTTP 400, o que explica a cobrança não ser gerada. O erro é reproduzido sempre que a Taxa Matrícula é preenchida. Sem a taxa, o cancelamento funcionou na execução gravada.

Também foi observado que a janela "Quantidade Parcelas" exibe a data no formato americano (ex.: 11/19/2026), diferente do restante do sistema (dia/mês/ano).

## Status
⚠️ Aprovado com ressalva.

## Observação
O cadastro da matrícula funciona, mas o passo final gera erro de servidor ao recusar o pagamento da primeira parcela. O erro está ligado ao preenchimento da Taxa Matrícula: com a taxa ele acontece sempre. Quando o erro acontece, o cliente fica com "Última conta R$ 0,00" mesmo com o plano de R$ 52,00, indicando que a cobrança não foi gerada corretamente. A data da parcela em formato americano também pode confundir o usuário (19/11 aparece como 11/19).

## Evidência
[Visualizar gravação no Jam](https://jam.dev/c/86c45c49-8a78-40a5-81cf-7cacb6ed0c44)
