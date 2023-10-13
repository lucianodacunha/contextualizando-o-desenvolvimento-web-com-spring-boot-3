# Contextualizando o Desenvolvimento Web com Spring Boot 3

## Entendendo a Arquitetura Rest - Parte I

- API, application programming interface
- Contrato de serviço entre duas aplicações
- Documentação orientar a forma de integração
- Cliente x Servidor
- HTTP, request <- json -> response
- GET, POST, PUT/PATCH, DELETE
- Além do REST: SOAP, RPC, Websocket, etc.
- Transferência representacional de estado
- CRUD, create, read, update e delete.
- http://localhost:1234/services/v1/users/{id}
- protocolo://host:porta/context/version/resource/parameter

## Entendendo a Arquitetura Rest - Parte II

- Status HTTP: 
- 200: sucesso
- 300: redirection
- 400: Client error
- 500: Server error
- JSON: formato de troca de dados entre app's.

```
{
    "valor" : 1
}
```


## Overview do Spring Framework

- Idealizado para simplificar o desenvolvimento Web, do que era o JEE.
- Baseado em IoC e DI.
- Spring Boot, idealizado para agilizar o start de um projeto com Spring.
- Spring Initializr: UI que facilita a construção inicial de um projeto Spring.

## Arquitetura de Três Camadas com Spring Boot

- Objetivo: promover a separação das funcionalidades usando camadas para separação lógica de apresentação, lógica, regras de negócio e persistência de dados.
- Arquitetura Projeto Spring: JSON -> DTO -> Controller -> Service -> DAO -> DB
- Controller: API layer
- Service: Business Logic
- DAO = Repository: Persistent Logic.
- Arquivo de Configuração: application.properties, application.yaml.

Para saber mais:

- [O que é uma API?](https://aws.amazon.com/pt/what-is/api/)
- [Arquitetura Rest: Saiba o que é e seus diferenciais](https://www.totvs.com/blog/developers/rest/)
- [Design da API Web RESTful](https://learn.microsoft.com/pt-br/azure/architecture/best-practices/api-design)
- [Introdução ao JSON: Um Guia Para JSON que vai Direto ao Ponto](https://www.amazon.com.br/Introdu%C3%A7%C3%A3o-JSON-Guia-Direto-Ponto/dp/8575224514?keywords=introdu%C3%A7%C3%A3o+ao+json+um+guia+para+json+que+vai+direto+ao+ponto&qid=1672489051&sprefix=json,aps,188&sr=8-1&linkCode=sl1&tag=cami08-20&linkId=0ca047e8b97212a1357581d005eb5440&language=pt_BR&ref_=as_li_ss_tl)
- [Introduction to Spring Framework](https://docs.spring.io/spring-framework/docs/3.0.x/spring-framework-reference/html/overview.html)
- [Spring Boot: como começar](https://www.zup.com.br/blog/spring-boot)
- [Common Application Properties](https://docs.spring.io/spring-boot/docs/current/reference/html/application-properties.html#appendix.application-properties.core)
- [Slides](https://academiapme-my.sharepoint.com/:p:/g/personal/renato_dio_me/ERVAxF7Z_uBIoMMef0ns7EUB-pRDR2J0pSJ4PS29L27_2w?e=2y1vhV)
