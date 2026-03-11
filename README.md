# Shree Ram Precast – Profile Website

Profile website for **Shree Ram Precast Concrete Pipes** (Rohtak, Haryana). Single-page site with products, about, gallery, testimonials, and contact. No e‑commerce.

## Run locally

Open `index.html` in a browser, or serve the folder with any static server:

```bash
# Python
python3 -m http.server 8000

# Node (npx)
npx serve .
```

Then open `http://localhost:8000`.

## Deploy

The site is static (HTML, CSS, JS, images). Deploy the whole project folder to any static host:

- **Netlify:** Drag the folder into [Netlify Drop](https://app.netlify.com/drop) or connect the repo.
- **Vercel:** Import the repo and use default static build (no build command).
- **GitHub Pages:** Push to a repo, enable Pages, set source to main branch and root (or `/docs` if you put the files there).

Keep the `helper_images` folder next to `index.html` so image paths work.
