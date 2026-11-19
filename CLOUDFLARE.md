# Cloudflare Pages staging

Staging project: vice-capital (vice-capital.pages.dev), created 2026-11-19.
It builds this branch with `npm run build` into `dist`.

Production stays on Vercel at gta6.wxza.net until a cutover is approved.
The /api functions still run on Vercel only; the live stock quote does not
work on staging yet. No environment secrets are set on the Pages project.
