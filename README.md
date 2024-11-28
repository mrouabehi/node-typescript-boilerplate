# NodeJS TypeScript Boilerplate

A minimal boilerplate for Node.js projects using TypeScript and Jest for testing. Perfect for small projects, training purposes, or as a foundation for larger applications.

## Features

- **TypeScript** - Write type-safe JavaScript code
- **Jest** - Popular testing framework with TypeScript support
- **Minimal Dependencies** - Start with only the essentials
- **Ready to Use** - Pre-configured TypeScript and Jest settings

## Prerequisites

- Node.js (version 20 or higher recommended)
- npm, yarn, or pnpm package manager

## Installation

Clone the repository and install dependencies:

```bash
# Clone the repository
git clone https://github.com/mrouabehi/node-typescript-boilerplate.git ./project-name

# Navigate to project directory
cd project-name

# Install dependencies
npm install
# or
yarn install
# or
pnpm install
```

## Available Scripts

```bash
# Run tests
pnpm test

# Build TypeScript
pnpm build

# Run in watch mode
pnpm start:watch

# Run the normal mode
pnpm start

# Run the build scripts
node dist/index.js
```

## Project Structure

```
.
├── src/             # Source files
├── dist/            # Compiled JavaScript files
├── jest.config.ts   # Jest configuration
├── tsconfig.json    # TypeScript configuration
└── package.json     # Project dependencies and scripts
```

## TypeScript Configuration

The project includes a basic `tsconfig.json` with common settings. Modify it according to your needs:


## Testing

Jest is configured to work with TypeScript out of the box. Write your tests in the `.test.ts` or `.spec.ts` files.

