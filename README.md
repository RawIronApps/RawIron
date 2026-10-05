# RawIron Website

Static website for RawIron, publisher of focused, private apps. Apps: RawIron Log (workout log) and RawIron Fuel (macro tracker).

## Files

- `index.html` — RawIron home page (apps overview, featuring RawIron Log and RawIron Fuel)
- `styles.css` — RawIron styles. The brand palette ("Graphite & Iron Red") in `:root` is shared with the RawIron Log and RawIron Fuel apps (`Resources/Styles/Colors.xaml`); keep them in sync. The red bar before each `.eyebrow` is the shared brand signature.
- `images/` — RawIron mark (`rawiron-mark.svg`, from `_proposals/digital-product-icons/05-raw-mark.svg`), tab icon, and iOS home-screen icon
- `rawironlog/` — RawIron Log landing, support, privacy, and terms pages (see `rawironlog/README.md`)
- `rawironfuel/` — RawIron Fuel landing, tips, support, privacy, and terms pages (see `rawironfuel/README.md`)
- `_proposals/` — design drafts; not published by GitHub Pages while Jekyll is enabled

## Local testing

Press F5 in VS Code. It starts a local server on port 8081 and opens Chrome.

## Before publishing

1. Complete the checklists in `rawironlog/README.md` and `rawironfuel/README.md`.
2. Replace the placeholder RawIron mark with a final logo when one is designed.
3. Push to a public GitHub repository and enable GitHub Pages from the `main` branch and `/ (root)` folder.
