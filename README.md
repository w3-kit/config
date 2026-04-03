# @w3-kit/config

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
