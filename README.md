# Dhyani Patel — personal portfolio

A light editorial portfolio across digital marketing, AI, creative technology, and business.

**Live site:** https://dhyanipatel01.github.io/dhyanipatel-portfolio/

## Repository contents

The repository root contains the production static website, including its interactive JavaScript, local fonts, and native HTML fallbacks. GitHub Pages publishes `main` from the repository root. `.nojekyll` preserves the framework asset folders.

`portfolio-source.zip` contains the complete editable React/TypeScript source, build configuration, dependency lockfile, and validation scripts. It excludes installed dependencies, environment files, and generated caches.

## Editing and rebuilding

1. Extract `portfolio-source.zip` and open the `dhyani-portfolio` folder.
2. Use Node.js 22.13 or later and run `pnpm install`.
3. Edit content in `app/portfolio-data.ts` and design in `app/page.tsx` / `app/globals.css`.
4. Run `PORTFOLIO_BASE_PATH=/dhyanipatel-portfolio pnpm build`.
5. Replace the published files with the contents of `dist/client`, preserving their folders and `.nojekyll`.

The build checks all 73 approved skills, both certification records, anchor targets, asset references, native HTML fallbacks, and size budgets. Public contact details remain omitted until supplied.

## Offline edition

`dhyani-patel.html` is a self-contained copy with embedded styles and fonts. Download this file for offline viewing; it uses native HTML interactions. The hosted edition adds enhanced tabs, dialogs, and motion.
