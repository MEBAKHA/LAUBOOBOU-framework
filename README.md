# Lauboobou (SCSS Framework) — Copy

This is a working copy that contains a built CSS and a demo page for quick testing.

## Quick start

- Open `index.html` in this folder to try the demo (it links to `dist/main.css`).
- Or run a local server:

```powershell
Set-Location 'C:\Users\Rakha\lauboobou-copy'
python -m http.server 8000
# then open http://localhost:8000
```

## Build

If you want to change SCSS and rebuild:

```powershell
npm install
npm run build
```

## Release & ZIP

A tag `v0.1.0` was created. I also placed a ZIP of this working copy at:

`C:\Users\Rakha\Desktop\lauboobou-copy.zip`

To publish a GitHub Release with that ZIP attached, create a release on GitHub using tag `v0.1.0` and upload the ZIP.

## CI

The repo includes a GitHub Actions workflow that builds SCSS on push (`.github/workflows/build.yml`).

## Notes

If you see an error-page CSS (e.g. in `dist/style.css`) like "There's already a module with namespace 'reset'", it means a prior build failed and produced an error stylesheet. Remove that `style.css` and rebuild.
