# Paperforge — PDF & DOCX Signature Editor

A polished, single-file document editor that lets you open, edit, and sign **PDF** and **Word (.docx)** files directly in your browser. Nothing is uploaded — everything happens locally.

## How it works

1. **Open a document** — Drag a file onto the page or click "Open a document". PDF and DOCX files are supported.
2. **Add text or signatures** — Use the toolbar to place text boxes or signatures. On PDFs, tap anywhere on a page to drop them in.
3. **Create your signature** — Draw it with your finger or mouse, type it in a script font, or upload an image.
4. **Save locally** — Click Save to download the finished file. Everything runs in your browser — nothing is uploaded.

## Features

- **PDF + DOCX in one tool** — Handle both formats without switching apps.
- **Flexible signing** — Draw, type (in cursive fonts), or upload signature images.
- **Fast intake** — Drag-and-drop or open via the toolbar.
- **Private by default** — All processing happens client-side. No backend, no account, no upload flow.
- **Drafts** — Work in progress is saved locally so you can come back to it.

## Running it

It's a single HTML file. Just open `index.html` in a modern browser (Chrome, Edge, Safari, or Firefox), or serve the folder with any static file server:

```bash
# Option 1: open directly
open index.html

# Option 2: serve locally (recommended)
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Built with

- [pdf.js](https://mozilla.github.io/pdf.js/) — PDF rendering
- [pdf-lib](https://pdf-lib.js.org/) — PDF editing & saving
- [mammoth.js](https://github.com/mwilliamson/mammoth.js) — DOCX import
- [html-docx-js](https://github.com/evidenceprime/html-docx-js) — DOCX export
- [html2pdf.js](https://github.com/eKoopmans/html2pdf.js) — HTML → PDF conversion

## License

Free to use. Modify it however you like.
