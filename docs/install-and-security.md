# Installation and Security

This document explains how to install the Automator workflows in this repository and how to resolve common macOS security issues.

## Installation

1. Download or clone this repository
2. Open a `.workflow` file
3. Automator will prompt you to install it
4. Confirm to add it as a **Quick Action**

Installed workflows are stored at:

```text
~/Library/Services
```

You can remove a workflow at any time by deleting it from that folder.

## Where workflows appear

Once installed, workflows are available via:

- Finder → right-click → **Quick Actions**
- Finder → right-click → **Services**

Some workflows only appear for compatible file types.

## macOS security prompts

macOS may block workflows the first time they run.

If a workflow does not appear or fails silently:

1. Open **System Settings**
2. Go to **Privacy & Security**
3. Scroll to **Security**
4. Allow the workflow if prompted

You may also need to allow access to:

- Files and folders
- Desktop (for workflows that write output there)

## If a workflow does not appear

Try the following:

- Restart Finder
- Log out and back in
- Re-open the `.workflow` in Automator and re-save it
- Check **System Settings → Privacy & Security → Automation**

## Updating workflows

If you install a newer version:

- Replace the existing `.workflow` file in `~/Library/Services`
- macOS uses the filename to identify the action
