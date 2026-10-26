# Daily Sport Admin

Standalone administration app for Daily Sport. It owns the admin UI, admin authentication, and admin API routes while sharing the existing database schema with the public app.

## Run locally

Install dependencies from this directory, configure the variables in `.env.local` using `.env.example`, then run `pnpm dev`.

Deploy this directory as its own Vercel project. The public Daily Sport app no longer needs to host the `/admin` route after the admin deployment is cut over.
