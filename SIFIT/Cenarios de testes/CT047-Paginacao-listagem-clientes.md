# CT047 - Paginação da listagem de clientes

## Objetivo
Verificar se a paginação da listagem respeita a quantidade de registros e os filtros.

## Pré-condições
- Usuário autenticado no SIFIT.
- Acesso ao módulo Clientes.

## Passos para execução
1. Acessar o menu Clientes (filtro padrão Status "Ativo", 50 por página).
2. Observar a quantidade de páginas exibidas abaixo da tabela.
3. Clicar na página 2.

## Resultado esperado
A quantidade de páginas deve corresponder ao número de registros filtrados.

## Resultado obtido
O filtro "Ativo" retorna 22 clientes, que cabem em uma página de 50, mas a paginação mostra 3 páginas. A página 2 fica vazia e sem mensagem. O mesmo acontece na busca por nome (2 resultados, 3 páginas).

## Status
❌ Reprovado.

## Observação
A lista abre com o filtro Status "Ativo" e 50 registros por página. Como existem só cerca de 21 a 22 clientes ativos (ver card "Clientes Ativos"), tudo deveria caber em 1 página. Mesmo assim aparecem os botões 1, 2 e 3, e a página 2 fica vazia. Isso indica que o sistema calcula a quantidade de páginas pelo total geral de clientes (cerca de 143), e não pelo resultado do filtro. Na gravação, mostre o card de ativos, o seletor "50" e depois clique na página 2 vazia.

## Evidência
[Visualizar gravação no Jam](https://jam.dev/c/549b85d4-62df-4de0-a675-9911eab6f72a)
