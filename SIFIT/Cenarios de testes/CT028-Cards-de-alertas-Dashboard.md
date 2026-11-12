# CT028 - Consistência dos cards de alertas do Dashboard

## Objetivo
Verificar se os valores apresentados nos cards de alertas do Dashboard correspondem às informações exibidas ao acessar a funcionalidade "Ver inteligência".

## Pré-condições
- Usuário autenticado no SIFIT.
- Acesso ao módulo Dashboard.
- Indicadores disponíveis na seção Inteligência Sifit.

## Passos para execução
1. Acessar o menu Dashboard.
2. Observar os valores apresentados nos cards de alertas.
3. Clicar no botão "Ver inteligência".
4. Verificar os indicadores apresentados na tela Resultados da Inteligência.
5. Comparar os valores das duas telas.

## Resultado esperado
Os indicadores devem apresentar valores consistentes quando considerados os mesmos períodos e critérios de contagem.

## Resultado obtido
No Dashboard, os cards apresentaram 1 aluno em risco, 9 aniversariantes, 0 avaliações vencendo e 0 alunos com frequência em queda.

Após clicar em "Ver inteligência", a tela de resultados apresentou 1 aluno em risco, 4 aniversariantes, 0 avaliações vencendo e 0 alunos com frequência em queda.

Foi identificada uma divergência na quantidade de aniversariantes, enquanto os demais indicadores comparados apresentaram os mesmos valores.

Entretanto, a tela Resultados da Inteligência estava configurada para "Últimos 7 dias", não sendo possível confirmar se o Dashboard utilizava o mesmo período.

## Status
Inconclusivo — divergência identificada, necessita confirmação dos períodos e critérios de contagem.

## Observação
É necessário verificar se os indicadores das duas telas utilizam os mesmos filtros e regras de negócio antes de classificar a diferença como defeito.

## Evidência
[Visualizar gravação no Jam](https://jam.dev/c/dafddd64-ea87-4fe5-9f01-573d9e5b6229)
