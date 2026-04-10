# Split PDF

Splits a multi-page PDF into individual page files.

## What it does

- Takes a single PDF file as input
- Splits it into **one PDF per page**
- Names each output file using the original name plus a page suffix
  - Example: `Document.pdf` → `Document-page1.pdf`, `Document-page2.pdf`
- Does **not modify the original PDF**

## How to use

1. Select a PDF file in Finder
2. Right-click → **Quick Actions** → **Split PDF**
3. The PDF is split into individual pages

## Important notes

- Original PDF is preserved
- Output files are created on the **Desktop**
- Page numbering starts at `1`
- Large PDFs may take a few seconds to process
- Tested on macOS 26
