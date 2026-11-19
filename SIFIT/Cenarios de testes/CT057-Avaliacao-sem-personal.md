# CT057 - Avaliação sem personal

## Objetivo
Verificar se o sistema impede salvar uma avaliação sem personal responsável.

## Pré-condições
- Usuário autenticado no SIFIT.
- Acesso ao módulo Avaliações.
- Cliente cadastrado (ex.: 434 - QA Felipe Cadastro Valido).

## Passos para execução
1. Acessar Avaliações > "Cadastrar Avaliação".
2. Selecionar o aluno 434 pela lupa e manter o personal como "Selecione".
3. Clicar em "Salvar".

## Resultado esperado
O sistema deve impedir o cadastro e pedir a seleção do personal.

## Resultado obtido
O sistema exibiu o aviso "Selecione o personal responsável." e não salvou.

## Status
✅ Aprovado.

## Evidência
[Visualizar gravação no Jam](https://jam.dev/c/2f070379-b643-4fbe-825a-5bf8f20601db)
