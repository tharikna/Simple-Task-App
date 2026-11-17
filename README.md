# Task & Project Board

A simple single-page app to create, view, edit and delete **tasks** and **projects**.

Each item has:
- **Category**: Task or Project
- **Title**
- **POC** (point of contact)
- **Status**: Haven't started, In progress, Finished
- **Due date** (optional; overdue unfinished items are highlighted)
- **Notes** (optional)

You can filter by category or status and search by title, POC or notes.

## Run it

It's one static file with no build step. Open `index.html` in a browser, or serve the folder with any static host (for example GitHub Pages).

## Storage

When the page runs as a claude.ai artifact, items are saved in the artifact's shared database. Anywhere else, items are saved in the browser's `localStorage`, so each browser keeps its own list.
