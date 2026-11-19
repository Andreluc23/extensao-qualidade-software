# CT058 - Filtro de avaliações por status

## Objetivo
Verificar se o filtro de status exibe apenas avaliações com o status escolhido.

## Pré-condições
- Usuário autenticado no SIFIT.
- Acesso ao módulo Avaliações.

## Passos para execução
1. Acessar o menu Avaliações.
2. Selecionar Status "Realizado".
3. Conferir a coluna Status da listagem.

## Resultado esperado
A listagem deve mostrar apenas avaliações com o status escolhido.

## Resultado obtido
Com "Realizado" foram exibidas somente avaliações realizadas (o filtro já é aplicado ao trocar a opção). Observação: algumas avaliações antigas aparecem com datas suspeitas, como 01/01/1970 00:00 (#42) e 02/01/1980 (#25).

## Status
✅ Aprovado.

## Observação
O filtro funciona. A observação é que algumas avaliações antigas aparecem com datas como 01/01/1970 00:00, que é o valor que sistemas costumam gravar quando a data fica vazia. Isso indica que em algum momento foi possível salvar avaliação sem data.

## Evidência
[Visualizar gravação no Jam](https://jam.dev/c/17438640-319f-4382-b523-e33fe6f6c0e9)
