# 🎨 Biblioteca Frontend

Interface web para consumo da Biblioteca API, permitindo interação completa com o sistema de gerenciamento de livros, usuários e empréstimos.

---

## 🚀 Tecnologias

* HTML5
* CSS3
* JavaScript (ES6+)
* Fetch API

---

## 🧱 Estrutura

```text
frontend/
├── index.html
├── livros.html
├── usuarios.html
├── emprestimos.html
├── css/
│   └── style.css
└── js/
    ├── api.js          # Comunicação com backend
    ├── livros.js       # Lógica da tela de livros
    ├── usuarios.js     # Cadastro de usuários
    └── emprestimos.js  # Controle de empréstimos
```

---

## ⚙️ Funcionalidades

* 📚 Listagem de livros com status de disponibilidade
* 👤 Cadastro de usuários
* 📘 Cadastro de livros
* 🔄 Registro de empréstimos
* ✅ Devolução de livros

---

## 🔌 Integração com API

A comunicação com o backend é feita via `fetch`:

```javascript
fetch("http://localhost:8080/livros")
  .then(res => res.json())
  .then(data => console.log(data));
```

---

## ▶️ Como executar

1. Certifique-se de que o backend está rodando
2. Abra qualquer arquivo `.html` no navegador

Exemplo:

```bash
frontend/livros.html
```

---

## ⚠️ Requisitos

* Backend rodando em `http://localhost:8080`
* Navegador moderno (Chrome, Edge, etc.)

---

## 📌 Próximos passos

* Melhorias de UI/UX
* Feedback visual (loading, mensagens)
* Deploy do frontend

---

## 🎯 Objetivo

Este projeto demonstra a integração completa entre frontend e backend, consolidando conhecimentos de desenvolvimento full stack.
