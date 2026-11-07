# HAWEROLANDIA Notebook

A personal browser-based notebook for organizing stories, worlds, characters, music, ideas and more.

## Features

* Dark, desktop-style interface
* Separate categories for different types of notes
* Custom text markers with visual effects
* Automatic saving using IndexedDB with localStorage fallback
* JSON import and export for complete notebook backups
* Readable, decorative TXT export
* UltraBox links rendered as clickable track titles
* Search across notes
* Keyboard shortcuts
* Works directly in a web browser

## Special markers

The notebook supports special markers that change the appearance or behavior of text:

| Marker | Meaning                    |
| ------ | -------------------------- |
| `#$`   | Separator                  |
| `#>`   | Header                     |
| `#?`   | Uncertain information      |
| `#!`   | Important information      |
| `#X`   | Lost / deleted information |
| `#@`   | Character                  |
| `#M`   | Music                      |
| `#U`   | UltraBox track link        |
| `#)`   | End current effect         |

Effects such as `#!`, `#?`, `#>`, `#X`, `#@`, `#M` and `#U` continue until `#)` is encountered.

### UltraBox marker

Use `#U` followed by an UltraBox URL:

```text
#U https://ultraabox.github.io/#...
```

The notebook keeps the full URL in the note, but displays the track title as a clickable link. The title is read from the song data embedded in the UltraBox URL. Clicking it opens the track in UltraBox.

The existing `#M` marker is unchanged and continues to work as a regular music-related text effect.

## Running

HAWEROLANDIA Notebook is a static HTML application.

Open `index.html` in a modern browser.

It can also be hosted using GitHub Pages.

## Data

Notes are stored locally in the browser.

You can export the complete notebook to JSON and import that file later.

A separate TXT export creates a human-readable version of the notes, grouped under category headings. It is intended for reading and sharing, rather than restoring the notebook's full data structure. UltraBox entries are represented by their track titles in this decorative export.

## Project status

Current version: **v0.6**

The core notebook functionality is complete.

## License

No license is currently provided.
