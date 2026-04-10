# Workflow Index

A catalogue of all Automator workflows in this repository.

## Image workflows

| Workflow                      | Description                                        | Modifies originals |
| ----------------------------- | -------------------------------------------------- | ------------------ |
| Flip Images Horizontally      | Mirrors images left-to-right                       | Yes                |
| Rotate Images Left            | Rotates images 90° counter-clockwise               | Yes                |
| Rotate Images Right           | Rotates images 90° clockwise                       | Yes                |
| Rotate Image 180°             | Rotates images upside down                         | Yes                |
| Scale Images to 1280px        | Resizes images to 1280px wide                      | Yes                |
| Normalise JPG Extension Names | Converts `.JPEG` / `.jpeg` / `.JPG` to `.jpg`      | Yes                |
| Number Images Sequentially    | Renames images to `IMG_0001` format                | Yes                |
| Reverse Image File Names      | Reverses numbering of an image sequence            | Yes                |
| Number Pages Sequentially     | Renames images to `PAGE_0000` format (starts at 0) | Yes                |

## PDF workflows

| Workflow            | Description                               | Modifies originals |
| ------------------- | ----------------------------------------- | ------------------ |
| New PDF from Images | Creates a single PDF from selected images | No                 |
| Split PDF           | Splits a PDF into one file per page       | No                 |

## Notes

- Destructive workflows **modify files in place**
- Non-destructive workflows create new files on the **Desktop**
- See individual workflow READMEs for exact behaviour
