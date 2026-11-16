## Live Link - https://sarthaop444.github.io/pyrun/
# PyRun · Python Compiler

A mobile-first Python editor and runner that lives in one HTML file.
Write and run Python in your browser, with no install and no backend.

## Features
- Run Python in the browser with Brython
- Syntax highlighting, line numbers and error-line marking
- Word wrap (toggle in the ⋮ menu)
- Inline `input()` support in the output pane
- Multiple files, with imports between them
- Emulated `sqlite3` module, saved in localStorage
- Find and replace, go to line, comment toggle, undo and redo
- Symbol keyboard bar and autocomplete suggestions
- Light and dark themes, Material 3 style
- Download, open and share code

## Usage
Open `index.html` in any modern browser, or use the GitHub Pages link.
An internet connection is needed on first load to fetch Brython from a CDN.

Run with the Run button or Ctrl/Cmd + Enter.

## Limitations
- Brython is not full CPython. Some libraries (e.g. NumPy) are unavailable.
- `sqlite3` is a lightweight emulation that supports basic SQL only.
- Code runs on the main thread, so infinite loops can freeze the tab.

## License
MIT
