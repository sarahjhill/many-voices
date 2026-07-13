# Many Voices — D&I Student Initiative Template

A single-file Bootstrap 5 template (`index.html`) for a student diversity &
inclusion project page.

Many Voices is a project for students to interact and communicate between all
diversities. You can learn, ask, socialise, and find a place safe to belong to.

## Opening this project

1. Unzip this folder anywhere on your machine.
2. Open VS Code → **File → Open Workspace from File...** → select
   `many-voices-web.code-workspace`.
   (Or just `File → Open Folder...` on this folder — the `.vscode/extensions.json`
   inside will still prompt you to install the recommended extensions.)
3. VS Code will prompt you to install the recommended extensions — accept it.
   The main one you need is **Live Server**.

## Previewing the page

- Right-click `index.html` in the file explorer → **Open with Live Server**.
- Or click "Go Live" in the bottom-right status bar.
- The page reloads automatically whenever you save changes.

## Editing

Everything — copy, colors, fonts, layout — lives in `index.html`:
- `<style>` block in the `<head>` holds all custom CSS (search for `:root` to
  find the color/token variables).
- Bootstrap and fonts are loaded from CDNs, so you'll need an internet
  connection while editing/previewing.
- Section comments (`<!-- ============ HERO ============ -->` etc.) mark each
  part of the page if you want to jump around quickly (Cmd/Ctrl+F).

## Deploying

Since it's a single static HTML file with no build step, you can drag
`index.html` into any static host (GitHub Pages, Netlify, Vercel) or just
open it directly in a browser.

The repository also includes a GitHub Pages workflow in `.github/workflows/static.yml`.
