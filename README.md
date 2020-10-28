# Project References Test

### Build

```bash
yarn #install deps
yarn build
```

### Current issue

When building, an `index.js` file is made alongside `index.ts` for both packages, while also making a `dist/index.js`

Expecting output files to only be in `dist/*`