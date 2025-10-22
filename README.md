# Simulando um Ataque de Brute Force de Senhas com Medusa no Kali Linux
DIO.me | Santander Bootcamp 2025

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

Este projeto documenta uma análise de vulnerabilidades e um pentest simulado, executados em um ambiente de laboratório estritamente controlado e isolado. O objetivo principal foi aplicar técnicas de reconhecimento e exploração de serviços para fins estritamente educacionais, como parte do desafio do Bootcamp Santander 2025.

O laboratório foi configurado utilizando duas máquinas em uma rede interna e isolada:

* **Máquina Atacante:** Kali Linux, executado diretamente no Windows através do WSL 2 (Windows Subsystem for Linux). Esta abordagem permite o uso nativo das ferramentas do Kali sem a necessidade de uma máquina virtual separada para o atacante.

* **Máquina Alvo:** Metasploitable 2, uma imagem de máquina virtual baseada em Ubuntu e intencionalmente vulnerável, projetada especificamente para treinamento de segurança. Esta VM foi executada no Oracle VirtualBox.

O foco do estudo foi identificar serviços vulneráveis (como FTP, HTTP, SMB) na máquina alvo e demonstrar como credenciais fracas e configurações inseguras podem ser exploradas usando ferramentas padrão da indústria.

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
