# nikkiwendt.com

Personal professional site for Nikki Wendt. Plain HTML and CSS, no build step, no JavaScript.

## Deploying

GitHub Pages serves the `main` branch at https://nikkiwendt.com (see `CNAME`).
Push to `main` and the site updates in about a minute.

DNS for the domain is managed in AWS Route 53: four `A` records for the apex pointing at GitHub Pages
(185.199.108.153, 185.199.109.153, 185.199.110.153, 185.199.111.153) and a `www` CNAME to `joeythompson10.github.io`.

## Files

| Path | What it is |
|---|---|
| `index.html` | The home page |
| `resume.html` | One-page printable resume (prints on a single Letter page) |
| `404.html` | Not-found page |
| `style.css` | All styles, including dark mode and print |
| `favicon.svg` | Site icon |
| `sitemap.xml`, `robots.txt` | For search engines |

Fonts (Fraunces and Barlow, SIL Open Font License) load from Google Fonts.

## Facts

Every claim on the site comes from Nikki's master resume and LinkedIn experience. Change a fact there first, then here.

## Previewing locally

```
python3 -m http.server 8000
```

Then open http://localhost:8000. Paths are absolute, so open it through a server, not as a file.
