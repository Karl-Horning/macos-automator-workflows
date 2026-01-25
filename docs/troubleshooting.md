# Troubleshooting

This page covers common issues when running the Automator workflows in this repository.

## The workflow does not appear in Quick Actions

### What to check

- The workflow is installed (open the `.workflow` file and confirm)
- You are selecting compatible file types

### Things to try

- Restart Finder
- Log out and back in
- Re-open the workflow in Automator and save it again
- Check **System Settings → Privacy & Security → Automation**

## The workflow appears but does nothing

### Likely causes

- macOS security permissions were denied
- The workflow requires files, but folders (or vice versa) were selected

### Fix

1. Open **System Settings → Privacy & Security**
2. Check for blocked or denied actions
3. Allow access to Files and Folders if prompted

## Files are processed in the wrong order

Some workflows rely on **Finder selection order**.

### Tips

- Use List View in Finder
- Sort explicitly before selecting
- Select files in the correct order

## Files were renamed or modified unexpectedly

Many workflows are **destructive by design**.

### Important reminders

- Image workflows usually modify files in place
- No undo is available after renaming or overwriting
- Duplicate files before running if unsure

## Output files are missing

Some workflows write output to the **Desktop**.

Check:

- Desktop permissions in **Privacy & Security**
- Existing files with the same name (may be overwritten)

## Large batches fail or stop early

Automator has internal limits.

Examples:

- Some rename workflows are limited to **1000 items**
- Very large PDFs may take time to process

Try splitting work into smaller batches.

## Still stuck?

Open the workflow in **Automator** and run it there.
Errors are often shown in the Automator log.
