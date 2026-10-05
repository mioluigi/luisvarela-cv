# Luis Emanuel Varela — Personal Website

A professional portfolio and résumé website created with Hugo.

## Assignment purpose

This website demonstrates the use of Hugo, Markdown, Go templates, Git, GitHub, and static-site deployment to present a technical professional profile.

## Technology

- Hugo static site generator
- Go template-based layouts and theme components
- Markdown content pages
- JSON data files for résumé content
- Git and GitHub for version control
- Netlify for continuous deployment

## Local development

```bash
hugo server -D --disableFastRender
```

Open `http://localhost:1313/`.

## Production build

```bash
hugo --minify
```

Hugo writes the static site to the `public/` directory.

## Site sections

- Home / résumé
- About
- Projects
- Writing
- Contact

## Technical portfolio highlights

- AI-powered authentication and digital provenance
- Responsible AI, AI security, governance, and secure MLOps
- Enterprise AI strategy and digital transformation

## Deployment

Pushes to the `main` branch are configured to trigger automated deployment through Netlify.
