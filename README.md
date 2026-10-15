# Movieflix API

API REST de gerenciamento de filmes desenvolvida como projeto de estudo durante o curso [DevQuest, da Dev em Dobro](https://devquest.curseduca.pro/).

O projeto tem como objetivo praticar conceitos de desenvolvimento back-end, incluindo criação e gerenciamento de banco de dados, operações CRUD, validação de dados e documentação de endpoints.

## Tecnologias

- Node.js
- Express
- TypeScript
- JavaScript
- PostgreSQL
- Prisma
- Docker
- Swagger
- pgAdmin
- DBeaver
- Prettier
- JSON

## Funcionalidades

- Criação e utilização de banco de dados.
- Listagem e ordenação de filmes.
- Relacionamentos entre dados.
- Cadastro de filmes.
- Validação de títulos duplicados.
- Atualização e remoção de filmes.
- Filtragem de filmes.
- Documentação da API com Swagger.

## Instalação

### Pré-requisitos

Antes de começar, você precisará ter o Git, o Node.js e o npm instalados. Também será necessário configurar o PostgreSQL ou o ambiente de banco de dados utilizado pelo projeto.

### 1. Clone o repositório

```bash
git clone https://github.com/arthurscdev/movieflix-api.git
```

### 2. Entre na pasta do projeto

```bash
cd movieflix-api
```

### 3. Instale as dependências

```bash
npm install
```

### 4. Configure o ambiente

Configure as variáveis de ambiente necessárias para a conexão com o banco de dados, conforme a configuração do projeto. Não publique credenciais ou senhas reais.

### 5. Execute a aplicação

```bash
npm run dev
```

#### Outros comandos

```
npm run build
npm start
npm run format
```

npm run build: compila o código TypeScript.

npm start: inicia a aplicação compilada.

npm run format: formata os arquivos TypeScript de src.

## Documentação da API

O Movieflix API utiliza Swagger UI para documentar seus endpoints, facilitando a visualização e a consulta das rotas disponíveis.

Com o servidor em execução, acesse a documentação pelo caminho /docs, utilizando a porta configurada na aplicação.

Exemplo de acesso local: http://localhost:3000/docs.

## Créditos

Projeto desenvolvido como parte dos estudos de back-end no curso [DevQuest, da Dev em Dobro](https://devquest.curseduca.pro/).
