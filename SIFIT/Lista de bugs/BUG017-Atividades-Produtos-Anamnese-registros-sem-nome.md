# BUG017 - Registros ativos aparecem sem nome, indicando possível ausência de validação

## Módulo

Atividades / Produtos / Anamnese

## Objetivo

Documentar a existência de registros ativos sem identificação (nome em branco) nos módulos de Atividades, Produtos e Anamnese.

## Pré-condições

- Usuário autenticado no sistema SIFIT.
- Acesso aos módulos **Atividades**, **Produtos** e **Anamnese**.

## Passos para reprodução

1. Acessar sequencialmente os menus **Atividades**, **Produtos** e **Anamnese**.
2. Verificar a listagem de registros com status **Ativo**.
3. Tentar salvar um novo registro deixando o campo **Nome** em branco.

## Resultado esperado

Todos os registros ativos devem possuir um nome válido, e o sistema deve impedir o cadastro de itens sem nome.

## Resultado obtido

Existem registros ativos exibidos sem nome nas listagens, indicando ausência de validação de campo obrigatório no cadastro.

## Status

🔍 Identificado

## Observação

Problema recorrente em múltiplos cadastros auxiliares do sistema.

## Evidência


