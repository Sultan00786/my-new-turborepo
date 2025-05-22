# SampleProject Turborepo

This is a custom Turborepo setup featuring one frontend app and two backend servers using modern tooling and a monorepo architecture.

## Using this starter

Run the following command to create a new project based on this template:

```sh
git clone https://github.com/Sultan00786/my-new-turborepo.git
```

## What's inside?

This Turborepo includes the following apps and packages:

### Apps

- `web`: a [Next.js](https://nextjs.org/) frontend application
- `https-server`: a backend server using HTTPS (e.g., Express or Node's HTTPS module)
- `websocket-server`: a backend server handling WebSocket connections

### Packages

- `@sample/ui`: shared React UI components used by multiple apps
- `@sample/eslint-config`: shared ESLint configuration
- `@sample/typescript-config`: base tsconfig used throughout the monorepo

All apps and packages are written in [TypeScript](https://www.typescriptlang.org/).

## Utilities

This monorepo includes the following tools:

- [TypeScript](https://www.typescriptlang.org/) for static type checking
- [ESLint](https://eslint.org/) for code linting
- [Prettier](https://prettier.io) for code formatting
- [Turborepo](https://turbo.build/repo) for monorepo build orchestration

## Run in Development

To run all apps and packages simultaneously in local, run the following command:

```sh
pnpm run dev
```

## Build

To build all apps and packages, run the following command:

```sh
pnpm run build
```

## Useful Links

- [Turborepo Tasks](https://turbo.build/repo/docs/core-concepts/monorepos)
- [Caching](https://turbo.build/repo/docs/features/caching)
- [Remote Caching](https://turbo.build/repo/docs/ci/remote-caching)
- [Configuration](https://turbo.build/repo/docs/reference/configuration)
- [Command Line Usage](https://turbo.build/repo/docs/reference/command-line-reference)
