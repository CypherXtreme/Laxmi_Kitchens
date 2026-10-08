# Laxmi's Kitchen – Food Delivery Website

A single-page food ordering site (HTML + CSS + JavaScript in one file, no build step).

## Features
- Menu with search (press `/` to jump to it), category tabs, veg/non-veg filter and price sorting
- Add / remove items, live bill (item total, delivery, 5% GST), free-delivery progress bar
- Cart drawer, checkout form with validation, remembered customer details, cooking instructions
- Demo order tracking, open/closed badge, mobile menu, mobile cart bar, back-to-top button
- Cart is saved in `localStorage`, so it survives a page refresh

## Project structure
```
.
├── index.html      # all HTML, CSS and JavaScript
├── README.md
└── images/         # optional: your own photos (illustrations are used if missing)
    ├── hero.jpg
    ├── chef.jpg
    ├── red-sauce-pasta.jpg
    ├── white-sauce-pasta.jpg
    ├── veg-maggie.jpg
    ├── plain-maggie.jpg
    ├── paneer-maggie.jpg
    └── chicken-momos.jpg
```

## Run locally
Open `index.html` in any browser.

## Deploy with GitHub Pages
Repo → Settings → Pages → Branch: `main`, folder: `/ (root)`.

## Edit the menu
Change the `MENU` array near the top of the `<script>` in `index.html` (name, price, category, veg flag, image file).
