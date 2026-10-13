# Baozi Store API - Desenvolvimento Web - backend

## Descrição
A Baozi Store API é um sistema REST simples desenvolvido para a disciplina de Desenvolvimento Web Back-End. O projeto visa gerenciar o controle básico de clientes, produtos e pedidos de uma pequena loja que vende pãozinho chinês.

## Tecnologias Utilizadas
* Java
* Spring Boot
* Spring Data JPA
* Banco de dados H2 (em memória)
* Maven

## Estrutura do Projeto
O projeto segue a arquitetura mínima exigida e o padrão MVC do Spring. Ele está organizado nos seguintes pacotes principais:
* `model`: Contém as classes das entidades (Cliente, Produto e Pedido).
* `repository`: Contém as interfaces de conexão com o banco de dados.
* `controller`: Contém as classes com os endpoints GET, POST e DELETE.

## Como Executar
1. Clone este repositório para a sua máquina.
2. Certifique-se de ter o Java instalado.
3. Não é necessário configurar um banco de dados externo. O H2 é um banco de dados em memória e cria as tabelas do zero de forma totalmente local quando a aplicação é executada.
4. Rode a classe principal do projeto através de sua IDE (Eclipse, IntelliJ IDEA, VS Code) ou via Maven.
5. A API estará disponível no endereço `http://localhost:8080`.

## Endpoints da API
Para as entidades de Cliente, Produto e Pedido, a API implementa os seguintes endpoints:
* **POST** – criar
* **GET** – listar todos
* **GET /{id}** – consultar por ID
* **DELETE /{id}** – apagar

**Rotas base da aplicação:**
* `/clientes`
* `/produtos`
* `/pedidos`
