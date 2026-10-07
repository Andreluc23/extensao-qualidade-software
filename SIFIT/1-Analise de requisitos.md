
# 1 - Análise de Requisitos

## 1. Sistema analisado

**Sistema:** SIFIT - Gestão de Academias

## 2. Objetivo

Realizar o levantamento das principais funcionalidades do sistema SIFIT, identificando os requisitos funcionais que servirão como base para a elaboração e execução dos casos de teste.

A análise foi realizada por meio da navegação e observação das funcionalidades disponíveis no sistema.

---

## 3. Funcionalidades identificadas

### 3.1 Autenticação

A tela de acesso ao sistema apresenta:

- Campo Login
- Campo Senha
- Opção "Manter conectado"
- Opção "Esqueci minha senha"
- Botão "Entrar"

### 3.2 Página Inicial

Após realizar o login, o usuário é direcionado para a página inicial do sistema.

A página apresenta informações gerais da academia, como:

- Clientes ativos
- Clientes ausentes
- Alunos em risco de evasão
- Matrículas
- Desistências
- Renovações
- Mensalidades pendentes
- Avaliações pendentes
- Quantidade de profissionais
- Agenda do dia
- Inteligência de retenção

Também é possível selecionar um período para visualização das informações.

### 3.3 Módulos disponíveis

Durante a navegação inicial foram identificados os seguintes módulos no menu:

**Principal**
- Página Inicial
- Dashboard
- Check-in
- Presenças
- SifitBox

**Operação da Academia**
- Clientes
- Matrículas
- Avaliações
- Contas a Receber
- Contas a Pagar

**Treinamento**
- Ficha de Treino
- Exercícios
- Grupos Musculares
- Objetivos Treino
- Grupos
- Turmas

---

## 4. Requisitos Funcionais

### RF001 - Autenticação de usuário

O sistema deve permitir que o usuário realize login informando suas credenciais de acesso.

### RF002 - Validação de credenciais

O sistema deve validar o login e a senha informados antes de permitir o acesso.

### RF003 - Manter usuário conectado

O sistema deve disponibilizar a opção "Manter conectado" na tela de autenticação.

### RF004 - Recuperação de senha

O sistema deve disponibilizar a opção "Esqueci minha senha" para recuperação do acesso.

### RF005 - Acesso à página inicial

Após uma autenticação válida, o sistema deve direcionar o usuário para a página inicial.

### RF006 - Exibição do resumo da academia

A página inicial deve apresentar informações resumidas relacionadas à situação e movimentação da academia.

### RF007 - Seleção de período

O sistema deve permitir selecionar um período para consulta das informações apresentadas na página inicial.

### RF008 - Navegação entre módulos

O sistema deve disponibilizar um menu para acesso aos diferentes módulos e funcionalidades disponíveis ao usuário.

---

## 5. Observações

Os requisitos apresentados neste documento foram identificados por meio da observação e navegação no sistema SIFIT.

O documento poderá ser atualizado conforme novas funcionalidades forem analisadas durante a execução do projeto.
