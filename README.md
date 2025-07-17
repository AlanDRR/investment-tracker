# 📈 Investment Tracker

Sistema de controle de investimentos em renda variável desenvolvido em Java com Spring Boot.

## 💡 Sobre o Projeto

O **Investment Tracker** é um projeto em desenvolvimento que tem como objetivo fornecer uma plataforma para:

- Cadastrar usuários e ativos de investimento
- Registrar operações de compra e venda
- Calcular posições e lucros/prejuízos
- Expor APIs REST para consumo de dados

Este projeto é parte do meu portfólio e está sendo desenvolvido com foco em aprendizado e evolução contínua.

## 🚀 Tecnologias Utilizadas

- **Java 17**
- **Spring Boot**
- **Spring Data JPA**
- **H2 Database** (para ambiente de desenvolvimento)
- **Lombok**
- **Swagger/OpenAPI** (para documentação da API)

## 🎯 Objetivos do Projeto

✅ Criar uma API RESTful para controle de operações financeiras  
✅ Implementar cálculos de preço médio e P&L (Profit & Loss)  
✅ Permitir consultas de posições por cliente  
✅ Evoluir gradualmente com:
  - Autenticação e segurança
  - Persistência em bancos relacionais (MySQL, PostgreSQL)
  - Deploy em ambientes cloud (Heroku, AWS)
  - Integração com mensageria (Kafka)

## 📝 Status

📌 **Em desenvolvimento**  
Atualmente, o projeto está na fase inicial de estruturação de entidades, repositórios e configuração do ambiente Spring Boot.

## ⚙️ Como Rodar

1. Clone este repositório:

   ```bash
   git clone https://github.com/AlanDRR/investment-tracker.git

2. Navegue até a pasta do projeto:

    cd investment-tracker

3. Compile e rode a aplicação com Maven:

    mvn spring-boot:run

4. Acesse o Swagger para testar a API:

   http://localhost:8080/swagger-ui/index.html

📂 Estrutura do Projeto

    Copiar
    Editar
    investment-tracker/
    ├── src/
    │   ├── main/
    │   │   ├── java/com/example/investmenttracker/
    │   │   │   ├── controller/
    │   │   │   ├── model/
    │   │   │   ├── repository/
    │   │   │   ├── service/
    │   │   │   └── InvestmentTrackerApplication.java
    │   │   └── resources/
    │   │       └── application.yml
    └── pom.xml

✨ Próximos Passos

  Implementar os CRUDs completos

  Criar lógica de cálculos financeiros

  Adicionar testes unitários

  Publicar primeira versão funcional da API

🤝 Contribuição

  Este projeto está em desenvolvimento individual como parte do meu processo de aprendizado. Feedbacks e sugestões são sempre bem-vindos!

Projeto criado e mantido por AlanDRR.
