# CT043 - Opções em branco no campo Tipo Pagamento

## Objetivo
Verificar se a lista de tipos de pagamento da matrícula exibe apenas opções válidas.

## Pré-condições
- Usuário autenticado no SIFIT.
- Acesso ao módulo Matrículas.

## Passos para execução
1. Acessar o menu Matrículas.
2. Clicar em "Cadastrar Matrícula".
3. Abrir a lista do campo "Tipo Pagamento".

## Resultado esperado
A lista deve exibir apenas tipos de pagamento com nome.

## Resultado obtido
A lista exibe 3 opções em branco (sem nome) entre os tipos de pagamento, que podem ser selecionadas pelo usuário.

## Status
❌ Reprovado.

## Observação
Opções em branco não deveriam existir numa lista de seleção. Se o atendente escolher uma delas sem querer, a matrícula fica salva com um tipo de pagamento sem nome, o que atrapalha relatórios e o controle financeiro.

## Evidência
[Visualizar gravação no Jam](https://jam.dev/c/f6cc1d59-8ccb-4fb0-8007-d8c51161a66f)
