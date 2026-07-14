# CSS Practice Tasks

This project contains three small HTML/CSS exercises. Each task has its own
HTML file and its own CSS file — keep each pair together in the same folder
so the styling loads correctly.

---

## Task 1 — Table Style

**Files:** `Task1.html`, `Task1.css`

A simple 2x3 table where each cell looks like a separate rounded "chip"
with a border and a drop shadow, instead of a plain grid.

**What it practices:**
- `border-spacing` to add gaps between table cells (since normal tables
  touch edge to edge by default)
- `border-radius` on table cells to round their corners
- `box-shadow` to give each cell a subtle drop-shadow / floating look
- Basic table structure with `<table>`, `<tr>`, and `<td>`

---

## Task 2 — Floating Articles

**Files:** `Task2.html`, `Task2.css`

A simple article board made of small gray "article" boxes and one bold,
scrollable "featured" box in the middle.

**What it practices:**
- `float: left` to line boxes up side by side and wrap them into rows
- `clear: both` to force an element to always start on its own new line,
  breaking the floated boxes into two separate rows
- `overflow: hidden` to clip text that doesn't fit inside a fixed-height box
- `overflow-y: scroll` plus custom `::-webkit-scrollbar` styling to make a
  scrollable box with a styled scrollbar

---

## Task 3 — Have Fun while Styling

**Files:** `Task3.html`, `Task3.css`

A styled text page with colored links, a highlighted link, and a nested
bullet list (a normal list, a circle-bulleted list inside it, and a
no-bullet list inside that).

**What it practices:**
- Styling links differently using classes (`.red`, `.highlight`) on top of
  a default `a` color
- `background-color` to highlight a link like a text marker
- Nested `<ul>` lists and changing `list-style-type` (`circle`, `none`) at
  different levels
- Coloring text with simple classes (`.blue`)

And this is the Live URL : 
https://noureddin004.github.io/CSS-Practice/
