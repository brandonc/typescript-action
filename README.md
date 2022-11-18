# Template Typescript Action

A template repository for building javascript github actions in Typescript. Here is the tooling setup:

- Compiles typescript to a single file using [@vercel/ncc](https://github.com/vercel/ncc)
- Jest + Typescript
- Built-in Github Actions CI workflow with checks:
  - Prettier formatting
  - Build is up to date
  - Tests
- Pre-commit hook using Husky ensures build is up to date

## Install

`npm install`
`npm prepare`

## Run Tests

`npm run test`

---

Example README for Actions follows

---

# Template Typescript Action

This action logs a phrase given as input

## Inputs

### `motd`

**Optional** The phrase to log
