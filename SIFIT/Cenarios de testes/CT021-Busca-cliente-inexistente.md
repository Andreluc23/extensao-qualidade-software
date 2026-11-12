# CT021 - Busca por cliente inexistente no Check-in

## Objetivo
Verificar se o sistema SIFIT identifica uma pesquisa sem resultados e impede o registro de entrada de um cliente inexistente.

## Pré-condições
- Usuário autenticado no SIFIT.
- Acesso ao módulo Check-in.

## Passos para execução
1. Acessar o menu Check-in.
2. Clicar em "+ Check-in manual".
3. Manter a aba "Cliente existente".
4. Informar um nome que não corresponda a nenhum cliente cadastrado.
5. Observar o resultado da pesquisa.
6. Verificar se o botão "Registrar entrada" permanece desabilitado.

## Resultado esperado
O sistema deve informar que nenhum cliente foi encontrado e impedir a realização do check-in.

## Resultado obtido
Ao pesquisar um nome inexistente, o sistema apresentou a mensagem "Nenhum cliente encontrado", acompanhada de uma orientação para buscar por nome completo, código ou CPF.

O botão "Registrar entrada" permaneceu desabilitado, impedindo o registro.

## Status
Aprovado.

## Evidência
[Visualizar gravação no Jam](https://jam.dev/c/4db7c9f6-76eb-4fe8-992e-1887cc23a0bd)
