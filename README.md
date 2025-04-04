# Desafio Full Stack: Todo List com React, Node.js e TypeScript

## Visão Geral

Este desafio consiste em desenvolver uma aplicação completa de Lista de Tarefas (Todo List) com frontend em React e backend em Node.js, utilizando TypeScript. O objetivo é avaliar suas habilidades técnicas, organização de código, aplicação de boas práticas e conhecimentos em desenvolvimento full stack.


## Requisitos Funcionais

### Frontend (React + TypeScript)
- Interface para visualizar, adicionar, editar, excluir e marcar tarefas como concluídas
- Filtros para visualizar todas as tarefas, apenas as ativas ou apenas as concluídas
- Contador de tarefas pendentes
- Formulário para adicionar novas tarefas
- Integração com a API do backend

### Backend (Node.js + TypeScript)
- API RESTful para gerenciar tarefas (CRUD)
- Persistência de dados em banco de dados
- Validação de dados
- Tratamento de erros

## Requisitos Técnicos

### Obrigatórios
- Utilizar TypeScript tanto no frontend quanto no backend
- Implementar todas as funcionalidades básicas da Todo List
- Integração completa entre frontend e backend
- Documentação clara de como executar o projeto

### Diferenciais
- Aplicação de princípios SOLID
- Utilização de Design Patterns
- Organização de código em camadas (controllers, services, repositories)
- Containerização com Docker e Docker Compose
- Implementação de CI/CD
- Testes unitários e/ou de integração

## Estrutura Sugerida

### Frontend

```bash
frontend/
├── src/
│ ├── components/ # Componentes React
│ ├── hooks/ # Custom hooks
│ ├── services/ # Serviços de API
│ ├── types/ # Definições de tipos TypeScript
│ ├── utils/ # Funções utilitárias
│ ├── App.tsx # Componente principal
│ └── index.tsx # Ponto de entrada
├── package.json
└── tsconfig.json
```

### Backend

```bash
backend/
├── src/
│ ├── controllers/ # Controladores da API
│ ├── services/ # Lógica de negócio
│ ├── repositories/ # Acesso ao banco de dados
│ ├── models/ # Modelos de dados
│ ├── routes/ # Rotas da API
│ ├── types/ # Definições de tipos TypeScript
│ └── server.ts # Ponto de entrada
├── package.json
└── tsconfig.json
```

## Banco de Dados

Recomendamos o uso do MySQL, mas você pode escolher o banco de dados de sua preferência. 

## Entrega

- Código fonte em um repositório Git (GitHub, GitLab, etc.)
- Instruções claras de como executar o projeto
- Documentação da API (pode ser um arquivo README ou Swagger/OpenAPI)
- Se implementar Docker, incluir os arquivos Dockerfile e docker-compose.yml

## Critérios de Avaliação

- Funcionalidade completa da aplicação
- Qualidade e organização do código
- Uso correto de TypeScript (tipagem adequada)
- Aplicação de princípios SOLID e padrões de projeto
- Documentação
- Extras implementados (Docker, CI/CD, testes, etc.)

## API Sugerida

### Endpoints

- `GET /api/todos` - Listar todas as tarefas
- `GET /api/todos/:id` - Obter uma tarefa específica
- `POST /api/todos` - Criar uma nova tarefa
- `PUT /api/todos/:id` - Atualizar uma tarefa existente
- `DELETE /api/todos/:id` - Excluir uma tarefa

## Dicas

- Comece pelo básico e adicione funcionalidades extras conforme o tempo permitir
- Priorize a qualidade do código e a organização sobre a quantidade de funcionalidades
- Documente suas decisões técnicas
- Trate adequadamente os erros tanto no frontend quanto no backend
- Utilize bibliotecas e frameworks que você já conhece para economizar tempo

Boa sorte! Estamos ansiosos para ver sua solução.