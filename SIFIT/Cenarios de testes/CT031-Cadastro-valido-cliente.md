# CT031 - Cadastro válido de cliente

## Objetivo
Verificar se o sistema SIFIT permite cadastrar um cliente com os campos obrigatórios preenchidos com dados válidos.

## Pré-condições
- Usuário autenticado no SIFIT.
- Acesso ao módulo Clientes.
- Dados fictícios preparados para o cadastro.

## Passos para execução
1. Acessar o menu Clientes.
2. Clicar em "Novo Cliente".
3. Preencher os campos Nome, Status, Sexo e Data de Nascimento.
4. Preencher o campo CPF.
5. Clicar em "Cadastrar Cliente".
6. Observar a resposta do sistema.
7. Pesquisar o cliente cadastrado na listagem.

## Resultado esperado
O sistema deve salvar o cadastro, confirmar a operação e apresentar o novo cliente na listagem com os dados informados.

## Resultado obtido
Os campos Nome ("andre"), Status ("Ativo"), Sexo ("Masculino"), Data de Nascimento ("15/02/2002") e CPF foram preenchidos.

Após clicar em "Cadastrar Cliente", o sistema apresentou o estado "Salvando..." e redirecionou para a listagem de clientes, onde o novo registro foi exibido com o código 436.

Na pesquisa pelo nome "andre", o sistema apresentou o cliente com status "Ativo" e plano "Sem Matrícula".

Não foi exibida uma mensagem explícita de confirmação do cadastro.

## Status
Aprovado com ressalva — cadastro realizado e cliente localizado na listagem, sem mensagem de confirmação.

## Observação
O CPF informado (222.222.222-12) possui dígito verificador inválido e foi aceito pelo sistema. O comportamento deverá ser verificado em teste específico de validação de documentos.

As seções intermediárias do formulário não foram exibidas na gravação.

## Evidência
[Visualizar gravação no Jam](https://jam.dev/c/c25634b0-b364-4462-bcff-77962321c209)
