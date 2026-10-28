# BOM Dashboard Generator

Browser-based tool that turns a BOM table (`.xlsx`, `.csv`, `.tsv`, or pasted text) into a self-contained procurement status dashboard (single HTML file).

**Live page (bookmark this):** `https://<your-github-username>.github.io/<repo-name>/`

## How it works
- Everything runs in your browser. The BOM is never uploaded anywhere.
- Required columns (matched by header name, any order): Module, Supplier Part No., Item Description, Manufacturer, Manufacturer Part No., Total Qty, Status.
- Build and download the dashboard, or preview it in a new tab.

## Files
| File | Purpose |
|---|---|
| `index.html` | The generator (dashboard template embedded; no external dependencies) |
| `.nojekyll` | Tells GitHub Pages to serve the file as-is |

## Updating
Replace `index.html` with the new version and commit. The page updates within a minute or two.
