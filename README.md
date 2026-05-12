# Event Management System

Projeto desenvolvido como desafio do módulo de Modelo de Domínio e ORM do curso Java Spring Professional da DevSuperior.

## Sobre o projeto

O sistema tem como objetivo gerenciar participantes e atividades de um evento acadêmico.

As atividades podem representar:

- Palestras
- Cursos
- Oficinas
- Workshops

Cada atividade possui:

- Nome
- Descrição
- Preço
- Blocos de horários

Os participantes podem se inscrever em várias atividades do evento.

---

## Modelo conceitual

O projeto foi desenvolvido utilizando modelagem de domínio com relacionamentos entre entidades através de ORM com JPA/Hibernate.

Principais entidades:

- Participant
- Activity
- Block

Relacionamentos implementados:

- Many-to-Many
- Many-to-One
- One-to-Many

---

## Tecnologias utilizadas

- Java
- Spring Boot
- Spring Data JPA
- Hibernate
- Banco de dados H2
- Maven

---

## Banco de dados

O projeto utiliza banco H2 em memória com seeding automático dos dados conforme especificação do desafio.

H2 Console:

```text
http://localhost:8080/h2-console
```

---

## Como executar o projeto

```bash
# clonar repositório
git clone https://github.com/seuusuario/event-management-system.git

# entrar na pasta
cd event-management-system

# executar aplicação
./mvnw spring-boot:run
```

---

## Objetivos do desafio

- Implementar modelo de domínio
- Trabalhar com ORM
- Criar relacionamentos entre entidades
- Configurar banco H2
- Realizar seeding da base de dados
- Utilizar JPA e Hibernate