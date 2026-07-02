# 🚀 PostBoy - Modern Postman Clone

A powerful and modern **Postman Clone** built with the latest web technologies.  
PostBoy helps developers create, test, and manage API requests with a clean and intuitive interface.

> ⚡ Built using **Next.js 16**, **TypeScript**, **Prisma**, **PostgreSQL**, **Docker**, and **shadcn/ui**.

---

## 📸 Preview

> 🚧 Project is currently under active development.

---

# ✨ Features

- 🔐 Secure Authentication
- 📁 Workspace Management
- 📂 API Collections
- 🌐 HTTP Request Builder
- 📜 Request History
- 💾 Save API Requests
- ⚡ Fast & Responsive UI
- 🌙 Dark / Light Theme
- 🔍 Search Collections
- 📊 API Response Viewer
- 🛠 Modern Dashboard
- 📱 Fully Responsive

---

# 🛠 Tech Stack

## Frontend

- Next.js 16
- React 19
- TypeScript
- Tailwind CSS v4
- shadcn/ui
- Radix UI
- Lucide React

## Backend

- Next.js Server Actions
- Prisma ORM
- PostgreSQL

## State Management

- Zustand
- TanStack Query

## Authentication

- Better Auth

## Validation

- Zod

## Database

- PostgreSQL
- Prisma ORM

## DevOps

- Docker
- Docker Compose

---

# 📂 Project Structure

```bash
postboy/
│
├── app/
├── components/
├── lib/
├── prisma/
├── public/
├── hooks/
├── actions/
├── providers/
├── docker-compose.yml
├── package.json
└── README.md
```

---

# 🚀 Getting Started

## Clone Repository

```bash
git clone https://github.com/your-username/postboy.git
```

```bash
cd postboy
```

---

## Install Dependencies

```bash
npm install
```

---

## Setup Environment Variables

Create a `.env` file.

```env
DATABASE_URL="postgresql://postgres:postgres@localhost:5432/postboy?schema=public"
```

---

## Start PostgreSQL

```bash
docker compose up -d
```

---

## Generate Prisma Client

```bash
npx prisma generate
```

---

## Run Database Migration

```bash
npx prisma migrate dev
```

---

## Start Development Server

```bash
npm run dev
```

---

# 📦 Available Scripts

```bash
npm run dev
```

Starts development server.

```bash
npm run build
```

Build production application.

```bash
npm run start
```

Start production server.

---

# 🐳 Docker

Start PostgreSQL

```bash
docker compose up -d
```

Stop PostgreSQL

```bash
docker compose down
```

View Running Containers

```bash
docker ps
```

---

# 🗄 Database

Database is managed using **Prisma ORM**.

Generate Prisma Client

```bash
npx prisma generate
```

Create Migration

```bash
npx prisma migrate dev --name migration_name
```

Open Prisma Studio

```bash
npx prisma studio
```

---

# 🎯 Project Goals

This project is built to:

- Learn Modern Full Stack Development
- Master Next.js 16
- Learn Docker & PostgreSQL
- Build Production Ready Applications
- Understand Clean Architecture
- Improve Backend Skills

---

# 🚀 Upcoming Features

- ✅ Authentication
- ✅ User Dashboard
- ✅ Collections
- ✅ Request History
- ✅ Environment Variables
- ✅ Import/Export Collections
- ✅ API Testing
- ✅ Team Collaboration
- ✅ AI Request Generator
- ✅ Code Snippets
- ✅ GraphQL Support

---

# 🤝 Contributing

Contributions, issues and feature requests are welcome.

Feel free to fork the repository and create a Pull Request.

---

# 👨‍💻 Author

**Hardeep Singh**

GitHub:
https://github.com/your-github

LinkedIn:
https://linkedin.com/in/your-linkedin

---

# ⭐ Support

If you like this project, consider giving it a ⭐ on GitHub.

It motivates me to build more open-source projects.

---

## 💙 Built with passion using Next.js, Prisma, Docker & PostgreSQL.
