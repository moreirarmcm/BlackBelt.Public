# Backend (API) - Documentação

## Tecnologias

- ASP.NET Core
- DbUp: versionamento e execução de scripts SQL
- Dapper: mapeamento de entidades
- JWT

## Arquitetura

Clean Architecture:

- API
- Application
- Infrastructure
- Domain

## Padrões

- DTOs: Request / Response
- Services: regras de negócio
- Repositories: acesso a dados
- uso obrigatório de stored procedures
- métodos assíncronos (Async)

## Convenções e regras

- Middleware global para tratamento de exceções.
- Autenticação por JWT.

## Execução

*Veja mais na documentação do repositório oficial*
