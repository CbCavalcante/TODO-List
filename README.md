<h1 align="center">
  TO-DO List
</h1>

<p align="center">
 <img src="https://img.shields.io/static/v1?label=LinkedIn&message=Cauã Bernardo&color=697565&labelColor=000000" alt="Cauã Bernardo" />
 <img src="https://img.shields.io/static/v1?label=Tipo&message=Projeto Pessoal&color=697565&labelColor=000000" alt="Desafio" />
</p>

API para gerenciar tarefas (CRUD)

## Tecnologias
 
- [Spring Boot](https://spring.io/projects/spring-boot)
- [Spring MVC](https://docs.spring.io/spring-framework/reference/web/webmvc.html)
- [Spring Data JPA](https://spring.io/projects/spring-data-jpa)
- [SpringDoc OpenAPI 3](https://springdoc.org/v2/#spring-webflux-support)
- [Mysql](https://dev.mysql.com/downloads/)

## Práticas adotadas

- SOLID, DRY, YAGNI, KISS
- API REST
- Consultas com Spring Data JPA
- Injeção de Dependências
- Geração automática do Swagger com a OpenAPI 3

## Como Executar

- Clonar repositório git
- Construir o projeto:
```
$ ./mvnw clean package
```
- Executar a aplicação:
```
$ java -jar target/todolist-0.0.1-SNAPSHOT.jar
```

A API poderá ser acessada em [localhost:8080](http://localhost:8080).
O Swagger poderá ser visualizado em [localhost:8080/swagger-ui.html](http://localhost:8080/swagger-ui.html)
