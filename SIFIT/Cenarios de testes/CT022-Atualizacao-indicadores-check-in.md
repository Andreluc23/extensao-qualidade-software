# CT022 - Atualização dos indicadores após check-in

## Objetivo
Verificar se os indicadores do módulo Check-in são atualizados após o registro de uma nova entrada.

## Pré-condições
- Usuário autenticado no SIFIT.
- Acesso ao módulo Check-in.
- Cliente cadastrado disponível para realizar o teste.

## Passos para execução
1. Acessar o menu Check-in.
2. Observar o valor do indicador "Check-ins hoje".
3. Clicar em "+ Check-in manual".
4. Pesquisar e selecionar um cliente.
5. Registrar a entrada.
6. Verificar se o indicador foi atualizado.

## Resultado esperado
O sistema deve atualizar o indicador "Check-ins hoje" após o registro de uma nova entrada, refletindo a quantidade correta de check-ins realizados.

## Resultado obtido
Antes do registro, o indicador "Check-ins hoje" apresentava 6 entradas.

Após realizar um novo check-in, o indicador foi atualizado automaticamente para 7 entradas. O novo registro também apareceu na listagem.

Os demais indicadores não apresentaram alterações perceptíveis durante a gravação.

## Status
Aprovado — atualização do indicador "Check-ins hoje".

## Evidência
[Visualizar gravação no Jam](https://jam.dev/c/b51b08fc-43e4-4b2a-9f35-c238cd2dd817)
