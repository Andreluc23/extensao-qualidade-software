# CT020 - Check-in de cliente inativo

## Objetivo
Verificar como o sistema SIFIT se comporta ao tentar realizar o check-in de um cliente com cadastro inativo.

## Pré-condições
- Usuário autenticado no SIFIT.
- Acesso ao módulo Check-in.
- Cliente cadastrado com status Inativo.

## Passos para execução
1. Acessar o módulo Clientes.
2. Identificar um cliente com status Inativo.
3. Acessar Check-in.
4. Clicar em "+ Check-in manual".
5. Pesquisar o cliente inativo.
6. Observar o resultado da pesquisa.

## Resultado esperado
O sistema deve respeitar as regras de acesso para clientes inativos, impedindo entradas não autorizadas.

## Resultado obtido
Ao pesquisar o cliente inativo, o sistema apresentou a mensagem "Nenhum cliente encontrado", impedindo a seleção e a realização do check-in.

Não foi possível confirmar se a ausência do cliente na pesquisa é uma regra de negócio intencional.

## Status
Inconclusivo — registro não realizado, mas regra de negócio não confirmada.

## Evidência
[Visualizar gravação no Jam](https://jam.dev/c/8b352915-f30f-4eef-b3cb-50b85223ff99)
