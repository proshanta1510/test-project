# test-Project

A Node.js project for building a **Next.js** app with **TypeScript**.

Author: **proshanta**

## Tech stack

- Node.js
- TypeScript (strict)
- Next.js App Router
- React (`.tsx`)
- npm

## Current status

The repo is in early setup. `package.json` and `Cursor.md` are in place. Next.js itself is not scaffolded yet, so `npm run dev` is not available until the app is created.

## Getting started

**Requirements:** Node.js (LTS) and npm.

```bash
npm install
```

When the Next.js app is added, use:

```bash
npm run dev      # local development
npm run build    # production build
npm start        # run the production build
npm run lint     # lint
```

## Project layout (planned)

```
app/                 # Next.js App Router (pages, layouts, API routes)
components/          # Reusable UI
lib/                 # Shared helpers
public/              # Static assets
Cursor.md            # AI / Cursor project instructions
package.json
```

## Environment

Put secrets in `.env.local`. Do not commit that file.

## License

ISC
