# Proposal Generator

Self-contained HTML sales proposal templates. A single file per proposal, driven
by one JavaScript config object, deployable to any static host. No build step,
no dependencies, no server.

## What it does

- **Info one-pager** — a content-rich proposal with toggleable sections,
  comparison table, timeline and step-by-step components, and a print-ready
  layout so the same file works on screen and as a PDF.
- **Pricing proposal** — a modular quote with benefit cards, implementation
  steps, module detail, an ROI table, and pricing cards that support an optional
  grant or discount line.
- **Data-driven sections** — every block hides itself when its data is empty and
  numbering re-flows automatically, so one template covers proposals of very
  different shapes without hand-editing markup.
- **Zero infrastructure** — because a proposal is a leaf asset with a short life,
  the template stays a static file rather than an app to operate.

## Status

In production. Used to produce client-facing proposals.

## Code

This repository holds the description. The implementation lives in a private
repository, because the templates carry commercial pricing structure and client
positioning that is not mine alone to publish.

Happy to walk through how it is built: **[jakubjamny.com](https://jakubjamny.com)**

## License

MIT, see [LICENSE](LICENSE).
