# Losing Someone Who Is Still Here

Companion website for the book, live at
**https://losingsomeonewhoisstillhere.com**.

It's a plain static site: a few HTML pages and one stylesheet, hosted free
on GitHub Pages. There's no build step. Any change saved to the `main`
branch goes live within a minute or two.

## Files

| File | What it is |
|------|------------|
| `index.html` | Home page |
| `resources.html` | Reader resources (the list of links) |
| `style.css` | Colors, fonts and layout for every page |
| `CNAME` | Tells GitHub Pages the custom domain. Don't delete it. |
| `.nojekyll` | Tells GitHub to serve files as-is. Don't delete it. |

## Editing in the browser (no tools needed)

1. Open the file on github.com (for example `resources.html`).
2. Click the pencil icon ("Edit this file").
3. Make the change. In `resources.html`, copy an existing `<li> ... </li>`
   block to add a new link. Comments marked `EDIT ME` show what to replace.
4. Click **Commit changes**, add a short note about what changed, and commit
   to `main`.
5. Wait a minute, then reload the site.

## Previewing locally (optional)

```bash
python -m http.server 8080
# then open http://localhost:8080
```

## Issue tracking

This repo uses [beads](https://github.com/gastownhall/beads) (`bd`) for
to-dos and ideas. See `AGENTS.md`.
