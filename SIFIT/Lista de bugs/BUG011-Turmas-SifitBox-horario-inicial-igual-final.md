# BUG011 - Permite cadastrar turmas com horário inicial igual ao final

## Módulo

Turmas SifitBox

## Objetivo

Documentar a ausência de validação lógica de intervalo de tempo no cadastro de turmas do SifitBox.

## Pré-condições

- Usuário autenticado no sistema SIFIT.
- Acesso ao módulo **Turmas SifitBox**.

## Passos para reprodução

1. Navegar até o módulo **SifitBox** > **Turmas**.
2. Iniciar o cadastro de uma nova turma.
3. Preencher os dados da turma informando o mesmo valor para **Horário Inicial** e **Horário Final** (ex.: `08:00` às `08:00`).
4. Clicar em **Salvar**.

## Resultado esperado

O sistema deve validar o intervalo e impedir o cadastro, informando que o horário final deve ser posterior ao horário inicial.

## Resultado obtido

O sistema permite salvar a turma com horário inicial idêntico ao horário final (duração zero).

## Status

🔄 Reproduzido

## Observação

Bug reproduzido; pode gerar conflitos na geração automática de aulas (`CT030`).

## Evidência


