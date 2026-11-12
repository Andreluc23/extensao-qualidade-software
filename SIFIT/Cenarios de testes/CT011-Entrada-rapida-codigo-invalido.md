# CT011 - Entrada rápida com código inválido

## Objetivo
Verificar se o SIFIT impede o check-in quando um código de cliente inválido é informado.

## Pré-condições
- Usuário autenticado no SIFIT.
- Acesso ao módulo Check-in.

## Passos para execução
1. Acessar Check-in.
2. Localizar a funcionalidade "Entrada rápida".
3. Informar um código de cliente inexistente.
4. Confirmar a tentativa de entrada.
5. Observar a resposta do sistema.

## Resultado esperado
O sistema deve rejeitar o código inválido, apresentar uma mensagem de erro e impedir o registro da entrada.

## Resultado obtido
O sistema apresentou uma mensagem de erro e não registrou a entrada com o código inválido.

## Status
Aprovado.

## Evidência
[Visualizar gravação no Jam](https://jam.dev/c/60eb9dfe-40c2-41c6-b2a2-9476563489b3)
