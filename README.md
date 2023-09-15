# Turborepo kitchen sink starter

Replaces [Express](https://expressjs.com/) with [NestJS](https://docs.nestjs.com/) for API implementation in the official [Kitchen Sink](https://github.com/vercel/turbo/tree/15abc2564fe0721e8eda3a55e23f04896eb1fb2a/examples/kitchen-sink) starter for [Turborepo](https://turbo.build/repo).

## Using this example

```sh
git clone git@github.com:dotslashlabs/turborepo-kitchen-sink-nestjs.git
npm install
npm run dev
```

## What's inside?

This Turborepo includes the following packages and apps:

### Apps and Packages

- `api`: a [NestJS](https://docs.nestjs.com/) server
- `storefront`: a [Next.js](https://nextjs.org/) app
- `admin`: a [Vite](https://vitejs.dev/) single page app
- `blog`: a [Remix](https://remix.run/) blog
- `logger`: isomorphic logger (a small wrapper around console.log)
- `ui`: a dummy React UI library (which contains a single `<CounterButton>` component)
- `scripts`: Jest and ESLint configurations
- `tsconfig`: tsconfig.json's used throughout the monorepo

Each package and app is 100% [TypeScript](https://www.typescriptlang.org/).

### Utilities

This Turborepo has some additional tools already setup for you:

- [TypeScript](https://www.typescriptlang.org/) for static type checking
- [ESLint](https://eslint.org/) for code linting
- [Jest](https://jestjs.io) test runner for all things JavaScript
- [Prettier](https://prettier.io) for code formatting
