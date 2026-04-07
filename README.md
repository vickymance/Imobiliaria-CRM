# Projeto de Portifólio - CRM Imobiliária VMR

Sistema completo de CRM imobiliário com arquitetura fullstack, composto por backend (API REST) e frontend web.

O projeto simula a operação de um corretor de imóveis, permitindo gestão de clientes, imóveis e relacionamento comercial (follow-up e pipeline).

---

## 📌 Arquitetura do Projeto

O sistema está organizado em um modelo monorepo:

```
Imobiliaria-CRM/
├── backend/   → API REST (Node.js + Express)
├── frontend/  → Interface Web (HTML, CSS, JS)
```

---

## 🚀 Tecnologias

### Backend
- Node.js
- Express
- JWT
- Swagger (OpenAPI)
- Arquitetura MVC

### Frontend
- HTML
- CSS (Bulma)
- JavaScript (Vanilla)
- Fetch API

---

## ⚙️ Pré-requisitos

- Node.js
- npm
- Navegador (Chrome recomendado)
- VS Code (opcional)

---

## 🔧 Setup

### 1. Clonar o repositório

```bash
git clone https://github.com/vickymance/Imobiliaria-CRM.git
cd Imobiliaria-CRM
```

---

### 2. Executar Backend

```bash
cd backend
npm install
npm run dev
```

API disponível em:
```
http://localhost:3000
```

Swagger:
```
http://localhost:3000/api-docs
```

---

### 3. Executar Frontend

Abrir:
```
frontend/index.html
```

Ou usar Live Server no VS Code.

---

## 🔐 Autenticação

- Login:
```
POST /auth/login
```

- Token salvo em:
```
localStorage
```

- Header:
```
Authorization: Bearer TOKEN
```

---

## 📡 Funcionalidades

### 🏠 Imóveis
- Cadastro, listagem, edição e exclusão
- Visualização detalhada
- Vinculação com clientes

### 👥 Clientes
- CRUD completo
- Edição via modal
- Exclusão com confirmação

### 📞 Follow-up
- Histórico de interações
- Próxima atualização

### 📊 Pipeline
- Frio | Morno | Quente

### ⏰ Prioridade
- 🔴 Atrasado
- 🟡 Hoje
- 🟢 Futuro

### 🖼️ Imagens
- Upload (PNG/JPEG)
- URL + base64
- Galeria e viewer
- Remoção de imagens inválidas

---

## 📁 Estrutura

### Backend
```
backend/
├── src/
├── package.json
```

### Frontend
```
frontend/
├── index.html
├── js/
├── css/
```

## 👨‍💻 Autor

Projeto de portfólio fullstack.
