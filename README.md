# blombos-scripts-cdn

Built, versioned browser scripts for the Blombos Webflow site, served publicly via
[jsDelivr](https://www.jsdelivr.com/)'s GitHub CDN.

**Do not edit files here directly.** Source lives in
[version-control-script-manager](https://github.com/Vincent-At-Savoir-Dessiner/version-control-script-manager)
(`src/`) — this repo only holds build output, published one tag per release. It's public
only because jsDelivr's GitHub CDN requires that; the source repo stays private.

## Usage in Webflow

```
https://cdn.jsdelivr.net/gh/Vincent-At-Savoir-Dessiner/blombos-scripts-cdn@<tag>/<name>.min.js
```

Always pin to a specific tag, never `@latest` — a release should be a deliberate version
bump, not something that changes underneath a live page.
