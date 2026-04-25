# React Pro Application

A clean React 18 starter template with Redux Toolkit, TypeScript, and a testing setup using Jest and React Testing Library. Bootstrapped with Create React App.

## Tech Stack

- **React 18** with React DOM
- **TypeScript 4.9** for type safety
- **Redux Toolkit** for state management
- **React-Redux** for React bindings to Redux
- **Jest** and **React Testing Library** for unit and integration testing
- **Create React App** as the build toolchain

## Getting Started

### Prerequisites

- Node.js (v14 or later recommended)
- npm or yarn

### Installation

```bash
npm install
```

### Available Scripts

| Command | Description |
|---------|-------------|
| `npm start` | Runs the app in development mode at [http://localhost:3000](http://localhost:3000) |
| `npm test` | Launches the test runner in interactive watch mode |
| `npm run build` | Builds the app for production to the `build` folder |
| `npm run eject` | Ejects the CRA configuration (one-way operation) |

## Project Structure

```
src/
  app/
    hooks.ts        # Typed Redux hooks
    store.ts        # Redux store configuration
  App.tsx           # Root component
  App.test.tsx      # Root component tests
  index.tsx         # Application entry point
public/
  index.html        # HTML template
```

## License

This project is available as open source.
