# AHK Radiology Shortcut Manager

This repository provides a lightweight web interface for creating and managing AutoHotkey shortcut expansions.
The project consists of a single HTML file (`index.html`) containing JavaScript that builds `.ahk` scripts directly in the browser.

## Features
- **Load an existing script** or start a new one from scratch
- **Add or update shortcuts** using a simple form
- **Bulk import** shortcuts from a CSV file
- **Search and filter** your shortcuts table
- **Download** the generated `.ahk` file for use with AutoHotkey

## Getting Started
1. Clone or download this repository.
2. Open `index.html` in your web browser.
3. Use the interface to add shortcuts or import them from CSV.
4. Click **Download .ahk** to save your script.

No build step or server is required; everything runs client‑side.

## CSV Format
The CSV import expects two columns:

```
shortcut,expansion
```

Each row is added to the list, with options to handle duplicates.

## License
This project is provided as-is without a specific license. Feel free to modify for your own use.
