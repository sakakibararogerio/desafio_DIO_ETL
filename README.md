# 📊 Desafio DIO – Pipeline ETL com IA Generativa

## 📌 Descrição do Projeto
Este projeto faz parte de um desafio da **Digital Innovation One (DIO)** e tem como foco a construção de um **pipeline ETL (Extract, Transform, Load)** integrado com **IA Generativa**.

Para simular um cenário real, foi utilizada uma **API Fake** disponibilizada no repositório:

🔗 https://github.com/PauloHLeme/Fake-API-Santander-Dio

---

## 🎯 Objetivo
Utilizar o poder da **IA Generativa** para criar **mensagens de marketing personalizadas**, que serão associadas e entregues individualmente a cada cliente retornado pela API.

O fluxo do projeto contempla:
- Extração de dados via API REST
- Geração de mensagens personalizadas com IA
- Atualização dos dados dos usuários na API

---

## 🔄 Fluxo ETL

- **Extract**
  - Consumo da API Fake para obtenção dos dados dos usuários

- **Transform**
  - Geração automática de mensagens personalizadas utilizando IA Generativa (Google Gemini)

- **Load**
  - Atualização dos usuários na API com as mensagens geradas

---

## 🛠️ Tecnologias e Ferramentas

### 🧑‍💻 Linguagem
- **Python**

### 🧪 Ambiente
- **Jupyter Notebook**

### 📚 Bibliotecas Principais
- **pandas**  
  Utilizada para manipulação e análise de dados tabulares.

- **requests**  
  Responsável pela comunicação HTTP com a API REST.

- **google-genai**  
  Cliente oficial para utilização dos modelos **Google Gemini**, responsável pela geração das mensagens de marketing personalizadas.

---

## 🤖 IA Generativa
A IA Generativa é utilizada para criar mensagens de marketing contextualizadas e personalizadas, tornando a comunicação mais relevante para cada usuário, com base nos dados disponíveis.

---

## 📎 Observações
- A API utilizada é apenas para fins educacionais.
- O projeto simula um cenário real de integração entre **engenharia de dados** e **inteligência artificial**.
- Ideal para estudos de:
  - ETL
  - Consumo de APIs REST
  - Automação de dados
  - IA aplicada a negócios
