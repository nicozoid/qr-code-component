<!-- Automatically generated — concise, actionable guidance for coding agents -->
# Copilot instructions — qr-code-component-main

Purpose: Help AI agents make productive, low-risk edits to this repository.

Quick summary
- This is a tiny static Frontend Mentor solution: the component lives in the repo root as a static page. Key files:
  - [index.html](index.html) — single-page demo (currently empty/placeholder in this fork).
  - [style.css](style.css) — global styles (edit here).
  - [style-guide.md](style-guide.md) — design tokens, breakpoints, colors and typography.
  - [README.md](README.md) — template describing the challenge and meta information.
  - [images/](images/) — static assets (screenshots, QR image, etc.).

Big-picture architecture & intent
- No build system, frameworks, or tests — this is a static HTML/CSS component. Changes should be local edits to the HTML/CSS and assets.
- Mobile-first, single-component layout: stylesheet follows the challenge's mobile (375px) and desktop (1440px) design targets (see [style-guide.md](style-guide.md)).

Developer workflows (how to run/test locally)
- Quick preview: open the file in a browser:

```bash
open index.html
```

- Lightweight static server (helps with font loading and CORS-sensitive assets):

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

- Recommended editor extensions: Live Server for incremental preview and Prettier/formatters for HTML/CSS if you add tooling.

Project-specific patterns & conventions
- Mobile-first responsive CSS: prefer increasing rules for larger breakpoints rather than mobile overrides.
- Typography & colors are defined in [style-guide.md](style-guide.md). Use the Outfit font family and the listed HSL color tokens.
- Assets: keep images in `images/` and update README links if filenames change. Add `screenshot.jpg` at repo root if you add a project screenshot referenced by README.
- Keep styles in `style.css`; avoid creating multiple stylesheet files unless you add a build step and document it in README.

Integration points and external deps
- The only external dependency is Google Fonts for Outfit (if used) and the hosting environment (static). There is no package.json, CI, or test runner in this repo.

Editing guidance and safe-first edits
- Small visual tweaks: edit `style.css` and preview via Live Server or `open index.html`.
- Structural changes: if modifying HTML structure in `index.html`, keep semantics (headings, landmarks) and preserve asset paths in `images/`.
- Documentation updates: prefer updating [README.md](README.md) and [style-guide.md](style-guide.md) when you change design tokens or layout breakpoints.

Examples
- Add a responsive container in `index.html` and tweak spacing in `style.css`.
- To serve locally and verify fonts load correctly:

```bash
python3 -m http.server 8000
# open http://localhost:8000 in browser
```

What I didn't find (so avoid assumptions)
- No tests, no build scripts, and no CI configuration. Do not add complex build steps without documenting them in `README.md`.

When merging or updating agent instructions
- If a `.github/copilot-instructions.md` already exists in future branches, merge preserving any project-specific examples or required credentials. Keep this file concise (20–50 lines).

Questions for maintainers
- Should I add a short `CONTRIBUTING.md` or a tiny `run-dev` script for convenience? Reply with preferences and I can add it.

— End of file
