# 🧰 Simple TypeScript Starter | 2021

This is a fork from [https://github.com/stemmlerjs/simple-typescript-starter](https://github.com/stemmlerjs/simple-typescript-starter) 

### Features

- [Features from original repo](https://github.com/dami2/simple-typescript-starter#features)
- Commit conventions with [commitlint](https://commitlint.js.org)
- Automated version management with [semantic-release](https://semantic-release.gitbook.io/semantic-release/) (See [Using semantic-release with GitHub Actions](https://github.com/semantic-release/semantic-release/blob/1405b94296059c0c6878fb8b626e2c5da9317632/docs/recipes/github-actions.md) )

### Scripts

#### `npm run start:dev`

Starts the application in development using `nodemon` and `ts-node` to do hot reloading.

#### `npm run start`

Starts the app in production by first building the project with `npm run build`, and then executing the compiled JavaScript at `build/index.js`.

#### `npm run build`

Builds the app at `build`, cleaning the folder first.

#### `npm run test`

Runs the `jest` tests once.

#### `npm run test:dev`

Run the `jest` tests in watch mode, waiting for file changes.

#### `npm run prettier-format`

Format your code.

#### `npm run prettier-watch`

Format your code in watch mode, waiting for file changes.

#### `npm run prepare`

Enable Git hooks
