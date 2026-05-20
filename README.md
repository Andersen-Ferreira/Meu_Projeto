# 📌 API CRUD com Spring Boot + PostgreSQL

## 📖 Sobre o projeto
Este projeto é uma API REST CRUD desenvolvida com Spring Boot, com integração ao banco de dados PostgreSQL, gerenciado pelo pgAdmin 4.

A aplicação permite realizar operações básicas de:
- Criação
- Listagem
- Atualização
- Exclusão de dados

---

## 🚀 Tecnologias utilizadas
- Java 17+
- Spring Boot
- Spring Data JPA
- Hibernate
- PostgreSQL
- pgAdmin 4
- Maven

---

## ⚙️ Configuração do ambiente

### 🔹 Pré-requisitos
- Java instalado
- PostgreSQL instalado
- pgAdmin 4

### 🔹 Configuração do banco

Edite o arquivo `application.properties`:

spring.datasource.url=jdbc:postgresql://localhost:5432/meu_banco  
spring.datasource.username=seu_usuario  
spring.datasource.password=sua_senha  

spring.jpa.hibernate.ddl-auto=update  
spring.jpa.show-sql=true  

---

## ▶️ Como executar o projeto

# Clonar repositório  
git clone https://github.com/Andersen-Ferreira/Meu_Projeto.git  

# Entrar na pasta  
cd Meu_Projeto  

# Rodar aplicação  
./mvnw spring-boot:run  

Ou execute pela IDE (IntelliJ / Eclipse)

---

## 📌 Endpoints da API

GET /usuarios → Lista todos  
GET /usuarios/{id} → Busca por ID  
POST /usuarios → Cria novo  
PUT /usuarios/{id} → Atualiza  
DELETE /usuarios/{id} → Remove  

---

## 🧪 Testes
Você pode testar os endpoints usando:
-[] Postman
-[x] Insomnia

---

## 📂 Estrutura do projeto

src/main/java  
├── controller  
├── service  
├── repository  
├── model  

---

## 📸 Demonstração
Adicione prints aqui (Postman ou Swagger)

---

## 👨‍💻 Autor
Andersen Ferreira
