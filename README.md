![Logo](/src/assets/banner.png)

# Luno Academy

A Luno Academy é uma plataforma voltada para estudantes de programação, onde os alunos podem aprender por meio de cursos, interagir com a comunidade e compartilhar conhecimento.

O acesso é controlado manualmente — os alunos solicitam cadastro e o professor aprova ou recusa direto pelo Telegram.

---

## Stack

| Camada | Tecnologia |
|---|---|
| Frontend | React + Vite + TypeScript |
| Estilização | Tailwind CSS v3 |
| Estado global | Zustand |
| Requisições | TanStack Query v5 |
| Roteamento | React Router v6 |
| Ícones | Lucide React |
| Backend / Banco / Auth | Supabase |
| Notificações e aprovação | Telegram Bot API |

---

## Pré-requisitos

- [Node.js](https://nodejs.org) v18 ou superior
- Conta no [Supabase](https://supabase.com)
- Bot no Telegram criado via [@BotFather](https://t.me/BotFather)
- [Supabase CLI](https://supabase.com/docs/guides/cli) instalado

---

## Instalação

### 1. Clone o repositório

```bash
git clone https://github.com/seu-usuario/luno-academy.git
cd luno-academy
```

### 2. Instale as dependências

```bash
npm install
```

---

### 3. Rodando localmente

```bash
npm run dev
```

Acesse em [http://localhost:5173](http://localhost:5173).

---

## Estrutura do projeto

```
luno-academy/
├── src/
│   ├── components/
│   │   ├── layout/        # Sidebar e Layout principal
│   │   └── ui/            # Botões, Cards e componentes reutilizáveis
│   ├── hooks/             # useAuth e outros hooks
│   ├── lib/               # Cliente Supabase, funções de API e utilitários
│   ├── pages/             # Todas as páginas da aplicação
│   ├── store/             # Zustand (estado global de autenticação)
│   └── types/             # Tipos TypeScript do projeto
├── supabase/
│   ├── schema.sql                         # Schema completo do banco
│   └── functions/
└── .env
```

## Autores

- [@Rigby01](https://github.com/Rigby01)
- [@LuccasAlencar](https://github.com/LuccasAlencar)