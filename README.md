# mabeet

Booking prototype for verified stays in **Makkah** and **Madinah** — walk times to the Haram, private rooms or shared beds, multi-city Umrah trips, VAT-inclusive totals.

## Features

- Search by city, dates, guests, and room vs shared bed
- Filter by walking time, star rating, and saved stays
- Hotel detail with rooms, reviews, and walk-to-prayer panel
- Multi-city trip builder and checkout (Mada / card / Apple Pay / pay at hotel)
- Arabic / English toggle with RTL layout
- Saved stays and trip persisted in `localStorage`
- Mobile nav + WhatsApp help links

## Run locally

```bash
cd projects/mabeet
npx --yes serve .
```

Open the URL shown (usually `http://localhost:3000`).

## Deploy

Static site — `index.html` is the entry. Deploy the folder to Vercel or any static host.

```bash
npx vercel --prod
```

## Stack

Design Canvas runtime (`support.js` + React from CDN), plain HTML/CSS/JS, Unsplash photos with attribution.
