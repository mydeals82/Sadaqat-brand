# SADAQAT BRAND — multi-language website starter

## Included technologies
- HTML: page structure (`public/index.html`)
- CSS: responsive black-and-gold styling (`public/styles.css`)
- JavaScript: product cards, shopping bag, and order form (`public/app.js`)
- Node.js + Express: backend API (`server.js`)
- JSON: demo product and order files (`data/`)

## Important
This is a demo/starter store, not yet ready for real customer orders. The order file is local JSON; many free hosting services reset local files, so orders may not persist. Before accepting real orders, connect a proper database, add an authenticated admin dashboard, privacy safeguards, and backups. Product images and prices are examples.

## Publish with Render
1. Upload these files to a new GitHub repository. Upload the *contents* of this folder, so `package.json`, `server.js`, `render.yaml`, `public/`, and `data/` are at the repository root.
2. Sign in to Render and choose **New → Blueprint** (or create a Web Service connected to the repository).
3. If using Web Service manually, set **Build Command** to `npm install` and **Start Command** to `npm start`.
4. Render will build and give the site an `onrender.com` address. The first start can take a few minutes. Free services may sleep while idle.
5. Open the public URL and test the products and shopping bag. Do not accept real customer orders until a persistent database is configured.

## Run on a computer
Install Node.js, open a terminal in this folder, then run:
- `npm install`
- `npm start`
- Open `http://localhost:3000`

## Change product data
Edit `data/products.json`. Put real product photos in `public/images/` and update each product's `image` path.
