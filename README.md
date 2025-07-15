# Fullstack Todo

A full-stack Todo app with persistent storage, built to demonstrate full CRUD functionality using modern web technologies.

## 🛠 Tech Stack

- **Frontend**: React, Vite, TypeScript, Redux Toolkit
- **Backend**: Node.js, Express, TypeScript
- **Database**: PostgreSQL with Prisma ORM

---

## 📁 Project Structure

```
/
├── client/   → React frontend
├── server/   → Express backend with Prisma
```

---

## 🚀 Getting Started

### 1. Clone the repository

```
git clone https://github.com/TSherpa1/fullstack-todo.git
cd fullstack-todo
```

### 2. Install dependencies

```
# Frontend
cd client && npm install

# Backend
cd ../server && npm install
```

### 3. Run the app

```
# In client/
npm run dev

# In server/
npx prisma generate
npx ts-node-dev src/index.ts
```

---
