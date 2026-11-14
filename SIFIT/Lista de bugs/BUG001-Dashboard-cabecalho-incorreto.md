# BUG001 - Cabeçalho apresenta “Despesas Fixas” em vez de “Dashboard”

## Módulo

Dashboard

## Objetivo

Documentar a inconsistência visual no título do cabeçalho exibido ao acessar a tela principal (Dashboard) do sistema SIFIT.

## Pré-condições

- Usuário autenticado no sistema SIFIT com credenciais válidas.
- Sistema SIFIT disponível para acesso (`https://sifit.centrion.com.br/dashboard`).

## Passos para reprodução

1. Acessar a página de login do SIFIT e realizar autenticação.
2. Aguardar o redirecionamento automático para a página inicial (Dashboard) ou clicar no menu lateral **Dashboard**.
3. Observar o título exibido no cabeçalho superior da página.

## Resultado esperado

O cabeçalho da página inicial deve exibir o título **“Dashboard”**, correspondendo à seção ativa no menu.

## Resultado obtido

O cabeçalho da página apresenta incorretamente o texto **“Despesas Fixas”** em vez de **“Dashboard”**.

## Status

🔍 Identificado

## Observação

Falha de rotulagem/interface que pode gerar confusão de navegação para o usuário.

## Evidência

https://sifit.centrion.com.br/dash
