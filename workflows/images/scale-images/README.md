# Scale Images

Scales selected image files to a fixed width.

**Warning: This workflow modifies the original image files in place.**

## Included workflows

- **Scale Images to 1280px** – Resizes images so the width is 1280 pixels

## What it does

- Takes one or more image files as input
- Scales images to **1280px wide**, preserving aspect ratio
- Normalises `.jpeg` / `.JPG` extensions to lowercase `.jpg`
- **Overwrites the original image files**

## How to use

1. Select one or more images in Finder
2. Right-click → **Quick Actions**
3. Choose **Scale Images to 1280px**

## Important notes

- **No copies are created**
- File contents are modified
- File extensions are normalised to `.jpg`
- Accepts a mix of JPEG and PNG files in the same selection
- Tested on macOS 26
