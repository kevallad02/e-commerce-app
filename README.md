# Secure E-commerce Platform

Full-stack e-commerce platform built with Next.js (App Router), NestJS, and PostgreSQL.

## Repository Structure

- `frontend/`: Next.js app (App Router + Tailwind CSS)
- `backend/`: NestJS API server

## Getting Started

Install dependencies in each workspace:

```bash
cd frontend && npm install
cd ../backend && npm install
```

## Root Scripts

Run both apps in dev mode (requires root dependencies):

```bash
npm install
npm run dev
```

Run individually:

```bash
npm run dev:frontend
npm run dev:backend
```

Lint:

```bash
npm run lint
```

Format:

```bash
npm run format
```

## Notes

- Frontend uses Next.js App Router with Tailwind.
- Backend is a standard NestJS setup.
- Prisma is initialized in `backend/` with a PostgreSQL datasource.
- Update `backend/.env` with a real `DATABASE_URL` before running migrations.
- Copy `.env.example` to `backend/.env` (and optionally `frontend/.env.local`) to get started.
