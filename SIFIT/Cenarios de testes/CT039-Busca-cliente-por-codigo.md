# CT039 - Busca de cliente por código

## Objetivo
Verificar se a busca por código retorna o cliente correspondente e trata corretamente um código que não existe.

## Pré-condições
- Usuário autenticado no SIFIT.
- Acesso ao módulo Clientes.

## Passos para execução
1. Acessar o menu Clientes, digitar "434" no campo Código e clicar em "Buscar".
2. Trocar o código para "99999" (código inexistente) e clicar em "Buscar".
3. Observar a mensagem exibida.

## Resultado esperado
Com o código 434 o sistema deve exibir o cliente correspondente. Com um código inexistente deve mostrar a lista vazia ou uma mensagem como "Nenhum cliente encontrado".

## Resultado obtido
Com o código 434 o sistema exibiu corretamente o cliente "QA Felipe Cadastro Valido". Com o código inexistente 99999 o sistema exibiu o erro "Erro no servidor - Erro interno inesperado.", em vez de informar que nenhum cliente foi encontrado. Na gravação, o Jam registrou resposta HTTP 500 do servidor na busca pelo código inexistente.

## Status
❌ Reprovado.

## Observação
A busca por código funciona quando o código existe. O problema é o tratamento do código inexistente: em vez de mostrar a lista vazia ou "Nenhum cliente encontrado", o sistema mostra um erro de servidor, como se o sistema tivesse quebrado. Na gravação, deixe a mensagem "Erro no servidor" visível por alguns segundos.

## Evidência
[Visualizar gravação no Jam](https://jam.dev/c/a90067b5-e355-46a5-b924-1e30966ac7ed)
