# codyportfolio

Personal portfolio site for [Cody Kandarian](https://github.com/codyk2) — Data Science @ Baylor University '27, incoming SWE @ SpaceX (Summer 2026).

**Live:** https://codyk2.github.io/codyportfolio

## Layout

- **Hero** — intro animation
- **About** — bio + stats
- **Life** — photo carousel (IRONMAN 70.3 Waco, YC × DeepMind hackathon, Baylor Line Half)
- **Work** — experience timeline (SpaceX incoming, Keysight co-op, SMART Hub research, Entry co-founder, ECS Ambassador)
- **Projects** — nine selected builds with live GitHub links
- **Contact** — GitHub / LinkedIn / email

## Structure

```
.
├── index.html       # single-file site (CSS + JS inline)
├── assets/          # 4 images: portrait, Ironman Waco, YC hackathon, Baylor half
└── README.md        # this file
```

## Local preview

```bash
python3 -m http.server 8000
# → http://localhost:8000
```

## Deploy

Served by GitHub Pages from the `main` branch root.
