---
tags:
  - iot
  - engenharia
  - firmware
  - fullstack
  - devops
status: planejado
---

# Cronograma de Leitura: Engenharia de Sistemas IoT End-to-End

Este roteiro estabelece uma progressão lógica para o domínio completo do ecossistema IoT, dividida entre o desenvolvimento de firmware (ESP32/ESP-IDF), arquitetura full-stack, segurança e infraestrutura em nuvem (VPS/DevOps).

---

## Método de Execução: Estratégia dos Dois Trilhos
- **Trilho Prático:** Leitura ativa em frente ao computador. Cada capítulo deve ser convertido em código, testes ou configurações aplicadas a projetos reais.
- **Trilho Conceitual:** Leitura passiva (cabeceira/transporte). Foco na absorção de padrões arquiteturais, design e filosofia de engenharia.

---

## Fase 1: Fundações e Estrutura de Código
**Objetivo:** Mitigar falhas críticas no firmware do chip e organizar a arquitetura do backend para manutenibilidade.

- **Trilho Prático (Firmware):**
  - *Developing IoT Projects with ESP32 (2nd Edition)* – Vedat Ozan Oner
  - *Alternativa em PT-BR:* *ESP32 com IDF* – José V. S. Morais
- **Trilho Conceitual (Arquitetura):**
  - *Clean Architecture: A Craftsman's Guide to Software Structure and Design* – Robert C. Martin

---

## Fase 2: Concorrência, Conectividade e Segurança
**Objetivo:** Dominar o comportamento de tempo real do microcontrolador e blindar o acesso do usuário final aos dispositivos.

- **Trilho Prático (Firmware/RTOS):**
  - *Hands-On RTOS with Microcontrollers* – Brian Amos
- **Trilho Prático (Segurança Web):**
  - *API Security in Action* – Neil Madden
- **Trilho Conceitual (Redes):**
  - *IoT Fundamentals: Networking Technologies, Protocols, and Use Cases for IoT* – David Hanes et al.

---

## Fase 3: Escala de Dados e Resiliência da VPS
**Objetivo:** Isolar serviços em containers e estruturar o backend para suportar alta concorrência de telemetria sem perda de dados.

- **Trilho Prático (Infraestrutura):**
  - *Docker Deep Dive* – Nigel Poulton
  - *Designing Distributed Systems* – Brendan Burns
- **Trilho Conceitual (Dados):**
  - *Designing Data-Intensive Applications* – Martin Kleppmann

---

## Fase 4: Automação (DevOps) e Sistemas de Borda
**Objetivo:** Implementar esteiras automáticas de CI/CD para firmware/backend e expandir escopo para gateways industriais.

- **Trilho Prático (Automação ou Linux Embarcado):**
  - *Infrastructure as Code* – Kief Morris
  - *Mastering Embedded Linux Programming* – Chris Simmonds
- **Trilho Conceitual (Cultura DevOps):**
  - *The DevOps Handbook* – Gene Kim, Jez Humble et al.

---

## Apêndice: Consulta e Referência Técnica (Leitura sob demanda)
Livros altamente técnicos para sanar problemas específicos de engenharia ao longo do percurso.

- **C Puro e Qualidade de Firmware:**
  - *Effective C: An Introduction to Professional C Programming* – Robert C. Seacord
  - *Test-Driven Development for Embedded C* – James W. Grenning
  - *Making Embedded Systems* – Elecia White
- **Segurança de Ecossistemas:**
  - *Practical IoT Hacking* – Fotios Chantzis, Ioannis Stais et al.
- **Modelagem de Serviços e UX:**
  - *Building Microservices* – Sam Newman
  - *Designing Connected Products* – Claire Rowland et al.