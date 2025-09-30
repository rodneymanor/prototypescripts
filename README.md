# PrototypeScripts Next.js Template

This repository hosts a ready-to-use Next.js starter configured with Turbopack, TypeScript, ESLint, and the `@rmanor/gc-dash` component library. Use it to bootstrap new prototypes quickly without repeating boilerplate setup.

## Getting Started Via `create-next-app`

```bash
npx create-next-app@latest my-app \
  --example "https://github.com/rodneymanor/prototypescripts/tree/main"
```

Replace `my-app` with your desired project directory name. `create-next-app` will clone this template into that directory, install dependencies, and initialize a git repo for you.

## Local Development

1. `cd my-app`
2. Install dependencies: `npm install`
3. Start the dev server with Turbopack: `npm run dev`
4. Visit `http://localhost:3000`

## What's Included

- Next.js 15 with Turbopack-enabled `dev` and `build` scripts
- React 19, React DOM 19
- TypeScript 5 with strict linting via `eslint-config-next`
- `@rmanor/gc-dash` UI components

## Updating Your Template Version

If you make improvements here, push them to `main` and reference the branch or a tag when scaffolding a new project:

```bash
npx create-next-app@latest my-app \
  --example "https://github.com/rodneymanor/prototypescripts/tree/v0.2.0"
```

Tagging releases (`git tag v0.2.0 && git push origin v0.2.0`) helps lock projects to a known version.

## Contributing Updates

1. Fork or branch from `main`.
2. Make your changes and run `npm run lint`/`npm run build`.
3. Commit and push, then open a pull request or tag a release.

Enjoy building with the PrototypeScripts template!
