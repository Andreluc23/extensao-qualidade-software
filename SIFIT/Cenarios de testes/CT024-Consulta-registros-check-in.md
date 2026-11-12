# CT024 - Consulta dos registros de entrada

## Objetivo
Verificar a apresentação e a consistência das informações dos registros de check-in, especialmente os horários de entrada e seus respectivos status.

## Pré-condições
- Usuário autenticado no SIFIT.
- Acesso ao módulo Check-in.
- Existência de registros de entrada.

## Passos para execução
1. Acessar o menu Check-in.
2. Selecionar a aba "Todos".
3. Observar os registros e suas informações.
4. Comparar os horários de entrada com os status apresentados.
5. Pesquisar um cliente pelo nome.
6. Conferir as informações do registro filtrado.

## Resultado esperado
O sistema deve apresentar informações coerentes sobre os registros de entrada, incluindo horários e status correspondentes à situação de cada check-in.

## Resultado obtido
A listagem apresentou sete registros com horários preenchidos na coluna "Entrada", porém todos estavam identificados com status "Pendente".

Ao pesquisar pelo termo "car", o sistema filtrou corretamente a listagem, apresentando o registro correspondente. Esse registro também possuía horário de entrada preenchido e status "Pendente".

O botão "Registrar entrada" permanecia disponível.

## Status
Pendente de validação da regra de negócio — possível inconsistência entre entrada registrada e status.

## Evidência
[Visualizar gravação no Jam](https://jam.dev/c/c79f2a60-24d0-4ec4-bcc3-00668d9ea884)
