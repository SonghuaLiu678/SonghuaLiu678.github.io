# SonghuaLiu678.github.io

Personal academic website. Plain HTML/CSS, no build step required —
GitHub Pages serves these files directly.

## Structure

- `index.html` — Home / about
- `research.html` — Working papers & research interests
- `cv.html` — CV (add `assets/cv.pdf` for the download link)
- `contact.html` — Contact info & links
- `assets/style.css` — Shared stylesheet

## Editing

Open any `.html` file and edit the text directly. Lines marked with
`<!-- ... -->` comments are placeholders — search for `[` brackets and
`TODO`-style comments and fill in your real info (name details,
university, dissertation title, paper abstracts, links, email, etc.).

## Preview locally

Just open `index.html` in a browser, or run a tiny local server:

```
python3 -m http.server 8000
```

then visit http://localhost:8000

## Deploy to GitHub Pages

1. Create a repository named exactly `SonghuaLiu678.github.io` on GitHub.
2. Push this folder's contents to the `main` branch of that repo.
3. In the repo settings → Pages, make sure the source is set to the
   `main` branch, root folder (this is usually automatic for
   `<username>.github.io` repos).
4. Your site will be live at `https://SonghuaLiu678.github.io/`
   (may take a minute or two after the first push).
