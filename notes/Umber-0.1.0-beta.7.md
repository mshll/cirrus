
- Regroup ⌘K into Note, This Note, Edit, View, and Umber, with the destructive row last. New rows: Copy Link to Note, Open Notes Folder, Check for Updates, and About Umber.
- Move to Trash no longer asks. The Undo toast and Recently Deleted already hold the note, so the sheet was only friction.
- Give every action a shortcut and show it on its palette row. New: ⇧⌘R rename, ⇧⌘P pin, ⌥⌘V capture the clipboard, ⌥⌘L copy a note link, ⌥⌘R reveal in Finder, ⌥⌘O open the notes folder, ⌥⌘F formatting, ⇧⌘⌫ Recently Deleted, ⌃⌘T keep on top, ⌃⌘H dynamic height. Changed: the link command is ⌘L, because ⌘K opens the actions palette; the task list is ⇧⌘9, because ⇧⌘C now copies the note as Markdown. Bullet ⇧⌘8, ordered ⇧⌘7, quote ⇧⌘B, code block ⌥⌘C, paragraph ⌥⌘0, and divider ⌥⌘- were already in the editor and are now listed.
- Run every formatting command from ⌘K. "Formatting…" opens a nested list of headings, marks, highlights, and blocks; a search at the root finds them directly. Escape, ⌫, or ← steps back out.
- Pin notes from ⌘K or the Browse card. Pinned notes head the list, and the pins live with the notes folder in `.umber/state.json`.
- Browse now lists notes by when they were last opened, not by when they were last changed.
- Keep on Top holds the panel open while you work in another app. It lasts for the session and shows a small marker beside the title.
- Add `umber://` links: create, open, append to, prepend to, and search notes, capture the clipboard, and show, hide, or toggle the panel. See [docs/DEEPLINKS.md](docs/DEEPLINKS.md).
- Add Shortcuts and Siri support: New Note, Append to Note, Open Note, Capture Clipboard, Toggle Umber, and Search Notes. Open Note offers a picker of the notes in the folder.
- Replace the text size setting with editor zoom. ⌘+, ⌘-, and ⌘0, or the palette's new View group, scale headings, lists, code, and spacing together.
- Fix opening a note rewriting its file. A note is only written after the user edits it, so the modification date no longer moves on open.
- Move to Trash now moves the note to `.umber/trash/` inside the notes folder. Restore it from the new Recently Deleted card in ⌘K, or from the trash toast's Undo. Notes deleted over 30 days ago go to the system Trash.
- Confirm trash, copy, capture, duplicate, dynamic height, and a saved conflict copy with a glass pill that drops in under the header. Its tint carries the kind: warnings amber, restores and captures green, unknown links red. Trashing a note offers Undo.

