# Publishing Aperçu to GitHub Pages

This folder is already arranged to match the root of the `signorabraham/apercu.pro` repository.

## Folder structure

```text
apercu.pro/
├── index.html
├── styles.css
├── main.js
├── favicon.svg
├── division.css
├── CNAME
├── images/
│   └── hero-bg.jpg
├── research/
│   ├── index.html
│   └── favicon.svg
├── advisory/
│   ├── index.html
│   └── favicon.svg
├── thinking/
│   ├── index.html
│   └── favicon.svg
└── labs/
    ├── index.html
    ├── favicon.svg
    └── assets/
        ├── styles.css
        ├── main.js
        └── abstract-line.png
```

The favicons are SVG files with the same drawn asterisk and different backgrounds:

- Group: pale blue
- Research: coral
- Advisory: violet
- Thinking: blue
- Labs: lime

## Publish through the GitHub website

1. Download and unzip `apercu-pro-complete.zip`.
2. Open the `apercu-pro-complete` folder on your computer.
3. In GitHub, open `signorabraham/apercu.pro` on the `main` branch.
4. Select **Add file → Upload files**.
5. Drag the **contents inside** `apercu-pro-complete` into the upload area. Do not upload the enclosing folder or the ZIP itself.
6. Make sure `index.html` and `CNAME` appear at the repository root, while `labs`, `research`, `advisory`, `thinking`, and `images` appear as folders.
7. Add a commit message such as `Publish redesigned Aperçu website`.
8. Select **Commit changes**.
9. Wait one or two minutes for GitHub Pages to redeploy.

The finished routes will be:

- `https://apercu.pro/`
- `https://apercu.pro/research/`
- `https://apercu.pro/advisory/`
- `https://apercu.pro/thinking/`
- `https://apercu.pro/labs/`

If GitHub does not replace an existing file during a folder upload, delete that one old file in GitHub and upload its replacement from this package. Do not delete `CNAME`.
