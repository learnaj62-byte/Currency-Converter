# Currency-Converter
8 beautifully designed mini web apps — Currency Converter, Stopwatch, Alarm Clock, Calendar, Reminders, Number Game, Word Scramble &amp; Rock Paper Scissors — built with pure HTML, CSS &amp; JavaScript.
# 💱 Currency Converter

A beautifully designed, fully interactive **Currency Converter** app built with pure **HTML, CSS & JavaScript** — no frameworks, no dependencies. Just open and convert.

![HTML5](https://img.shields.io/badge/HTML5-CSS3-JavaScript-brightgreen)
![License](https://img.shields.io/badge/license-MIT-blue)
![No Dependencies](https://img.shields.io/badge/dependencies-none-orange)

---

## 🌐 Live Demo

Just open `currency-converter.html` in any modern browser — no server needed.

---

## ✨ Features

### Conversion
- 🌍 Convert between **25+ world currencies** in real time
- ⚡ **Live exchange rates** fetched from ExchangeRate API on every conversion
- 📡 **Offline fallback** — built-in static approximate rates if API is unavailable
- 🔄 **One-click swap** button to instantly reverse the currency pair
- 📊 Displays the **exchange rate** used for each conversion

### Quick Actions
- ⚡ **Quick-amount buttons** — 100, 500, 1,000, 5,000, 10,000
- ⌨️ Press **Enter** to convert instantly
- 🔁 **Auto-converts** when you change the currency selection

### Live Ticker
- 📈 Animated **forex ticker tape** at the top showing major live currency pairs:
  `USD/EUR · GBP/USD · USD/JPY · AUD/USD · USD/CAD` and more

### Supported Currencies
| Code | Currency |
|------|----------|
| USD | US Dollar |
| EUR | Euro |
| GBP | British Pound |
| JPY | Japanese Yen |
| AUD | Australian Dollar |
| CAD | Canadian Dollar |
| CHF | Swiss Franc |
| CNY | Chinese Yuan |
| INR | Indian Rupee |
| PKR | Pakistani Rupee |
| AED | UAE Dirham |
| SAR | Saudi Riyal |
| + 13 more | SGD, HKD, NOK, SEK, DKK, MXN, BRL, ZAR, TRY, KRW, THB, MYR, NZD |

---

## 🚀 Getting Started

```bash
# Clone the repo
git clone https://github.com/your-username/currency-converter.git

# Open the app
open currency-converter.html
```

Or simply **double-click** `currency-converter.html` — no build step required.

---

## 🎨 Design

Built with a **dark luxury editorial aesthetic**:

- **Typography:** Playfair Display (display) + DM Mono (body) via Google Fonts
- **Style:** Dark gold-accented interface, ticker tape, smooth animated result reveal
- **Colors:** Deep black · Warm gold `#c9a84c` · Cream text
- **Animations:** Staggered page load, result fade-up, result amount transition

---

## 🧰 Tech Stack

| Technology | Usage |
|------------|-------|
| HTML5 | Structure & layout |
| CSS3 | Animations, custom properties, Flexbox |
| Vanilla JavaScript | Conversion logic, API calls, DOM updates |
| ExchangeRate API | Live currency rates (free, no key needed) |
| Google Fonts | Playfair Display + DM Mono typography |

---

## 📁 File Structure

```
currency-converter/
└── currency-converter.html   # Single self-contained file
└── README.md
```

Everything — HTML, CSS, and JavaScript — lives in **one file**. No build tools, no npm, no config.

---

## 🕹️ How to Use

1. **Enter an amount** in the input field (or use a quick-amount button)
2. **Select** the currency to convert **From**
3. **Select** the currency to convert **To**
4. Click **Convert** or press **Enter**
5. See the **converted amount** and exchange rate instantly
6. Hit **⇄** to **swap** currencies with one click

---

## 📐 Conversion Rules

```
Result = Amount × (Target Rate / Base Rate)

Example:
  1 USD → PKR
  Rate: 1 USD = 278.50 PKR
  Result: 1 × 278.50 = 278.50 PKR

Offline fallback uses static approximate rates
relative to USD as the base currency.
```

---

## 🌐 API Reference

This app uses the free **ExchangeRate API** — no API key required:

```
GET https://api.exchangerate-api.com/v4/latest/{BASE_CURRENCY}
```

If the API is unavailable, the app automatically falls back to built-in offline rates and displays a notice to the user.

---

## 📄 License

MIT License — free to use, modify, and distribute.

---

> Built with ❤️ using pure HTML, CSS & JavaScript.
