# Vite + TypeScript + ESLint + Prettier Template

A simple template for TypeScript projects with Vite, featuring:

- ⚡️ [Vite](https://vitejs.dev/) - Next Generation Frontend Tooling
- 🦕 [TypeScript](https://www.typescriptlang.org/) - Type-Safe JavaScript
- 🛠️ [ESLint](https://eslint.org/) - Pluggable JavaScript Linter
- 💅 [Prettier](https://prettier.io/) - Opinionated Code Formatter

## Prerequisites

- Node.js 18+ (LTS recommended)
- npm (comes with Node.js) or yarn

## Getting Started

1. **Create a new repository** using this template
2. **Clone the repository**
   ```bash
   git clone <your-repository-url>
   cd <repository-name>
   ```
3. **Install dependencies**
   ```bash
   npm install
   ```
4. **Start the development server**
   ```bash
   npm run dev
   ```
5. **Open your browser** to `http://localhost:5173`

## Available Scripts

- `npm run dev` - Start the development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build
- `npm run lint` - Run ESLint
- `npm run lint:fix` - Fix auto-fixable linting issues
- `npm run format` - Format code with Prettier

## Editor Setup

### VS Code

1. Install the following extensions:
   - [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)
   - [Prettier - Code formatter](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)

2. Add the following to your VS Code settings (`.vscode/settings.json`):
   ```json
   {
     "editor.defaultFormatter": "esbenp.prettier-vscode",
     "editor.formatOnSave": true,
     "editor.codeActionsOnSave": {
       "source.fixAll.eslint": "explicit"
     },
     "eslint.validate": ["typescript"]
   }
   ```

## License

MIT
