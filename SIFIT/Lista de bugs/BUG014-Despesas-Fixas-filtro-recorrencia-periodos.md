# BUG014 - Filtro de recorrência não contempla períodos personalizados cadastrados

## Módulo

Despesas Fixas

## Objetivo

Documentar a limitação do filtro de recorrência que omite períodos personalizados cadastrados pelo usuário.

## Pré-condições

- Usuário autenticado no sistema SIFIT.
- Existência de despesas fixas cadastradas com períodos de recorrência personalizados.

## Passos para reprodução

1. Navegar até o menu Financeiro > **Despesas Fixas**.
2. Abrir o seletor/dropdown do **Filtro de Recorrência**.
3. Verificar as opções disponíveis para filtragem.

## Resultado esperado

O filtro deve listar dinamicamente todos os tipos e períodos de recorrência cadastrados no sistema, incluindo os personalizados.

## Resultado obtido

O filtro exibe apenas opções fixas padrão e não contempla os períodos personalizados cadastrados.

## Status

🔍 Identificado

## Observação

Impede a filtragem eficiente de despesas com ciclos customizados.

## Evidência

https://sifit.centrion.com.br/dashboard
