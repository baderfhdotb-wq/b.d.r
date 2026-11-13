# AETHER — The Future of Innovation

Interactive Arabic-first science exhibition with Three.js 3D assembly and GSAP ScrollTrigger.

## Run locally

```bash
npm install
npm run dev
```

## Build

```bash
npm run build
npm run preview
```

## GitHub + Vercel

1. Create a new GitHub repository and upload this folder (including `package.json`, `src/`, and `index.html`).
2. In Vercel, select **Add New > Project > Import Git Repository** and authorize your GitHub account.
3. Import the repository. Framework preset: **Vite**. Build: `npm run build`. Output: `dist`.
4. Click **Deploy**. Each subsequent push to the connected GitHub branch triggers a new deployment.

Note: The interactive values are educational illustrative models, not real-world engineering measurements. Requires WebGL and a modern browser. The app has a fallback message when WebGL is unavailable.
