# Number Images Sequentially

**Renames selected image files to a sequential format.**

**Warning: This workflow renames the original files in place.**

## What it does

- Takes one or more image files as input
- Renames files to the format `IMG_0001`, `IMG_0002`, etc.
- **Overwrites the original filenames**
- Normalises `.jpeg` / `.JPG` extensions to lowercase `.jpg`

## How to use

1. Select one or more images in Finder
2. Right-click → **Quick Actions** → **Number Images Sequentially**
3. Files are renamed immediately

## Important notes

- **No copies are created**
- File extensions are normalised to `.jpg`
- There is a **macOS Automator limit of 1000 files**
- Numbering restarts at `IMG_0001` each time the workflow runs
- Tested on macOS 26
