# Simulando um Ataque de Brute Force de Senhas com Medusa no Kali Linux - DIO.me | Santander Bootcamp 2025

<p align="center">
  Projeto [Ataque de Brute Force de Senhas com Medusa] desenvolvido durante o Bootcamp Santander 2025, em parceria com a DIO.me.
</p>

---

* **Autor:** Evandro Mucha
* **Data de Execução:** 22 de outubro de 2025
* **GitHub:** [evandromucha](https://github.com/evandromucha)
* **LinkedIn:** [Evandro Mucha](https://br.linkedin.com/in/evandromucha)

---

## 📖 Índice

* [Sobre o Projeto](#-sobre-o-projeto)
* [Tecnologias Utilizadas](#-tecnologias-utilizadas)
* [Funcionalidades](#-funcionalidades)
* [Como Executar](#-como-executar)
* [Autor](#-autor)

---

## 🚀 Sobre o Projeto

[Aqui você deve dar uma descrição clara e concisa do que o seu projeto faz. Tente responder:]

* **Qual problema ele resolve?** (Ex: "Uma API REST para gerenciamento de clientes de um banco digital.")
* **Qual foi o desafio proposto?** (Ex: "Implementar um sistema de recomendações de investimentos com base no perfil do usuário.")
* **Qual o principal objetivo?** (Ex: "Consolidar os conhecimentos em Spring Boot, padrão DTO e boas práticas de API RESTful.")

---

## 🛠️ Tecnologias Utilizadas

Liste as principais ferramentas, frameworks e linguagens que você utilizou.

* **Linguagem:** [Ex: Java 17, Kotlin, Python 3.10]
* **Framework:** [Ex: Spring Boot 3, Angular 17, React, Flask]
* **Banco de Dados:** [Ex: PostgreSQL, MySQL, H2 Database, MongoDB]
* **Testes:** [Ex: JUnit 5, Mockito, Jest]
* **Cloud:** [Ex: AWS, Google Cloud (se aplicável)]
* **Outros:** [Ex: Docker, Git, Postman, Swagger/OpenAPI]

---

## ✨ Funcionalidades

Descreva o que o projeto é capaz de fazer. Use uma lista para ficar mais claro.

* **[Ex: Cadastro de Usuário]**: Permite a criação de novos usuários no sistema.
* **[Ex: Consulta de Saldo]**: Endpoint que retorna o saldo atual do cliente.
* **[Ex: Transferência Bancária]**: Lógica de negócio para transferir valores entre contas.
* **[Ex: Geração de Cartão Virtual]**: (Se for um projeto mais complexo).

*(Opcional: Se seu projeto tiver uma interface visual, coloque screenshots ou GIFs aqui!)*
---

## ▶️ Como Executar

Forneça um guia passo a passo para que outra pessoa possa rodar o seu projeto localmente.

### Pré-requisitos

Antes de começar, você vai precisar ter instalado em sua máquina as seguintes ferramentas:

* [Java 17 (ou a versão que usou)]
* [Maven ou Gradle]
* [Seu SGBD (Ex: PostgreSQL) rodando na porta Padrão]
* [Git]
* [IDE de sua preferência (Ex: IntelliJ, VSCode)]

### Rodando o Projeto

```bash
# 1. Clone o repositório
git clone [URL_DO_SEU_REPOSITÓRIO_AQUI]

# 2. Acesse a pasta do projeto
cd [NOME_DA_PASTA_DO_PROJETO]

# 3. Configure as variáveis de ambiente (se houver)
# Crie um arquivo `.env` ou altere o `application.properties`
# Exemplo para application.properties:
# SPRING_DATASOURCE_URL=jdbc:postgresql://localhost:5432/meu_banco
# SPRING_DATASOURCE_USERNAME=seu_usuario
# SPRING_DATASOURCE_PASSWORD=sua_senha

# 4. Instale as dependências (Exemplo com Maven)
mvn clean install

# 5. Execute a aplicação (Exemplo com Spring Boot)
mvn spring-boot:run

# 6. (Opcional) Acesse a documentação da API (se houver)
# A aplicação estará disponível em http://localhost:8080
# A documentação do Swagger/OpenAPI pode ser acessada em http://localhost:8080/swagger-ui.html
