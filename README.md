# NextPay API

API REST desenvolvida com Spring Boot com o objetivo de estudar e aplicar conceitos de desenvolvimento backend utilizados no mercado.

## Tecnologias utilizadas

* Java 17
* Spring Boot
* Maven

## Funcionalidades atuais

* Endpoint de teste `/hello`
* Estrutura inicial de API REST
* Organização em camadas (controller)

## Como executar o projeto

Pelo terminal:

```bash
./mvnw spring-boot:run
```

Ou diretamente pela IDE (IntelliJ), executando a classe `Application.java`.

## Endpoint disponível

GET

```
http://localhost:8080/hello
```

## Resposta

```
NextPay API rodando com sucesso!
```

## Estrutura do projeto

```
src/
 └── main/
     ├── java/com/nextpay/api
     │   ├── controller
     │   └── Application.java
     └── resources/
```

## Objetivo

Esse projeto está sendo desenvolvido com foco em evolução prática no backend com Java, visando a construção de APIs reais e aplicáveis em cenários de produção.

---

Desenvolvido por Ytalo Rodrigues
