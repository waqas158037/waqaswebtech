# Waqas Builds: portfolio

A cinematic, 3D one-page portfolio for **Muhammad Waqas (Shopify, WordPress & Custom Website Developer)**.

Next.js 15 · React 19 · Tailwind CSS 4 · Framer Motion · GSAP · React Three Fiber. No database, no environment variables, no setup.

## Deploy (GitHub + Vercel)

1. Create a new repository on [github.com/new](https://github.com/new) and upload the contents of this folder (or `git push` it).
2. On [vercel.com/new](https://vercel.com/new), import that repository. Vercel detects Next.js automatically.
3. Click **Deploy**. Done.

Every time you push a change to GitHub, Vercel rebuilds and updates the site automatically.

Custom domain: Vercel → Project → Settings → Domains. *(Optional)* add an environment variable
`NEXT_PUBLIC_SITE_URL=https://yourdomain.com` so Google and social previews use your domain. Without it the Vercel address is used.

## Run locally

```bash
npm install
npm run dev     # http://localhost:3000
```

Requires Node 20+. Production check: `npm run build && npm start`.

## Editing content

All content is in plain files. Edit, commit, push, and Vercel updates the site.

| What | File |
| --- | --- |
| Name, role, email, WhatsApp, Instagram, Facebook, LinkedIn, SEO title | `src/data/profile.ts` |
| Websites in *Selected Work* | `src/data/work.ts` (screenshots in `public/work/`) |
| Experience | `src/data/experience.ts` |
| Services | `src/data/services.ts` |
| Skills | `src/data/skills.ts` |
| Process / why work with me | `src/data/process.ts` |
| Photo | `public/waqas.webp` |

To add a website: put a full-page screenshot (about 800 px wide, WEBP) in `public/work/`, then copy an entry in `work.ts` and change its details.

## Content sources

All copy comes from Muhammad Waqas's resume and the links he supplied. Nothing was invented. The only statistics shown (3+ years, 350+ websites, 200+ at Loops Technologies, 4 companies) are stated in the resume.
