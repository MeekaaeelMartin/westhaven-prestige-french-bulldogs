# Westhaven French Bulldogs

Static website for **Westhaven** (Katrina & Colton West).

## Pages

- `index.html` — Home
- `about.html` — About
- `dogs.html` — Dogs, current litter & previous litter
- `contact.html` — Contact

## Hostinger deploy

This is a **static** site. No `npm install` or build step is required.

1. In Hostinger, use **Static Website** / file hosting (not a Node.js app).
2. Upload the site files into `public_html` (or point Git deploy at the repo root).
3. Leave **Build command** empty.
4. Set **Publish directory** to `.` (the folder that contains `index.html`).

Do **not** run `npm install` — there are no app dependencies.

## Local preview

Open `index.html` in a browser, or:

```bash
npx --yes serve .
```
