# BUG021 - Campo “Dias para contar cliente como ausente” apresenta valor negativo (-120)

## Módulo

Configurações

## Objetivo

Documentar a presença de valor negativo inválido (`-120`) em parâmetro numérico de configuração de ausência.

## Pré-condições

- Usuário autenticado no sistema SIFIT com perfil administrativo.
- Acesso ao menu **Configurações**.

## Passos para reprodução

1. Navegar até o menu **Configurações**.
2. Localizar o campo **“Dias para contar cliente como ausente”**.
3. Observar o valor preenchido e tentar salvar valores negativos no campo.

## Resultado esperado

O campo deve aceitar apenas números inteiros positivos maiores que zero (`> 0`) e exibir um valor padrão válido.

## Resultado obtido

O campo apresenta o valor negativo `-120`, o que distorce a regra de cálculo de clientes ausentes no Dashboard.

## Status

🔍 Identificado

## Observação

Falta validação de valor mínimo (`min="1"`) no input e no backend.

## Evidência

https://sifit.centrion.com.br/dashboard
