# Reverse Image File Names

**Reverses the order of a selected image sequence.**

**Warning: This workflow renames the original files in place.**

## What it does

- Takes one or more image files as input
- Treats the selection as an ordered sequence
- Renames files so the order is **fully reversed**
- Example (10 files):
  - `IMG_0001.jpg` → `IMG_0010.jpg`
  - `IMG_0010.jpg` → `IMG_0001.jpg`
- Normalises `.jpeg` / `.JPG` extensions to lowercase `.jpg`
- **Overwrites the original filenames**

## How to use

1. Select the image sequence in Finder
2. Right-click → **Quick Actions** → **Reverse Image File Names**
3. Filenames are updated immediately

## Important notes

- **No copies are created**
- File contents are unchanged
- File extensions are normalised to `.jpg`
- Zero-padding (e.g. `0001`) is preserved
- Tested on macOS 26
