# CT019 - Tentativa de check-in duplicado

## Objetivo
Verificar o comportamento do SIFIT quando um cliente que já realizou check-in tenta registrar outra entrada.

## Pré-condições
- Usuário autenticado no SIFIT.
- Cliente de teste com entrada já registrada.
- Acesso ao módulo Check-in.

## Passos para execução
1. Acessar o módulo Check-in.
2. Localizar um cliente que já realizou check-in.
3. Clicar em "+ Check-in manual".
4. Selecionar o mesmo cliente.
5. Tentar registrar uma segunda entrada.
6. Observar a resposta do sistema.

## Resultado esperado
O sistema deve controlar as entradas consecutivas conforme suas regras de negócio, evitando registros duplicados indevidos.

## Resultado obtido
O sistema permitiu selecionar um cliente que já possuía entrada registrada e apresentou a mensagem "Cliente liberado para realizar o check-in".

Após a tentativa de registrar novamente, o sistema aceitou a segunda entrada.

Não foi verificado se foram criados dois registros distintos no histórico.

## Status
Falha potencial — necessita confirmação da regra de negócio e do histórico de registros.

## Evidência
[Visualizar gravação no Jam](https://jam.dev/c/8f02c311-40b8-4434-8fcf-29500affb009)
