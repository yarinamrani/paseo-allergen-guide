# פסאו — מדריך אלרגנים לצוות

Staff allergen & modification lookup tool for Paseo restaurant.

## Features
- 🔍 Search by dish, ingredient, or allergen
- 🏷️ Quick filters: gluten-free, dairy-free, vegan, nut-free, fish, meat
- 📱 PWA — installable on phone home screen, works offline
- 🔐 Admin mode (PIN: `1234`) — add/edit/delete dishes, export/import JSON

## Deploy

**GitHub Pages:** Settings → Pages → Source: `main` branch, `/ (root)` → Save.

**Vercel:** Import repo → deploy. Zero config needed.

The app is a single `index.html` file with no dependencies or build step.

## Admin
- Tap 🔒 button → enter PIN → edit dishes
- Change PIN from admin panel
- Export/import JSON to backup or sync data between devices
- Data stored in browser localStorage per device
