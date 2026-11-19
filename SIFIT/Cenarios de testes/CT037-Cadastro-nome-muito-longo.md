# CT037 - Cadastro de cliente com nome muito longo

## Objetivo
Verificar como o sistema trata um nome acima do tamanho esperado.

## Pré-condições
- Usuário autenticado no SIFIT.
- Acesso ao módulo Clientes.

## Passos para execução
1. Acessar Clientes > "Novo Cliente".
2. Informar um Nome com 160 caracteres e preencher Status, Sexo e Data de Nascimento.
3. Clicar em "Cadastrar Cliente".

## Resultado esperado
O campo deve limitar a quantidade de caracteres ou o sistema deve informar o tamanho máximo permitido.

## Resultado obtido
O campo aceitou os 160 caracteres sem limite. Ao salvar, o sistema bloqueou o cadastro, mas exibiu apenas "Erro ao criar cliente.", sem informar qual é o limite do nome. Na gravação, o Jam registrou que o servidor respondeu com erro HTTP 500 na requisição de cadastro.

## Status
⚠️ Aprovado com ressalva.

## Observação
O sistema até impede salvar, mas a mensagem "Erro ao criar cliente." é genérica: o usuário não sabe que o problema é o tamanho do nome. O ideal seria o campo ter um limite de caracteres ou uma mensagem como "O nome pode ter no máximo X caracteres".

## Bug relacionado
BUG003

## Evidência
[Visualizar gravação no Jam](https://jam.dev/c/90b09303-8679-4611-b9bb-b8746ffe3f66)
