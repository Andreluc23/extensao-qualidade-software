# BUG009 - Sistema permite cadastrar grupo sem nome e sem tipo de membro

## Módulo

Grupos Musculares

## Objetivo

Documentar a falha de validação de campos obrigatórios no cadastro de Grupos Musculares.

## Pré-condições

- Usuário autenticado no sistema SIFIT.
- Acesso ao formulário de cadastro em **Grupos Musculares**.

## Passos para reprodução

1. Navegar até o menu **Grupos Musculares**.
2. Clicar no botão para cadastrar um novo grupo muscular.
3. Deixar os campos **Nome** e **Tipo de Membro** vazios.
4. Clicar no botão **Salvar**.

## Resultado esperado

O sistema deve bloquear o salvamento e exibir mensagens alertando que os campos Nome e Tipo de Membro são obrigatórios.

## Resultado obtido

O sistema aceita a submissão e cadastra o grupo muscular sem nome e sem tipo de membro.

## Status

🔄 Reproduzido

## Observação

Bug reproduzido com sucesso; gera registros vazios que afetam outros módulos como Exercícios (`BUG008`).

## Evidência


