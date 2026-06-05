# 🏋️ Fit-IA API

API inteligente para geração e gerenciamento de planos de treino personalizados utilizando Inteligência Artificial.

## 📖 Sobre o Projeto

O Fit-IA é uma API desenvolvida para auxiliar usuários na criação de treinos personalizados com base em seus objetivos, nível de experiência e informações físicas.

A aplicação utiliza IA Generativa para interpretar dados do usuário e criar planos de treino estruturados automaticamente.

---

## 🚀 Tecnologias Utilizadas

### Backend
- Node.js
- TypeScript
- Fastify

### Banco de Dados
- PostgreSQL
- Prisma ORM

### Inteligência Artificial
- Google Gemini
- AI SDK

### Autenticação
- Better Auth

### Documentação
- Swagger
- Scalar API Reference

### DevOps
- Docker
- Docker Compose

### Validação
- Zod

---

## 🏗️ Arquitetura

```text
src/
├── routes/         # Rotas da aplicação
├── usecases/       # Regras de negócio
├── schemas/        # Validação de dados
├── lib/            # Configurações e integrações
├── errors/         # Tratamento de erros
└── server.ts       # Inicialização da API
```

A aplicação segue uma arquitetura baseada em Casos de Uso (Use Cases), promovendo maior organização e facilidade de manutenção.

---

## ⚙️ Funcionalidades

### 👤 Usuários
- Cadastro de usuário
- Login
- Autenticação

### 🏋️ Treinos
- Criação de plano de treino
- Listagem de treinos
- Atualização de treinos
- Estatísticas do usuário

### 🤖 IA
- Geração automática de planos de treino
- Personalização baseada em objetivos
- Atualização dinâmica de informações do usuário

### 📄 Documentação
- Swagger UI
- Scalar API Reference

---

## 📦 Instalação

### Clonar o repositório

```bash
git clone https://github.com/devantonio27/Fit-ia.git
```

```bash
cd Fit-ia
```

### Instalar dependências

```bash
npm install
```

### Configurar variáveis de ambiente

Crie um arquivo `.env`:

```env
DATABASE_URL=
GEMINI_API_KEY=
BETTER_AUTH_SECRET=
BETTER_AUTH_URL=
```

---

## 🐳 Executando com Docker

```bash
docker compose up -d
```

---

## 🗄️ Executando as migrations

```bash
npx prisma migrate dev
```

---

## ▶️ Executando o projeto

Modo desenvolvimento:

```bash
npm run dev
```

Modo produção:

```bash
npm run build
npm start
```

---

## 📚 Documentação da API

Após iniciar a aplicação:

Swagger:

```bash
http://localhost:3333/docs
```

Scalar:

```bash
http://localhost:3333/reference
```

---

## 🔗 Principais Endpoints

### Usuários

```http
POST /users
```

```http
POST /login
```

---

### Treinos

```http
POST /workout-plan
```

```http
GET /workout-plan
```

```http
GET /stats
```

---

### IA

```http
POST /ai/chat
```

---

## 💡 Motivação

Este projeto foi desenvolvido com o objetivo de aprofundar conhecimentos em:

- Arquitetura Backend
- TypeScript
- Fastify
- Prisma ORM
- PostgreSQL
- Docker
- Inteligência Artificial Generativa
- Integração com APIs modernas

---

## 📈 Próximos Passos

- [ ] Testes unitários
- [ ] Testes de integração
- [ ] CI/CD com GitHub Actions
- [ ] Deploy em produção
- [ ] Monitoramento e logs
- [ ] Frontend em React

---

## 👨‍💻 Autor

Desenvolvido por **Antonio Carlos**

- GitHub: https://github.com/devantonio27
- LinkedIn: adicionar link

---

## 📄 Licença

Este projeto está sob a licença MIT.
