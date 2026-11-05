# Blog

Roman's personal blog (developer, architect, AI). Astro static site, deployed to GitHub Pages by `.github/workflows/deploy.yml` on push to `main`.

- Posts live in `src/content/blog/*.md(x)`. Front matter schema is in `src/content.config.ts` (title, description, pubDate, optional updatedDate, heroImage, tags, draft).
- New posts start with `draft: true` until Roman says to publish.
- Write in Roman's voice: first person, plain and direct, short paragraphs, concrete examples and code. No hype.
- Site name and links are in `src/consts.ts`.
- Run `npm run build` before committing to catch front matter errors.
- When a custom domain is added: set `site` in `astro.config.mjs` and add `public/CNAME`.
