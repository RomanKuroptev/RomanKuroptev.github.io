# romankuroptev.github.io

My blog on software architecture, AI and the things I build. Built with [Astro](https://astro.build) and published to GitHub Pages on every push to `main`.

## Write a post

1. Add a Markdown file to `src/content/blog/`, for example `my-post.md`. The file name becomes the URL (`/blog/my-post/`).
2. Start it with this front matter:

   ```md
   ---
   title: 'My post'
   description: 'One sentence shown in lists and previews.'
   pubDate: '2026-11-05'
   tags: ['ai']
   draft: true   # remove or set false to publish
   ---
   ```

3. Push to `main`. The site rebuilds in about a minute.

Images go next to the post or in `src/assets/` and are referenced with a relative path. You can also use `.mdx` to embed components.

## Run locally

```sh
npm install
npm run dev      # http://localhost:4321
npm run build    # output in dist/
```
