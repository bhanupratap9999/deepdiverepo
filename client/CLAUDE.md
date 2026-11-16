# Client Overview

Next.js 16.4.6 (React 19, TypeScript) frontend application with Tailwind CSS v4.

---

## Commands

- **Run dev server**: `npm run dev`
- **Build**: `npm run build`
- **Start**: `npm run start`
- **Lint**: `npm run lint`

---

## Architecture & Styling Notes

- **App Router**: Uses Next.js App Router (`app/` directory).
- **Tailwind CSS v4**: Uses `@tailwindcss/turbopack` and Tailwind v4.
- **PostCSS**: `postcss.config.mjs` and `tailwind.config.js` are not needed in Tailwind v4. CSS rules and theme tokens are defined directly in [globals.css](file:///C:/Users/thaku/OneDrive/Documents/deepdiverepo/client/app/globals.css) using `@import "tailwindcss";`.
