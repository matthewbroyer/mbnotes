# Release notes · Notes (mbnotes.online)

Newest first. One entry per release, in plain words a user would understand.

## 2026-10-13

**New look and Google Keep import** (Official Web App · v1.0, was Alpha v1.1)

- **Import from Google Keep.** Settings → Import from Google Keep reads your Google Takeout .zip (or the Keep .json files) right in the browser. Titles, text, checklists, colors, pins, archive, trash, labels (as #tags), web links, dates and images come across. Running it again skips notes you already imported.
- **Fixed: "Load demo notes" could wipe your notes.** The button showed on any empty view (an empty Trash, no search results) and replaced everything. Sample notes are now only offered when you have no notes, and they're added, never swapped in.
- **Fixed: notes typed in the top box were lost if you clicked away.** Clicking anywhere else now saves the note, and a half-written note survives a reload or closed tab.
- **Fixed: on phones you couldn't pin, archive or delete a note.** Those buttons were hover-only. They're now always visible on touch screens and also in the note editor.
- **Fixed: Undo did nothing the first time.** Undo and Redo now use the browser's own history, so Ctrl+Z works as expected.
- **Safer imports.** Backups and Keep exports are cleaned before they're shown, so a crafted file can't run code in the app.
- **Import backup** now asks whether to add the backup to your notes or replace them, instead of always replacing.
- **Empty Trash** and **Delete all notes** (Settings), both with a confirmation. Moving a note to Trash or Archive shows an Undo.
- Checklists: Enter adds the next item, Backspace on an empty item removes it, and a finished list can be shared as an image (the list's title is hidden unless you turn it on).
- Search now also finds checklist items. Pasting a screenshot attaches it; pasted web formatting is cleaned up. Attachments open when clicked.
- New MB Suite design: left sidebar on computers, icon rail on tablets, bottom bar on phones, tag filter chips on smaller screens, Marigold accent and a new logo.
- Install it as an app (Settings, in Chrome/Edge/Android, or Add to Home Screen on iPhone). Works offline after the first visit.
- The app no longer loads anything from other sites (it used Tailwind, Font Awesome and Google Fonts from CDNs), so it's lighter and nothing about your visit goes to third parties.
- Added a Privacy page.
