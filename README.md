# A Style Guide for Grateful Javascript

## Deployment

```
npx lerna publish
```

## Description

ESLint configurations and bundles to enable rules and formatting based on:

- ESLint/recommended
- Prettier/recommended
- React/recommended _(requires babel-eslint parser)_

## Packages

- [eslint-config-node](#eslint-config-node)
- [eslint-config-react](#eslint-config-react)

### eslint-config-node

1. Install the sharable config:

   ```
   npm i -D @grateful/eslint-config-node
   ```

2. Install dependencies

   To use the sharable config, the following dev dependencies are required:

   ```
   npm i -D eslint \
     eslint-config-prettier \
     eslint-plugin-prettier \
     prettier
   ```

3. Add an ESLint config file, `.eslintrc`:

   ```json
   {
     "extends": "@grateful/node"
   }
   ```

### eslint-config-react

1. Install the sharable config:

   ```
   npm i -D @grateful/eslint-config-react
   ```

2. Install dependencies

   To use the sharable config, the following dev dependencies are required:

   ```
   npm i -D babel-eslint \
     eslint \
     eslint-config-prettier \
     eslint-plugin-prettier \
     eslint-plugin-react \
     prettier
   ```

3. Add an ESLint config file, `.eslintrc`:

   ```json
   {
     "extends": "@grateful/react"
   }
   ```
