# BUG006 - Nova conta apresenta o status padrão “Recebido” em vez de “Pendente”

## Módulo

Contas a Receber

## Objetivo

Documentar a definição incorreta do status inicial ao criar um novo lançamento em Contas a Receber.

## Pré-condições

- Usuário autenticado no sistema SIFIT com permissão de acesso ao módulo financeiro.
- Acesso à tela de **Contas a Receber**.

## Passos para reprodução

1. Navegar até o menu Financeiro > **Contas a Receber**.
2. Clicar na opção para adicionar/cadastrar uma nova conta a receber.
3. Observar o valor pré-selecionado no campo **Status** antes de salvar.

## Resultado esperado

Ao iniciar o cadastro de uma nova conta a receber, o status padrão deve vir definido como **“Pendente”**.

## Resultado obtido

A nova conta apresenta o status padrão **“Recebido”** em vez de **“Pendente”**.

## Status

🔍 Identificado

## Observação

Risco financeiro operacional: lançamentos futuros podem ser registrados acidentalmente como já quitados.

## Evidência

https://sifit.centrion.com.br/dashboard
