# Project References Test

### Goal

1. `packages/main` Should be the entry point of this application
2. Main should be able to import the "hello" module with `@refs/hello`
3. Copy *only* the built JS files into a Docker container for deployment

Bonus

4. Testing with ts-jest

### Build

```bash
yarn #install deps
yarn build
```

### Current issue

When building, an `index.js` file is made alongside `index.ts` for both packages, while also making a `dist/index.js`

Expecting output files to only be in `dist/*`