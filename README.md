# RupaFinds

Amazon affiliate picks site (English, for a US/global audience).
Live: https://rupafinds.pages.dev/

## What this repo holds

- `index.html` — the whole site in ONE file (CSS + JS + product images inlined).
  It is generated from the multi-file sources, not edited by hand.

## Source of truth

The editable sources live outside this repo (local workspace):
`index.html` + `style.css` + `script.js` + `images/` (+ `NOTES.md`).

To update the live site: edit the sources, regenerate the single file
with the inliner, then push it here as `index.html`.

## Products (launch)

1. STANLEY Quencher H2.0 FlowState Tumbler 40 oz, Ash
2. TOZO T6 True Wireless Earbuds
3. Anker PowerCore 10K Slim

All "Check Price on Amazon" buttons use official Amazon Associates
SiteStripe links (Store ID `ruparupaid-20`). The site carries the
required affiliate disclosure: "As an Amazon Associate, RupaFinds
earns from qualifying purchases."
