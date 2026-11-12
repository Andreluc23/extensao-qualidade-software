# CT026 - Filtro de unidade no Check-in

## Objetivo
Verificar se o sistema SIFIT permite selecionar diferentes unidades e apresentar os registros de check-in correspondentes.

## Pré-condições
- Usuário autenticado no SIFIT.
- Acesso ao módulo Check-in.
- Existência de unidades cadastradas.

## Passos para execução
1. Acessar o módulo Check-in.
2. Localizar o seletor de unidade.
3. Abrir a lista de unidades disponíveis.
4. Selecionar uma unidade diferente da atual.
5. Verificar a unidade selecionada.
6. Observar os indicadores e registros apresentados.

## Resultado esperado
O sistema deve permitir a seleção de uma unidade e apresentar os dados de check-in correspondentes, quando o seletor tiver função de filtragem.

## Resultado obtido
O seletor apresentou três opções: Unidade Centro, Unidade Sul e Unidade Norte.

Após selecionar a Unidade Norte, o nome exibido no seletor foi atualizado corretamente.

Entretanto, o indicador "Check-ins hoje" permaneceu em 7, e os mesmos sete registros continuaram visíveis na listagem.

Não foi possível confirmar se esse comportamento é esperado ou se existe uma falha na filtragem dos dados por unidade.

## Status
Parcialmente aprovado — seleção de unidade funcionando, filtragem dos registros não confirmada.

## Evidência
[Visualizar gravação no Jam](https://jam.dev/c/c6f52fbe-e5e9-4ad5-a0b8-8238e46ed055)
