# 🚀 Node.js Project & Tasks API

<p align="center">
  <img src="https://img.shields.io/badge/Node.js-16%2B-339933?style=for-the-badge&logo=node.js"/>
  <img src="https://img.shields.io/badge/Express-4.17.1-000000?style=for-the-badge&logo=express"/>
  <img src="https://img.shields.io/badge/license-MIT-blue?style=for-the-badge"/>
</p>

<div align="center">
  <b>🇧🇷 Português | <a href="#english-version">🇺🇸 English below</a></b>
</div>

---

## 📑 Sumário | Table of Contents
- [Sobre o Projeto | About](#sobre-o-projeto--about)
- [Tecnologias | Technologies](#tecnologias--technologies)
- [Estrutura | Structure](#estrutura--structure)
- [Rotas da API | API Routes](#rotas-da-api--api-routes)
- [Instalação e Execução | Setup & Run](#instalação-e-execução--setup--run)
- [Autor | Author](#autor--author)

---

## Sobre o Projeto | About

**PT-BR:**
> API simples em Node.js com Express para gerenciar projetos e tarefas (CRUD em memória). Ideal para estudos de backend, middlewares e rotas REST.

**EN:**
> Simple Node.js API with Express to manage projects and tasks (in-memory CRUD). Ideal for backend, middleware, and REST routes studies.

---

## 🚀 Tecnologias | Technologies

**PT-BR:**
- **Node.js 16+**: Ambiente de execução JavaScript para backend.
- **Express 4.17+**: Framework minimalista para criação de APIs REST.

**EN:**
- **Node.js 16+**: JavaScript runtime for backend.
- **Express 4.17+**: Minimalist framework for building REST APIs.

---

## 🗂️ Estrutura | Structure

```
Nodejs-Primeiro-estudo/
├── index.js
├── package.json
├── yarn.lock
└── README.md
```

---

## 📚 Rotas da API | API Routes

- `GET /projects` — Lista todos os projetos
- `POST /projects` — Cria um novo projeto `{ id, title }`
- `PUT /projects/:id` — Atualiza o título de um projeto
- `DELETE /projects/:id` — Remove um projeto
- `POST /projects/:id/tasks` — Adiciona uma tarefa ao projeto `{ title }`

---

## ⚙️ Instalação e Execução | Setup & Run

**PT-BR:**
1. **Pré-requisitos:** Node.js 16+ e npm ou yarn
2. **Instale as dependências:**
   ```bash
   npm install
   # ou
   yarn
   ```
3. **Inicie o servidor:**
   ```bash
   node index.js
   ```
   O servidor estará disponível em `http://localhost:4000`.

**EN:**
1. **Prerequisites:** Node.js 16+ and npm or yarn
2. **Install dependencies:**
   ```bash
   npm install
   # or
   yarn
   ```
3. **Start the server:**
   ```bash
   node index.js
   ```
   The server will be available at `http://localhost:4000`.

---

## 👨‍💻 Autor | Author

**PT-BR:**

<div align="center">

**Rodolfo M. F. Abreu**  
Desenvolvedor de software apaixonado por tecnologia, aprendizado contínuo e boas práticas de programação. Sempre em busca de novos desafios e oportunidades para colaborar em projetos inovadores.

[![GitHub](https://img.shields.io/badge/GitHub-rodolfomfabreu-black?style=for-the-badge&logo=github)](https://github.com/salamandery)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Rodolfo%20Abreu-blue?style=for-the-badge&logo=linkedin)](https://linkedin.com/in/rodolfo-marques-ferreira-de-abreu/)

Sinta-se à vontade para entrar em contato para dúvidas, sugestões ou colaborações!

</div>

**EN:**

<div align="center">

**Rodolfo M. F. Abreu**  
Software developer passionate about technology, continuous learning, and best programming practices. Always looking for new challenges and opportunities to collaborate on innovative projects.

[![GitHub](https://img.shields.io/badge/GitHub-rodolfomfabreu-black?style=for-the-badge&logo=github)](https://github.com/salamandery)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Rodolfo%20Abreu-blue?style=for-the-badge&logo=linkedin)](https://linkedin.com/in/rodolfo-marques-ferreira-de-abreu/)

Feel free to get in touch for questions, suggestions, or collaborations!

</div>

---

<div align="center">
  <b>Feito com 💚 usando Node.js e Express para estudos de APIs REST.<br/>
  Made with 💚 using Node.js and Express for REST API studies.</b>
</div>

---

<div align="center" id="english-version">
  <b>🇺🇸 English version above | <a href="#top">🇧🇷 Versão em português acima</a></b>
</div>