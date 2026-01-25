# New PDF from Images

**Creates a single PDF from selected image files** using macOS Automator.

## What it does

- Takes one or more image files as input
- Combines them into **one PDF file**
- Uses the current Finder selection order
- Does **not modify the original image files**

## How to use

1. Select image files in Finder (in the desired order)
2. Right-click → **Quick Actions** → **New PDF from Images**
3. A new PDF is created

## Inputs and outputs

- **Input:** Image files (JPG, PNG, TIFF, etc.)
- **Output:** A single PDF file named `New PDF from Images Output.pdf`

## Where it appears

- Finder **Quick Action** (Services menu)

## Important notes

- Original image files are preserved
- The PDF is created on the **Desktop**
- Selection order determines page order
- Tested on recent macOS versions
