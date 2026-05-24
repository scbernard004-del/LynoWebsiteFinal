# Lyno Associate Website

Root-level Vercel/GitHub package.

## Local test

```bash
npm install
npm run dev
```

Open http://localhost:5173

## GitHub upload

Upload/replace:

- index.html
- package.json
- vercel.json
- .npmrc
- .gitignore
- README.md
- public

Do not upload:

- node_modules
- dist
- old package-lock.json

If an old package-lock.json exists in GitHub, delete it before redeploying.
