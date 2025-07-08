# 📦 Workshop Spring Boot 3 JPA

Projeto desenvolvido em Java utilizando o framework Spring, com integração ao banco de dados PostgreSQL e testes de API realizados no Postman.

## 🚀 Tecnologias Utilizadas

- [Java 21+](https://www.oracle.com/java/)
- [Spring Tools 4 (STS)](https://spring.io/tools)
- [Apache Tomcat](https://tomcat.apache.org/)
- [Maven](https://maven.apache.org/)
- [Postman](https://www.postman.com/)
- [PostgreSQL](https://www.postgresql.org/)

## 🧩 Principais Dependências

- Spring Boot Starter Web
- Spring Boot Starter Data JPA
- PostgreSQL Driver
- Spring Boot DevTools
- Lombok (opcional)

> Todas as dependências estão configuradas no arquivo `pom.xml`.

## 💡 Funcionalidades

- [x] Cadastro de entidades (ex: usuários, produtos, etc.)
- [x] Listagem, atualização e exclusão
- [x] Integração com banco de dados PostgreSQL
- [x] Testes de endpoints REST com Postman
- [x] Tratamento de erros com `@ControllerAdvice`
- [x] Validações com `javax.validation`

## ⚙️ Como executar o projeto

1. Clone o repositório:
```bash
git clone https://github.com/ThiagoV70/workshop-springboot3-jpa.git

```
2. Navegue até o diretório do projeto:
```
cd workshop-springboot3-jpa
```
3. Crie o projeto usando Maven:
```
mvn clean install
```
Execute o aplicativo:
```
mvn spring-boot:run 
```
## 🧪 Testes com Postman
Os testes podem ser realizados via Postman nos endpoints REST, como:

- GET /users :  Retorna todos os usuário.

- POST /orders :  Cria um novo pedido.

- PUT /users/{id} :  Adiciona um usuário.

- GET /orders :  Recupera todos os pedidos.

- ## 🙏 Agradecimentos

Este projeto foi desenvolvido como parte dos estudos com base no excelente conteúdo do professor [Nélio Alves](https://github.com/nelioalves).  
Agradeço pelo comprometimento, clareza nas explicações e pelo incentivo constante à prática.

📚 Cursos realizados na [Udemy](https://www.udemy.com/user/nelio-alves/) que foram fundamentais para esse aprendizado.
