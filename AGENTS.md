# Project Instructions

This repository is a personal cookbook knowledge site published with GitHub Pages.

## Site Shape

- Keep the project as a static GitHub Pages site.
- Each `.html` file should be a complete, standalone page with its own content.
- Do not introduce a build system, framework, template engine, or shared runtime unless the user explicitly asks for one.
- Prefer plain semantic HTML with inline page-specific CSS and, only when needed, small inline JavaScript.
- Use relative links so pages work both locally and on `github.io`.

## Content Conventions

- Treat `index.html` as the table of contents for the cookbook.
- Use lowercase kebab-case filenames for new pages, for example `tomato-fried-rice.html`.
- Recipe pages should include enough detail to stand alone: title, context, ingredients, steps, timing, serving notes, substitutions, and storage notes when relevant.
- Knowledge pages can cover techniques, ingredient notes, menus, or experiments, but should still be complete on their own.
- Avoid splitting recipe content into external data files or partials.

## Quality Bar

- Keep pages readable on phones and desktops.
- Use accessible heading order, descriptive link text, and sufficient color contrast.
- Before finishing changes, open or inspect the affected HTML page and make sure links and layout still make sense.
