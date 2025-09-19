# Next E-commerce

Aplicação de **e-commerce de roupas** desenvolvida com **Next.js 15**, oferecendo uma solução moderna para venda de artigos de moda.  
O sistema possui **login social ou via e-mail/senha**, integração completa com **Stripe** para pagamentos e uma interface **responsiva (mobile-first)**.

## 🚀 Tecnologias Principais

- **Next.js 15** – Framework React com App Router  
- **React 19** – Biblioteca de UI  
- **Tailwind CSS 4** – Estilização com utilitários  
- **Radix UI** – Componentes acessíveis e modernos  
- **Lucide React** – Ícones  
- **Drizzle ORM** – ORM TypeScript-first para PostgreSQL  
- **PostgreSQL** – Banco de dados relacional  
- **Better Auth** – Autenticação segura (social login e e-mail/senha)  
- **Stripe** – Processamento de pagamentos  
- **React Query (TanStack Query)** – Gerenciamento de estado do servidor  
- **Zod** – Validação de dados  
- **React Hook Form** – Formulários com validação integrada  

## Banco de Dados

O projeto utiliza **Drizzle ORM** para gerenciar a persistência de dados com PostgreSQL. O sistema possui as seguintes entidades principais:

![Image](https://github.com/user-attachments/assets/d7e1d3bb-e53d-45bc-8dc3-6def262fe269)

## 📦 Funcionalidades

### 👤 Autenticação
- Login com e-mail/senha  
- Login social (Google, etc.)  
- Sessões seguras e gerenciamento de conta  

### 🛍️ E-commerce
- Listagem de produtos (roupas e acessórios)  
- Página de detalhes de produto  
- Carrinho de compras  
- Checkout integrado com Stripe  
- Histórico de pedidos  

### 💳 Pagamentos
- Integração com Stripe  
- Processamento de cartões de crédito/débito  
- Webhooks para sincronização de pedidos  

### 🎨 Interface
- Design responsivo (mobile-first)  
- Tema claro/escuro (next-themes)  
- Componentes acessíveis (Radix UI + Tailwind)  

### 📷 Telas da aplicação

![Image](https://github.com/user-attachments/assets/1aeb1512-32a8-45dd-b5b7-7211e5ee1436)

![Image](https://github.com/user-attachments/assets/74e9df1d-f8e5-4c0a-9b5d-f068f13bb84e)

![Image](https://github.com/user-attachments/assets/8dd77a83-be72-4942-b297-a1459d09a1c1)

![Image](https://github.com/user-attachments/assets/d819326f-cdf6-4722-8476-79fef84687b9)

![Image](https://github.com/user-attachments/assets/11fb5091-54c8-476e-9e42-c767a5fbb573)

![Image](https://github.com/user-attachments/assets/a6567159-a714-4f40-bfb4-1d28ea8db3c2)

## 🛠️ Como Rodar o Projeto

### 1. Clone o repositório
git clone https://github.com/seu-usuario/next-ecommerce.git
cd next-ecommerce

### 2. Instale as dependências
npm install

### 3. Configure as variáveis de ambiente
Crie um arquivo `.env` na raiz do projeto com as seguintes chaves (substitua pelos valores reais):
DATABASE_URL=******
BETTER_AUTH_SECRET=******
BETTER_AUTH_URL=******
GOOGLE_CLIENT_ID=******
GOOGLE_CLIENT_SECRET=******
NEXT_PUBLIC_STRIPE_PUBLISHABLE_KEY=******
STRIPE_SECRET_KEY=******
STRIPE_WEBHOOK_SECRET=******
NEXT_PUBLIC_APP_URL=******

### 4. Configure o banco de dados
# Execute as migrações
npm run db:generate
npm run db:migrate

### 5. Inicie o servidor de desenvolvimento
npm run dev

### 6. Acesse a aplicação
http://localhost:3000
