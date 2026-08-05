# NW3 Baby Calendar 🍼

A free community resource for families in NW3 London. Get a personalised Google Calendar with baby & toddler classes, and discover free places to go with your little one.

## 🔗 Live Site

👉 [nw3-baby-calendar](https://erpolina-prog.github.io/Baby-events-calendar-/)

## 📅 Google Calendars

| Age Group | Calendar Link | Events |
|-----------|--------------|--------|
| 👶 **0–12 months** | [Add to Google Calendar](https://calendar.google.com/calendar/u/0?cid=8ba089b474c0eb04a53c86824aff7e78faefd28fc7e57bb01cad2e476c28ff34@group.calendar.google.com) | 51 recurring events |
| 🚶 **12–36 months** | [Add to Google Calendar](https://calendar.google.com/calendar/u/0?cid=4143f3280872be0a3a1e7260fe5d544fdaebe34c3f0c503268acf64f4b4b5f89@group.calendar.google.com) | 48 recurring events |

## 📊 Google Sheet (Submissions)

All form submissions are stored in a Google Sheet with 3 tabs:

- **Calendar Requests** — Age input, calendar sent, email
- **Email Subscribers** — Who wants the free places list
- **Feedback** — Community suggestions

🔗 [Open Sheet](https://docs.google.com/spreadsheets/d/1q7DWFP-ns5t1TddJFAbfBaUTJ9mkuSzsrYNqi5PPwnk/edit)

## 🛠 Tech Stack

- **Landing page**: Vanilla HTML/CSS/JS, hosted on GitHub Pages
- **Calendars**: Google Calendar API
- **Database**: Google Sheets (via Apps Script Web App)
- **Data collection**: Hermes AI agent for web scraping + manual curation

## 🗺 Places featured

- 📚 Swiss Cottage Library — free Rhyme Time & Stay & Play
- 🏛️ Keats Community Library — Rhyme Time (£5)
- 🧩 JW3 — sandpit, cafe, indoor play
- 🎨 Camden Art Centre — green lawn, cafe, exhibitions
- 🌳 Parliament Hill Fields + Splash Pool
- 🧸 One O'Clock Club (Peggy Jay Centre) — free under-5s play

## ⚙️ Development Setup

### How to deploy the Apps Script backend

1. Open the [Google Sheet](https://docs.google.com/spreadsheets/d/1q7DWFP-ns5t1TddJFAbfBaUTJ9mkuSzsrYNqi5PPwnk/edit)
2. Go to **Extensions → Apps Script**
3. Paste code from `docs/apps_script.gs`
4. Click **Deploy → New Deployment → Web app**
5. Set: Execute as "Me", Who has access "Anyone"
6. Copy the deployment URL
7. Replace `YOUR_DEPLOYMENT_URL_HERE` in `index.html`

### How to update the calendar data

Calendars are populated via Hermes agent with Google Calendar API.

## 📝 License

Non-profit community project. Made with ❤️ for NW3 families.