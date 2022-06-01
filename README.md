[![Content Wind](https://github.com/Atinux/content-wind/raw/main/public/cover.jpg)](https://content-wind.nuxt.dev)

# Clone: Content Wind

A lightweight Nuxt template to write a Markdown driven website, based on [Nuxt Content](https://content.nuxtjs.org), [TailwindCSS](https://tailwindcss.com) and [Iconify](https://iconify.design).

- [Demo & Docs](https://content-wind.nuxt.dev)
- [Play online](https://stackblitz.com/github/Atinux/content-wind?file=content%2F1.index.md)

## Features

- pnpm
- WindiCSS
- UnpluginIcons (no FOUC)
- SchemaOrg (todo)

## Usage

Take a look at [content-wind.nuxt.dev](https://content-wind.nuxt.dev) for the complete documentation.

## Setup

Make sure to install the dependencies:

```bash
# yarn
yarn install

# npm
npm install
```

## Development Server

Start the development server on http://localhost:3000

```bash
npm run dev
```

## Deployment

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2FAtinux%2Fcontent-wind) [![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/Atinux/content-wind)


### Static Hosting

Pre-render the website to be deployed on any static hosting:

```bash
npm run generate
```

The `dist/` directory is ready to be deployed (symlink to `.output/public`), [learn more on Nuxt docs](https://v3.nuxtjs.org/guide/deploy/static-hosting).

### Node server

Build the application for production:

```bash
npm run build
```

Start the server in production:

```bash
node .output/server/index.mjs
```

Learn more on [Nuxt docs](https://v3.nuxtjs.org/guide/deploy/node-server) for more information.
