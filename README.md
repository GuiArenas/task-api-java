# Task API Java

API REST CRUD para gerenciamento de tarefas construída em **Java 17** com **Spring Boot** e **Maven**.

## Tecnologias utilizadas

- Java 17
- Spring Boot 3
- Maven
- Spring Data JPA
- H2 Database (para testes locais)
- Postman (para testes dos endpoints)
- Git/GitHub (versionamento)

## Funcionalidades

- Criar tarefas com título e status
- Listar todas as tarefas
- Buscar tarefa por ID
- Atualizar tarefa existente
- Deletar tarefa

## Estrutura do projeto

- `TaskApiApplication` → classe principal que inicializa o Spring Boot  
- `Task` → entidade que representa uma tarefa  
- `TaskRepository` → interface para acesso ao banco de dados  
- `TaskService` → camada de serviço para lógica de negócio  
- `TaskController` → controller REST que expõe os endpoints da API  

