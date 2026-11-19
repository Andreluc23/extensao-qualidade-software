# CT060 - Visualização/atualização de avaliação

## Objetivo
Verificar se é possível alterar a data e a hora de uma avaliação pendente.

## Pré-condições
- Usuário autenticado no SIFIT.
- Avaliação pendente cadastrada (ex.: #99).

## Passos para execução
1. Acessar Avaliações e clicar no ícone de lápis da avaliação #99.
2. Informar Nova Data "19/11/2026" e Nova Hora "14:00".
3. Clicar em "Salvar".

## Resultado esperado
A avaliação deve ser atualizada com a nova data e hora, ou o sistema deve informar o que está faltando.

## Resultado obtido
A janela "Alterar Data / Hora" abriu normalmente. Foram informadas nova data (20/11/2026) e nova hora (12:00) e o botão "Salvar" foi clicado várias vezes, mas nada aconteceu: a janela continuou aberta e nenhuma mensagem foi exibida. Na gravação, o Jam mostra que nenhuma requisição foi enviada ao servidor ao clicar em "Salvar", ou seja, o botão não executa nenhuma ação.

## Status
❌ Reprovado.

## Observação
A janela de alteração abre, mas o botão "Salvar" não faz nada: não salva, não fecha a janela e não mostra nenhuma mensagem explicando o que está faltando. Para o usuário parece que o sistema travou. Na gravação, depois de clicar em Salvar, espere alguns segundos para mostrar que nada muda.

## Evidência
[Visualizar gravação no Jam](https://jam.dev/c/b5249430-15b8-4aa1-ade0-1d190154933e)
