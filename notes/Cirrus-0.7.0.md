
iCloud sync that works, and a panel made of glass.

### New

- On macOS 26 the panel, its pills, the command palette, and toasts are drawn in Liquid Glass.
- Swipe sideways with two fingers on the panel to switch notes.
- Share and Move to Trash from the panel's footer. Share adds Copy as Rich Text, Copy Link, and Export as Markdown.
- A pin beside a pinned note's title.
- Settings › Editor › Start new notes with a title.
- Settings › Editor › Move ticked items to the bottom.
- Reset Panel Size and Position, in the command palette.

### Improved

- Exporting a note with images writes a folder holding the note and its attachments, which Import Notes reads back.
- The formatting bar grows out of its toggle and stays open across launches.
- The opacity slider covers the glass panel's whole range.
- Ticking a checkbox springs the tick and fades the item's text. Sections fold and unfold with an animation.
- Tags in notes written outside the editor, by import or Shortcuts, show up in #tag search without opening the note.
- The panel shows and hides faster.

### Fixed

- Notes now reach iCloud. Earlier versions had every save refused without saying so; this version sends all your notes once.
- An edit made on another device merges into the note instead of being overwritten, including a note left unsent when Cirrus quit.
- When another device edits the open note, you keep your caret, scroll position, and undo history.
- A note iCloud refuses, for example when iCloud is full, is sent again and shown as a sync error.
- An image shows when its attachment syncs after its note.
- A new device waits for your trash retention setting to sync before it empties the trash.
- Empty checklist items no longer count as tasks.
- Tooltips no longer show a toggle's previous state.

