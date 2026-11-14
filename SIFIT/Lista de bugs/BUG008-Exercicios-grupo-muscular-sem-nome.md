# BUG008 - Grupo muscular aparece sem nome no card

## Módulo

Exercícios

## Objetivo

Documentar a ausência de exibição do nome do grupo muscular nos cards do módulo de Exercícios.

## Pré-condições

- Usuário autenticado no sistema SIFIT.
- Existência de exercícios cadastrados na base.

## Passos para reprodução

1. Navegar até o módulo de treinos > **Exercícios**.
2. Visualizar os cards de exercícios exibidos na grade/listagem.
3. Observar a tag ou campo destinado ao **Grupo Muscular** dentro de cada card.

## Resultado esperado

Cada card de exercício deve exibir claramente o nome do grupo muscular associado.

## Resultado obtido

O grupo muscular aparece em branco/sem nome no card do exercício.

## Status

🔍 Identificado

## Observação

Pode estar relacionado ao cadastro de grupos sem nome (`BUG009`) ou falha no mapeamento do atributo no card.

## Evidência


