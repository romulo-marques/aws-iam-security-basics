# Projeto 01: Gestão de Identidade e Acesso (AWS IAM)

Este projeto demonstra as melhores práticas de segurança e controle de acesso na nuvem da AWS utilizando o AWS Identity and Access Management (IAM).

## 🚀 Tecnologias e Conceitos Utilizados
* **AWS IAM:** Gerenciamento centralizado de usuários, grupos e permissões
* **Príncipe do Menor Privilégio (Least Privilege):** Concessão apenas das permissões estritamente necessárias
* **AWS Managed Policies:** Aplicação de políticas nativas da AWS (`AdministratorAccess`, `PowerUserAccess`, etc.)
* **Segurança da Conta Root:** Ativação de MFA (Autenticação Multi-fator) e criação de usuários administrativos dedicados

## 🛠️ Passos Executados

1. **Proteção da Conta Root:** Configurado o MFA (Autenticação de Múltiplos Fatores) na conta raiz para garantir a máxima segurança da infraestrutura.
2. **Criação de Grupos de Acesso:**
   * Criado o grupo `Administradores` com a política `AdministratorAccess`.
3. **Criação e Gestão de Usuários:**
   * Criado o usuário individual de trabalho (`rmarques`) com acesso ao Console de Gerenciamento da AWS.
   * Associado o usuário ao grupo de administradores.
4. **Governança e Boas Práticas:**
   * Bloqueado o uso cotidiano da conta Root, realizando todas as operações diárias através do usuário IAM dedicado.
## 📸 Evidências de Execução

### 1. Configuração do Usuário IAM e Políticas de Acesso
<img width="954" height="504" alt="image" src="https://github.com/user-attachments/assets/f4bc55aa-8b59-4631-ac49-88df52277591" />


### 2. Autenticação Multi-fator (MFA) Ativada
