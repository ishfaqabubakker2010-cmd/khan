# Afzal Electronics Peshawar Website

Static website (HTML + CSS, no build step).

## Structure
- `index.html` main page
- `css/style.css` styles
- `images/` product and store photos
- `logo.svg`, `favicon.svg` brand files
- `vercel.json` Vercel config

## Deploy to GitHub
```
git init
git add .
git commit -m "Afzal Electronics website"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/afzal-electronics.git
git push -u origin main
```

## Deploy to Vercel
1. Go to vercel.com, click **Add New > Project**, import the GitHub repo.
2. Framework Preset: **Other**. Leave build command and output directory empty.
3. Click **Deploy**.

## Edit
- Phone/address: search `index.html` for `923069345047` and `Achini`.
- Add products: copy a `<div class="card">` block in the products grid and add the photo to `images/`.
