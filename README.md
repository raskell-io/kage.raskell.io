# kage.raskell.io

Landing page for [Kage](https://github.com/raskell-io/kage).

**Live:** https://kage.raskell.io

## Quick Start

```bash
# Install tools
mise install

# Start dev server
mise run serve
```

Visit http://127.0.0.1:1111

## Tasks

| Task | Description |
|------|-------------|
| `mise run serve` | Dev server with live reload |
| `mise run build` | Build for production |
| `mise run convert-images` | Convert images to AVIF |

## Structure

```
kage.raskell.io/
├── config.toml          # Zola configuration
├── content/
│   └── _index.md        # Homepage
├── sass/style.scss      # Styles (Catppuccin palette)
├── static/              # Images, fonts, favicon
└── templates/           # Zola templates
```

## Tech Stack

- [Zola](https://www.getzola.org/) — Static site generator
- [mise](https://mise.jdx.dev/) — Task runner
- [Catppuccin](https://catppuccin.com/) — Color palette
- [Geist](https://vercel.com/font) — Typeface

## Related

- [kage](https://github.com/raskell-io/kage) — Main repository
- [kage.raskell.io-docs](https://github.com/raskell-io/kage.raskell.io-docs) — Documentation site
- [Discussions](https://github.com/raskell-io/kage/discussions) — Questions and ideas

## License

Apache 2.0
