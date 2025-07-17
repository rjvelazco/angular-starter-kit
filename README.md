# Angular Starter Kit

A ready-to-use Angular project with ESLint, Prettier, and Husky pre-configured for a modern development workflow.

## Features

- **Angular 20.0.0** - Latest Angular framework
- **ESLint** - Code linting with TypeScript and Angular rules
- **Prettier** - Code formatting with consistent styling
- **Husky** - Git hooks for automated code quality checks
- **Pre-commit hooks** - Automatic linting and formatting before commits

## Configuration

### ESLint

- TypeScript ESLint rules
- Angular-specific linting rules
- Prettier integration for consistent formatting
- Custom component and directive selector rules

### Prettier

- 2-space indentation
- Single quotes
- Semicolons enabled
- 120 character line width
- ES5 trailing commas

### Husky Pre-commit Hook

Automatically runs before each commit:

- `npm run lint` - Lints all code
- `npm run format` - Formats code with Prettier
- `git add .` - Stages any formatting changes

## Getting Started

1. **Install dependencies**

   ```bash
   npm install
   ```

2. **Start development server**

   ```bash
   npm start
   ```

3. **Build for production**
   ```bash
   npm run build
   ```

## Available Scripts

- `npm start` - Start development server
- `npm run build` - Build for production
- `npm run test` - Run unit tests
- `npm run lint` - Run ESLint
- `npm run format` - Format code with Prettier
- `npm run watch` - Build in watch mode

## Development Workflow

The project ensures code quality through:

- Automated linting on every commit
- Consistent code formatting
- Angular best practices enforcement
- TypeScript strict checking

Simply code and commit - the tools will handle the rest!

## Code Scaffolding

Angular CLI includes powerful code scaffolding tools. To generate a new component, run:

```bash
ng generate component component-name
```

For a complete list of available schematics (such as `components`, `directives`, or `pipes`), run:

```bash
ng generate --help
```

## Additional Resources

For more information on using the Angular CLI, including detailed command references, visit the [Angular CLI Overview and Command Reference](https://angular.dev/tools/cli) page.
