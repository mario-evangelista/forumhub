# ForumHub API

## Descrição
A ForumHub API é uma aplicação desenvolvida em Spring Boot que oferece funcionalidades de gerenciamento de tópicos em um fórum online. Os usuários podem criar, visualizar, atualizar e excluir tópicos, além de autenticar-se para acessar as funcionalidades protegidas da API.

## Tecnologias Utilizadas
- Java 17
- Spring Boot 3
- Maven
- MySQL
- Flyway Migration
- Spring Data JPA
- Spring Security
- OAuth2 Resource Server
- JSON Web Token (JWT)
- SpringFox Swagger

## Endpoints Principais
- `/topicos`: Endpoint para operações CRUD de tópicos.
- `/login`: Endpoint para autenticar usuários e obter token JWT.
- `/swagger-ui.html`: Interface gráfica do Swagger para visualizar e testar os endpoints da API.

## Como Executar
1. Clone este repositório:
   ```
   git clone https://github.com/mario-evangelista/forumhub.git
   ```
2. Importe o projeto em sua IDE favorita (ex: IntelliJ IDEA, Eclipse, NetBeans).
3. Configure o banco de dados MySQL e atualize as informações de conexão no arquivo `application.properties`.
4. Execute a aplicação Spring Boot.
5. Acesse a interface gráfica do Swagger em `http://localhost:8080/swagger-ui.html` para visualizar e testar os endpoints da API.

Developed by Mário Evangelista
