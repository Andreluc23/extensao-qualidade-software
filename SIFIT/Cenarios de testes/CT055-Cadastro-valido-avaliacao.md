# CT055 - Cadastro válido de avaliação

## Objetivo
Verificar se o sistema permite agendar uma avaliação com dados válidos.

## Pré-condições
- Usuário autenticado no SIFIT.
- Acesso ao módulo Avaliações.
- Cliente cadastrado (ex.: 434 - QA Felipe Cadastro Valido).

## Passos para execução
1. Acessar Avaliações > "Cadastrar Avaliação" e selecionar o aluno 434 pela lupa.
2. Selecionar um personal e informar a hora "10:00".
3. Clicar em "Salvar" e conferir a avaliação na listagem.

## Resultado esperado
A avaliação deve ser salva com status Pendente e aparecer na listagem.

## Resultado obtido
A avaliação foi criada e apareceu na listagem com status "Pendente", com a data de hoje, hora 10:00 e o personal selecionado. Na gravação, o Jam registrou a resposta 201 (criado) do servidor ao salvar.

## Status
✅ Aprovado.

## Evidência
[Visualizar gravação no Jam](https://jam.dev/c/0bd60a7a-ca21-4d0e-8600-66d41767c4b8)
