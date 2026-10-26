# Front-end

## React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react) uses [Babel](https://babeljs.io/) (or [oxc](https://oxc.rs) when used in [rolldown-vite](https://vite.dev/guide/rolldown)) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

### React Compiler

The React Compiler is not enabled on this template because of its impact on dev & build performances. To add it, see [this documentation](https://react.dev/learn/react-compiler/installation).

### Expanding the ESLint configuration

This front-end is implemented using JavaScript with JSX. Please write components and examples in JSX/JavaScript (files using the `.jsx` or `.js` extensions). The repository and project tooling are configured for a JavaScript (JSX) codebase — do not introduce TypeScript files for this project. If you need type-checked examples for learning purposes, document them separately, but keep the main source and examples in JSX.

## Dependencies

### Core Libraries

This project uses several key dependencies for enhanced functionality:

- **jsPDF** (`^3.0.3`) - PDF generation library for the export notes feature. Allows users to export their article notes and highlights as properly formatted PDF files directly in the browser without requiring server-side processing.

### Setup

1. Install all dependencies:
   ```bash
   npm install
   ```

2. Start the development server:
   ```bash
   npm start
   # or
   npm run dev
   ```

Both commands start the Vite development server with hot module replacement (HMR).

**For deployment:**
```bash
npm run build    # Build for production
npm run preview  # Preview production build locally
```

The development server will start on `http://localhost:5173` by default.
