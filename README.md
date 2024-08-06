# Template Typescript Action

A template repository for building javascript github actions in Typescript. Here is the tooling setup:

- [tsup](https://github.com/egoist/tsup) compiles typescript to a single file, including dependencies-- just add all dependencies to devDependencies
- ts-jest testing
- prettier formatting
- CI checks
- pre-commit protections

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
