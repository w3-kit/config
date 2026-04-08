# Contributing to @w3-kit/config

Thanks for your interest in contributing to w3-kit's shared configs!

## How to contribute

1. Fork the repo
2. Create a branch (`git checkout -b my-change`)
3. Make your changes
4. Test that configs still work by installing in a test project
5. Commit and push
6. Open a pull request

## What to contribute

- ESLint rule improvements
- TypeScript config refinements
- Prettier adjustments
- Tailwind preset enhancements
- Reusable GitHub Actions workflows

Check [open issues](https://github.com/w3-kit/config/issues) for ideas.

## Local development

```bash
git clone https://github.com/YOUR_USERNAME/config.git
cd config
npm install
```

### Testing configs locally

Link the package locally and test in another w3-kit repo:

```bash
npm link
cd ../cli  # or any other repo
npm link @w3-kit/config
```

### Run all CI checks locally

```bash
npm run lint && npm run format:check
```

## Guidelines

- Keep configs minimal and well-documented
- Changes affect all repos in the org — test thoroughly
- Follow existing patterns
