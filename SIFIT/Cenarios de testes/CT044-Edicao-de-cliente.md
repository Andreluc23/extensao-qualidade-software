# CT044 - Edição de cliente

## Objetivo
Verificar se o sistema permite alterar os dados de um cliente.

## Pré-condições
- Usuário autenticado no SIFIT.
- Cliente cadastrado (ex.: 432).

## Passos para execução
1. Acessar Clientes e abrir a visualização do cliente 432.
2. Clicar em "Alterar dados" e mudar o nome para "QA Felipe Teste Editado".
3. Clicar em "Salvar Alterações" e conferir o nome na listagem.

## Resultado esperado
Os dados devem ser atualizados e exibidos corretamente.

## Resultado obtido
O nome do cliente 432 foi alterado (para "QA Felipe Teste Editado 3") e aparece atualizado na listagem. Ressalvas: não apareceu mensagem de confirmação, e na tela de edição um campo que foi deixado vazio no cadastro aparece preenchido com o texto "null" (confirmado na gravação), mesmo problema do BUG004.

## Status
⚠️ Aprovado com ressalva.

## Observação
A edição funciona. As ressalvas são: não aparece mensagem de "alterado com sucesso", e na tela de edição alguns campos que foram deixados vazios no cadastro aparecem preenchidos (provavelmente com o texto "null", mesmo problema do BUG004). Se quiser reforçar na gravação, role a tela de edição até esses campos antes de salvar.

## Bug relacionado
BUG004

## Evidência
[Visualizar gravação no Jam](https://jam.dev/c/b6094846-cd08-4c86-814c-7f856eed0acd)
