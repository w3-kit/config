# @w3-kit/config

[![CI](https://github.com/w3-kit/config/actions/workflows/ci.yml/badge.svg)](https://github.com/w3-kit/config/actions/workflows/ci.yml)
[![npm](https://img.shields.io/npm/v/@w3-kit/config)](https://www.npmjs.com/package/@w3-kit/config)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](./LICENSE)

Shared configs for the w3-kit org.

## Usage

### TypeScript

```jsonc
// tsconfig.json
{ "extends": "@w3-kit/config/typescript/react" }
```

### ESLint

```js
// eslint.config.js
export { default } from "@w3-kit/config/eslint";
```

### Prettier

```js
// prettier.config.js
export { default } from "@w3-kit/config/prettier";
```

### Tailwind

```ts
// tailwind.config.ts
import preset from "@w3-kit/config/tailwind";
export default { presets: [preset], content: ["./src/**/*.tsx"] };
```
