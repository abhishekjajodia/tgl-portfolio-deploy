# TGL Portfolio Deploy

Static-site deployment of the TGL multi-ingredient pivot master brief HTML for Deepika.

Built: 2026-05-09. Source: `~/boco/clients/the-good-leaf/expansion-planning/product-briefs/tgl-product-portfolio.html`.

Auth: HTTP basic auth (deepika / [generated password — surfaced in deploy log]).

## Update flow

1. Regenerate HTML locally: `python3 ~/boco/clients/the-good-leaf/expansion-planning/product-briefs/build/build_tgl_portfolio.py`
2. Copy to deploy dir: `cp ~/boco/clients/the-good-leaf/expansion-planning/product-briefs/tgl-product-portfolio.html ./index.html`
3. Commit + push: `git add index.html && git commit -m "..." && git push`
4. Coolify auto-deploys on push.
