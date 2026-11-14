# BUG010 - Após excluir um grupo, a tabela e os indicadores não atualizam automaticamente

## Módulo

Grupos Musculares

## Objetivo

Documentar a falha de atualização reativa da interface após a exclusão de um registro em Grupos Musculares.

## Pré-condições

- Usuário autenticado no sistema SIFIT.
- Existência de ao menos um registro cadastrado em **Grupos Musculares**.

## Passos para reprodução

1. Navegar até o menu **Grupos Musculares**.
2. Observar a quantidade total nos cards de indicadores e os itens na tabela.
3. Clicar na opção de **Excluir** em um dos grupos listados e confirmar a ação.
4. Observar a tabela e os indicadores sem recarregar a página manualmente.

## Resultado esperado

Imediatamente após a confirmação da exclusão, o item deve ser removido da tabela e os contadores/indicadores devem ser atualizados automaticamente.

## Resultado obtido

A tabela e os indicadores permanecem exibindo os dados antigos até que o usuário atualize a página manualmente (F5).

## Status

🔄 Reproduzido

## Observação

Bug reproduzido; indica ausência de re-renderização de estado após requisição DELETE.

## Evidência

https://sifit.centrion.com.br/dashboard
