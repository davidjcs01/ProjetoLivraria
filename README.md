### API RESTful para Livraria com MVC e Autenticação

## Descrição do Sistema
API para gerenciar usuários e livros, desenvolvida com Node.js, Express e PostgreSQL, seguindo a arquitetura MVC:
- Controllers: Gerenciam requisições HTTP.
- Models: Representam os dados.
- Services: Contêm a lógica de negócios.
- Helpers: Incluem funções auxiliares, como validação e hashing de senhas.

## Funcionalidades
- Autenticação de Usuário
- Registro e login de usuários com validação e hashing de senhas.
- Gerenciamento de Livros
- Cadastro e listagem de livros (título, autor, preço).
- Gerenciamento de Usuários
- Cadastro e listagem de usuários com validação de dados.

## Requisitos Funcionais:
- Rotas organizadas para autenticação, livros e usuários.

## Não Funcionais:
- Segurança: Hashing de senhas e suporte a HTTPS.
- Desempenho: Respostas rápidas e escaláveis.
- Confiabilidade: Tratamento de erros e registro de logs.
- Manutenibilidade: Código modular e testável.

# Rotas
- Autenticação (/auth)
- POST /register: Cria um usuário.
- POST /login: Realiza login.
- Livros (/livros)
- GET /livros: Lista todos os livros.
-POST /livros: Adiciona um novo livro.
- Usuários (/users)
- GET /users: Lista todos os usuários.
- POST /users: Adiciona um novo usuário.

# Tecnologias
- Express: Framework web.
- pg: Conexão com PostgreSQL.
- crypto: Hashing de senhas.
- dotenv: Gerenciamento de variáveis de ambiente.
- Uma API segura, modular e preparada para expansão e testes automatizados.