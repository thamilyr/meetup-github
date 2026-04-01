# 📍 Meetup GitHub

## 🚀 Sobre o projeto

Este projeto consiste em uma aplicação que permite consultar e exibir informações relacionadas a eventos (meetups) utilizando dados provenientes de uma API externa.

O objetivo principal é praticar consumo de APIs, organização de código e boas práticas de desenvolvimento.

---

## 🛠️ Tecnologias utilizadas

* Java
* Spring Boot
* REST API
* JSON
* Maven
* Consumo de API externa

---

## 📌 Funcionalidades

* Consulta de eventos via API
* Listagem de dados retornados
* Tratamento de respostas JSON
* Organização em camadas (Controller, Service, etc.)
* Estrutura orientada a boas práticas

---

## ▶️ Como executar o projeto

### 1. Clonar o repositório

```bash id="clone_meetup"
git clone https://github.com/thamilyr/meetup-github.git
```

### 2. Acessar a pasta

```bash id="cd_meetup"
cd meetup-github
```

### 3. Executar com Maven

```bash id="run_meetup"
mvn spring-boot:run
```

---

## 📡 Exemplo de uso

Após executar a aplicação, os dados dos meetups serão retornados via endpoint REST:

```http id="endpoint1"
GET /meetups
```

Resposta exemplo:

```json id="json1"
[
  {
    "id": 1,
    "name": "Tech Meetup",
    "location": "São Paulo"
  }
]
```

---

## 🧠 O que aprendi

* Consumo de APIs REST
* Manipulação de JSON em Java
* Estrutura de aplicações Spring Boot
* Separação em camadas (Controller, Service, Repository)
* Boas práticas de organização de código

---

## 👩‍💻 Autora

**Thamily Gimenes Rissi**
