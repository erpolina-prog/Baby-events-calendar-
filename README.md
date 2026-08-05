# NW3 Baby Calendar 🍼

A free community resource for families in NW3 London. Get a personalised Google Calendar with baby & toddler classes, and discover free places to go with your little one.

## 🔗 Live Site

👉 [nw3-baby-calendar](https://erpolina-prog.github.io/Baby-events-calendar-/)

## 📅 Google Calendars

| Age Group | Calendar Link | Events |
|-----------|--------------|--------|
| 👶 **0–12 months** | [Add to Google Calendar](https://calendar.google.com/calendar/u/0?cid=8ba089b474c0eb04a53c86824aff7e78faefd28fc7e57bb01cad2e476c28ff34@group.calendar.google.com) | 51 recurring events |
| 🚶 **12–36 months** | [Add to Google Calendar](https://calendar.google.com/calendar/u/0?cid=4143f3280872be0a3a1e7260fe5d544fdaebe34c3f0c503268acf64f4b4b5f89@group.calendar.google.com) | 48 recurring events |

## 🛠 Tech Stack

- **Landing page**: vanilla HTML/CSS/JS, a single `index.html`, hosted on GitHub Pages
- **Calendars**: Google Calendar
- **Forms**: Google Apps Script Web App → Google Sheets
- **Data collection**: web research + manual curation

Form submissions (email signups and contributions) are written to a private Google
Sheet with three tabs — *Calendar Requests*, *Email Subscribers* and *Feedback*.
Emails are never used for marketing and never shared.

## 🗺 Places featured

- 📚 Swiss Cottage Library — free Rhyme Time & Stay & Play
- 🏛️ Keats Community Library — Rhyme Time (£5)
- 🧩 JW3 — sandpit, cafe, indoor play
- 🎨 Camden Art Centre — green lawn, cafe, exhibitions
- 🌳 Parliament Hill Fields + Splash Pool
- 🧸 One O'Clock Club (Peggy Jay Centre) — free under-5s play

## ⚙️ Development

This repo holds only what GitHub Pages serves: `index.html` and this README. The
backend (`Code.js` / clasp project), research notes and config live in the private
project folder alongside it — see its `README.md` for deployment steps, calendar IDs
and the Apps Script setup.

To change the site, edit `index.html` and push. There is no build step.

## 📝 License

Non-profit community project. Made with ❤️ for NW3 families.
