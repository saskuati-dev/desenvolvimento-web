# API de Gerenciamento de Vendas
João Vitor Ferreira Carneiro, Gabriel Henrique de Souza Carvalho e Dyonatam Terluk
Esta API oferece recursos para gerenciar produtos e pedidos em um sistema de vendas.

## Endpoints

### Produtos

#### GET http://localhost:8080/produtos/produto

Retorna todos os produtos cadastrados.

#### GET http://localhost:8080/produtos/produtoCod/{codigo}

Retorna um produto com base no código fornecido.

#### POST http://localhost:8080/produtos/produto

Cria um novo produto.

#### PUT http://localhost:8080/produtos/produto/{codigo}

Atualiza um produto existente com base no código fornecido.

#### DELETE http://localhost:8080/produtos/produto/{codigo}

Deleta um produto com base no código fornecido.

#### DELETE http://localhost:8080/produtos/produto

Deleta todos os produtos.

### Produtos Pedidos

#### GET http://localhost:8080/produto-pedido

Retorna todos os produtos pedidos cadastrados.

#### GET http://localhost:8080/produto-pedido/{id}

Retorna um produto pedido com base no ID fornecido.

#### POST http://localhost:8080/produto-pedido

Cria um novo produto pedido.

#### PUT http://localhost:8080/produto-pedido/{id}

Atualiza um produto pedido existente com base no ID fornecido.

#### DELETE http://localhost:8080/produto-pedido/{id}

Deleta um produto pedido com base no ID fornecido.

#### DELETE http://localhost:8080/produto-pedido

Deleta todos os produtos pedidos.
