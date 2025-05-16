// Você está trabalhando em um projeto NestJS para um sistema de blog com suporte a CRUD de postagens e comentários, incluindo tags.
// Este projeto usa o TypeORM para manipulação de banco de dados e validação com class-validator.
// Estruture os módulos e implemente as seguintes funcionalidades:

// 1. Módulo de Postagens (Posts):
// - Criação de entidade Post com campos: id (UUID, PK), title (string, único), content (texto), tags (array de strings), createdAt e updatedAt (datas automáticas).
// - Implementação de DTOs para criação e atualização de postagens.
// - CRUD completo com validação de dados e mapeamento de endpoints RESTful.
// - Suporte a filtros de listagem (ex.: por título, data, ou tags) usando Query Builder do TypeORM.

// 2. Módulo de Comentários (Comments):
// - Criação de entidade Comment com campos: id (UUID, PK), content (texto), author (string), createdAt (data automática), postId (FK para Post).
// - DTOs para criação de comentários.
// - Rotas para adicionar, listar, editar e excluir comentários relacionados a postagens específicas.

// 3. Relacionamento entre entidades:
// - Configurar relacionamento um-para-muitos entre Post e Comment no banco de dados.
// - Atualizar controladores para incluir os comentários de uma postagem ao listá-la.

// 4. Middleware de Logs:
// - Criar um middleware global para registrar logs de cada requisição (rota acessada, método HTTP, e tempo de execução).

// Use melhores práticas do NestJS, como:
// - Separação de responsabilidades com módulos, serviços, e controladores.
// - Utilização de Pipes e Guards quando necessário.
// - Configuração de erros customizados para melhorar a experiência de debug.

// Estruture o código modularmente, seguindo os padrões do NestJS.
