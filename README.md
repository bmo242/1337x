# 1337x Smart Search

A lightweight, single-file browser tool that builds targeted Google search queries for [1337x](https://www.1377x.to/) — with quality, size, category, and encode group filters built in.

No backend. No dependencies. No install. Just open and search.

---

## Why

1337x's built-in search can be frustrating to filter precisely. Searching Google with `site:1377x.to` tends to surface better results — this tool makes it fast to build those queries without typing them manually every time.

---

## Features

- **Quick combo presets** — one-click filter sets for common scenarios (Small & Sharp, Cinema Quality, 4K Overkill, Binge TV, Quick Download)
- **Video quality filter** — 4K, 1080p, 720p, BluRay, WEB-DL, HDRip, HEVC, x265, x264, REMUX
- **File size filter** — <1GB, <2GB, 1–3GB, 3–10GB, >10GB
- **Encode group filter** — YTS, YIFY, RARBG, GalaxyRG, MkvCage, TIGOLE, EVO, FGT, GECKOS, DEFLATE, CMRG, SPARKS
- **Category filter** — Movies, TV, Anime, Documentaries, Games, Software, Music
- **Live query preview** — see exactly what Google will search before you fire
- **Copy to clipboard** — grab the raw query to use anywhere
- **Three search engines** — Google (20 results), DuckDuckGo, Bing
- **Enter key shortcut** — hit Enter to search Google instantly

---

## Usage

1. Type your movie, show, or content title
2. Pick a quick combo or set filters manually
3. Check the query preview at the bottom
4. Click **Google**, **DuckDuckGo**, or **Bing** to open results

---

## Combo Presets

| Combo | Quality | Size | Group | Category |
|---|---|---|---|---|
| Small & Sharp | 1080p · HEVC | < 2 GB | YTS | — |
| Cinema Quality | 1080p · BluRay | — | — | Movies |
| 4K Overkill | 4K · REMUX | > 10 GB | — | — |
| Binge TV | 1080p · WEB-DL | — | — | TV |
| Quick Download | 720p | < 1 GB | YTS | — |

---

## Encode Groups Reference

| Group | Known for |
|---|---|
| YTS / YIFY | Small, well-compressed movies — typically 700MB–2GB |
| GalaxyRG | Reliable small encodes, good quality-to-size ratio |
| MkvCage | Consistent small-file releases |
| TIGOLE | High quality x265 encodes |
| RARBG | Legendary scene group (defunct but releases still circulate) |
| EVO / FGT / GECKOS | Popular general release groups |
| DEFLATE / CMRG / SPARKS | Scene groups with strict size standards |

---

## Deployment

This is a single `index.html` file with no build process, no dependencies, and no server requirements.

**GitHub Pages** — the recommended way to host this:

1. Fork or clone this repo
2. Go to **Settings → Pages**
3. Set source to `main` branch, `/ (root)` folder
4. Save — your tool will be live at `https://yourusername.github.io/repo-name`

**Local use** — just open `index.html` directly in any browser. No server needed.

**Other hosts** — drop the single file into Netlify Drop, Vercel, or any static host.

---

## Note on File Size Filtering

The size filter appends common file size terms (e.g. `"2gb"`, `"1.5gb"`) to the Google query. This works when the torrent title includes the size — which encode groups like YTS typically do. For releases that don't include size in the title, use the **Encode group** filter instead as a reliable proxy for smaller files.

---

## License

Personal use tool. No warranties. Use responsibly and in accordance with the laws in your jurisdiction.
