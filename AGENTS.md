# AGENTS.md

- The page is `site/index.html`; read [`site/README.md`](site/README.md) before changing it.
  No links to itch.io; the contact is waterwizardstudios@gmail.com.
- **Don't publish to a store unless explicitly asked.**

## GitHub Actions: Pages deploys only

- The only workflow allowed in `.github/workflows/` is the GitHub Pages deploy (`pages.yml`).
  No CI, tests, builds, releases, scheduled checks or other deploys.
- Never upload build artifacts (`actions/upload-artifact`).
