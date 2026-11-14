# BUG020 - Enquetes ativas aparecem sem perguntas cadastradas

## Módulo

Enquetes

## Objetivo

Documentar a inconsistência de regra de negócio onde enquetes sem perguntas vinculadas permanecem com status Ativo.

## Pré-condições

- Usuário autenticado no sistema SIFIT.
- Acesso ao módulo **Enquetes**.

## Passos para reprodução

1. Navegar até o menu **Enquetes**.
2. Verificar os registros listados com status **Ativo**.
3. Abrir os detalhes ou visualizar a quantidade de perguntas vinculadas a essas enquetes.

## Resultado esperado

O sistema não deve permitir ativar ou manter ativa uma enquete que não possua ao menos uma pergunta cadastrada.

## Resultado obtido

Existem enquetes marcadas como ativas sem nenhuma pergunta cadastrada.

## Status

🔍 Identificado

## Observação

Pode causar telas vazias ou erros para os alunos que tentarem responder à enquete.

## Evidência

https://sifit.centrion.com.br/dashboard
