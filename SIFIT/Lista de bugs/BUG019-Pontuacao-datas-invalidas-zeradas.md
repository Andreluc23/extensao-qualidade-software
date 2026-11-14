# BUG019 - Registros ativos apresentam datas inválidas 0000-00-00

## Módulo

Pontuação

## Objetivo

Documentar a exibição de datas não formatadas/zeradas (`0000-00-00`) em registros ativos do módulo de Pontuação.

## Pré-condições

- Usuário autenticado no sistema SIFIT.
- Existência de registros ativos no módulo **Pontuação**.

## Passos para reprodução

1. Navegar até o menu **Pontuação**.
2. Analisar as colunas de data nos registros ativos exibidos na tabela.

## Resultado esperado

As datas devem ser exibidas no padrão brasileiro válido (`DD/MM/AAAA`) ou, caso não existam, apresentar um indicador vazio (`-`).

## Resultado obtido

Os registros ativos apresentam a string de data inválida `0000-00-00`.

## Status

🔍 Identificado

## Observação

Valor padrão de campo `DATE` vazio do MySQL sendo renderizado diretamente sem tratamento no frontend.

## Evidência


