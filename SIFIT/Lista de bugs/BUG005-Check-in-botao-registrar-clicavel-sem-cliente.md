# BUG005 - Botão “Registrar entrada” continua clicável sem selecionar um cliente

## Módulo

Check-in

## Objetivo

Verificar e documentar o comportamento do botão “Registrar entrada” no módulo de Check-in quando nenhum cliente está selecionado.

## Pré-condições

- Usuário autenticado no sistema SIFIT.
- Acesso à tela do módulo **Check-in**.

## Passos para reprodução

1. Acessar o menu **Check-in**.
2. Certificar-se de que nenhum cliente foi buscado ou selecionado no formulário de entrada.
3. Observar o estado visual e funcional do botão **“Registrar entrada”** e clicar sobre ele.

## Resultado esperado

O botão **“Registrar entrada”** deve permanecer desabilitado (`disabled`) enquanto nenhum cliente válido estiver selecionado, ou exibir imediatamente um alerta orientando a seleção.

## Resultado obtido

O botão **“Registrar entrada”** permanece habilitado e clicável mesmo sem nenhum cliente selecionado.

## Status

⚠️ A verificar

## Observação

Relacionado ao cenário de teste `CT007-Check-in-sem-cliente.md`. Necessário confirmar o impacto da requisição disparada ao clicar.

## Evidência

https://jam.dev/c/5a05f61f-4988-454f-a054-34d74fdec8bd
