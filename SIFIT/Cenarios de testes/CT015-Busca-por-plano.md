# CT015 - Busca por plano no Check-in

## Objetivo
Verificar se o sistema SIFIT permite filtrar os registros de check-in pelo nome do plano do cliente.

## Pré-condições
- Usuário autenticado no SIFIT.
- Acesso ao módulo Check-in.
- Existência de registros associados a planos.

## Passos para execução
1. Acessar o menu Check-in.
2. Localizar o campo de pesquisa da listagem.
3. Informar parte do nome de um plano cadastrado.
4. Verificar os resultados apresentados.
5. Limpar o campo de pesquisa.
6. Verificar se a listagem original é restaurada.

## Resultado esperado
O sistema deve apresentar somente os registros correspondentes ao plano pesquisado e restaurar a listagem ao limpar a pesquisa.

## Resultado obtido
Ao pesquisar pelo termo "plano di", o sistema apresentou apenas o registro associado ao Plano Diário. Após limpar o campo, os três registros anteriores voltaram a aparecer na listagem.

## Status
Aprovado.

## Evidência
[Visualizar gravação no Jam](https://jam.dev/c/25275108-029e-4ed4-9f8f-039b461a4761)
