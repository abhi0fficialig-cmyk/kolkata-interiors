# Kolkata Interior & Furniture website

Static website for **Kolkata Interior & Furniture**, interior design company in Kolkata, West Bengal.
Plain HTML, CSS and JavaScript. No build step.

## Run locally

```bash
python -m http.server 5530
```

Then open http://localhost:5530

## Deploy on Vercel

1. Import this repository in Vercel.
2. Framework preset: **Other**. Leave build command and output directory empty.
3. Deploy. `vercel.json` already sets clean URLs, caching and security headers.

## Folders

| Folder | What is in it |
| --- | --- |
| `index.html` | The whole page |
| `css/style.css`, `js/main.js` | Styles and interactions |
| `assets/` | Logo, room category, trending design, service, people and partner images |
| `gallery/thumbs`, `gallery/large` | Gallery photos (small for the carousel, large for the viewer) |
| `videos/` | Hero video and the four showcase videos |

## Placeholders

Every photo and video is currently a placeholder showing its size.
Replace each file with a real one **using the same file name and path** (for example `assets/products/modular-kitchen.jpg`)
and the site picks it up with no code changes. Partner logos are `assets/partners/partner-1.png` … `partner-7.png`;
update their `alt` text in `index.html` with the partner names.

Testimonials in `index.html` are sample reviews – replace them with real customer reviews before going live.
Add the Facebook page link where `href="#"` sits next to the Facebook icons.
