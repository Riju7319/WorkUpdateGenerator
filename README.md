# 📋 Work Update App

A lightweight, mobile-friendly web app for **Toton Shit** — Block Health Worker (Jamboni) — to log daily field activities and generate monthly PDF travel reports for the **Manbhum Ananda Ashram Nityananda Trust** High Impact Rural Eye Health Project, Jhargram.

---

## ✨ Features

- **Add Work Update** — Opens a Google Form to log visits, contacts, topics, and outcomes for the day.
- **Monthly Reports** — Auto-fetches data from Google Sheets and displays all months grouped year-wise.
- **PDF Generation** — Click any month chip to instantly generate and download a formatted A4 landscape PDF report.
- **Mobile-First UI** — Designed like a native mobile app with a gradient header, card layout, pill chips, and a bottom navigation bar.
- **No Backend Needed** — Pure HTML + JavaScript, deployable anywhere (Netlify, GitHub Pages, etc.).

---

## 🚀 Deployment

### Local (Open Directly)
Just open `Index.html` in any modern browser. A CORS proxy is used automatically to fetch Google Sheets data.

### Netlify / Any Web Server
Deploy `Index.html` by dropping it into [Netlify Drop](https://app.netlify.com/drop) or connecting your GitHub repo. Google Sheets data is fetched directly — no proxy needed.

---

## 🛠️ Tech Stack

| Library | Purpose |
|---|---|
| [Bootstrap 5](https://getbootstrap.com/) | JS bundle |
| [Bootstrap Icons](https://icons.getbootstrap.com/) | Icon set |
| [Google Fonts — Inter](https://fonts.google.com/specimen/Inter) | Typography |
| [PapaParse](https://www.papaparse.com/) | CSV parsing from Google Sheets |
| [jsPDF](https://github.com/parallax/jsPDF) | PDF generation |
| [jsPDF-AutoTable](https://github.com/simonbengtsson/jsPDF-AutoTable) | Table layout in PDF |

---

## 📊 Data Source

- **Google Form (Add):** [forms.gle/8TbY5fmMs9rPeiQx7](https://forms.gle/8TbY5fmMs9rPeiQx7)
- **Google Sheet (Report):** Published as CSV via Google Sheets → `File → Share → Publish to web`

---

## 📄 PDF Report Format

Each generated PDF includes:
- Organisation header & project name
- Month/Year and staff details
- Grid table: **Sl · Date of Visit · Place · Person · Topic · Outcome · Follow-Up**
- Signature section at the bottom

---

## 👤 Author

**Riju Karmakar** — © 2025 · All rights reserved
