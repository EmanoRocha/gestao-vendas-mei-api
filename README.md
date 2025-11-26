# 🚀 Sistema de Gestão de Vendas MEI (FRONT-END + BACK-END)

Sistema completo de gestão de vendas desenvolvido para Microempreendedores Individuais (MEIs), com frontend moderno e backend robusto.

---

# 🎨 FRONT-END — Gestão de Vendas MEI

Sistema moderno de gestão de vendas para MEIs, desenvolvido com **React, TypeScript e shadcn/ui**.

---

## ✨ Funcionalidades

### 🔐 Autenticação
- Login seguro com JWT  
- Registro de novos usuários  
- Proteção de rotas privadas  
- Logout automático com token expirado  

### 📊 Dashboard Executivo
- Resumo mensal e anual de vendas  
- Ticket médio calculado automaticamente  
- Produtos mais vendidos (ranking)  
- Vendas por categoria (visual)  
- Vendas por dia do mês  
- Exportação JSON e CSV  

### 🛍️ Gestão de Vendas
- Listagem paginada  
- Cadastro de novas vendas  
- Filtros por período  
- Cálculo automático dos valores  

### 📦 Gestão de Produtos
- Catálogo organizado  
- Cadastro e edição  
- Categorização  
- Status ativo/inativo  

---

## 🎨 Sistema de Design — shadcn/ui

### Componentes
- Cards responsivos  
- Botões com variantes  
- Inputs com validação  
- Layout com sidebar  
- Feedback visual e loading  

### Tema
- Cores primárias azul profissional  
- Tipografia limpa  
- Layout responsivo  

---

## 🛠️ Tecnologias

### Core
- React 19  
- TypeScript  
- React Router DOM  
- Axios  

### UI/UX
- shadcn/ui  
- Tailwind CSS  
- Radix UI  
- Lucide Icons  

### Desenvolvimento
- React Scripts  
- ESLint  
- PostCSS  

---

## 🚀 Como Executar (Frontend)

### Pré-requisitos
- Node.js 18+  
- NPM ou Yarn  
- API rodando em **http://localhost:3333/api**

### Instalação
```bash
git clone <repo>
cd Vendas-App-Frontend
npm install
npm start


Configuração da API

Alterar o arquivo:

src/services/api.ts

const API_BASE_URL = 'http://localhost:3333/api';

📱 Páginas e Rotas
Públicas

/login

/register

Privadas

/dashboard

/vendas

/produtos

/venda-form

🔧 Estrutura do Projeto (Frontend)
src/
├── components/
│   ├── ui/
│   ├── Layout.tsx
│   └── ProtectedRoute.tsx
├── pages/
│   ├── Dashboard.tsx
│   ├── Login.tsx
│   ├── Register.tsx
│   └── Vendas.tsx
├── services/
│   └── api.ts
├── lib/
│   └── utils.ts
└── context/
    └── VendaContext.tsx

🎯 Funcionalidades Implementadas (Frontend)

Autenticação completa

Dashboard moderno

Layout responsivo

Integração total com API

Exportações

Loading e feedback visual

🔮 Próximas Funcionalidades

Relatórios avançados

Gestão de estoque

Modo escuro

Temas customizáveis

PWA

🚀 BACK-END — Gestão de Vendas MEI API

API REST desenvolvida com NestJS + Prisma para controlar vendas, produtos, usuários e relatórios.

🎯 Sobre o Projeto

A API oferece:

Controle financeiro

Registro de vendas

Gestão de produtos

Relatórios

Exportações

Análises

👤 Gestão de Usuários

Cadastro

Login com JWT

Perfil MEI

Segurança com Passport

📦 Gestão de Produtos

CRUD completo

Categorias

Status

Mais vendidos

💰 Gestão de Vendas

Registro rápido

Histórico completo

Filtros por período

Cálculo automático

📊 Relatórios e Analytics

Dashboard

Comparativos

JSON/CSV

Ticket médio

🛠 Tecnologias

NestJS (Node + TypeScript)

Prisma ORM

MySQL

JWT + Passport

Swagger (em desenvolvimento)

📋 Pré-requisitos

Node 18+

MySQL 8+

npm/pnpm

🔧 Instalação (Backend)
Clone
git clone <repo>
cd Vendas-API

Instale as dependências
npm install

Configure o Banco

Crie o banco:

CREATE DATABASE vendas_db;

Configure as variáveis
cp .env.example .env


Exemplo:

DATABASE_URL="mysql://usuario:senha@localhost:3306/vendas_db"
JWT_SECRET="jwt-super-secreto"
JWT_EXPIRES_IN="7d"
PORT=3000

Migrações
npx prisma generate
npx prisma db push

Executar

Dev:

npm run start:dev


Produção:

npm run build
npm run start:prod

🔌 Uso da API
Autenticação

Todas as rotas (exceto login/registro) usam Bearer Token.

📚 Endpoints
🔐 Auth

POST /api/auth/register

POST /api/auth/login

👤 Usuários

GET /api/users

GET /api/users/:id

PATCH /api/users/:id

DELETE /api/users/:id

📦 Produtos

GET /api/produtos

POST /api/produtos

GET /api/produtos/:id

PATCH /api/produtos/:id

DELETE /api/produtos/:id

GET /api/produtos/categoria/:categoria

GET /api/produtos/mais-vendidos

💰 Vendas

GET /api/vendas

POST /api/vendas

GET /api/vendas/:id

PATCH /api/vendas/:id

DELETE /api/vendas/:id

GET /api/vendas/periodo

GET /api/vendas/resumo-mensal

📊 Relatórios

GET /api/relatorios/dashboard

GET /api/relatorios/comparativo-mensal

GET /api/relatorios/detalhado

GET /api/relatorios/exportar

🔍 Sistema

GET /api

GET /api/health

📁 Estrutura do Projeto (Backend)
src/
├── auth/
│   ├── dto/
│   ├── guards/
│   └── strategies/
├── common/
│   └── dto/
├── prisma/
├── produtos/
├── relatorios/
├── users/
├── vendas/
├── app.module.ts
└── main.ts

🎨 Padrões

Arquitetura modular

DTOs

JWT + Guards

Prisma ORM

Swagger (em breve)

🤝 Contribuição

Fork

Crie uma branch

Commit

Push

Pull Request

📄 Licença

MIT

👨‍💻 Autor

Desenvolvido com ❤️ para ajudar MEIs brasileiros a crescerem.
