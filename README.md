# Portfolio — setup

## Files

```
portfolio/
├── index.html      ← the whole site
└── img/            ← put every image here
```

## What to put in `img/`

| File | What it is |
|---|---|
| `me.jpg` | your photo (square crops best) |
| `resume.pdf` | your CV |
| `splitwise-lite-1.png`, `-2.png`, `-3.png` | app screenshots, 3–5 per app |
| `meta-android-developer.png` | certificate images |

Screenshots look best as raw phone captures (portrait, ~1080×2340). No need to add
phone frames — the site already renders them inside rounded frames.

## Editing your content

Open `index.html` and scroll to the line that says **EDIT EVERYTHING BELOW THIS LINE**.
Three things to change:

1. `PROFILE` — your name, role, links, about text, skills.
2. `APPS` — one entry per app. The `highlight` field is the one recruiters read, so
   make it specific: the actual technical problem and how you solved it.
3. `CERTS` — one entry per certificate.

Then fill in the `screenshots: []` arrays with your file paths, e.g.
`screenshots: ["img/splitwise-1.png", "img/splitwise-2.png"]`.

Until you do, the gallery shows dashed placeholders telling you the filename it expects.

## Hosting it free

**GitHub Pages** — create a repo, upload the `portfolio` folder contents to the root,
then Settings → Pages → Deploy from branch → `main` / root. Live in about a minute at
`yourhandle.github.io`.

**Netlify Drop** — go to app.netlify.com/drop and drag the whole `portfolio` folder
onto the page. Instant URL, no account needed to start.

Custom domain later: both support it under their domain settings.
