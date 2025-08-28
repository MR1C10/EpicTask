# EpicTask

EpicTask é uma aplicação web simples para gerenciamento de tarefas, desenvolvida com Spring Boot.

## Funcionalidades
- Listar tarefas
- Cadastrar novas tarefas
- ...

## Tecnologias Utilizadas
- Java 17
- Spring Boot
- Maven
- Thymeleaf

## Como rodar o projeto

1. Clone o repositório ou baixe os arquivos.
2. No terminal, navegue até a raiz do projeto.
3. Execute o comando abaixo para iniciar a aplicação:

   No Windows:
   ```sh
   mvnw spring-boot:run
   ```
   Ou, se preferir:
   ```sh
   ./mvnw spring-boot:run
   ```

4. Acesse a aplicação em: [http://localhost:8080/tasks](http://localhost:8080/tasks)

## Estrutura do Projeto
```
├── src/
│   ├── main/
│   │   ├── java/br/com/etecia/epictask/
│   │   │   ├── EpictaskApplication.java
│   │   │   ├── controller/TaskController.java
│   │   │   └── model/Task.java
│   │   └── resources/
│   │       ├── application.properties
│   │       └── templates/
│   │           ├── form.html
│   │           ├── index.html
│   │           └── tasks.html
│   └── test/
│       └── java/br/com/etecia/epictask/EpictaskApplicationTests.java
├── pom.xml
├── mvnw / mvnw.cmd
```

## Autor
- MR1C10
