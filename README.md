# noellch

A retro, chill dark theme for VS Code / Cursor.

Inspired by the feeling of walking on the beach at sunset — that moment where summer transitions into autumn. Warm breeze, cold beer, golden hour light, and the calm energy of a day winding down.

## Color Palette

| Role | Hex |
|------|-----|
| Background | `#1a1520` |
| Foreground | `#d4c4a8` |
| Keyword | `#c46a58` — Terracotta sunset |
| Function | `#e8a758` — Golden hour |
| Type/Class | `#c4b063` — Amber sand |
| Number | `#d18a60` — Warm copper |
| String | `#7aa776` — Coastal sage |
| Property | `#79a0c2` — Twilight blue |
| Teal accent | `#59afa6` — Ocean cyan |
| Decorator | `#af78ab` — Dusk purple |
| Comment | `#766788` — Fading light |

## Optimized For

- TypeScript / JavaScript / JSX
- Python
- Go
- JSON / Markdown / HTML / CSS

## Installation

### From `.vsix` (local)

```bash
# In VS Code / Cursor
# Cmd+Shift+P → "Extensions: Install from VSIX..." → select the .vsix file
```

### From source (development)

```bash
# Clone or copy the folder to your extensions directory
cp -r noellch-theme ~/.vscode/extensions/noellch

# Or for Cursor
cp -r noellch-theme ~/.cursor/extensions/noellch

# Restart editor, then Cmd+Shift+P → "Preferences: Color Theme" → select "noellch"
```

## Tips for Customization

To inspect what scope a piece of syntax belongs to:

1. `Cmd+Shift+P` → `Developer: Inspect Editor Tokens and Scopes`
2. Click on any token to see its TextMate scope
3. Edit `themes/noellch-color-theme.json` to adjust

## Publishing

```bash
npm install -g @vscode/vsce
vsce package        # generates .vsix
vsce publish        # publishes to marketplace (needs Azure PAT)
```

## License

MIT
