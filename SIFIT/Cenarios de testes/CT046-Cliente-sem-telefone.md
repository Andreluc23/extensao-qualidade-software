# CT046 - Cliente sem telefone cadastrado

## Objetivo
Verificar como o sistema exibe um cliente que não possui telefone.

## Pré-condições
- Usuário autenticado no SIFIT.
- Cliente cadastrado sem telefone (ex.: 435).

## Passos para execução
1. Acessar o menu Clientes.
2. Clicar no ícone de visualizar do cliente 435 (cadastrado sem telefone).
3. Observar a informação de telefone na tela.

## Resultado esperado
O sistema deve informar que o cliente não possui telefone, sem mostrar textos como "null".

## Resultado obtido
Na visualização do cliente 435 o sistema exibiu corretamente "Sem telefone cadastrado", sem mostrar textos como "null".

## Status
✅ Aprovado.

## Observação
Na tela de visualização o sistema trata bem a falta de telefone. Já na tela de edição de clientes, campos vazios podem aparecer com o texto "null" (ver CT044 e BUG004).

## Bug relacionado
BUG004

## Evidência
[Visualizar gravação no Jam](https://jam.dev/c/163a93a0-ca91-4b05-b60b-0c156dc14d8b)
