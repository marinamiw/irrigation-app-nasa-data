# Smart Irrigation NASA 🌱

Aplicativo para auxiliar produtores rurais na gestão da irrigação, utilizando dados climáticos fornecidos pela NASA.

---

## 📋 Descrição do Projeto

Este projeto tem como objetivo o desenvolvimento de um aplicativo que utiliza dados climáticos de satélite (NASA) para ajudar o produtor rural a tomar decisões mais precisas sobre quando e quanto irrigar suas plantações.

A proposta é integrar informações científicas com uma interface simples, acessível e funcional.

---

## 🧑‍💻 Tecnologias e Ferramentas

- **Linguagem:** Python [![py](https://skillicons.dev/icons?i=js,html,css,wasm)](https://skillicons.dev)
- **Framework Back-end:** FastAPI [![fastapi](https://skillicons.dev/icons?i=js,html,css,wasm)](https://skillicons.dev)
- **Banco de Dados:** MongoDB [![mongodb](https://skillicons.dev/icons?i=js,html,css,wasm)](https://skillicons.dev) 
- **API Externa:** NASA POWER API 
- **Plataforma de Versionamento:** GitHub [![github](https://skillicons.dev/icons?i=js,html,css,wasm)](https://skillicons.dev) 

---

## 🛠️ Estrutura Técnica (Resumo)

### 📡 API Externa (NASA):
- Consumo de dados climáticos: temperatura, umidade, precipitação, entre outros.
- Os dados serão utilizados para gerar recomendações de irrigação.

### 🖥️ Back-end (API Própria):
- Desenvolvimento de uma API REST usando FastAPI.
- Comunicação com a API da NASA.
- Processamento e formatação dos dados antes de enviar ao front-end.
- Possível integração com MongoDB para:
  - Armazenamento de histórico de dados climáticos.
  - Cadastro e gerenciamento de usuários (futuramente).

### 📱 Front-end:
- Interface do aplicativo (em desenvolvimento nas próximas fases).
- Exibição de dados e recomendações para o produtor.


