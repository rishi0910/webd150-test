# Project Summary: webd150-test

## Overview
- **Project name:** webd150-test (from `package.json`)
- **App title:** Web3 Shopping Cart (from `index.html`)
- **Description:** A small React + Vite app using TailwindCSS that fetches products from `fakestoreapi.com` and displays them in a simple store UI.

## Quick Start

1. Install dependencies:

```powershell
npm install
```

2. Run development server:

```powershell
npm run dev
```

3. Build for production:

```powershell
npm run build
```

## Scripts (from `package.json`)
- `dev`: `vite` (starts local dev server)
- `build`: `vite build` (bundle for production)
- `preview`: `vite preview` (preview production build)

## Dependencies
- react ^18.2.0
- react-dom ^18.2.0
- lucide-react ^0.263.1

## Dev Dependencies
- @vitejs/plugin-react
- tailwindcss, postcss, autoprefixer
- vite
- @types/react, @types/react-dom

## Project Structure

```
index.html
package.json
postcss.config.js
tailwind.config.js
vite.config.js
src/
  ├─ App.jsx
  ├─ main.jsx
  └─ index.css
```

## Key Files

- `index.html`: App entry; sets `<div id="root"></div>` and loads `/src/main.jsx`.

- `package.json`: Project metadata and npm scripts.

- `vite.config.js`: Minimal Vite config with React plugin.

- `tailwind.config.js` & `postcss.config.js`: Tailwind + PostCSS setup. Tailwind content includes `./index.html` and `./src/**/*.{js,ts,jsx,tsx}`.

- `src/main.jsx`: React DOM bootstrap that mounts `<App />` and imports `index.css`.

- `src/index.css`: Tailwind directives (`@tailwind base; @tailwind components; @tailwind utilities;`).

- `src/App.jsx`: Main application. Behavior summary:
  - Fetches products from `https://fakestoreapi.com/products` on mount.
  - Displays loading / error states.
  - Provides a search input to filter products by title.
  - Renders `ProductCard` components showing image, title, price, and a button.
  - Uses `lucide-react` for the search icon.

## Notes and Recommendations
- Uses Tailwind for styling; ensure `npm install` runs to add `tailwindcss`, `postcss`, and `autoprefixer`.
- If you plan to add web3 wallet integration (hinted by title), consider installing `ethers` or `web3modal` and adding a provider context.
- For production builds, verify external image loading and consider local caching or CDN.

## How I generated this file
- Scanned repository files and read `package.json`, `index.html`, Vite/Tailwind/PostCSS configs, and `src` files to produce this summary.
