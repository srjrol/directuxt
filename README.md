[![nuxt-directus](https://raw.githubusercontent.com/Intevel/nuxt-directus/main/docs/public/cover.png)](https://nuxt-directus.site/)

# Nuxt Directus

[![npm version][npm-version-src]][npm-version-href]
[![npm downloads][npm-downloads-src]][npm-downloads-href]
[![License][license-src]][license-href]
[![Nuxt][nuxt-src]][nuxt-href]

A [Dockerized](https://www.docker.com/) setup for running [Nuxt](https://nuxt.com/)&[Directus](https://directus.io/) ([nuxt-directus](https://github.com/Intevel/nuxt-directus)).

Integrate  to your  application.

- [✨ &nbsp;Release Notes](https://github.com/directus-community/nuxt-directus/releases)
- [📖 &nbsp;Read the documentation](https://nuxt-directus.site/)

## Features

- Nuxt 3 ready
- Handle authentication
- RESTful methods
- TypeScript Support

## Setup

1. Clone the repository:
```bash
git clone https://github.com/srjrol/nuxt-directus-docker.git
cd nuxt-directus-docker
```
## Basic usage

Add `nuxt-directus` to your Nuxt config:

```javascript
// nuxt.config.ts

export default defineNuxtConfig({
  modules: ["nuxt-directus"],
});
```

## Development

1. Clone this repository
2. Install dependencies using `pnpm install` or `npm install`
3. Run `pnpm dev:prepare` or `npm run dev:prepare`
4. Start development server using `pnpm dev` or `npm run dev`

## License

Copyright (c) 2022 Conner Luka Bachmann
[MIT License](./LICENSE)

<!-- Badges -->

[npm-version-src]: https://img.shields.io/npm/v/nuxt-directus/latest.svg?style=flat&colorA=18181B&colorB=28CF8D
[npm-version-href]: https://npmjs.com/package/nuxt-directus
[npm-downloads-src]: https://img.shields.io/npm/dt/nuxt-directus.svg?style=flat&colorA=18181B&colorB=28CF8D
[npm-downloads-href]: https://npmjs.com/package/nuxt-directus
[license-src]: https://img.shields.io/npm/l/nuxt-directus.svg?style=flat&colorA=18181B&colorB=28CF8D
[license-href]: https://npmjs.com/package/nuxt-directus
[nuxt-src]: https://img.shields.io/badge/Nuxt-18181B?logo=nuxt.js
[nuxt-href]: https://nuxt.com
