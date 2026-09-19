# Ledger — Personal Finance Tracker

A full-stack web app for tracking personal income and expenses, built as a
second-year CS project to practice the full stack: authentication, a REST
API, a relational database, and a React frontend working together.

## Features
- Secure authentication with bcrypt password hashing and JWT sessions
- Full CRUD for transactions — create, list (with pagination and filters),
  update, and delete, all scoped to the logged-in user
- Currency stored safely as integer cents to avoid floating-point rounding
  errors
- A dashboard showing income, expenses, and running balance at a glance

## Tech stack
**Frontend:** React, TypeScript, Vite, Tailwind CSS, React Router
**Backend:** Node.js, Express, TypeScript
**Database:** PostgreSQL, Prisma ORM
**Auth:** JWT, bcrypt

## Getting started
See `README.md` inside for full setup instructions — you'll need Node.js
and a PostgreSQL database (a free [Neon](https://neon.tech) instance works
well for local development).
