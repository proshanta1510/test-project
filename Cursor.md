# Cursor.md

Project instructions for Cursor when working in this repository.

## Project

- **Name:** test-Project
- **Status:** new / empty workspace
- **Goal:** Node.js app with TypeScript and Next.js

## Tech stack

- **Runtime:** Node.js
- **Language:** TypeScript (strict). Do not add new `.js` / `.jsx` files.
- **Framework:** Next.js (App Router)
- **UI:** React + TypeScript (`.tsx`)
- **Package manager:** npm
- **Env:** `.env.local` for secrets (never commit)

### Commands (after the app is scaffolded)

- **Dev:** `npm run dev`
- **Build:** `npm run build`
- **Start:** `npm start`
- **Lint:** `npm run lint`

### Expected layout

```
app/                 # Next.js App Router (pages, layouts, API routes)
  layout.tsx
  page.tsx
  api/               # Route handlers
components/          # Reusable UI
lib/                 # Shared helpers, clients, utils
public/              # Static assets
Cursor.md
package.json
tsconfig.json
next.config.ts
```

## How to work in this repo

- Read this file before making changes.
- Prefer small, focused edits over large rewrites.
- Do not invent files, APIs, or dependencies that are not needed.
- Match the existing style once code exists.
- Ask before committing, pushing, or deleting files unless the user asked for that.

## Language and communication

- The user may write in Bangla, Banglish, or English.
- Reply in the same language the user used, unless they ask otherwise.
- Keep explanations short and practical.

## TypeScript + Next.js conventions

- Use the App Router (`app/`), not the Pages Router (`pages/`), unless the user asks otherwise.
- Prefer Server Components by default. Add `"use client"` only when the file needs browser APIs, state, or event handlers.
- Type props, API payloads, and function returns. Avoid `any`.
- Put Route Handlers in `app/api/**/route.ts`.
- Use `next/link` and `next/image` instead of raw `<a>` / `<img>` when it fits.
- Keep server-only secrets out of Client Components.

## When adding code

- Create only the files needed for the current task.
- Include a README only if the user asks, or if the project has no way to run without one.
- Prefer clear names over clever names.
