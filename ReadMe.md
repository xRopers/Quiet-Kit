# Quiet Kit

Resize images and merge PDFs — right in your browser. Nothing you open here is ever uploaded anywhere.

**[Try it live →](https://yourusername.github.io/quiet-kit/)**
*(replace with your actual GitHub Pages link once it's live)*

---

## Why

Most free image and PDF tools (TinyPNG, iLovePDF, Smallpdf) work by uploading your files to a server, processing them, and sending them back. That means your files leave your computer — which is a problem if you care about privacy, or you're working with anything sensitive.

Quiet Kit does the same everyday tasks, but every bit of processing happens locally in your browser. No uploads. No accounts. No tracking. You could disconnect your wifi after the page loads and it would still work.

## Features

- **Image tool** — resize, compress, and convert JPG / PNG / WebP files, in bulk. Choose a max width, target quality, and output format. Download everything as a single zip, or as individual files.
- **PDF tool** — merge multiple PDFs into one. Drag to reorder before merging.
- **Dark / light theme** — toggle in the top right, remembers your choice.
- No login, no install, no server, no cost to run.

## How to use it

1. Open the [live link](https://yourusername.github.io/quiet-kit/) (or open `index.html` locally in any modern browser).
2. Pick a tab: **Images** or **PDFs**.
3. Drag your files in, or click to choose them.
4. Adjust the settings, then process or merge.
5. Your download starts immediately — nothing is sent anywhere first.

## Running it locally

No build step, no dependencies to install. Just download `index.html` and open it in a browser, or clone this repo:

```bash
git clone https://github.com/xRopers/quiet-kit.git
cd quiet-kit
open index.html   # or just double-click the file
```

## Tech

A single self-contained HTML file. Image resizing uses the browser's native Canvas API; zipping uses [JSZip](https://stuk.github.io/jszip/); PDF merging uses [pdf-lib](https://pdf-lib.js.org/) — both loaded from a CDN. No frameworks, no build tools, no backend.

## License

MIT — use it, fork it, ship your own version.
