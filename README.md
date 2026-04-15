# macOS Automator Workflows — Finder Quick Actions

Personal collection of **macOS Automator workflows** exposed as **Finder Quick Actions** for batch-processing images and PDFs in Finder.

Built to keep filenames consistent across folder-based file management — normalising extensions, sequencing scans, and handling common PDF tasks without leaving Finder.

## Quick Start

```bash
git clone https://github.com/Karl-Horning/macos-automator-workflows.git
```

Open any `.workflow` file to install it via Automator. Installed workflows appear as **Finder Quick Actions**.

## Usage

Select files in Finder, then right-click → **Quick Actions** → choose a workflow.

> **Warning:** Many image workflows modify files in place with no undo. Duplicate files first if unsure. See individual workflow READMEs for exact behaviour.

## Project Structure

```text
workflows/
├─ images/
│  ├─ flip-images-horizontally/
│  ├─ rotate-images/
│  ├─ scale-images/
│  ├─ normalise-jpg-extension-names/
│  ├─ number-images-sequentially/
│  ├─ number-pages-sequentially/   # renames images to PAGE_0000 for use in PDF creation
│  └─ reverse-image-file-names/
└─ pdf/
   ├─ new-pdf-from-images/
   └─ split-pdf/

docs/
├─ workflow-index.md
├─ install-and-security.md
└─ troubleshooting.md
```

## Feedback

Found a bug? [Open an issue](https://github.com/Karl-Horning/macos-automator-workflows/issues).

## License

Released under the [MIT License](./LICENSE) by [Karl Horning](https://github.com/Karl-Horning).
