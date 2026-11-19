# CT045 - Visualização de cliente

## Objetivo
Verificar se a tela de visualização exibe corretamente os dados do cliente.

## Pré-condições
- Usuário autenticado no SIFIT.
- Cliente cadastrado (ex.: 434).

## Passos para execução
1. Acessar o menu Clientes.
2. Clicar no ícone de visualizar do cliente 434.
3. Conferir nome, idade, data de nascimento, telefone, matrícula e situação financeira.

## Resultado esperado
A tela deve mostrar os dados reais do cliente.

## Resultado obtido
Nome, idade, data de nascimento e telefone foram exibidos corretamente. Porém, o bloco "Objetivos" mostra dados prontos ("Perda de peso e ganho de resistência", progresso 60% e "Evolução positiva") em um cliente recém-cadastrado, e a Situação financeira mostra "Em dia" junto com "Última conta R$ 0,00 - Pendente".

## Status
⚠️ Aprovado com ressalva.

## Observação
A tela de visualização mostra os dados reais do cliente (nome, idade, nascimento, telefone), mas também mostra informações que nunca foram cadastradas: o bloco "Objetivos" aparece com texto fixo, 60% de progresso e "Evolução positiva" em um cliente novo. Além disso, a Situação financeira diz "Em dia" e logo abaixo mostra "Última conta R$ 0,00 - Pendente", o que é contraditório. Por isso o status é aprovado com ressalva: a tela funciona, mas exibe dados falsos ou incoerentes.

## Evidência
[Visualizar gravação no Jam](https://jam.dev/c/c6d29544-b3a9-4c43-bc2b-1d7089820113)
