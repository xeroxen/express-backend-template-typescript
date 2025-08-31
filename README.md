# Node.js Express TypeScript App

A boilerplate Node.js Express server built with TypeScript, including ESLint and Prettier for code quality.

## Features

- [Express](https://expressjs.com/) - Fast, unopinionated, minimalist web framework for Node.js
- [TypeScript](https://www.typescriptlang.org/) - Typed superset of JavaScript that compiles to plain JavaScript
- [ESLint](https://eslint.org/) - Pluggable JavaScript linter
- [Prettier](https://prettier.io/) - Opinionated code formatter
- [Nodemon](https://nodemon.io/) - Tool that helps develop Node.js based applications by automatically restarting the node application when file changes in the directory are detected

## Getting Started

### Prerequisites

- [Bun](https://bun.sh/), [npm](https://www.npmjs.com/), or [pnpm](https://pnpm.io/) - JavaScript runtimes and package managers

### Installation

1. Clone the repository
2. Install dependencies with your preferred package manager:
   ```bash
   # Bun
   bun install
   # npm
   npm install
   # pnpm
   pnpm install
   ```

### Development

To start the development server:

```bash
# Bun
bun run dev
# npm
npm run dev
# pnpm
pnpm run dev
```

### Building for Production

To build the app for production:

```bash
# Bun
bun run build
# npm
npm run build
# pnpm
pnpm run build
```

### Running in Production

To start the production server:

```bash
# Bun
bun run start
# npm
npm start
# pnpm
pnpm start
```

### Linting and Formatting

To check for linting errors:

```bash
# Bun
bun run lint
# npm
npm run lint
# pnpm
pnpm run lint
```

To fix linting errors:

```bash
# Bun
bun run lint:fix
# npm
npm run lint:fix
# pnpm
pnpm run lint:fix
```

To check code formatting:

```bash
# Bun
bun run prettier:check
# npm
npm run prettier:check
# pnpm
pnpm run prettier:check
```

To fix code formatting:

```bash
# Bun
bun run prettier:fix
# npm
npm run prettier:fix
# pnpm
pnpm run prettier:fix
```

## Project Structure

```
.
├── src/
│   └── server.ts      # Main server file
├── dist/              # Compiled JavaScript files
├── .env               # Environment variables
├── .eslintrc.json     # ESLint configuration
├── .gitignore         # Files to be ignored by git
├── .prettierrc        # Prettier configuration
├── package.json       # Project dependencies and scripts
├── README.md          # This file
└── tsconfig.json      # TypeScript configuration
```
