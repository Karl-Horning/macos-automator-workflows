# Normalise JPG Extension Names

**Normalises JPEG file extensions** using macOS Automator.

**Warning: This workflow renames the original files in place.**

## What it does

- Takes one or more image files as input
- Converts `.JPEG` / `.jpeg` to `.jpg`
- Converts `.JPG` to lowercase `.jpg`
- **Renames the original files**

## How to use

1. Select one or more image files in Finder
2. Right-click → **Quick Actions** → **Normalise JPG Extension Names**
3. Filenames are updated immediately

## Inputs and outputs

- **Input:** Image files with `.jpeg`, `.JPEG`, `.JPG`, or `.jpg` extensions
- **Output:** Same files, renamed to use `.jpg`

## Where it appears

- Finder **Quick Action** (Services menu)

## Important notes

- **No copies are created**
- File contents are unchanged
- Useful for tooling that expects `.jpg` exactly
- Tested on recent macOS versions
