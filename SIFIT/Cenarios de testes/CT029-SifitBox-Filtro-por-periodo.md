# CT029 - Filtro por período no SifitBox

## Objetivo
Verificar se o sistema SIFIT permite filtrar as aulas do módulo SifitBox conforme o período selecionado.

## Pré-condições
- Usuário autenticado no SIFIT.
- Acesso ao módulo SifitBox.
- Existência de aulas cadastradas em diferentes datas.

## Passos para execução
1. Acessar o menu SifitBox.
2. Observar as aulas apresentadas inicialmente.
3. Alterar as datas nos campos de período.
4. Clicar no botão "Buscar".
5. Verificar os registros apresentados.
6. Repetir o procedimento utilizando outro período.

## Resultado esperado
O sistema deve atualizar a listagem de aulas conforme o período informado, apresentando os registros correspondentes às datas selecionadas.

## Resultado obtido
Durante o teste, foi possível alterar as datas dos filtros e realizar novas buscas.

A listagem apresentou inicialmente cinco registros. Após a alteração do período, foram exibidos três registros. Em outra seleção de datas, a listagem passou a apresentar seis registros.

O sistema respondeu às alterações realizadas, atualizando a quantidade de aulas apresentadas conforme os filtros utilizados.

## Status
Aprovado — filtro por período funcionando.

## Observação
A gravação demonstrou a atualização da listagem após as alterações dos períodos. Entretanto, não foi realizada uma conferência independente da totalidade das aulas cadastradas em cada intervalo.

## Evidência
[Visualizar gravação no Jam](https://jam.dev/c/167d8b77-4507-4290-89f9-873e8eeb3094)
