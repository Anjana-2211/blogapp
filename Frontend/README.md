# Blog App Frontend

A React + Vite frontend for the Blog App project, built with Tailwind CSS, React Router, Zustand, Axios, and React Hook Form.

## Project Overview

This frontend provides a responsive blog platform interface with:
- user authentication and role-based navigation
- article listing, article detail pages, and search support
- author dashboard for creating and editing articles
- protected routes for authors and admins
- client-side state management with Zustand
- API communication via Axios

## Tech Stack

- React 19
- Vite
- Tailwind CSS 4
- React Router 7
- Zustand
- Axios
- React Hook Form
- ESLint

## Getting Started

### Requirements

- Node.js 18+ (or compatible LTS version)
- npm or yarn

### Install dependencies

```bash
cd Frontend
npm install
```

### Run locally

```bash
npm run dev
```

Open the local server URL shown in the terminal, usually `http://localhost:5173`.

### Build for production

```bash
npm run build
```

### Preview production build

```bash
npm run preview
```

### Lint source files

```bash
npm run lint
```

## Project Structure

- `src/` - application source code
  - `components/` - React UI components and pages
  - `store/` - Zustand auth store
  - `styles/` - shared styling utilities
- `public/` - static public assets
- `package.json` - frontend dependencies and scripts
- `vite.config.js` - Vite configuration
- `index.html` - application entry template

## Environment Configuration

This frontend expects the backend API to be available separately. Update API URLs or environment settings as needed in the application code or a dedicated config file.

## Notes

- The backend is not included in this folder. Use the `Backend/` directory in the root workspace for API server setup.
- If you upgrade dependencies or change the Vite configuration, verify that the application still builds and that client routing works correctly.

## License

This project is provided as-is for development and learning purposes.
