# Purnima's Pixel Café — Engineering Studio

A responsive React portfolio with an animated CSS café, interactive cat, project filters, career timeline, and a dedicated **Behind the Build** page.

## Run locally

```bash
npm install
npm run dev
```

Open the local URL shown in the terminal.

## Deploy to GitHub Pages

1. Create a new public GitHub repository.
2. Upload these project files, including the hidden `.github/workflows/deploy.yml` directory. Do not upload `node_modules`.
3. On GitHub, open **Settings → Pages → Build and deployment** and choose **GitHub Actions** as the source.
4. Push to the `main` branch. The included workflow builds and publishes the website.
5. Your site URL will be `https://YOUR-USERNAME.github.io/REPOSITORY-NAME/` (or your root user site if configured that way).

## Before publishing

- Replace placeholder GitHub and LinkedIn links in `src/main.jsx` with your own profile URLs.
- The **say hello** control is deliberately inactive until you provide a public contact address. Update it with your real email or contact form.
- Review each project description for accuracy and add real project links/case studies as you publish them.
- The Soundscape project is explicitly identified as a concept, not a shipped product.
- Northrop Grumman is presented as past experience, not current employment.
- The Behind the Build page credits ChatGPT assistance accurately; don't claim use of other AI tools unless you use them.

## Tech

React, JavaScript, Vite, CSS animations, Lucide icons, GitHub Actions, GitHub Pages.

## Structure

- `src/main.jsx` — components, project data, pages and interaction
- `src/style.css` — design system, pixel café illustration and responsive styles
- `vite.config.js` — Vite config with relative asset paths for GitHub Pages
- `.github/workflows/deploy.yml` — CI deployment
