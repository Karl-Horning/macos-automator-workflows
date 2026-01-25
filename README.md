# macOS Automator Workflows — Image and PDF Finder Quick Actions

A curated collection of **macOS Automator workflows** exposed as **Finder Quick Actions** for working with images and PDFs.

All workflows were created by me using **Automator on macOS** and are shared in case they are useful to others who batch-process files in Finder.

## Table of Contents

- [macOS Automator Workflows — Image and PDF Finder Quick Actions](#macos-automator-workflows--image-and-pdf-finder-quick-actions)
  - [Table of Contents](#table-of-contents)
  - [Overview](#overview)
  - [Quick Start](#quick-start)
  - [Usage](#usage)
  - [Project Structure](#project-structure)
  - [License](#license)
  - [Author](#author)

## Overview

This repository contains small, focused **macOS Automator Quick Actions** for common image and PDF tasks such as rotating images, renaming files, and splitting PDFs.

Each workflow is documented individually and designed to be explicit about whether it **modifies files in place** or creates new output.

Supporting documentation covers installation, macOS security prompts, and common Automator issues.

## Quick Start

```bash
git clone https://github.com/Karl-Horning/macos-automator-workflows.git
```

Open any `.workflow` file to install it via Automator.

Installed workflows appear as **Finder Quick Actions**.

## Usage

- Select files or folders in Finder
- Right-click → **Quick Actions**
- Choose a workflow

Important notes:

- Many image workflows are **destructive**
- Files are often modified **in place**
- Duplicate files first if unsure

Refer to individual workflow READMEs for exact behaviour.

## Project Structure

```text
workflows/
├─ images/
│  ├─ flip-images-horizontally/
│  ├─ rotate-images/
│  ├─ scale-images/
│  ├─ normalise-jpg-extension-names/
│  ├─ number-images-sequentially/
│  ├─ reverse-image-file-names/
│  └─ number-pages-sequentially/
└─ pdf/
   ├─ new-pdf-from-images/
   └─ split-pdf/

docs/
├─ workflow-index.md
├─ install-and-security.md
└─ troubleshooting.md
```

## License

This project is licensed under the **MIT License**.

See the `LICENSE` file for details.

## Author

Made with ❤️ by [Karl Horning](https://github.com/Karl-Horning)
