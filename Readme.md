# The Champion's Mind — Course Project Website

This repository contains a one-page website project based on *The Champion's Mind* by Jim Afremow.

## Local preview

```bash
python3 -m http.server 8000
```

Then open <http://localhost:8000>.

## Deploy to GitHub

```bash
git remote add origin https://github.com/<your-username>/the-champions-mind.git
git push -u origin main
```

### Phone-only GitHub upload (no terminal)
If you are on your phone and cannot run `git push`, you can still publish this project:

1. Open the GitHub app (or mobile browser) and go to your `the-champions-mind` repository.
2. Tap **Add file** → **Upload files**.
3. Upload these files from this project: `index.html`, `styles.css`, `vercel.json`, and `README.md`.
4. Commit directly to `main`.

> Why pushing may fail in an AI/runtime environment: there is usually no authenticated GitHub account connected, and often no `origin` remote is configured for your personal repo.

## Deploy to Vercel

### Option A: Vercel Dashboard
1. Import the GitHub repository into Vercel.
2. Framework preset: **Other**.
3. Build command: leave blank.
4. Output directory: leave blank.
5. Deploy.

### Phone-only Vercel deploy
1. Open the Vercel app (or `vercel.com`) on your phone.
2. Tap **Add New Project**.
3. Import `the-champions-mind` from GitHub.
4. Keep defaults (static site) and tap **Deploy**.
5. After deploy finishes, copy your live URL.

### Option B: Vercel CLI
```bash
npm i -g vercel
vercel
vercel --prod
```

## Included project sections
- Title + Introduction
- Goals and context for change
- Book choice and rationale
- Two tested strategies from the book
- Two+ tracking/documentation examples over 2+ weeks
- Three major takeaways + progress reflection + advice
- APA reference entry
