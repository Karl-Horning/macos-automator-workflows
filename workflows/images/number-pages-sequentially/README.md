# Number Pages Sequentially

Renames image files to page-based sequential names.

**Warning: This workflow renames the original files in place.**

## What it does

- Takes image files **or folders** as input
- Renames images to the format `PAGE_0000`, `PAGE_0001`, etc.
- Numbering **starts at 0** (assumes the first page is a cover)
- Normalises `.jpeg` / `.JPG` extensions to lowercase `.jpg`
- **Overwrites the original filenames**

## How to use

1. Select image files or folders in Finder
2. Right-click → **Quick Actions** → **Number Pages Sequentially**
3. Filenames are updated immediately

## Important notes

- **No copies are created**
- File contents are unchanged
- File extensions are normalised to `.jpg`
- Zero-padding (e.g. `0000`) is preserved
- Tested on macOS 26
