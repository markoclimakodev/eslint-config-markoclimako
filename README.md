# Marko Climako ESLint config

## What is included?

- Standard config base;
- React plugin;
- React Hooks plugin;
- JSX a11y plugin;
- Import-helpers  plugin;
- Prettier;

## Setup

### React (with Next.js)

Install dependencies:
```
npm i -D eslint @markoclimako/eslint-config
```
Inside `.eslintrc.json`
```
{
  "extends": [
    "@markoclimako/eslint-config/next", 
    "next/core-web-vitals"
  ]
}
```
