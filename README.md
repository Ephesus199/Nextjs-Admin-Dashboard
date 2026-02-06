# Simple Next.js Admin Dashboard

Live demo: https://simple-nextjs-admin-dashboard.vercel.app/

A minimal, responsive admin dashboard built with Next.js and shadcn/ui components. This project provides a clean starter for admin interfaces, with tables, charts, sidebar navigation, and example pages for users and payments.

## Features

- Clean, responsive admin layout with sidebar and top navigation
- Example pages: Users list, Payments table, User profile
- Charts and data visualizations (line, bar, pie) using reusable components
- UI primitives from a shadcn-style `ui/` component library
- Accessibility-minded components and keyboard-friendly navigation
- Ready for Vercel deployment (Demo hosted on Vercel)

## Tech stack

- Next.js (App Router)
- TypeScript
- Tailwind CSS (postcss config included)
- React + shadcn-style UI primitives

## Demo

Visit the live demo: https://simple-nextjs-admin-dashboard.vercel.app/

## Getting started (Local development)

Prerequisites:

- Node.js 18+ and npm (or pnpm)

Install dependencies:

```bash
npm install
```

Run the development server:

```bash
npm run dev
```

Open http://localhost:3000 in your browser.

Build for production:

```bash
npm run build
npm run start
```

Lint & format (if configured):

```bash
npm run lint
```

## Environment variables

This starter does not require any secret environment variables to run the demo. If you add integrations (APIs, auth, databases), store secrets in a `.env.local` file and do not commit them.

## Project structure (important files)

- `app/` — Next.js App Router pages and route handlers
- `components/` — App-specific components (charts, sidebar, navbar)
- `ui/` — Reusable UI primitives (button, input, table, etc.)
- `hooks/` — Custom hooks (e.g., `use-mobile.ts`)
- `lib/` — Utilities
- `public/` — Static assets

Key files:

- [app/layout.tsx](app/layout.tsx#L1) — Root layout and providers
- [app/page.tsx](app/page.tsx#L1) — Dashboard home
- [components/AppSidebar.tsx](components/AppSidebar.tsx#L1) — Sidebar navigation
- [components/Navbar.tsx](components/Navbar.tsx#L1) — Top navigation

## Customization

- To change theme colors, edit Tailwind config and CSS in `app/globals.css`.
- Add or remove pages under `app/` following Next.js App Router conventions.
- Reuse UI primitives in `ui/` to keep consistent styling across the app.

## Deployment

This project is ready for Vercel. To deploy:

1. Push to GitHub.
2. Import the repo in Vercel and set the root to the repository.
3. Set any environment variables in the Vercel dashboard (if needed).

The demo is hosted at: https://simple-nextjs-admin-dashboard.vercel.app/



