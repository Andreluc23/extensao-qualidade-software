# BUG007 - Contas com status “PAGO” apresentam valor pago de R$ 0,00

## Módulo

Contas a Pagar

## Objetivo

Documentar a inconsistência financeira onde registros marcados como “PAGO” exibem valor pago igual a R$ 0,00.

## Pré-condições

- Usuário autenticado no sistema SIFIT.
- Existência de registros quitados no módulo **Contas a Pagar**.

## Passos para reprodução

1. Navegar até o menu Financeiro > **Contas a Pagar**.
2. Filtrar ou localizar contas que estejam com o status **“PAGO”**.
3. Comparar a coluna de status com a coluna de **Valor Pago**.

## Resultado esperado

Contas com status **“PAGO”** devem exibir o montante efetivamente quitado correspondente ao valor da despesa.

## Resultado obtido

As contas com status **“PAGO”** apresentam o valor pago zerado (`R$ 0,00`).

## Status

🔍 Identificado

## Observação

Impacta diretamente a confiabilidade dos relatórios e indicadores de fluxo de caixa.

## Evidência

https://sifit.centrion.com.br/dashboard
