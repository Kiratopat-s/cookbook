# Project Instructions

This repository is a personal DevSecOps cookbook knowledge site published with GitHub Pages.

## Site Shape

- Keep the project as a static GitHub Pages site.
- Each `.html` file should be a complete, standalone page with its own content.
- Do not introduce a build system, framework, template engine, or shared runtime unless the user explicitly asks for one.
- Prefer plain semantic HTML with inline page-specific CSS and, only when needed, small inline JavaScript.
- Use relative links so pages work both locally and on `github.io`.
- Keep `index.html` as the landing and knowledge browser page.
- Keep detailed cookbook entries under `cookbook/`.

## Content Conventions

- Treat `index.html` as the table of contents and browser for the cookbook.
- Use lowercase kebab-case filenames for new pages, for example `trivy-container-scan.html`, `kubectl-debugging.html`, or `github-actions-oidc.html`.
- Treat each page as a complete DevSecOps recipe or note: title, context, when to use it, prerequisites, commands, expected output, gotchas, troubleshooting, and references when relevant.
- Knowledge pages can cover tools, CLI usage, security checks, CI/CD workflows, cloud identity, Kubernetes, secrets handling, threat modeling, incident response, or experiments, but should still be complete on their own.
- Prefer copy-pasteable command examples with placeholders clearly marked, for example `<image>`, `<namespace>`, or `<account-id>`.
- Include safety notes for destructive commands, credential handling, production changes, and scans that may affect systems.
- Avoid splitting recipe content into external data files or partials.

## Quality Bar

- Keep pages readable on phones and desktops.
- Use accessible heading order, descriptive link text, and sufficient color contrast.
- Before finishing changes, open or inspect the affected HTML page and make sure links and layout still make sense.
