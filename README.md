# Playful Dolphins

Personal resume and portfolio website built from scratch with Astro.

## Scope Implemented

- Multi-page personal website: Home, About, CV, Experience, Projects, Skills, Certifications, Blog, Contact
- Markdown-driven content collections for Experience, Projects, Certifications, and Blog
- Secure-by-default hosting headers for free-tier deployment
- Contact via direct email and static form handling (Netlify-compatible)

## Project Structure

- `src/pages` route pages
- `src/content` markdown collections
- `src/layouts` shared layout
- `src/components` reusable UI pieces
- `public` static assets, robots, security.txt, and header config

## Local Development

1. Install dependencies:

```bash
npm install
```

1. Run dev server:

```bash
npm run dev
```

1. Build production:

```bash
npm run build
```

## Content Updates

- Experience: `src/content/experience/*.md`
- Projects: `src/content/projects/*.md`
- Certifications: `src/content/certifications/*.md`
- Blog: `src/content/blog/*.md`

## CV PDF

Place your latest PDF at `public/cv/resume.pdf`.

## Deployment

### Netlify (free tier)

- Connect this repo
- Build command: `npm run build`
- Publish directory: `dist`
- Security headers are preconfigured in `netlify.toml`

### Cloudflare Pages (free tier)

- Build command: `npm run build`
- Output directory: `dist`
- Static header policies are defined in `public/_headers`

## Post-Setup Security Checklist

- Replace placeholder contact email in `src/data/site.ts`
- Set final production site URL in `astro.config.mjs`
- Verify Content Security Policy after adding any third-party embeds
- Enable DNSSEC and CAA at your DNS provider
