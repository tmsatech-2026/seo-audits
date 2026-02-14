# SEO Audits Deployment

## Project Purpose
This repository hosts completed SEO audit reports as standalone HTML files.
Currently deployed via GitHub Pages (subject to change).

## Workflow
1. SEO audits are generated using Claude Code with the `seo-audit` skill
2. Completed HTML files are saved to this repo
3. Files are committed and pushed to trigger GitHub Pages deployment
4. All audits are kept permanently (no deletion/archival)

## File Naming Convention
- Format: `[clientname]-seo-audit.html`
- All lowercase
- Use hyphens for spaces (e.g., `elevatemarketing-seo-audit.html`)
- Always include the `-seo-audit` suffix for consistency

## File Characteristics
- Standalone HTML files (self-contained)
- Generated via Claude Code using global SEO audit skill
- No build process required
- No external dependencies

## Deployment
- **Current:** GitHub Pages (auto-deploys from main branch)
- **Future:** May migrate to different hosting platform
- Files should work on any static host (self-contained HTML)

## Git Workflow
- Commit new audits directly to main branch
- Push immediately after adding new audits
- Keep all historical audits in the repository

## Adding a New Audit
When adding a new client audit:
1. Generate audit using `/seo-audit` skill (or seo-audit skill)
2. Save as `[clientname]-seo-audit.html` in repo root
3. Commit and push to deploy
