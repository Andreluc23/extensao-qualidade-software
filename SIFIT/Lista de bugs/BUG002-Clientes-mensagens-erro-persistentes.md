# BUG002 - Mensagens de erro continuam aparecendo mesmo após corrigir os campos

## Módulo

Clientes

## Objetivo

Documentar a falha na validação reativa do formulário de cadastro/edição de clientes, onde alertas de erro permanecem visíveis após a correção.

## Pré-condições

- Usuário autenticado no sistema SIFIT.
- Acesso ao formulário de cadastro ou edição no módulo **Clientes**.

## Passos para reprodução

1. Navegar até o menu **Clientes** e abrir o formulário de cadastro/edição.
2. Submeter o formulário ou sair de campos obrigatórios sem preenchê-los para disparar as mensagens de validação.
3. Preencher corretamente os campos que apresentaram erro.
4. Observar o comportamento das mensagens de alerta na tela.

## Resultado esperado

As mensagens de erro de validação devem desaparecer automaticamente assim que os respectivos campos forem preenchidos com dados válidos.

## Resultado obtido

As mensagens de erro continuam sendo exibidas na interface mesmo após a correção dos campos.

## Status

🔍 Identificado

## Observação

Prejudica a experiência do usuário (UX), dando a falsa impressão de que o formulário ainda contém pendências.

## Evidência

https://sifit.centrion.com.br/dashboard
