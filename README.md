# Public Portfolio Repository

This folder is intended to become a separate public repository for portfolio use.

## Structure

- `index.html`: main landing page for the portfolio
- `projects/eolico-v22/`: first published case study

## Refresh the eolico project page

From the technical repo root:

```powershell
powershell -ExecutionPolicy Bypass -File scripts/v22/build_portfolio_site.ps1
powershell -ExecutionPolicy Bypass -File scripts/v22/export_to_public_portfolio.ps1
```

## Suggested next steps

1. Create a dedicated public GitHub repository.
2. Copy the contents of this folder into that repository root.
3. Publish it via GitHub Pages or connect the repo to Netlify.
