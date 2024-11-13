# Projeto de Aprendizado com Spring Boot e Banco de Dados

Este projeto foi desenvolvido com o objetivo de aprimorar minhas habilidades em manipulação de banco de dados, especialmente em:

    Relacionamentos N-N (muitos para muitos)
    Mapeamento Objeto-Relacional (ORM)

O projeto utiliza Spring Boot com JPA, H2 Database para testes e PostgreSQL para produção.
Tecnologias e Ferramentas Utilizadas

 - Java 21 : Linguagem de programação principal do projeto.
 - Spring Boot: Framework utilizado para criação de aplicações Spring simplificadas.
-  Spring Data JPA: Utilizado para facilitar o acesso e manipulação de dados
-  H2 Database: Banco de dados em memória para facilitar testes e desenvolvimento rápido
-  PostgreSQL: Banco de dados relacional para ambientes de produção e desenvolvimento avançado.
-  Postman: Ferramenta para testes e integração de API RESTful

# Objetivos do Projeto

O foco deste projeto é:

    Relacionamentos N-N: Implementação de relações muitos-para-muitos entre entidades no banco de dados, utilizando JPA.
    Mapeamento Objeto-Relacional (ORM): Configuração de mapeamentos entre classes Java e tabelas de banco de dados, aproveitando as anotações do JPA.

Topicos importantes do Projeto:

-  Conceitos
- Sistemas web e recursos
- Cliente/servidor, HTTP, JSON
- Padrão Rest para API web
- Estruturação de projeto Spring Rest
- Entidades e ORM
- Database seeding
- Padrão camadas
- Controller, service, repository
- Padrão DTO

    

Banco de Dados

Este projeto utiliza dois bancos de dados:

  - H2 Database: Para testes e desenvolvimento local rápido.
  - PostgreSQL: Configurado para o ambiente de produção.

Para trocar de banco de dados, basta alterar as configurações no arquivo application.properties.
