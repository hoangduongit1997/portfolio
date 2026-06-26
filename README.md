# Nguyen Minh Hoang Duong — Portfolio

Single-file static portfolio for **Nguyen Minh Hoang Duong**, Senior Flutter Developer.
Built from [CV_Nguyen_Minh_Hoang_Duong](CV_Nguyen_Minh_Hoang_Duong.pdf). No build step, no dependencies — just `index.html`.

🔗 Live demo: _add your GitHub Pages link here after deploying_

## Stack

- Plain HTML / CSS / vanilla JS (no framework, no bundler)
- Google Fonts: Sora, Inter, JetBrains Mono
- Design language: a Flutter/Dart "code editor" motif — hero is a `class Developer extends Engineer` snippet with a live preview pane, skills are rendered as `import` statements, experience as a collapsible git-log style timeline, education as a `pubspec.yaml` block.

## Run locally

Just open `index.html` in a browser. No server required.

```bash
# or serve it locally
python3 -m http.server 8080
# then visit http://localhost:8080
```

## Deploy with GitHub Pages

1. Create a new repo on GitHub (e.g. `portfolio`), public.
2. Push this folder:
   ```bash
   git init
   git add .
   git commit -m "Initial portfolio"
   git branch -M main
   git remote add origin https://github.com/hoangduongit1997/portfolio.git
   git push -u origin main
   ```
3. On GitHub: **Settings → Pages → Build and deployment → Source: Deploy from a branch → Branch: `main` / root**.
4. Your site goes live at `https://hoangduongit1997.github.io/portfolio/` after ~1 minute.

## Update content

All content lives directly in `index.html` (no CMS/data file) — search for the section comments
(`<!-- hero -->`, experience `<details class="commit">` blocks, etc.) and edit the text/markup in place.

## License

Personal portfolio content — feel free to fork the *code/structure* for your own portfolio,
but please swap out the personal content first.
