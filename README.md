# Projeto MVC Web - Cadastro de Alunos

Projeto simples desenvolvido com Spring Boot e Thymeleaf para demonstrar o funcionamento da arquitetura MVC em uma aplicação web.

## Participantes

- Gustavo Negrão de Souza Berengani Ramos

## Funcionalidade

A aplicação permite cadastrar um aluno informando nome e matrícula. Depois do cadastro, os alunos adicionados são exibidos em uma tabela.

Os dados ficam armazenados em memória enquanto a aplicação estiver executando.

## Estrutura MVC

- `model/Aluno.java`: representa o aluno e contém a validação do nome obrigatório.
- `controller/AlunoController.java`: recebe as requisições, cadastra os alunos e envia a lista para a página.
- `templates/alunos-form.html`: formulário para preencher os dados.
- `templates/alunos-lista.html`: página que exibe os alunos cadastrados.

## Como executar

É necessário ter o Java instalado. Na pasta do projeto, execute:

```bash
./mvnw spring-boot:run
```

No Windows PowerShell:

```powershell
.\mvnw.cmd spring-boot:run
```

Depois, acesse no navegador:

```text
http://localhost:8080/alunos
```

## Tecnologias utilizadas

- Java 17
- Spring Boot
- Spring Web
- Thymeleaf
- Maven
