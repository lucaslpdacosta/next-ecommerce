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

![Image](https://github.com/user-attachments/assets/a25af6da-9848-47bc-97b8-0d4cfdda4435)

![Image](https://github.com/user-attachments/assets/6871367b-cf32-461e-8514-923732ce57ec)

![Image](https://github.com/user-attachments/assets/163c2e8f-d003-4909-8657-124cd1bacfb4)

![Image](https://github.com/user-attachments/assets/33fb396f-6a98-4acd-bda4-01380f5f27a1)

![Image](https://github.com/user-attachments/assets/583b5293-eb22-402a-940c-edca0ee7cbaf)

![Image](https://github.com/user-attachments/assets/157cb487-a7a1-417e-afec-2b353f42eb99)

![Image](https://github.com/user-attachments/assets/441de237-a46f-4e77-b1ce-77a7b1bcb783)

## 🛠️ Como Rodar o Projeto

### 1. Clone o repositório
git clone https://github.com/seu-usuario/next-ecommerce.git

### 2. Instale as dependências
npm install

### 3. Configure as variáveis de ambiente
Crie um arquivo `.env` na raiz do projeto com as seguintes chaves (substitua pelos valores reais):
```sh
DATABASE_URL=******
BETTER_AUTH_SECRET=******
GOOGLE_CLIENT_ID=******
GOOGLE_CLIENT_SECRET=******
NEXT_PUBLIC_STRIPE_PUBLISHABLE_KEY=******
STRIPE_SECRET_KEY=******
STRIPE_WEBHOOK_SECRET=******
NEXT_PUBLIC_APP_URL=******
```

### 4. Configure o banco de dados
# Execute as migrações
```sh
npm run db:generate
npm run db:migrate
```

### 5. Inicie o servidor de desenvolvimento
npm run dev

### 6. Acesse a aplicação

```sh
http://localhost:3000
```

## Caso queira conferir a versão com deploy feito na Vercel:

- Escaneie o QR Code:

![Image](https://github.com/user-attachments/assets/5b64e4de-6de7-4d7b-a1e2-69bf46bd7088)

- Ou acesse este [Link](https://next-ecommerce-orpin-ten.vercel.app/).
