# Simulando um Ataque de Brute Force de Senhas com Medusa

**Plataforma:** DIO.me | **Curso:** Santander Cibersegurança 2025

**Autor:** Evandro Mucha
**Data de Execução:** 22 de outubro de 2025
**GitHub:** [evandromucha](https://github.com/evandromucha)
**LinkedIn:** [Evandro Mucha](https://br.linkedin.com/in/evandromucha)

---

## 📖 Índice

* [Sobre o Projeto](#-sobre-o-projeto)
* [Tecnologias Utilizadas](#-tecnologias-utilizadas)
* [Execução](#-execução)
* [Conclusão](#-conclusão)
* [Autor](#-autor)

---

## ⚠️ Aviso Ético e de Responsabilidade

Este projeto foi conduzido em um ambiente de laboratório virtual, isolado e controlado.
Todas as técnicas de enumeração de serviços e ataques de força bruta foram aplicadas para fins estritamente educacionais e como parte do desafio de projeto do Santander Cibersegurança 2025.
Nunca realize testes de invasão, varreduras de vulnerabilidade ou qualquer tipo de ataque em sistemas ou redes para os quais você não possua autorização explícita e por escrito. A utilização dessas ferramentas em ambientes de produção sem permissão é ilegal e antiética.

___

## 🚀 Sobre o Projeto

Este projeto documenta uma análise de vulnerabilidades e um pentest simulado, executados em um ambiente de laboratório estritamente controlado e isolado. O objetivo principal foi aplicar técnicas de reconhecimento e exploração de serviços para fins estritamente educacionais, como parte do desafio do Santander Cibersegurança 2025.

O laboratório foi configurado utilizando duas máquinas em uma rede interna e isolada:

* **Máquina Atacante:** Kali Linux, executado diretamente no Windows através do WSL 2 (Windows Subsystem for Linux). Esta abordagem permite o uso nativo das ferramentas do Kali sem a necessidade de uma máquina virtual separada para o atacante.

* **Máquina Alvo:** Metasploitable 2, uma imagem de máquina virtual baseada em Ubuntu e intencionalmente vulnerável, projetada especificamente para treinamento de segurança. Esta VM foi executada no Oracle VirtualBox.

O foco do estudo foi identificar serviços vulneráveis (como FTP, HTTP, SMB) na máquina alvo e demonstrar como credenciais fracas e configurações inseguras podem ser exploradas usando ferramentas padrão da indústria.

---

## 🛠️ Tecnologias Utilizadas

A execução deste projeto dependeu de um ambiente de laboratório controlado. Abaixo estão os principais componentes e ferramentas utilizados:

* **Oracle VirtualBox:** Software de virtualização (hypervisor) que permitiu a criação de um ambiente de rede isolado. Foi utilizado para hospedar e executar a máquina virtual alvo (Metasploitable 2) de forma segura, sem expô-la a redes externas.

* **Metasploitable 2:** A máquina virtual alvo. É um sistema operacional baseado em Linux (Ubuntu) intencionalmente projetado pela Rapid7 com uma vasta gama de vulnerabilidades de segurança. Serve como um "laboratório" legal e ético para praticar técnicas de pentest.

* **Kali Linux (via WSL 2):** A distribuição Linux utilizada como máquina atacante. É o padrão da indústria para testes de invasão, pois vem pré-carregada com um extenso arsenal de ferramentas de segurança. Foi executada via WSL (Windows Subsystem for Linux) para integração direta com o host Windows.

* **Medusa:** Uma ferramenta de linha de comando especializada em ataques de força bruta. Foi a principal ferramenta utilizada para automatizar a descoberta de credenciais, testando rapidamente milhares de combinações de usuário e senha contra serviços de rede como FTP e SMB.
---

## ✨ Funcionalidades

Descreva o que o projeto é capaz de fazer. Use uma lista para ficar mais claro.

* **[Ex: Cadastro de Usuário]**: Permite a criação de novos usuários no sistema.
* **[Ex: Consulta de Saldo]**: Endpoint que retorna o saldo atual do cliente.
* **[Ex: Transferência Bancária]**: Lógica de negócio para transferir valores entre contas.
* **[Ex: Geração de Cartão Virtual]**: (Se for um projeto mais complexo).

*(Opcional: Se seu projeto tiver uma interface visual, coloque screenshots ou GIFs aqui!)*
---

## ▶️ Execução

