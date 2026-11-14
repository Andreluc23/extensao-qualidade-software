# BUG012 - Caixa fechado apresenta data de encerramento futura

## Módulo

Caixas

## Objetivo

Documentar inconsistência cronológica na data de fechamento exibida em registros de Caixas encerrados.

## Pré-condições

- Usuário autenticado no sistema SIFIT.
- Existência de registros de caixas fechados no módulo **Caixas**.

## Passos para reprodução

1. Navegar até o menu Financeiro > **Caixas**.
2. Consultar a listagem ou o histórico de caixas com status **Fechado**.
3. Verificar a coluna/campo **Data de Encerramento**.

## Resultado esperado

A data e hora de encerramento do caixa devem corresponder ao momento real em que o fechamento foi efetuado (data atual ou passada).

## Resultado obtido

O registro de caixa fechado apresenta uma data de encerramento futura.

## Status

🔍 Identificado

## Observação

Possível falha de fuso horário, formatação de data ou preenchimento automático incorreto.

## Evidência

https://sifit.centrion.com.br/dashboard
