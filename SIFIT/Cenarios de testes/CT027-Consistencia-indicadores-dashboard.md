# CT027 - Consistência dos indicadores do Dashboard

## Objetivo
Verificar a apresentação dos indicadores e gráficos do Dashboard, identificando possíveis inconsistências nas informações exibidas.

## Pré-condições
- Usuário autenticado no SIFIT.
- Acesso ao módulo Dashboard.

## Passos para execução
1. Acessar o menu Dashboard.
2. Observar o título apresentado na página.
3. Verificar os indicadores da seção Inteligência Sifit.
4. Consultar os gráficos de clientes e matrículas.
5. Percorrer as demais seções do Dashboard.
6. Observar possíveis inconsistências nas informações apresentadas.

## Resultado esperado
O Dashboard deve apresentar seus indicadores e gráficos corretamente, com identificação adequada da página e informações coerentes com os dados do sistema.

## Resultado obtido
Os indicadores e gráficos foram apresentados durante a navegação.

Entretanto, a página identificada como Dashboard no menu lateral e acessada pelo endereço /dash apresentou o título "Despesas Fixas".

Essa inconsistência de identificação já havia sido registrada no levantamento de bugs como BUG001.

Não foi possível confirmar a precisão dos valores dos indicadores sem compará-los com os respectivos dados de origem.

## Status
Parcialmente aprovado — gráficos exibidos, mas falha identificada no título da página. Consistência numérica não verificada.

## Bug relacionado
BUG001 - Dashboard apresenta o título "Despesas Fixas".

## Evidência
[Visualizar gravação no Jam](https://jam.dev/c/e8682026-0cff-4eec-a319-cdb472184af8)
