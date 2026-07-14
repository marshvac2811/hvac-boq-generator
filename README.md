# HVAC BOQ Generator

A growing set of self-contained HVAC/MEP estimation tools. No server, no build step, no dependencies — everything runs in the browser.

## Structure
```
/            landing page, links to each tool
/boq/        BOQ Generator (live)
```

## BOQ Generator
Bill of Quantities sheet for HVAC/MEP tenders and estimates.

- Title block: project, client, ref no., date, prepared by, revision
- 7 standard categories, ~30 pre-filled line items: Equipment, Ductwork & Accessories, Piping & Accessories, Insulation, Electrical, Civil & Structural, Testing & Commissioning
- Editable description, unit, qty, rate on every row — amounts calculate live
- Add / remove line items or whole categories
- Category subtotals → grand subtotal → editable Contingency %, Overhead & Profit %, Tax/GST % → Grand Total
- Print / Save as PDF

Quantities and rates are left blank on purpose — fill them in from your project takeoff and current vendor rates.

## Hosting
Enable GitHub Pages: Settings → Pages → Deploy from branch → `main` → `/root`. Live at:
`https://marshvac2811.github.io/hvac-boq-generator/`

## Roadmap
AMC cost & PM schedule generator, ductwork sizing calculator, pump head calculator — added as new folders under the same site.
