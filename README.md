# Hieu Pham – Portfolio (Next.js + Tailwind)

Live site: https://canquaca.netlify.app/

A clean, dark-themed personal portfolio built with Next.js and Tailwind CSS. Content is managed via Markdown/JSON in the `content/` directory and media in `public/`.

## Features

- Dark theme with accessible typography
- Interactive tech stack buttons linking to official sites
- Blog and Projects with featured images/media
- Pretty code snippets with simplified dark styling
- Project recommendation carousel (always 2, circular)
- Downloadable CV/Cover Letter buttons
- Social icon buttons (LinkedIn, GitHub, Instagram)

## Tech Stack

- Next.js 15, React
- TypeScript (components), JavaScript (some pages)
- Tailwind CSS + custom CSS (`src/css/main.css`)
- Markdown/YAML content files under `content/`

## Getting Started (Local Dev)

```bash
# Install dependencies
npm install

# Start dev server
npm run dev
# http://localhost:3000

# Build for production
npm run build

# Start production server (after build)
npm start
```

## Project Structure

- `content/pages/index.md` – Home page (hero, buttons, featured sections)
- `content/pages/info.md` – About page (bio, technologies, skills, social)
- `content/pages/blog/` – Blog posts (`.md`) with frontmatter-like blocks
- `content/pages/projects/` – Project pages (`.md`) with images/media
- `content/data/config.json` – Global config (header, social links)
- `public/images/` – All images (blog, projects, tech logos)
- `public/files/` – CV and Cover Letter PDFs
- `src/css/main.css` – Theme and code snippet styling
- `src/utils/static-props-resolvers.ts` – Data resolvers (project prev/next)

## Editing Content

### Home
- Edit `content/pages/index.md`.
- Hero buttons IDs: `cv-download-btn`, `projects-btn`, `blogs-btn`.
- “Connect with me” icon buttons live in the bottom `FeaturedItemsSection`.

### About
- Edit `content/pages/info.md`.
- Technologies section uses responsive button grid with official icons.
- Skills use a concise list (Agile/TDD/CI-CD/etc.).
- Social icon buttons are in a `FeaturedItemsSection` titled “You can find me here:”.

### Blog Posts
- Add files under `content/pages/blog/your-post.md`.
- Set `featuredImage` and optional `media` (use `/images/blog/`).
- Code blocks are auto-styled by `src/css/main.css`.

### Projects
- Add files under `content/pages/projects/your-project.md`.
- Set `featuredImage` and optional `media` (supports `ImageBlock` or `VideoBlock`).
- GitHub/live links can be added in Markdown sections.

## Images & Files

- Blog images: `public/images/blog/`
- Project images/videos: `public/images/projects/`
- Tech logos (SVG): `public/images/tech-*.svg`
- CV/Cover Letter PDFs: `public/files/Hieu_Pham_CV.pdf`, `public/files/Hieu_Pham_Cover_Letter.pdf`

Update references in the content files with absolute paths, e.g. `/images/blog/swe.jpg`.

## Theming & Code Styling

- Global styles: `src/css/main.css`
- Code blocks use a simple black background with bright, legible syntax colors.
- Buttons use subtle glass/gradient styles to fit the dark theme.

## Project Recommendations (Prev/Next)

Circular recommendation logic is implemented in `src/utils/static-props-resolvers.ts` to always show two projects (wraps at start/end).

## Social Links

- Navbar/social: `content/data/config.json`
- Page-level icon buttons: `content/pages/index.md` and `content/pages/info.md`

## Deployment

This repo includes `netlify.toml`. Typical options:

### Netlify
- Build command: `npm run build`
- Publish directory: `.next`
- Framework: Next.js (Netlify will detect and use the Next.js Runtime)

### Vercel
- Import the GitHub repo in Vercel and deploy (no extra config needed).

## License

Personal project – all rights reserved unless otherwise specified.
