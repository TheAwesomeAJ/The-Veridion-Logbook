# The Veridion Logbook

## Structure
- apps/web — Next.js (App Router, Tailwind v4, Once UI)
- apps/mobile — Expo / React Native
- apps/api — Fastify + tRPC
- packages/auth — Better Auth config
- packages/db — Drizzle ORM + Postgres client
- packages/ui — shared component library
- packages/shared — shared business logic
- packages/types — shared TypeScript types
- tooling/eslint, tooling/typescript — shared configs

## Local dev
1. `pnpm install`
2. Copy `.env.example` files to `.env` / `.env.local` and fill in values
3. `pnpm dev` runs all apps in parallel via Turborepo