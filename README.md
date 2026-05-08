# Motiv

> Your AI-powered task manager that keeps you moving.

Motiv is a fullstack SaaS task manager built with **React**, **Node.js**,
and **AI** — designed to help you organize your work, prioritize
what matters, and actually get things done.

## Features

- Auth — JWT-based register & login with protected routes
- Tasks — Create, edit, delete and track task status
- Kanban — Visual board with drag-and-drop (todo / in progress / done)
- AI — "Organize my tasks" and "Summarize my day" powered by OpenAI
- Responsive — Mobile-first design, works everywhere

## Tech stack

| Layer    | Tech                              |
|----------|-----------------------------------|
| Frontend | React + Vite + TailwindCSS        |
| Backend  | Node.js + Express                 |
| Database | MongoDB + Mongoose                |
| Auth     | JWT + bcrypt                      |
| AI       | OpenAI API (gpt-4o-mini)          |
| Deploy   | Vercel (frontend) + Render (API)  |

## Live demo

[motiv-app.vercel.app](https://motiv-app.vercel.app) · [API docs](#)

## Getting started

```bash
# Backend
cd backend && npm install && npm run dev

# Frontend
cd frontend && npm install && npm run dev
```

## Author

Built by [Luis Pedro Solares Serrano](https://github.com/Lpsolaress)
as a portfolio project — open to work.
