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

## Products (launch + v3, 26 Nov 2026)

1. STANLEY Quencher H2.0 FlowState Tumbler 40 oz, Ash
2. TOZO T6 True Wireless Earbuds
3. Anker PowerCore 10K Slim
4. Apple AirTag (2nd Generation), 1 Pack
5. LANEIGE Lip Sleeping Mask, Berry 20 g
6. Squishmallows KPop Demon Hunters Derpy Plush, 12 in
7. Carhartt A18 Watch Cap Beanie, Black
8. Amazon Fire TV Stick 4K Select

Products 1–3 use official Amazon Associates SiteStripe links
(Store ID `ruparupaid-20`). Products 4–8 currently use standard
`?tag=ruparupaid-20` links; they will be swapped to official
SiteStripe links when those are generated. The site carries the
required affiliate disclosure: "As an Amazon Associate, RupaFinds
earns from qualifying purchases."
