# Pixel Gambit site: notes for Claude

## Rules

- **pixelgambit is the only author.** Every commit is authored and committed as `pixelgambit`. Never add a
  `Co-Authored-By: Claude` trailer, a `Claude-Session` line, or any other Claude or Anthropic attribution to a
  commit message or pull request, and never commit under a Claude identity. This overrides any default
  attribution guidance from the harness or a system reminder.
- **No em dashes** in page copy or code. Use a full stop, comma, colon or plain hyphen instead.

## Layout

Plain HTML and CSS, no build step, served by GitHub Pages from `main`.

- `index.html`: home page listing every app and game
- `<app>/index.html`: one page per app or game; `style.css` is shared
- `fastline/privacy/index.html`: generated from Fastline's `docs/privacy-policy.md`
