# Piccadilly Pay Calculator V1.0

A simple, offline wage calculator for Network Rail Piccadilly station staff to quickly calculate gross pay including shift premiums.

## Features

- **Easy salary entry** with password-protected lock
- **Pay period tracking** - save calculations for 12 pay periods
- **Multiple shift premiums:**
  - Standard overtime (125%)
  - Sunday pay (125%)
  - Bank holiday - rostered (150%)
  - Bank holiday - not rostered (250%)
  - Christmas Day - rostered (200%)
  - Christmas Day - not rostered (300%)
  - Boxing Day - rostered (200%)
  - Boxing Day - not rostered (300%)
- **UK tax & NI estimation** (2025/26 rates, with disclaimer)
- **Dark mode** for comfortable viewing
- **Fully responsive** - works on desktop and mobile
- **No external dependencies** - single HTML file, works offline
- **Data persistence** - saves your settings to browser storage

## How to Use

1. Download or clone this repository
2. Open `index.html` in any web browser
3. Enter your annual salary and lock it with the padlock
4. Select your pay period
5. Enter your shift hours for the period
6. Click "Calculate" to see your gross pay
7. Optionally include UK tax & NI estimate

## Data Storage

All data is stored locally in your browser - nothing is sent to servers. Your salary and calculations are completely private.

## Browser Support

Works on all modern browsers:
- Chrome
- Firefox
- Safari
- Edge

## Made By

Made by Shaffy with a little help from Claude  
Started: 26.03.2026  
Version 1.0: 11.04.2026

---

**Disclaimer:** Tax and NI calculations are estimates only. They do not account for personal tax codes, pension contributions, student loan repayments, or other deductions. Consult HMRC or a tax professional for accurate figures.
