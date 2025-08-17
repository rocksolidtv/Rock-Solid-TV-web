# Rock Solid TV — Site (Manifest-first Vault)
This site uses a simple JSON manifest so your PDF Vault works even with a private repo.

## Files
- `index.html` — main page (About, Episodes, Vault, Contact)
- `style.css` — dark theme
- `vault/manifest.json` — list your PDFs here (no GitHub API needed)
- `vault/` — drop your PDFs here

## Deploy
Upload these files to your repo `rocksolidtv/Rock-Solid-TV-web` (root). Make sure GitHub Pages serves from `main` (root).

## Update the Vault
Edit `vault/manifest.json`, for example:
{
  "files": [
    { "name": "Mystery_Babylon_by_Rocky_Smith.pdf", "title": "Mystery Babylon — Full PDF" },
    { "name": "America_Mystery_Babylon_Index.pdf" }
  ]
}
The site will show download links for any files listed.
