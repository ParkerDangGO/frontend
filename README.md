# Frontend

A React + TypeScript + Vite project for the frontend application.

## Tech Stack

- React 19
- TypeScript
- Vite
- Redux Toolkit
- React Router
- Tailwind CSS
- Axios
- React Hook Form + Zod

## Getting Started

### Prerequisites

Before running the project, make sure you have installed:

- Node.js 18+
- npm or yarn or pnpm

### Installation

```bash
npm install
```

### Run in development mode

```bash
npm run dev
```

Then open the local URL shown in the terminal, usually:

```bash
http://localhost:5173
```

### Build for production

```bash
npm run build
```

### Preview production build

```bash
npm run preview
```

### Lint the project

```bash
npm run lint
```

## Project Scripts

```json
{
  "dev": "vite",
  "build": "tsc -b && vite build",
  "lint": "eslint .",
  "preview": "vite preview"
}
```

## Notes

This project was initialized with Vite and uses the React + TypeScript template. You can customize the app structure, routing, and state management based on your requirements.
