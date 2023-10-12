# Nuxt-Directus Dockerized Deployment

Forked from [Intevel/nuxt-directus](https://github.com/Intevel/nuxt-directus), this project dockerizes the Nuxt-Directus application for easy deployment.

## Features

| Feature                                                         | Description                                                   |
|-----------------------------------------------------------------|---------------------------------------------------------------|
| 🐳 Dockerized Deployment                                        | Simplifies the setup and deployment process.                  |
| 🐰 [Directus Integration](https://github.com/directus/directus) | Open-source headless CMS and API.                             |
| 🛠️ [Nuxt Devtools](https://github.com/nuxt/devtools)           | Debugging tools for Nuxt.js.                                  |
| 🖥️ [Nuxt UI](https://github.com/nuxt/ui)                       | A UI Kit for building Nuxt modules and projects.             |
| 🍬 [Tailwind CSS](https://github.com/nuxt-modules/tailwindcss)  | Add Tailwind CSS to your Nuxt Applications.                  |
| 🌗 [Nuxt Color Mode](https://github.com/nuxt-modules/color-mode)| Dark and Light mode with auto detection.                     |
| 🛸 [ufo](https://github.com/unjs/ufo)                          | Utilities to work with URLs across Nuxt projects.            |
| 📜 [TypeScript Support](https://github.com/microsoft/TypeScript)| Ensures type safety in your project.                          |
| 🚀 [Nuxt 3](https://github.com/nuxt/nuxt)                      | Compatible with the latest version of Nuxt.                   |
| 🔗 RESTful methods                                              | Convenient way to access or update resources on the server.  |
| 🔑 Environment Variables                                        | Easily configure your app settings.                           |

1. Clone the repository:
   ```bash
   git clone https://github.com/srjrol/nuxt-directus-docker
   cd nuxt-directus-docker
   ```

2. Setup your environment variables:
   Copy the `.env.example` to a new file named `.env` and update the variables as needed.
   ```bash
   cp .env.example .env
   ```

## Deployment

1. Build and run the Docker containers:
   ```bash
   docker-compose up --build -d
   ```

2. Access the application:
   - 🚀 Nuxt App: `http://localhost:3000`
   - 🐰 Directus Admin: `http://localhost:8055`

## Environment Variables Reference Table

| Variable                                       | Description                                                   |
|------------------------------------------------|---------------------------------------------------------------|
| `POSTGRES_USER`                                | PostgreSQL username                                           |
| `POSTGRES_PASSWORD`                            | PostgreSQL password                                           |
| `POSTGRES_DB`                                  | PostgreSQL database name                                      |
| `DIRECTUS_URL`                                 | Directus URL                                                  |
| `DIRECTUS_KEY`                                 | Directus Key                                                  |
| `DIRECTUS_SECRET`                              | Directus Secret                                               |
| `ADMIN_EMAIL`                                  | Admin email for Directus                                      |
| `ADMIN_PASSWORD`                               | Admin password for Directus                                   |
| `PUBLIC_URL`                                   | Public URL for Directus                                       |
| `CONTENT_SECURITY_POLICY_DIRECTIVES__FRAME_ANCESTORS` | Content Security Policy Directives for frame ancestors |
| `API_URL`                                      | API URL for Nuxt                                              |
| `NUXT_PUBLIC_DIRECTUS_URL`                     | Public Directus URL for Nuxt                                  |
| `NUXT_PUBLIC_API_BASE`                         | Public API base URL for Nuxt                                  |

## Integrate  to your  application.

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

## Development

1. Clone this repository
2. Install dependencies using `pnpm install` or `npm install`
3. Run `pnpm dev:prepare` or `npm run dev:prepare`
4. Start development server using `pnpm dev` or `npm run dev`

# Todo

- [ ] Optimize Dockerfile for faster build times.
- [ ] Add a Makefile to simplify build and deploy commands.
- [ ] Implement a logging system for troubleshooting and monitoring.
- [ ] Add authentication and authorization for enhanced security.
- [ ] Upgrade to the latest versions of Nuxt and Directus.
- [ ] Document the setup and deployment process in more detail.
- [ ] Create a backup and restore process for the database.
- [ ] Add CI/CD integration for automated testing and deployment.
- [ ] Improve error handling and add proper error messages.
- [ ] Include a feature for data migration and schema updates.

## License

Copyright (c) 2022 Sean Jennings, originally developed by Conner Luka Bachmann
[MIT License](./LICENSE)

## Additional Resources

- Repository: [https://github.com/srjrol/nuxt-directus-docker](https://github.com/srjrol/nuxt-directus-docker)
- Forked From: [https://github.com/Intevel/nuxt-directus](https://github.com/Intevel/nuxt-directus)