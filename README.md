# Stacked Overdrive — public assets

Public brand assets for [Stacked Overdrive](https://stackedoverdrive.com), a peer-to-peer guitar pedal rental platform in the Pacific Northwest.

The main app repo is private; this companion repo hosts assets that need public HTTPS URLs — most commonly the brand mark for transactional emails (Outlook and Gmail desktop don't render SVG in `<img>`, so emails reference the PNG version directly).

## Files

| File | Use |
|---|---|
| `logo.png` | Brand mark, raster. Used in transactional email templates. 1056×736 transparent PNG. |
| `logo.svg` | Brand mark, vector. Used on app surfaces (nav, footer, loading indicator). viewBox 1939×1448. |

## Direct URLs

- PNG: `https://raw.githubusercontent.com/andrewrubens-max/stacked-overdrive-assets/main/logo.png`
- SVG: `https://raw.githubusercontent.com/andrewrubens-max/stacked-overdrive-assets/main/logo.svg`

## Updating

When the brand mark changes, replace the file here and commit. The raw URL stays stable; consumers (transactional emails, social cards, etc.) pick up the new asset on next fetch.
