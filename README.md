# Suparna Deb Burman — Interactive Portfolio

A responsive React + Vite portfolio with Motion scroll animations, project filtering, glowing gradient backgrounds, education timeline, resume download, and contact links.

## Requirements
- Node.js LTS (20.19+ or 22.12+ recommended for modern Vite)
- npm

## Run locally
```bash
npm install
npm run dev
```
Open the local URL displayed by Vite (usually http://localhost:5173).

## Build for production
```bash
npm run build
npm run preview
```

## Personalize
- `src/components/Hero.jsx`: name, tagline, intro, social links
- `src/components/About.jsx`: bio
- `src/components/Skills.jsx`: tech stack
- `src/components/Projects.jsx`: project details and optional `repo` / `demo` links (currently null because resume did not provide verified URLs)
- `src/components/Education.jsx`: education and certifications
- `src/components/Contact.jsx`: email and social links
- `src/index.css`: theme, animations and layout
- `public/resume.pdf`: your uploaded resume, copied unchanged

**Before publishing:** Review resume for any draft notes, private contact details, or unverified claims. The uploaded PDF contains editor placeholders for deployment links and database confirmation. Replace it with a cleaned final PDF before going live.

## Deploy on Vercel
1. Push the folder to a new GitHub repository (do not upload `node_modules`).
2. Visit https://vercel.com/new and import the repository.
3. Framework preset: Vite. Build command: `npm run build`. Output directory: `dist`.
4. Click Deploy. Vercel supplies a public `.vercel.app` address.

The project is **not deployed yet**; deployment requires access to your own GitHub/Vercel account.
