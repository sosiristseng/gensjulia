# Julia resource list

https://gensjulia.pages.dev/

## Cloudflare Pages settings

The Cloudflare project builds this repository directly (legacy "build from git" style), so its build settings live in the Cloudflare dashboard, not in this repo:

- Framework preset: `None`
- Build command: `git clone --filter=blob:none --quiet https://github.com/jackyzha0/quartz runtime && git -C runtime checkout "$(tr -d '[:space:]' < quartz.version)" && cp -v quartz.config.yaml runtime/ && cd runtime && npm ci && npx quartz build -d ../content`
- Build output directory: `runtime/public`

GitHub Actions separately builds the site with [quartz-action](https://raven-wing.github.io/quartz-action/) and publishes it to GitHub Pages. Both builds use the Quartz version pinned in `quartz.version`.

## Obsidian plugins

- Linter
- Outliner
- Sort and permute lines
