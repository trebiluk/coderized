# Coderized

Solvay Middle School Technology — Chromebook coding arena.
NYS MST Standard 5. Aliases only. No phones.

## User origin (cart)

**https://coderized.kulibert.net/**

Chrome → Create shortcut → Open as window. Phones stay in lockers.

## Alias on the desk

**https://tw.kulibert.net/coderized/**

Same Cloudflare Pages project (`kulibert-desk`). Soft-pins to the user origin when that host answers.

## Light the origin

DNS for `coderized.kulibert.net` already exists.

1. Cloudflare (preferred): Pages → `kulibert-desk` → Custom domains → add `coderized.kulibert.net`. Point DNS at this Pages project the same way as `tw.kulibert.net`. Desk middleware serves the PWA at `/` on that host.
2. Vercel fallback: import `trebiluk/coderized`, framework Other, output `.`. Domain already CNAMEs to `cname.vercel-dns.com`.

Class code: `QUEST4`.
