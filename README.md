# Dejan Krivec — React Portfolio

Personal portfolio built with **React, TypeScript, Vite, CSS, and Motion**. This version adapts the original static HTML/CSS portfolio and adds animated reveals and expandable project contributions. All project visuals are abstract, not screenshots of employer products.

## Local development

```bash
npm install
npm run dev
```

Open the localhost URL shown by Vite.

## Build

```bash
npm run build
npm run preview
```

## Deploy to GitHub Pages (free)

1. Create a public GitHub repository named `YOUR_GITHUB_USERNAME.github.io`.
2. Push the **contents of this folder** to its `main` branch, including `.github/workflows/deploy.yml`.
3. In the repository go to **Settings → Pages → Build and deployment → Source: GitHub Actions**.
4. The workflow automatically installs dependencies, builds the site and deploys it on each push to `main`.
5. Your site will appear at `https://YOUR_GITHUB_USERNAME.github.io`.

If you instead use a project repository named e.g. `portfolio`, change `base: '/'` in `vite.config.ts` to `base: '/portfolio/'` before deploying.

## Customize

- Edit project descriptions in `src/main.tsx` (`projects` array).
- Edit colors, layout and typography in `src/styles.css`.
- Replace abstract artwork with screenshots **only if you have permission to publish them**.
- Verify the email and LinkedIn URL before publishing.
- This portfolio does not claim public access to private company code.

Accessibility: keyboard-operable project details, semantic sections, visible focus states, and reduced-motion support.
