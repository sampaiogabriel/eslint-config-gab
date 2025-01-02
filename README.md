#  EsLint Config Gabriel Sampaio

## Whats included?

- Standard config base;
- React plugin;
- React Hooks plugin;
- JSX a11y plugin;
- Prettier;

## Setup

### React (without Next.js)

Install dependencies:
```
npm i -D eslint eslint-config-gab
```
Inside `.eslintrc.json`
```
{
  "extends": "eslint-config-gab/react"
}
```

## Scripts 

```json
  scripts: {
    "lint": "yarn prettier --write src --single-quote && yarn eslint:fix"
  }
```