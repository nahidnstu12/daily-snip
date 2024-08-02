# Daily Snip Project
This project is handy blog post regular basis, making simple authentication and making visible to public very quickly. Here, my motivation is daily blog posting and provide some admin privilige. This is totally my pet project.

### Tools
- Next 14
- Prisma ORM
- Postgres
- Typescript 
- Zod

## Configuration

### Create .env file from .env.example

```
cp .env.example .env
```

### Database Integration
1. Open .env file
2. Create a database and connect it with Next.js by adjusting the `DATABASE_URL` with your own configuration

### Migrate the Database Migration

```
npx prisma db push
```

## Installation

### Node Packages 
```
pnpm install
```

## Run App
```
pnpm run dev
```