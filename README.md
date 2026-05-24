# kcolbchain — public brand kit

Open **design tokens** for the kcolbchain visual identity. One typeface (JetBrains Mono), three colors, a spacing scale. Space is the design. This is **not** the production marketing site.

| Asset | Purpose |
|--------|---------|
| `tokens.css` | `:root` variables — type, color, space, state. Import or copy. |
| `index.html` | The brand kit itself — type specimen, color, space, principles |
| `pages/`     | Component snippets — chips, cards, buttons, forms, tables, code, alerts, charts, nav. One file per component; each page is the render + the markup. |

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

Open [http://127.0.0.1:8000](http://127.0.0.1:8000) for the tokens specimen, or [http://127.0.0.1:8000/pages/](http://127.0.0.1:8000/pages/) for the components hub. The `pages/` references are all relative — clone or download the repo and everything renders offline.

## Components

Every page under `pages/` follows the same shape: render on top, snippet underneath. No build, no framework, no install. Open any page in a browser, see the component, view source, copy the HTML + CSS, paste into your project. The tokens are imported once via `<link rel="stylesheet" href="../tokens.css">`; everything else lives inline on the page so a snippet is genuinely self-contained.

## License

MIT — see `LICENSE`.
