# deboneil07.github.io

Personal site source, built with [matte](https://github.com/deboneil07/matte).

- `content/` — Markdown pages (`content/index.md` -> `/`).
- `templates/` — HTML shell + stylesheet.
- `.github/workflows/pages.yml` — installs matte from git, builds with
  `--base-url https://deboneil07.github.io`, deploys to Pages.

Local preview from this directory:

```sh
cargo install --git https://github.com/deboneil07/matte --locked
matte serve 3000 --base-url https://deboneil07.github.io
```
