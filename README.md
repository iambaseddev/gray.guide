# Gray Guide

Source for [gray.guide](https://www.gray.guide), built with [Mintlify](https://mintlify.com).

- Pages are MDX files; their paths are their URLs.
- Site settings, navigation and redirects live in `docs.json`.
- Images are in `img/` and are referenced as `/img/<file>`.

## Local preview

```bash
npm i -g mint
mint dev
```

Run `mint validate` and `mint broken-links` before pushing. Pushing to `main` deploys the site.
