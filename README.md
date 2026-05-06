# Woopsie Komban Dark

A deep, warm dark theme for VS Code. JetBrains-flavored palette — sky-blue accents, sage strings, amber warnings, magenta types — on a calm near-black canvas. Built for long sessions where you want the editor to recede and the code to step forward.

![Woopsie Komban Dark](./assets/preview.png)

## Install

### From VS Code Marketplace
*(Once published — pending. Until then, use the local install path below.)*

### From source

```bash
git clone https://github.com/narenkatakam/woopsie-komban-dark.git
cd woopsie-komban-dark
```

Then in VS Code: **F1 → Developer: Install Extension from Location** → pick the `woopsie-komban-dark` folder.

Activate: **F1 → Preferences: Color Theme → Woopsie Komban Dark**.

## Recommended pairings

- **Editor font:** IBM Plex Mono, JetBrains Mono, or FiraCode Nerd Font
- **Icon theme:** Seti Folder (matches the warm-icon glow of this palette best)
- **Line height:** 1.5–1.6 for readability on dense code
- **Cursor blinking:** smooth (`"editor.cursorBlinking": "smooth"`)

## Palette

| Role | Hex | Use |
|---|---|---|
| Canvas | `#181a1d` | Main background (editor, sidebar, panel) |
| Tab inactive | `#161619` | Subtle layering |
| Foreground | `#bcbec4` | Primary text |
| Description | `#7a7e85` | Secondary / inactive |
| Accent (blue) | `#548af7` | Links, buttons, active borders |
| Function (sky) | `#56a8f5` | Function names |
| Type (magenta) | `#c77dbb` | Types, classes, properties, namespaces |
| Keyword (orange) | `#cf8e6d` | Keywords, storage, control flow |
| String (sage) | `#6aab73` | Strings |
| Number (cyan) | `#2aacb8` | Numbers, regex, units |
| Decorator (mustard) | `#bbb529` | Decorators, annotations |
| Success (green) | `#73b00a` | Added, success |
| Warning (amber) | `#e8a33e` | Warnings, modified |
| Error (red) | `#f75464` | Errors, deleted |

## What this theme is *not*

- **Not a CSS-injection theme.** Woopsie Komban Dark is a pure VS Code color theme — no `Custom UI Style` extension required, no `product.json` patching, no rounded panels or glass effects. If you want the floating-panel aesthetic, see [Islands Dark](https://github.com/bwya77/vscode-dark-islands) — be aware that injecting CSS into VS Code triggers a *"Your Code installation appears to be corrupt"* warning and can break with VS Code updates.
- **Not opinionated about your fonts or settings.** Activate the theme and that's it. Pair as you like.

## Inspiration & Attribution

The palette and many of the syntax highlighting choices are derived from:

- **[easemate IDE](https://x.com/easemate)** — original aesthetic source for the deep canvas + warm syntax + sky accent direction
- **[Islands Dark by @bwya77](https://github.com/bwya77/vscode-dark-islands)** — VS Code interpretation of the easemate look that this theme draws its palette and syntax mappings from
- **JetBrains Darcula** — the broader tradition of warm syntax highlighting (orange keywords, magenta types, sage strings) that both above themes inherit

Woopsie Komban Dark adapts the palette and applies it as a **standalone, MIT-licensed VS Code color theme** — without the CSS-injection extension, without the brand identity, without the install scripts. If you want the full visual experience including floating panels and glass effects, install Islands Dark directly. If you want a clean color-theme-only version with MIT licensing and no editor-patching, this is it.

## Versions

- **0.1.0** — Initial release. Color theme only. No CSS, no install scripts.

See [CHANGELOG.md](./CHANGELOG.md) for full history.

## License

MIT — see [LICENSE](./LICENSE).

## Contributing

Open an issue or PR. Particularly welcome:

- Language-specific syntax improvements (the JetBrains-style mappings cover JS/TS, Python, Go, Rust, HTML/CSS, JSON, YAML, Markdown well; less tested elsewhere)
- A screenshot showing the theme in your favorite language
- Reports of any UI element that looks wrong (low contrast, missing color, etc.)

## Author

[Naren Katakam](https://www.narenkatakam.com)
