# Folio — HTML Folder to Text PDF

A tiny, browser-only tool that turns a folder of HTML chapter files (like the ones you get from unpacking an EPUB) into a single, lightweight, real-text PDF.

No uploads, no servers, no daily limits — everything runs locally in your browser tab.

## Why

Most "epub to PDF" converters either:
- rasterize every page into an image (huge file sizes, blurry text at small sizes), or
- limit you to a handful of free conversions per day.

Folio extracts the actual text from your HTML files and lays it out as **real, selectable text** in the PDF — so the output stays small and stays sharp at any zoom level.

## Features

- 📁 Select a whole folder of `.html` / `.xhtml` files at once
- 🔢 Reads files in natural sort order (`chapter_01`, `chapter_02`, ...)
- ✍️ Preserves headings (H1–H6), **bold**, and *italic* formatting
- 📄 Starts each chapter on a fresh page
- 🔒 100% client-side — your files never leave your machine
- ⚡ No installs, no accounts, no rate limits

## Usage

1. Open `folio-html-to-textpdf.html` in any modern browser (Chrome, Edge, Firefox)
2. Click **Choose folder** and select the folder containing your HTML chapter files
3. Click **Extract Text & Build PDF**
4. Your merged PDF downloads automatically

## Limitations

- Exact pixel-perfect layout from the original HTML/CSS is not preserved — this is a text-first tool, not a visual renderer
- Embedded images in the HTML are not included, only text
- Best suited for text-heavy content (novels, articles, documentation) rather than heavily illustrated books

## Built with

- [jsPDF](https://github.com/parallax/jsPDF) — PDF generation in the browser

## License

MIT — use it, fork it, adapt it.
