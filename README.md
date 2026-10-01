# HAWEROLANDIA Notebook

A personal browser-based notebook for organizing stories, worlds, characters, music, ideas and more.

## Features

* Dark, desktop-style interface
* Separate categories for different types of notes
* Custom text markers with visual effects
* Automatic saving using IndexedDB with localStorage fallback
* JSON import and export
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
| `#)`   | End current effect         |

Effects such as `#!`, `#?`, `#>`, `#X`, `#@` and `#M` continue until `#)` is encountered.

## Running

HAWEROLANDIA Notebook is a static HTML application.

Open `index.html` in a modern browser.

It can also be hosted using GitHub Pages.

## Data

Notes are stored locally in the browser.

You can also export the complete notebook to a JSON file and import it later.

## Project status

Current version: **v0.6**

The core notebook functionality is complete.

## License

No license is currently provided.
