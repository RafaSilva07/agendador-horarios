# Agendador de Horários

Este projeto é uma aplicação Java desenvolvida com **Spring Boot**, cujo objetivo é gerenciar **agendamentos de horários** de forma simples.  
Ele utiliza uma arquitetura organizada em camadas, separando responsabilidades entre controller, service e repository.

## 🧱 Tecnologias utilizadas

- Java 21
- Spring Boot
- Spring Data JPA
- Maven
- Banco de dados configurável via `application.properties`
  
## 📁 Estrutura do projeto

O projeto segue uma estrutura padrão do Spring Boot:

- `controller`  
  Responsável por receber as requisições HTTP e direcionar para a camada de serviço.

- `services`  
  Contém a lógica de negócio da aplicação.

- `infrastructure/entity`  
  Define as entidades JPA que representam as tabelas do banco de dados.

- `infrastructure/repository`  
  Camada de acesso aos dados, utilizando Spring Data JPA.

- `resources`  
  Contém arquivos de configuração, templates e arquivos estáticos.

### 📥 Clonando o repositório

Abra o terminal e execute:

```bash
git clone https://github.com/RafaSilva07/agendador-horarios.git
