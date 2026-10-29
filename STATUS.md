# STATUS

## What was built

A beginner manual for authors on GitHub: hosting a free author site, tracking edits, and publishing book excerpts with GitHub Pages. Step by step, no code assumed. Created for Dylan Asdale (registered nurse turned AI author, founder of Asdale Dynamics, LLC, Indiana, formed October 2026) and credited to Asdale Dynamics, LLC throughout.

## Contents

- `LICENSE` — MIT License, copyright line exactly "Copyright (c) 2026 Asdale Dynamics, LLC"
- `README.md` — project overview; credits Asdale Dynamics, LLC; warmer, polished tone
- `docs/README.md` — manual table of contents
- `docs/01-welcome.md` through `docs/06-publish-excerpts.md` — the six-step beginner manual (Markdown, printable)
- `docs/printable-checklist.md` — printable setup checklist
- `site/index.html` — static HTML landing page (open in any browser, no server needed)
- `site/01-welcome.html` … `site/06-publish-excerpts.html` — HTML versions of each section
- `site/printable-checklist.html` — HTML printable checklist (with @media print stylesheet)
- `site/LICENSE.html` — HTML version of the license
- `site/styles.css` — shared styles for the static site, including print styles
- `STATUS.md` — this file

## How to run it

The static HTML site needs no build step or server:

1. Open `site/index.html` in a web browser.
2. Navigate between sections with the links on each page.
3. Use your browser's Print command (Ctrl+P / Cmd+P) on `site/printable-checklist.html` (or `docs/printable-checklist.md`) for a printable checklist. A print stylesheet strips navigation and backgrounds for a clean printout.
4. The Markdown source lives in `docs/` and can be opened in any text editor or Markdown viewer.

No installation, no account, and no code required to read the manual. The manual itself teaches how to create a GitHub account and publish with GitHub Pages.

## Verification results

- HTML validity: all 9 files in `site/` parse cleanly (custom HTML parser check). PASS
- Internal links: all 90 internal links resolve to existing files. PASS
- Secrets/scan: no emails, API keys, tokens, or personal data found in any file. PASS
- LICENSE copyright line: exactly "Copyright (c) 2026 Asdale Dynamics, LLC". PASS
- README credit: Asdale Dynamics, LLC credited. PASS
- No `.github/workflows` files present. PASS
- No `node_modules`, build tooling, or package manager files present (static site only). PASS

## Known gaps

- The manual is written as general guidance; GitHub's UI wording and button placement change over time, so some button names may differ slightly from a live session.
- No actual GitHub Pages site was published (this is a manual, not a live author site); publishing requires the reader to follow the steps with their own GitHub account.
- No screenshots are included; steps are described in text only.
- No automation/CI (by design; `.github/workflows` was explicitly excluded).
- No personal data or real account credentials are included anywhere.
- Covers GitHub/authorship only; other LLC topic areas (AI tools, MCP, local AI, bookkeeping, healthcare aids, FFXIV/chess) are out of scope for this manual.