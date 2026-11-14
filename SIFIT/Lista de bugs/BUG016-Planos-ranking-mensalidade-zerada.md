# BUG016 - Ranking apresenta mensalidade R$ 0,00, diferente dos valores da tabela

## Módulo

Planos

## Objetivo

Documentar a divergência de valores de mensalidade entre o componente de Ranking e a tabela principal de Planos.

## Pré-condições

- Usuário autenticado no sistema SIFIT.
- Existência de planos ativos com valores de mensalidade superiores a R$ 0,00.

## Passos para reprodução

1. Navegar até o menu **Planos**.
2. Observar os valores de mensalidade exibidos na tabela geral de planos.
3. Comparar esses valores com os montantes exibidos na seção/card de **Ranking de Planos**.

## Resultado esperado

Os valores de mensalidade exibidos no Ranking devem refletir fielmente os mesmos valores cadastrados na tabela de planos.

## Resultado obtido

O Ranking exibe todos os planos com mensalidade de `R$ 0,00`, divergindo dos valores reais da tabela.

## Status

🔍 Identificado

## Observação

Falha no cálculo ou no mapeamento da propriedade de preço no componente de ranking.

## Evidência


