# AGENTS.md

## Project description
- GitHub profile README for **Shahadat Himel** (`dev-himel-0o0`), a full-stack software engineer focused on distributed backend architectures, end-to-end type safety, and AI-native product workflows.
- `README.md` is the entire profile: it presents professional experience, engineering principles, the technology stack, and contact links, and renders at the top of the owner's GitHub profile.
- There is no application, package manifest, build, test, lint, or CI. Do not invent or add tooling, dependencies, or scripts.
- Tracked files: `README.md` (all profile content) and `github-banner.png` (2056×765 banner).

## Editing `README.md`
- Treat the content as public-facing professional copy: keep claims, job titles, and experience accurate; do not fabricate credentials, projects, or metrics.
- Keep the banner reference relative (`./github-banner.png`); absolute or local filesystem paths break rendering on GitHub.
- Preserve the existing style: centered `<div>` banner layout, `<br/>` spacing, `###` section headings, and shields.io badges using `style=for-the-badge`, black `000000` backgrounds, and `logoColor=white`.
- Contact links (portfolio, LinkedIn, email) are canonical; do not replace them with placeholders.
- Verify changes in a Markdown preview; there is no build step. Badge and banner URLs load from the network, so validate them by eye rather than assuming they resolved.

## Git conventions
- Work on `main`; history is linear.
- Use Conventional Commits with the `docs(readme)` scope, e.g. `docs(readme): update technical expertise section`.
