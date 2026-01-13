# MangoFarm 🌱🥭

A multi-page front-end management system built with **HTML / CSS / JavaScript** for daily farm operations and information display.  
It includes announcements, a dashboard, environmental monitoring, inventory/material management, reminders, and history logs, with shared **header / footer** components for modular maintenance.

> Repo: `h102136/MangoFarm`

---

## Pages (by filename)

- `index.html`: Home
- `dashboard.html`: Dashboard
- `announcement.html`: Announcements
- `environmental_monitoring.html`: Environmental Monitoring
- `inventory.html`: Inventory
- `history.html`: History / Logs
- `reminder.html`: Reminders
- Detail pages (examples)
  - `equipment_details.html`: Equipment Details
  - `fertilizer_details.html`: Fertilizer Details
  - `mango_details.html`: Mango/Crop Details
  - `pesticide_details.html`: Pesticide Details

---

## Tech Stack

- Frontend: **HTML / CSS / JavaScript**
- Shared layout: `header.html`, `footer.html` + `include.js` (loads shared header/footer)
- Firebase (depending on project usage)
  - `firebase-config.js`: Firebase configuration (API keys, etc.)

---

## Project Structure (key files)

> Most files are located under `public/`.

```txt
public/
  ├─ index.html
  ├─ dashboard.html
  ├─ announcement.html
  ├─ environmental_monitoring.html
  ├─ inventory.html
  ├─ history.html
  ├─ reminder.html
  ├─ *_details.html
  ├─ header.html
  ├─ footer.html
  ├─ include.js
  ├─ firebase-config.js
  ├─ *.css
  ├─ *.js
  ├─ icon-EM/
  ├─ MangoFarmApp.png
  └─ favicon.ico
