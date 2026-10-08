# Baozi Store - API REST

Projeto desenvolvido para a disciplina de Desenvolvimento Web Back-End.

A aplicação consiste em uma API REST para gerenciamento de uma loja fictícia
de Baozi, permitindo o cadastro, consulta, listagem e exclusão de clientes,
produtos e pedidos.

## Tecnologias

- Java 21
- Spring Boot
- Spring Web
- Spring Data JPA
- MySQL
- Maven
- Postman

## Entidades

### Cliente

- id
- nome
- clienteDesde

### Produto

- id
- nome
- preco
- estoque

### Pedido

- id
- clienteId
- produtoId
- quantidade

## Endpoints

### Clientes

- POST /clientes
- GET /clientes
- GET /clientes/{id}
- DELETE /clientes/{id}

### Produtos

- POST /produtos
- GET /produtos
- GET /produtos/{id}
- DELETE /produtos/{id}

### Pedidos

- POST /pedidos
- GET /pedidos
- GET /pedidos/{id}
- DELETE /pedidos/{id}
