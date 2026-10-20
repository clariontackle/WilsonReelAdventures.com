# Wilson's Reel Adventures

Website for Wilson's Reel Adventures, private fishing charters with Capt. Bill Wilson out of Ruskin, FL.

Plain static site: `index.html` plus the `assets/` folder. No build step.

## Deploy on Vercel
1. Push this folder to a GitHub repo.
2. In Vercel: Add New → Project → import the repo.
3. Framework preset: **Other**. Leave build and output settings empty. Deploy.

Every push to the main branch redeploys automatically.

## Settings
Open `index.html`, scroll to the bottom, and edit the `SETTINGS` block:
- `bookingUrl`: Bill's FishingBooker Direct link. Every booking button uses it.
- `photoPrice`, `filmPrice`: Clarion Outdoor Films package prices.
