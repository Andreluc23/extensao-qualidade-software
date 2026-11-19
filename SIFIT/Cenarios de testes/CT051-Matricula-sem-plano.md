# CT051 - Matrícula sem plano

## Objetivo
Verificar se o sistema impede salvar uma matrícula sem plano.

## Pré-condições
- Usuário autenticado no SIFIT.
- Acesso ao módulo Matrículas.
- Cliente ativo cadastrado (ex.: 434 - QA Felipe Cadastro Valido).

## Passos para execução
1. Acessar Matrículas > "Cadastrar Matrícula".
2. Selecionar o cliente pela lupa e deixar o campo "Modalidade" vazio.
3. Clicar em "Salvar".

## Resultado esperado
O sistema deve impedir o cadastro e informar que é necessário escolher um plano.

## Resultado obtido
O campo "Modalidade" inicia vazio. Ao clicar em "Salvar" sem escolher um plano, o sistema impediu o cadastro e exibiu a mensagem "Selecione o Plano" abaixo do campo.

## Status
✅ Aprovado.

## Observação
A validação funciona. Como detalhe de usabilidade, a lista de planos não tem uma opção "Selecione" no topo: o campo aparece em branco, mas ao abrir a lista só existem planos. Ter a opção "Selecione" deixaria mais claro que o campo é obrigatório.

## Evidência
[Visualizar gravação no Jam](https://jam.dev/c/7031e68d-3eb0-48d8-897c-e56793fd8682)
