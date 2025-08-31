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

- [Bun](https://bun.sh/) - JavaScript runtime and toolkit

### Installation

1. Clone the repository
2. Install dependencies:
   ```bash
   bun install
   ```

### Development

To start the development server:
```bash
bun run dev
```

### Building for Production

To build the app for production:
```bash
bun run build
```

### Running in Production

To start the production server:
```bash
bun run start
```

### Linting and Formatting

To check for linting errors:
```bash
bun run lint
```

To fix linting errors:
```bash
bun run lint:fix
```

To check code formatting:
```bash
bun run prettier:check
```

To fix code formatting:
```bash
bun run prettier:fix
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