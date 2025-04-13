# Next.js Starter Template

[![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=flat-square&logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=next.js&logoColor=white)](https://nextjs.org/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=flat-square&logo=tailwind-css&logoColor=white)](https://tailwindcss.com/)
[![ESLint](https://img.shields.io/badge/ESLint-4B32C3?style=flat-square&logo=eslint&logoColor=white)](https://eslint.org/)
[![Prettier](https://img.shields.io/badge/Prettier-F7B93E?style=flat-square&logo=prettier&logoColor=black)](https://prettier.io/)
[![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white)](https://github.com/features/actions)

A production-ready Next.js template equipped with modern tooling, TypeScript, and best practices for building scalable web applications. This template provides a solid foundation for your projects with built-in code quality tools, testing setup, and CI/CD configuration. 🚀

## 📚 Table of Contents

- [Features](#-features)
- [Getting Started](#-getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation Options](#installation-options)
  - [Setting Up the Project](#setting-up-the-project)
- [Project Structure](#-project-structure)
  - [Source Directory Organization](#source-directory-organization)
- [Development Tools](#-development-tools)
  - [Code Quality Tools](#code-quality-tools)
  - [Git Hooks](#git-hooks-husky)
  - [Continuous Integration](#continuous-integration)
- [Building for Production](#-building-for-production)
- [License](#-license)

## ✨ Features

- 🎯 **TypeScript** - Full type safety and enhanced developer experience
- ⚡ **Next.js** - React framework with SSR, SSG, and file-based routing
- 🎨 **Tailwind CSS** - Utility-first CSS framework for rapid UI development
- 📏 **ESLint** - Pluggable linting utility for JavaScript and TypeScript
- 💖 **Prettier** - Opinionated code formatter
- 🐶 **Husky** - Git hooks made easy
- 🔄 **GitHub Actions** - Automated CI/CD workflows
- 📱 **Responsive Design** - Mobile-first approach
- 🌐 **SEO Optimized** - Built-in SEO best practices

## 🚀 Getting Started

### Prerequisites

- Node.js 18.x or later
- Package manager (npm, yarn, or pnpm)

### Installation Options

#### 1. Using the Template Feature

1. Click the "Use this template" button at the top of this repository
2. Choose a name for your new repository
3. Clone your new repository
4. Navigate to the project directory

#### 2. Direct Clone

```bash
git clone [repository-url]
cd [project-name]
```

### Setting Up the Project

1. Install dependencies using your preferred package manager:

```bash
# Using npm
npm install

# Using Yarn
yarn install

# Using pnpm
pnpm install
```

2. Create a `.env.local` file in the root directory:

```bash
cp .env.example .env.local
```

3. Start the development server:

```bash
# Using npm
npm run dev

# Using Yarn
yarn dev

# Using pnpm
pnpm dev
```

4. Open [http://localhost:3000](http://localhost:3000) in your browser

## 📁 Project Structure

```
└── src/              # Source directory
    ├── app/             # Next.js app router pages and layouts
    ├── features/        # Feature-based components and logic
    └── shared/          # Shared utilities, components, and hooks
```

### Source Directory Organization

The `src/` directory follows a modular architecture:

- **`app/`**: Contains Next.js 13+ app router pages and layouts
  - Each route is organized in its own directory
  - Includes layouts, loading states, and error boundaries

- **`features/`**: Feature-based components and business logic
  - Each feature has its own directory with isolated components
  - Includes feature-specific hooks, utils, and types
  - Check `features/README.md` for feature development guidelines

- **`shared/`**: Reusable components and utilities
  - Common UI components
  - Hooks, helpers, and utility functions
  - Type definitions and interfaces
  - Refer to `shared/README.md` for component guidelines

## 🛠️ Development Tools

### Code Quality Tools

#### ESLint Configuration

Our ESLint setup includes:
- TypeScript and React best practices
- Import sorting and organization
- React Hooks rules
- Accessibility checks
- Integration with Prettier

#### Prettier Configuration

```json
{
  "semi": false,
  "tabWidth": 2,
  "printWidth": 120,
  "trailingComma": "all",
  "jsxSingleQuote": true,
  "bracketSpacing": true,
  "bracketSameLine": false
}
```

### Git Hooks (Husky)

Pre-commit hooks ensure:
- Code is properly formatted
- Linting passes
- TypeScript types are valid
- Tests pass

### Continuous Integration

Our GitHub Actions workflow automatically:
1. Installs dependencies
2. Checks code formatting
3. Runs linting
4. Validates types
5. Runs tests
6. Builds the application

## 🧪 Testing

Run tests using:

```bash
# Run tests
npm test

# Run tests in watch mode
npm test:watch

# Generate coverage report
npm test:coverage
```

## 📦 Building for Production

```bash
# Create production build
npm run build

# Start production server
npm start
```

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

🚀 **Start building your React application with confidence using this comprehensive starter template!** 🚀