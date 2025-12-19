# Teller Connect GitHub Pages

A minimal Teller Connect demo hosted via GitHub Pages.

## What is here
- `index.html`: Teller Connect button using the Teller Connect JS snippet.

## How to deploy/update
1) Edit `index.html` as needed (e.g., change `applicationId`, copy, branding).
2) Commit and push to `main`.
3) In GitHub: Settings ? Pages ? Source = Deploy from a branch ? Branch = `main`, Folder = `/ (root)`.
4) After Pages builds, visit `https://<username>.github.io/teller-/` (or your custom domain).

## Teller dashboard
- Add your Pages URL (or custom domain) to the Teller allowlist so the widget loads.
- If you change `index.html` path/name, update the allowlist accordingly.

## Local preview
Serve the file locally:
```
python -m http.server 8080
```
Then open http://localhost:8080/.
