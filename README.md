# 🏦 Creador Bank

## 📜 Descrição
**Creador Bank** é uma aplicação de banco digital desenvolvida com Spring Boot e containerizada com Docker. O projeto oferece funcionalidades de gestão de contas, transferências e pagamentos, com segurança robusta utilizando OAuth2 e JWT.

## 🎯 Objetivo
Criar uma plataforma de banco digital que permita aos usuários realizar diversas operações financeiras de forma segura e eficiente.

## 🚀 Funcionalidades
- 📑 **Autenticação e Registro:** Usuários podem se registrar e fazer login. Autenticação segura com tokens JWT.
- 🏦 **Abertura de Conta:** Permitir que os usuários abram contas bancárias digitais. Verificação de identidade e documentos.
- 💰 **Gestão de Contas:** Visualização de saldo e histórico de transações. Gerenciamento de múltiplas contas bancárias.
- 💸 **Transferências e Pagamentos:** Transferências de dinheiro entre contas. Pagamento de contas e boletos. Integração com PIX para pagamentos instantâneos.
- 💳 **Gestão de Cartões:** Solicitação e gerenciamento de cartões de débito e crédito. Configuração de limites e bloqueio de cartões.
- 🔔 **Notificações e Alertas:** Envio de notificações sobre transações e atividades suspeitas. Alertas para contas com saldo baixo e vencimento de faturas.
- 🔒 **Segurança:** Implementação de autenticação multifator (MFA). Criptografia de dados sensíveis.

## 🛠️ Tecnologias Utilizadas
- **Backend:**
  - Spring Boot
  - Spring Data JPA
  - Spring Security
  - OAuth2 Resource Server
  - MySQL/PostgreSQL

- **Frontend:**
  - React.js
  - Redux
  - Material-UI

- **Segurança:**
  - JWT (JSON Web Token)
  - Spring Security OAuth2
  - Criptografia de dados
  - Autenticação multifator (MFA)

- **Infraestrutura:**
  - Docker
  - Docker Compose

## 🏗️ Configuração do Projeto

### 📦 Dependências
As dependências do projeto estão listadas no arquivo `pom.xml`.

### 🔧 Configurações
Configure as variáveis de ambiente no arquivo `application.properties`.

### 🏃‍♂️ Construção e Execução

1. **Construir a Imagem Docker:**
   ```sh
   docker build -t creador-bank:latest .
