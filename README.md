# Paper Template for Working Papers in Critical Search

This is a template for submitting to [Working Papers in Critical Search](https://working-papers-in-critical-search.github.io/home/).

## Quick Start

1. Click "Use this template" (green button, top right)
2. Name your repo: `paper-short-title` (e.g., `paper-ocr-benchmarks`)
3. Clone to your machine and start writing

## Files

```
├── index.qmd          # Your paper (edit this)
├── _quarto.yml        # Quarto config (usually leave alone)
├── references.bib     # Bibliography (optional)
├── data/              # Small data files (< 10MB)
├── figures/           # Images, plots
└── README.md          # This file (replace with your abstract)
```

## Writing Your Paper

Edit `index.qmd`. Structure it however makes sense for your work. There's no required format.

Include your code. If your analysis requires serious compute (GPU cluster, days of runtime), just say so honestly. The point is showing your work, not pretending everything runs on a laptop.

## Preview Locally

```bash
quarto preview
```

## When You're Ready to Publish

1. **Transfer the repo** to the Working Papers organization:
   - Settings → Danger Zone → Transfer ownership
   - Transfer to: `Working-Papers-in-Critical-Search`

2. **Editors review** and may request changes

3. **Create a release** (e.g., `v1.0`)
   - Zenodo automatically archives and mints a DOI

## License

Content: CC-BY 4.0
Code: MIT (unless you specify otherwise)

## Questions?

Open an issue on the [main site repo](https://github.com/Working-Papers-in-Critical-Search/home/issues).
