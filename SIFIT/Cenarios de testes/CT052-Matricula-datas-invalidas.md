# CT052 - Datas inválidas na matrícula

## Objetivo
Verificar se o sistema impede datas inválidas na matrícula.

## Pré-condições
- Usuário autenticado no SIFIT.
- Acesso ao módulo Matrículas.
- Cliente ativo cadastrado (ex.: 434 - QA Felipe Cadastro Valido).

## Passos para execução
1. Acessar Matrículas > "Cadastrar Matrícula".
2. Tentar digitar uma data ou texto nos campos "Data Inicial" e "Data Final".
3. Selecionar o cliente e um plano e observar o campo "Data Final".

## Resultado esperado
O sistema não deve aceitar datas inválidas.

## Resultado obtido
Os campos de data não aceitam digitação: ao clicar, abre um calendário e só é possível escolher dias existentes, então não há como informar uma data inválida (ex.: 31/02). Ao selecionar o plano, o sistema preencheu a Data Final automaticamente (ex.: plano "Aba" com início 18/11/2026 gerou Data Final 18/12/2026).

## Status
✅ Aprovado.

## Observação
O uso de calendário é uma boa forma de evitar datas inválidas. Além disso, o sistema calcula a Data Final sozinho a partir da duração do plano, o que evita erro de digitação do atendente.

## Evidência
[Visualizar gravação no Jam](https://jam.dev/c/b31c99c9-ddd3-4b12-9e54-132efe4c8e77)
