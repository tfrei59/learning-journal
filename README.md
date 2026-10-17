# Learning Journal

A running reference of things I've learned — Git workflows, AI agent usage, Hermes configuration, and other tools and processes. Started October 2025.

## Structure

- `index.html` — the main journal page, viewable in any browser
- `entries/` — (reserved for future individual entry files if the journal grows)

## How to add a new entry

1. Open `index.html` in a text editor
2. Copy the entry template (marked with `<!-- ENTRY TEMPLATE` in the HTML comments)
3. Paste it in the appropriate spot, fill in the content
4. Update the table of contents at the top
5. Save, then push to GitHub:

```bash
cd ~/learning-journal
git add .
git commit -m "Add entry: [topic name]"
git push
```

## Viewing the journal

Open `index.html` in any browser:

```bash
xdg-open ~/learning-journal/index.html
```

Or view it online at: https://tfrei59.github.io/learning-journal/ (if GitHub Pages is enabled)
