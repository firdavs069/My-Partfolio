# FIRDAVS® — React Portfolio

A dark, editorial portfolio with acid-lime accents, custom CSS artwork, responsive layouts, scroll reveals, a scroll progress bar, orbit animations, and a mobile menu.

## Run locally

1. Install Node.js (LTS recommended).
2. Extract this ZIP and open the folder in VS Code.
3. Open the terminal in this folder and run:

   ```bash
   npm install
   npm run dev
   ```

4. Open the local URL Vite prints, usually `http://localhost:5173`.

## Customize before publishing

Search `src/main.jsx` for:

- `Firdavs` and the intro text
- `hello@firdavs.dev` — replace with your real email
- `https://github.com/` and `https://www.linkedin.com/` — replace with your profiles
- `projects` — update each project title, description, tags, and link

The project cards currently use sample portfolio concepts. Replace them with real projects before presenting this as finished work. Skill labels intentionally describe a learning journey rather than claiming professional mastery.

## Free deployment

### Vercel

Import this project folder/repository on Vercel. Framework preset: **Vite**. Build command: `npm run build`. Output directory: `dist`.

### Cloudflare Pages

Connect the repository. Build command: `npm run build`. Build output directory: `dist`.

This is a frontend-only portfolio. If you later connect a Go API, deploy the Go backend separately and configure its URL in the frontend.
