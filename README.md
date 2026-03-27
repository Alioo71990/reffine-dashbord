# Reffine MENA — Unified Project

A self-contained multi-page web app. All pages are plain HTML and require no build step.

## File Structure

```
index.html              ← Main dashboard (JLR Hub)
translation.html        ← Translation Hub (text + document mode)
translation-tool.html   ← Excel Translation Tool
seo-tool.html           ← SEO Report Explainer
offer-generator.html    ← Offer Studio (DOCX → CSV)
netlify.toml            ← Netlify config (optional)
```

## Hosting Options

### Option 1: Netlify (Recommended — Free)
1. Go to https://app.netlify.com
2. Drag and drop the entire project folder onto the Netlify dashboard
3. Done — you'll get a live URL instantly

### Option 2: GitHub Pages
1. Push this folder to a GitHub repository
2. Go to Settings → Pages → Source: main branch / root
3. Your site will be live at `https://<username>.github.io/<repo>/`

### Option 3: Any Static Host
Upload all `.html` files + `netlify.toml` to any static hosting service
(Vercel, Cloudflare Pages, etc.). No server-side processing required.

### Option 4: Local
Just open `index.html` in your browser — all pages work offline.

## Navigation
- Every tool page has a **← Dashboard** button to return to `index.html`
- The Tools section on the dashboard links directly to all tool pages
