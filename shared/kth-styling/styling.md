# KTH Quarto Styling — Fallback Reference

The live source of truth for KTH visual identity is the `kth-quarto` repo.
Use this file **only** if live retrieval of the URLs below fails.

## Primary sources (fetch live first)

- Styling guide: `https://raw.githubusercontent.com/KTH-Library/kth-quarto/main/LLM_PROMPT.md`
- Brand definition (colors, typography, logo paths): `https://raw.githubusercontent.com/KTH-Library/kth-quarto/main/_extensions/kth-quarto/brand.yml`
- Repo (browsable): `https://github.com/KTH-Library/kth-quarto`

## Fallback notes (last confirmed, may be outdated — verify against the live files when possible)

- Logo assets are defined in `brand.yml`, e.g. `img/kth_logo_blue.svg` (small/SVG),
  `img/kth_logo_blue_spaced.png` (wide/tall variants), `favicon.png` (icon).
- Core palette includes (hex codes from `brand.yml`):
  - blue: `#004791`
  - darkblue: `#08004f`
  - indigo: `#6298d2`
  - lightblue: `#e0edfc`
  - sand: `#e6e1dd`
  - red: `#d8351e`
  - green: `#3f824e`
  - (full palette also includes grays, yellow, orange, purple, teal — see live `brand.yml`)
- Output should be Quarto-compatible Markdown with correct YAML front-matter.
- Never override the KTH color hex codes.
- Data source and LLM-model attribution should appear in the top-right of the
  header of generated content.

**Do not treat this file as authoritative.** It exists only to keep work
moving if the live repo is temporarily unreachable — always prefer the live
`LLM_PROMPT.md` and `brand.yml`, and flag to the user that a fallback was used.
