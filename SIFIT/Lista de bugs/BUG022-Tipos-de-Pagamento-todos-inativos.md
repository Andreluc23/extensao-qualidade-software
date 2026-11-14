# BUG022 - Todos os 15 tipos de pagamento estão inativos

## Módulo

Tipos de Pagamento

## Objetivo

Documentar e confirmar o motivo de todos os 15 tipos de pagamento cadastrados constarem como inativos no ambiente.

## Pré-condições

- Usuário autenticado no sistema SIFIT.
- Acesso ao módulo **Tipos de Pagamento**.

## Passos para reprodução

1. Navegar até o menu Financeiro/Configurações > **Tipos de Pagamento**.
2. Verificar o status de cada um dos 15 registros listados.

## Resultado esperado

Os tipos de pagamento padrão utilizados pela academia (ex.: Dinheiro, Pix, Cartão de Crédito/Débito) devem estar ativos ou devidamente configuráveis.

## Resultado obtido

Todos os 15 tipos de pagamento listados encontram-se com status **Inativo**.

## Status

⚠️ A confirmar

## Observação

Status *A confirmar* — necessário verificar se é uma configuração intencional do ambiente de testes ou um bug na carga inicial/listagem de status.

## Evidência

https://sifit.centrion.com.br/dashboard
