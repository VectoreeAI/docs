# Vectoree Docs

Source for [docs.vectoree.ai](https://docs.vectoree.ai), hosted by [Mintlify](https://mintlify.com).

This repository is a **mirror** of `docs/` in the [Vectoree monorepo](https://github.com/Vectoree/Vectoree). Do not edit pages here by hand — they will be overwritten on the next sync.

## Local preview

```bash
npx mint dev
```

Open `http://localhost:3000`.

## How updates land

1. Change MDX / `docs.json` in the monorepo `docs/` folder.
2. Merge to `main`. GitHub Actions copies `docs/` here and pushes.
3. Mintlify deploys from this repo's `main` (content directory = repository root).
