# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react) uses [Oxc](https://oxc.rs)
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react-swc) uses [SWC](https://swc.rs/)

## React Compiler

The React Compiler is not enabled on this template because of its impact on dev & build performances. To add it, see [this documentation](https://react.dev/learn/react-compiler/installation).

## Expanding the ESLint configuration

If you are developing a production application, we recommend using TypeScript with type-aware lint rules enabled. Check out the [TS template](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts) for information on how to integrate TypeScript and [`typescript-eslint`](https://typescript-eslint.io) in your project.

### 3. Counters (Zustand)
A simple counter application demonstrating global state management.
- *State Management: Uses **Zustand* to share a single counter state across multiple component instances.
- *Reusability*: Shows how multiple independent-looking UI elements can stay in sync using a central store.

## How to Run

### Backend (MERN-MINI-APP/Backend)
1. Ensure MongoDB is running locally.
2. Navigate to the Backend folder.
3. Run npm install.
4. Run node server.js or npm run dev.

### Frontend
1. Navigate to the respective project folder (e.g., MERN-MINI-APP/frontend, React-App-2, or counters).
2. Run npm install.
3. Run npm run dev.
4. Open the local server link in your browser.
