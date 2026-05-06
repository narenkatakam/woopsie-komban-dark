# Changelog

All notable changes to Woopsie Komban Dark will be documented here.

The format follows [Keep a Changelog](https://keepachangelog.com/en/1.1.0/), and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [0.1.1] — 2026-05-06

### Changed
- **UI accent migration: blue → Anthropic-influenced earth orange.** Primary accent `#548af7` → `#d97757`; hover variants `#7cacf8` → `#e89378` and `#6d9df8` → `#c8694a`. Affects buttons, links, active borders, badges, progress bars, find match borders, peek view borders, status bar remote indicator, info icons, and all alpha-shifted variants.
- **Function name color preserved** at `#56a8f5` (sky blue) to maintain syntax distinguishability against the new orange UI accent. Functions remain visually distinct from keywords (`#cf8e6d`) and decorators (`#bbb529`).
- README and package description updated to reflect the new accent palette.

### Notes
- Bracket pair colors unchanged (still rainbow: orange/magenta/cyan/sage/amber/blue) — keeping the JetBrains-style nested-scope visualization.
- No syntax highlighting changes beyond the function-color preservation note above.

## [0.1.0] — 2026-05-06

### Added
- Initial release — Woopsie Komban Dark color theme for VS Code.
- Full UI palette (editor, sidebar, panel, tabs, status bar, terminal, notifications, peek view, diff editor, notebook, settings, debug toolbar).
- Syntax highlighting via `tokenColors` and `semanticTokenColors` for JavaScript / TypeScript, Python, Go, Rust, HTML / CSS, JSON, YAML, Markdown, Shell.
- Terminal ANSI palette matched to the theme.
- MIT license.

### Inspired by
- [easemate IDE](https://x.com/easemate) — original aesthetic direction.
- [Islands Dark by @bwya77](https://github.com/bwya77/vscode-dark-islands) — VS Code palette this theme adapts from.
- JetBrains Darcula — broader syntax highlighting tradition.

### Notes
- Color theme only. No CSS injection, no Custom UI Style dependency, no install scripts. If you want the floating-panel / glass-effect aesthetic, install Islands Dark directly.
