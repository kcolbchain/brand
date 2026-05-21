# kcolbchain — public brand kit

Open **design tokens** for the kcolbchain visual identity. One typeface (JetBrains Mono), three colors, a spacing scale. Space is the design. This is **not** the production marketing site.

| Asset | Purpose |
|--------|---------|
| `tokens.css` | `:root` variables — type, color, space. Import or copy. |
| `index.html` | The brand kit itself — type specimen, color, space, principles |

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
