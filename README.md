# kcolbchain — public brand kit

Open **design tokens** and an interactive **playground** for the kcolbchain visual identity (yellow + neon cyan, hexagon mark, motion studies). This is **not** the production marketing site: there is no Listmonk, join flows, or private copy here.

| Asset | Purpose |
|--------|---------|
| `tokens.css` | `:root` variables for dark UI — import or copy into your app |
| `index.html` | Self-contained demo: particles, logo animations, colour swatches, project identity grid |

**Live site:** enable GitHub Pages on this repo (root `/`) → `https://kcolbchain.github.io/brand/`

**Production website** source stays private; **product code** lives in [github.com/kcolbchain](https://github.com/kcolbchain).

## Use the tokens

```html
<link rel="stylesheet" href="https://kcolbchain.github.io/brand/tokens.css">
```

Or vendor the file and override in your own `:root`.

## Local preview

```bash
python3 -m http.server 8000
```

Open [http://127.0.0.1:8000](http://127.0.0.1:8000).

## License

MIT — see `LICENSE`.
