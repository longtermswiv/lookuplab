# LookupLab

**Free Excel function reference where every example runs live in your browser.**

🔗 **Live site: https://lookuplab.pages.dev**

Most Excel reference pages show a formula and a screenshot — you still have to open Excel to test edge cases. LookupLab removes that step: every page embeds a live grid powered by the open-source [HyperFormula](https://hyperformula.handsontable.com/) engine, so you can edit inputs and watch results recalculate in the browser.

## What's inside

- **68 function pages** — syntax, worked examples, and error / edge-case tables (VLOOKUP, XLOOKUP, INDEX, MATCH, SUMIFS, FILTER, UNIQUE, and more).
- **10 side-by-side comparisons** — VLOOKUP vs XLOOKUP, XLOOKUP vs INDEX MATCH, IF vs IFS, SUMIF vs SUMIFS, and more, with a clear verdict on when to use each.
- **Original benchmark data** on the lookup-family pages, with method and scope labeled.
- **Agent-readable** — ships an [llms.txt](https://lookuplab.pages.dev/llms.txt) index and JSON-LD structured data so AI assistants can cite it accurately.

## Principles

- **Tested, not asserted.** Truth values are computed at build time and verified against the live grid in a headless browser before publish. Excel-vs-engine differences are labeled, not hidden.
- **Free, no signup, no install.** Static site on Cloudflare Pages; all calculation happens client-side, so no data leaves your browser.

## Tech

Static HTML · HyperFormula (client-side spreadsheet engine) · Cloudflare Pages · JSON-LD structured data · llms.txt

## License

Content and original benchmarks © LookupLab. HyperFormula is licensed separately (GPL / commercial) by Handsontable.
