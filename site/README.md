# site/

The Water Wizard page: one static `index.html`, no build step. Pushing to `main` publishes it to GitHub Pages
through `.github/workflows/pages.yml` (the repository's Settings > Pages > Source must be
"GitHub Actions").

Live at **https://waterwizard.site** (custom domain set in Settings > Pages, DNS at Namecheap:
four `A` records on `@` to GitHub Pages and a `www` CNAME to `starseed-lucas.github.io`). With an
Actions deploy, GitHub ignores a `CNAME` file, so there isn't one here.

Preview locally from this folder: `python3 -m http.server`, then open http://localhost:8000.

- Copy follows the store pages and the publisher About text in the `lucas-stanford/waterwizard`
  repository (`godot/store/`, `unity/Store/`). No links to itch.io; contact is
  waterwizardstudios@gmail.com.
- Colours and fonts are the light store theme in `godot/docs/STYLE.md` there. Nothing may look like
  Tidewater or Stormtide.
- Images in `img/` are copies from that repository: `mark.png` (`godot/store/brand/mark-light.png`, 256 px),
  `favicon.png`, `godot-cover.png` (`godot/store/cover.png`) and `unity-cover.png`
  (`unity/Store/art/itch-cover-630x500.png`). Recopy them if the store art changes.
