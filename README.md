# NS.Cards Admin — prototype

Static, single-file clickable prototype (`index.html`). No build step.

## Publish on Cloudflare Pages (free)

1. Push this folder to a GitHub repository (as the repo root).
2. Cloudflare dashboard → **Workers & Pages** → **Create** → **Pages** → **Connect to Git** → pick the repo.
3. Build settings: **Framework preset** `None`, **Build command** empty, **Build output directory** `/`.
4. Deploy. Every push to the main branch redeploys.

`robots.txt` keeps search engines from indexing the prototype — delete it if you want it indexed.
