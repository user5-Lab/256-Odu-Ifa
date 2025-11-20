# 256-Odu-Ifa
This system consists of 16 major Odu (Oju Odu) and 240 minor Odu (Omo Odu) formed from combinations of the major ones. Each Odu contains verses, proverbs, and spiritual wisdom used by diviners (Babalawos) to offer guidance on life, destiny, and challenges.

***

# Ifá Odu 16 with VFS

A simple, private, and powerful web-based Virtual File System (VFS) for storing and searching Ifá Odu knowledge. All data is stored locally in your browser.

## Key Features

- **Local & Private:** Your data never leaves your browser. It's stored using IndexedDB.
- **File Management:** Create, upload, delete, and rename files and folders.
- **Content Editor:** View and edit your `.txt` and `.json` files directly.
- **Deep Content Search:** Search for words or phrases across all your files. The search is smart enough to navigate through JSON objects to find matches in specific fields.
- **Mobile-Friendly:** Works seamlessly on desktop and mobile devices.

## How to Use

1.  **Open:** Simply open the `index.html` file in any modern web browser (Chrome, Firefox, Safari, Edge).
2.  **Add Data:**
    *   Click the hamburger menu (☰) to open the left drawer.
    *   Use the "Upload" button to add your own `.json` or `.txt` files.
    *   Use the "+ New File" button to create a file from scratch.
3.  **Search Content:**
    *   Use the main "Content Search" bar on the page.
    *   Enter a term like "Ogbe", "truth", or "proverb" and press Enter.
    *   Click on any search result to view and edit the file.
4.  **Manage Files:**
    *   The right drawer (opens automatically when you select a file) shows your file tree and a content editor.
    *   The left drawer contains all file operations (Create, Delete, Rename, etc.).

## Recommended Data Format (for Ifá Odu)

For the best search experience, structure your Odu data as a JSON file containing an array of objects. Each object should represent one Odu.

**Example (`ifa_odu.json`):**
```json
[
  {
    "odu_id": 1,
    "odu_name": "Ogbe Ogbe",
    "meaning": "Beginnings, openness, expansion, truth.",
    "proverbs": [
      "The path is clear for him who walks in truth.",
      "As dawn brings light, so Ogbe brings opportunity."
    ],
    "verses": [
      "Ogbe Ogbe says: When hope is planted, it grows into greatness."
    ]
  },
  {
    "odu_id": 2,
    "odu_name": "Oyeku Meji",
    "meaning": "Endings, darkness, introspection, transition.",
    "proverbs": [
      "What is born must eventually die to make way for the new."
    ]
  }
]
```
