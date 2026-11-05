# CODENEX

Minimal React + Vite starter for the hackathon. No features, no styling framework — a blank foundation ready for development.

## Requirements

- Node.js (v18+ recommended)
- npm

## Setup

```bash
git clone <repo-url>   # or use the existing checkout
cd CODENEX
npm install
```

## Run

```bash
npm run dev
```

Opens a dev server (default: http://localhost:5173) with hot reload.

## Build

```bash
npm run build     # production build → dist/
npm run preview   # locally preview the production build
```

## Folder structure

```
src/
├── components/   # Reusable UI components
├── pages/        # Page-level components / views
├── services/     # API calls and external service integrations
├── hooks/        # Custom React hooks
├── utils/        # Pure helper functions
└── assets/       # Images, fonts, static files
```

## Stack

- [React 19](https://react.dev)
- [Vite](https://vite.dev)
- Plain JavaScript (JSX) — no TypeScript, no CSS framework
