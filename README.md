# Lista de Tarefas com Firebase e React

## Descrição

Este projeto é uma aplicação web completa de "Lista de Tarefas" (To-Do List) que permite aos usuários adicionar, ler, atualizar e excluir tarefas (operações CRUD). A aplicação utiliza o Firebase Firestore como base de dados em tempo real, proporcionando uma experiência dinâmica e responsiva ao usuário. O objetivo principal foi demonstrar a integração de um frontend React.js com um backend NoSQL em tempo real.

## Tecnologias Utilizadas

*   **Frontend:** React.js (com JavaScript ES6+)
*   **Backend/Database:** Firebase (Firestore para base de dados em tempo real, Authentication para gerenciamento de usuários - *se implementado*)
*   **Estilização:** CSS3 (ou Tailwind CSS, se utilizado)
*   **Controle de Versão:** Git

## Funcionalidades

*   **Adicionar Tarefa:** Inserir novas tarefas na lista.
*   **Visualizar Tarefas:** Exibir todas as tarefas existentes em tempo real.
*   **Atualizar Tarefa:** Marcar tarefas como concluídas ou editar seu conteúdo.
*   **Excluir Tarefa:** Remover tarefas da lista.
*   **Persistência de Dados:** Todas as alterações são salvas e sincronizadas em tempo real com o Firebase Firestore.

## Como Rodar o Projeto

Instruções passo a passo para configurar e executar o projeto localmente.

### Pré-requisitos

Certifique-se de ter as seguintes ferramentas instaladas:

*   Node.js (versão 14.x ou superior)
*   npm ou Yarn
*   Git

### Instalação

1.  Clone o repositório:
    ```bash
    git clone https://github.com/RenanGomes01/Lista-de-tarefa-.git
    cd Lista-de-tarefa-
    ```
2.  Instale as dependências:
    ```bash
    npm install
    # ou yarn install
    ```
3.  Configure as variáveis de ambiente:
    Crie um arquivo `.env` na raiz do projeto com as seguintes variáveis, obtidas do seu projeto Firebase:
    ```
    REACT_APP_FIREBASE_API_KEY=sua_api_key
    REACT_APP_FIREBASE_AUTH_DOMAIN=seu_auth_domain
    REACT_APP_FIREBASE_PROJECT_ID=seu_project_id
    REACT_APP_FIREBASE_STORAGE_BUCKET=seu_storage_bucket
    REACT_APP_FIREBASE_MESSAGING_SENDER_ID=seu_messaging_sender_id
    REACT_APP_FIREBASE_APP_ID=seu_app_id
    ```

### Execução

Para iniciar o servidor de desenvolvimento:

```bash
npm start
# ou yarn start
