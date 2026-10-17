# Learning Journal

A running reference of things I've learned — Git workflows, AI agent usage, Hermes configuration, and other tools and processes. Started October 2025.

## Structure

- `index.html` — the main journal page, viewable in any browser
- `entries/` — (reserved for future individual entry files if the journal grows)

## How to add a new entry

1. Open `~/learning-journal/index.html` in a text editor
2. Copy the entry template (marked with `<!-- ENTRY TEMPLATE` in the HTML comments)
3. Paste it in the appropriate spot, fill in the content
4. Update the table of contents at the top of the page
5. Save, then push to GitHub:

```bash
cd ~/learning-journal
git add .
git commit -m "Add entry: [topic name]"
git push
```

The live page at https://tfrei59.github.io/learning-journal/ updates automatically within a minute after pushing.

## Viewing the journal

Open `index.html` in any browser (local preview before pushing):

```bash
xdg-open ~/learning-journal/index.html
```

Or view it online at: https://tfrei59.github.io/learning-journal/

## Permissions

This repo is **public** — anyone can see it, but only the owner (tfrei59) can push changes directly. Other people can fork it or submit pull requests (proposed changes to review), but they cannot modify this repository directly.

## How the journal is structured

- `index.html` — the main journal page with all entries and a table of contents
- `entries/` — reserved for future individual entry files if the journal grows
- An HTML comment template inside `index.html` (search for `ENTRY TEMPLATE`) shows the format for new entries
