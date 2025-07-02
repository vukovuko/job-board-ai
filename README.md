# AI Job Board

This is a Next.js project using Clerk for authentication, Inngest for background jobs, Drizzle ORM with PostgreSQL, Resend for emails and AI searching for job listings.

## Getting Started

Start the database and development server:

```bash
npm install
docker compose up
npm run db:generate    # only needed if schema has changed
npm run db:migrate
npm run dev
```
