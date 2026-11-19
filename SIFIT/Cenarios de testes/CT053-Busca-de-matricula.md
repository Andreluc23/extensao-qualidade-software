# CT053 - Busca de aluno no cadastro de matrícula

## Objetivo
Verificar se a busca de aluno pelo nome, na tela de cadastro de matrícula, retorna os clientes correspondentes.

## Pré-condições
- Usuário autenticado no SIFIT.
- Acesso ao módulo Matrículas.
- Clientes cadastrados com o nome "QA Felipe".

## Passos para execução
1. Acessar Matrículas > "Cadastrar Matrícula" e clicar na lupa ao lado do campo Nome.
2. Digitar "qa fe" no campo Pesquisa e clicar no botão de pesquisar.
3. Conferir os resultados e clicar em "Selecionar" em um deles.

## Resultado esperado
O sistema deve listar apenas os clientes cujo nome contém o texto pesquisado e permitir selecionar um deles.

## Resultado obtido
A busca retornou apenas os clientes "QA Felipe" (432 - QA Felipe Teste Editado 3 e 434 - QA Felipe Cadastro Valido). Ao clicar em "Selecionar", o código e o nome do cliente foram preenchidos no formulário da matrícula.

## Status
✅ Aprovado.

## Evidência
[Visualizar gravação no Jam](https://jam.dev/c/5e9ed0ed-d55d-4b3f-b076-1f4bd1dc7eed)
