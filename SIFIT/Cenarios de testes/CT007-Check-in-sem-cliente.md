# CT007 - Check-in sem selecionar cliente

## Objetivo
Verificar se o sistema impede a realização de um check-in manual sem selecionar um cliente.

## Pré-condições
- Usuário autenticado no SIFIT.
- Acesso ao módulo Check-in.

## Passos para execução
1. Acessar o menu Check-in.
2. Clicar em "+ Check-in manual".
3. Manter a aba "Cliente existente".
4. Não selecionar nenhum cliente.
5. Verificar se é possível acionar o botão "Registrar entrada".

## Resultado esperado
O sistema deve impedir o registro de entrada sem um cliente selecionado.

## Resultado obtido
O botão "Registrar entrada" permaneceu desabilitado enquanto nenhum cliente estava selecionado, impedindo a realização do check-in.

## Status
✅ Aprovado.

## Evidência
[Visualizar gravação no Jam](https://jam.dev/c/a80dbdbf-67b3-4b9e-ba0f-156f516a7482)
