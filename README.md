# Notes App

Full-stack notes application using React, Node.js, TypeScript, and PostgreSQL.

## Database setup

The backend uses Prisma with PostgreSQL. Install PostgreSQL locally and create a database named `notes_app`. Prisma 7 needs Node.js 22.12 or newer on Node 22, or Node.js 24.

```powershell
Copy-Item backend/.env.example backend/.env
Set-Location backend
npm install
npm run db:generate
npm run db:migrate
```

## Layout

- `backend/` — Node.js and TypeScript API/database code
- `frontend/` — React application, to be added in a later milestone
