# Repository Guidelines

## Project Structure & Module Organization
- `index.html` is the single-page site; edit content and links here.
- `paul.css` holds all styling for the page.
- `paul.jpg` is the background image asset referenced by CSS.
- `foaf.rdf` and `MenairPaulNTAyMDE4.vcf` provide semantic/contact metadata.
- `robots.txt` and `CNAME` support hosting and SEO metadata.
- `CLAUDE.md` documents historical context for this repository.

## Build, Test, and Development Commands
This is a static site with no build system.
- Local preview: open `index.html` directly in a browser (for example, `open index.html`).
- Deployment: push changes to the `main` branch to update GitHub Pages.

## Coding Style & Naming Conventions
- Use tabs for indentation in HTML and CSS, consistent with existing files.
- Keep HTML semantic and minimal; prefer microformat class names already in use (for example, `h-card`, `p-name`, `u-url`).
- Use lowercase filenames with hyphens only if new assets are added.

## Testing Guidelines
- No automated tests are configured for this repository.
- Manually verify in a browser at common widths (mobile and desktop) after changes.

## Commit & Pull Request Guidelines
- Commit messages are short, imperative, and descriptive (for example, “Modernize site” or “Fix background image CSS”).
- PRs should describe the user-facing change and link any relevant issue if one exists.
- Include a before/after screenshot when visual changes are made.

## Security & Configuration Tips
- Do not commit sensitive data; this is a public GitHub Pages site.
- Update `CNAME` only when changing the custom domain.
