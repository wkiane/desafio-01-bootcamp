# Aplicação desenvolvida para gerenciamento de repositórios

### Packages usados no projeto:

- Express - Para criação da API
- uuidv4 - Para geração de uuid
- Jest - Para testes automatizados
- Nodemon - Para reinicialização automática do servidor a cada mudança

### Rotas

GET `/repositories` listagem de repositórios

POST `/repositories` criação de um novo repositório

PUT `/repositories/:id` atualização de um repositório existente

DELETE `/repositories/:id` apagar um repositório existente

POST `/repositories/:id/like` criação de 1 like em um repositório existente
