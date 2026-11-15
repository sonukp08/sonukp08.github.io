# Personal Website – Development Instructions

## Project

- Personal academic and professional portfolio built with Astro.
- Astro source, configuration, and npm files live in this repository root.
- The site uses static output and is previewed locally at `http://localhost:4321`.

## Development Environment

- Develop and verify locally on Windows.
- Use Node.js and npm. Install dependencies with `npm install`.
- Start the local development server with `npm run dev`.
- Preview a production build locally with `npm run preview`.

## Development Rules

1. Work directly in the existing project and preserve its Astro architecture.
2. Make focused changes; do not replace the project or existing files unnecessarily.
3. Reuse existing layouts, pages, content collections, and styles where possible.
4. Keep desktop and mobile layouts responsive.
5. Optimize images and loading performance when adding assets.
6. Run `npm run build` after implementation changes and resolve build errors.

## Git and Deployment

1. Never push changes automatically.
2. Never deploy without explicit approval.
3. Never modify hosting or domain settings without explicit approval.
4. Preserve existing Git history and review changes before committing.

## Verification

- Run `npm run build` to check the production build.
- Run `npm run dev` and inspect the site locally when testing a site change.
- Check desktop and mobile layouts when a change affects presentation.
