# BUG003 - Nome muito longo quebra o layout da tabela

## Módulo

Clientes

## Objetivo

Documentar a quebra de responsividade e alinhamento na tabela de listagem de clientes ao exibir nomes extensos.

## Pré-condições

- Usuário autenticado no sistema SIFIT.
- Existência de ao menos um cliente cadastrado com nome completo muito extenso.

## Passos para reprodução

1. Acessar o menu **Clientes**.
2. Localizar ou cadastrar um cliente com um nome muito longo (sem espaços ou com muitos caracteres).
3. Observar a renderização das colunas e linhas da tabela de listagem.

## Resultado esperado

O texto longo deve ser truncado com reticências (`...`) ou sofrer quebra de linha controlada (`word-wrap`), mantendo o alinhamento e a estrutura da tabela intactos.

## Resultado obtido

O nome extenso ultrapassa os limites da célula e quebra o layout da tabela.

## Status

🔍 Identificado

## Observação

Necessário aplicar regras CSS adequadas de truncamento ou quebra de texto na coluna de nome.

## Evidência

https://sifit.centrion.com.br/dashboard
