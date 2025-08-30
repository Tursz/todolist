# 📚 Projeto Fullstack - Spring Boot + Angular

Este repositório contém um sistema **Fullstack** composto por uma **API REST em Spring Boot** e uma **aplicação Angular** para o frontend.

---

## 🚀 Tecnologias

### Backend (API - [Spring Boot](https://spring.io/projects/spring-boot))
- Java 17+
- Spring Boot 3.x
- Spring Data JPA (Hibernate)
- Spring Security (JWT)
- Banco de dados: PostgreSQL / MySQL (configurável)
- Maven

### Frontend ([Angular](https://angular.io/))
- Angular 17+
- TypeScript
- Angular Material
- RxJS
- Serviço de autenticação JWT

---

## ⚡ Instalação

Clone o projeto e rode backend e frontend em paralelo:

```bash
# 1. Clone o repositório
git clone https://github.com/Tursz/todolist.git
cd seu-projeto

# 2. Suba o backend (Spring Boot)
cd todolist-api
mvn spring-boot:run

# 3. Suba o frontend (Angular)
cd todolist-web
npm install
ng serve
