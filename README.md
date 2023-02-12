# Alfred-workflow-move-files
A utility to move a selected file or files in Finder

This simple workflow operates on a selected file or files in Findar and allows the file or files to be moved to another destination. It makes use of the `Action in Alfred` Action and uses the `Jump to:` setting in that Action.

There is already a Universal Action to move selected files but this workflow saves you the step of selecting that Universal Action—providing the destination prompt immediately in response to the hotkey.

# Usage

The workflow operates (only) on a file or files selected in Finder. In response to your hot key (I chose `Control + Cmd + m` to mimic the move command in DEVONthink) the workflow will prompt you for the destination folder (listing those previously used). For a folder not already useed by the workflow just start typing the folder name to see, and select, it in Alfred's search results.

# Note

The hotkey will be stripped when you import the workflow (to ensure it does not conflict with any existing hotkeys you use) so you will need to set that in order for the workflow to work.
