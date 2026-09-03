## Development

When starting the dev server, use background mode:

```
astro dev --background
```

Manage the background server with `astro dev stop`, `astro dev status`, and `astro dev logs`.

## Blog articles

Before creating, rewriting, or formatting any blog article, read and follow
`docs/blog-writing-guide.md` completely. Treat it as the canonical article
template and editorial specification.

- Put publishable articles in `src/content/blog/` as `.md` or `.mdx` files.
- Do not invent project architecture, metrics, implementation details, or
  conclusions. Inspect the referenced source project and its current code and
  documentation before writing about it.
- Use Markdown heading levels and structure from the writing guide. Do not add
  per-article font sizes, alignment, or inline presentation styles; article
  typography is controlled centrally by `src/layouts/BlogPost.astro`.
- Preserve the author's first-person, practical tone and write for project
  review, interviewer evaluation, and reader usefulness.
- After changing an article, run `npm.cmd run build` and report the result.

## Blog articles

Before creating, rewriting, or formatting any blog article, read and follow
`docs/blog-writing-guide.md` completely. Treat it as the canonical article
template and editorial specification.

- Put publishable articles in `src/content/blog/` as `.md` or `.mdx` files.
- Do not invent project architecture, metrics, implementation details, or
  conclusions. Inspect the referenced source project and its current code and
  documentation before writing about it.
- Use Markdown heading levels and structure from the writing guide. Do not add
  per-article font sizes, alignment, or inline presentation styles; article
  typography is controlled centrally by `src/layouts/BlogPost.astro`.
- Preserve the author's first-person, practical tone and write for project
  review, interviewer evaluation, and reader usefulness.
- After changing an article, run `npm.cmd run build` and report the result.

## Documentation

Full documentation: https://docs.astro.build

Consult these guides before working on related tasks:

- [Adding pages, dynamic routes, or middleware](https://docs.astro.build/en/guides/routing/)
- [Working with Astro components](https://docs.astro.build/en/basics/astro-components/)
- [Using React, Vue, Svelte, or other framework components](https://docs.astro.build/en/guides/framework-components/)
- [Adding or managing content](https://docs.astro.build/en/guides/content-collections/)
- [Adding styles or using Tailwind](https://docs.astro.build/en/guides/styling/)
- [Supporting multiple languages](https://docs.astro.build/en/guides/internationalization/)
