# BUG013 - Valor monetário aparece quebrado em duas linhas

## Módulo

Despesas Fixas

## Objetivo

Documentar falha de formatação visual na coluna de valores monetários da tabela de Despesas Fixas.

## Pré-condições

- Usuário autenticado no sistema SIFIT.
- Existência de registros cadastrados em **Despesas Fixas**.

## Passos para reprodução

1. Navegar até o menu Financeiro > **Despesas Fixas**.
2. Observar a coluna de **Valor** na tabela de listagem em resolução padrão.

## Resultado esperado

O símbolo da moeda (`R$`) e o valor numérico devem ser exibidos juntos na mesma linha (ex.: `R$ 1.500,00`).

## Resultado obtido

O valor monetário sofre quebra de linha, exibindo o `R$` em uma linha e o valor numérico na linha abaixo.

## Status

🔍 Identificado

## Observação

Necessário aplicar `white-space: nowrap;` na célula da coluna de valores.

## Evidência


