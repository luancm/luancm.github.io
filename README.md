# luancm.github.io

Personal site, served at https://luancm.github.io. Built with [Astro](https://astro.build).

## Development

```sh
npm install
npm run dev
```

Site runs at http://localhost:4321.

## Build

```sh
npm run build
npm run preview
```

Production build is emitted to `dist/`.

## Deploy

Push to `main`. The `.github/workflows/deploy.yml` workflow builds and publishes to GitHub Pages.

## Routes

- `/` - landing page
- `/oauth-redirect/` - generic OAuth-style redirect receiver (used by CLI tools, e.g. bankerlog)
