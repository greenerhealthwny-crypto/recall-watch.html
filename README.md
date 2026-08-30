# Recall Watch

An iOS-shaped prototype for a consumer food-recall app: browse USDA/FDA recalls, see
what to do about them, and get ranked substitute products.

**This is a design prototype, not a shipping app.** All recall data is hardcoded. See
`Recall Watch Build Spec.dc.html` for what a real build requires.

**Live demo:** https://greenerhealthwny-crypto.github.io/recall-watch.html/

## Files

| File | What it is |
| --- | --- |
| `index.html` | Same file as `recall-watch.html`, served as the site's home page by GitHub Pages. |
| `recall-watch.html` | Standalone, self-contained prototype. Open in any browser — no build, no server, no network. |
| `Recall Watch.dc.html` | Source design component. Needs `support.js`, `ios-frame.jsx`, and `_ds/`. |
| `Recall Watch Build Spec.dc.html` | Printable 10-section build specification. |
| `_ds/` | The Organic design system (tokens + component bundle). |

## The prototype

Opens on onboarding (3 steps → allergen picks → notification opt-in). Skip lands on the feed.

Interactive: recall cards, filter chips, search, bottom tabs, detail → ranked swaps,
pantry → barcode scan (with a "simulate a scan" verdict sheet) → returns map.

## Deliberate copy constraints

Carried over from the spec, and worth preserving in any real build:

- Never the word "safe" — the app says **"no recall found."**
- A barcode identifies a product line, not an individual pack. Scan verdicts always
  point the user at the lot code.
- Feed freshness is stated wherever a verdict is given.
- Risk is never conveyed by color alone; every class badge carries a text label.

## Known placeholders

Store map, product thumbnails, receipt OCR. Empty and error states are not designed —
Table 2 of the spec lists them per screen.
