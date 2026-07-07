# Mi Portafolio Web

Static portfolio built with Astro.

## Runtime

Use Node.js 24 LTS. This repository pins the local runtime to `24.18.0` through `.nvmrc` and `.node-version`.

## Setup

Enable Corepack and install dependencies with pnpm:

```bash
corepack enable
pnpm install
```

## Commands

All commands are run from the repository root:

| Command | Action |
| :-- | :-- |
| `pnpm run dev` | Starts the local dev server at `localhost:4321` |
| `pnpm run build` | Runs Astro checks and builds the production site to `./dist/` |
| `pnpm run preview` | Previews the built site locally |
| `pnpm run astro ...` | Runs Astro CLI commands |

## Validation

```bash
pnpm install --frozen-lockfile
pnpm run build
```
