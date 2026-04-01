# Database - Documentação

## Tecnologia

- SQL Server

## Estrutura

Schemas:

*Veja mais na documentação do repositório oficial*


## Convenções e regras

Tabelas:

- Todas as tabelas devem estar dentro de um schema específico, de acordo com a área funcional a que pertencem.

Procedures:

- As procedures devem seguir a convenção de nomemclatura '[Schema].[Operação][Entidade][Detalhes]'.
- Operações padrões (CRUD), devem ser nomeadas como: Inserir, Buscar, Atualizar, Inativar e Excluir. 
- Detalhes devem ser usados para diferenciar operações específicas, como buscas por código ou nome.
Ex:
*Veja mais na documentação do repositório oficial*


Versionamento:

- Os scripts devem ser organizados nas pastas `runonce` e `rerunnable`.
- **Nenhum** script da pasta "runonce" deve ser editado após sua execução inicial.
- Script da tabela "development" devem ser escritos para evitar a criação duplicada de tabelas ou objetos, e garantindo que possam ser executados múltiplas vezes sem causar erros. 

## Comunicação com o backend

Toda a comunicação entre o banco de dados e o backend deve ser feita exclusivamente por meio de stored procedures. O backend não deve acessar ou manipular as tabelas diretamente, garantindo assim uma camada de abstração e segurança entre a aplicação e o banco de dados.

## Comunicação com o frontend

Não existe comunicação direta entre o banco de dados e o frontend.