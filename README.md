# FIXON e-catalogue

Static multilingual e-catalogue prepared for GitHub Pages.

## Published pages

- Polish: `/`
- English: `/en/`
- German: `/de/`

## GitHub Pages setup

1. Open repository settings on GitHub.
2. Go to `Pages`.
3. Set `Source` to `Deploy from a branch`.
4. Select branch `main`.
5. Select folder `/ (root)`.
6. Save.

After deployment, the pages will be available as:

- `https://YOUR_LOGIN.github.io/FIXON_e-katalog/`
- `https://YOUR_LOGIN.github.io/FIXON_e-katalog/en/`
- `https://YOUR_LOGIN.github.io/FIXON_e-katalog/de/`

## Updating

Update the source catalogue, regenerate language files, then commit and push:

```powershell
git add .
git commit -m "Update multilingual e-catalogue"
git push
```
