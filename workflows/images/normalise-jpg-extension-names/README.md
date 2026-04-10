# Normalise JPG Extension Names

Normalises JPEG file extensions to lowercase `.jpg`.

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

## Important notes

- **No copies are created**
- File contents are unchanged
- Useful for tooling that expects `.jpg` exactly
- Tested on macOS 26
