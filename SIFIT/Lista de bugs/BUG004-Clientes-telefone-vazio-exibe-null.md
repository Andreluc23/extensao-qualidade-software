# BUG004 - Campo de telefone vazio apresenta o texto null

## Módulo

Clientes

## Objetivo

Documentar a exibição literal da string `null` quando um cliente não possui telefone cadastrado.

## Pré-condições

- Usuário autenticado no sistema SIFIT.
- Existência de cliente cadastrado sem número de telefone informado.

## Passos para reprodução

1. Acessar o menu **Clientes**.
2. Cadastrar um novo cliente deixando o campo **Telefone** em branco (ou editar um cadastro existente removendo o telefone).
3. Visualizar o registro na listagem ou nos detalhes do cliente.

## Resultado esperado

Quando não houver telefone cadastrado, o campo deve ser exibido em branco, com traço (`-`) ou com o texto informativo “Não informado”.

## Resultado obtido

O sistema exibe literalmente o texto `null` no campo de telefone.

## Status

🔍 Identificado

## Observação

Tratamento ausente de valores nulos vindos da API/banco de dados na camada de visualização.

## Evidência

https://jam.dev/c/d2336900-1858-4b82-9cfd-caa300413848
