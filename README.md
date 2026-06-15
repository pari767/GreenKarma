# 🌿 GreenKarma — Commute Green. Earn Real Rewards.

> **Hackathon Project** · Built to solve India's urban carbon emission problem through behavioral incentives.

![GreenKarma](https://img.shields.io/badge/GreenKarma-Eco%20Credits-02C39A?style=for-the-badge&logo=leaf)
![HTML](https://img.shields.io/badge/HTML5-Pure%20Frontend-E34F26?style=for-the-badge&logo=html5)
![JavaScript](https://img.shields.io/badge/JavaScript-Vanilla%20JS-F7DF1E?style=for-the-badge&logo=javascript)
![License](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)

---
## Live Demo
[https://pari767.github.io/GreenKarma/](https://pari767.github.io/GreenKarma/)

## Demo Video
[https://drive.google.com/drive/folders/1fp6OJn9hByB_u2QdX8i8dRtUJSHEPZTz?usp=sharing](https://drive.google.com/drive/folders/1fp6OJn9hByB_u2QdX8i8dRtUJSHEPZTz?usp=sharing)

## Presentation Deck
[https://www.pdffiller.com/s/IgwlnzDzOc](https://www.pdffiller.com/s/IgwlnzDzOc)

## GitHub Repository
[https://github.com/pari767/GreenKarma](https://github.com/pari767/GreenKarma)

---

## 🚨 The Problem

**28% of India's urban CO₂ emissions come from personal transport.**

12 million people commute daily in cities like Chennai, Bengaluru, and Mumbai — yet there is **zero financial incentive** to take the bus, metro, or cycle instead of driving.

Result: More cars. More pollution. No change in behavior.

---

## 💡 Our Solution

**GreenKarma** rewards eco-friendly commuters with verifiable carbon credits for every GPS-tracked green trip.

```
Take Bus / Metro / Cycle  →  Earn Carbon Credits  →  Redeem at Swiggy, Zepto, BookMyShow & more
```

Every kilometre of green travel = real money saved + real CO₂ reduced.

---

## ✨ Key Features

### 🔒 GPS-Verified Trip Tracking
- Uses real browser GPS (`navigator.geolocation`) — no manual distance entry
- Haversine formula calculates exact distance from coordinates
- Filters GPS noise (ignores movement < 5 metres)
- **Fraud prevention built-in** — users cannot fake their distance

### 💳 Carbon Credit Wallet
- Credits calculated based on CO₂ saved vs driving a car
- Real-time rupee equivalent value (1 credit ≈ ₹5)
- Full transaction history with earned/redeemed filter tabs
- Eco Level system (Level 1 → 5 based on credits earned)

### 🎁 Rewards Marketplace
- 15 real partner brands across 5 categories
- Food: Swiggy, Zomato, McDonald's
- Grocery: Zepto, BigBasket, Instamart
- Entertainment: BookMyShow, Spotify, YouTube Premium
- Travel: Ola, RapidX, IRCTC
- Health: Cult.fit, PharmEasy, Nykaa
- Unique coupon code generated on every redemption

### 📊 Impact Dashboard
- Total CO₂ saved with real-world equivalents (trees planted, phone charges, car km)
- Transport breakdown by type with animated bar chart
- Achievement badges (First Trip, Cyclist, Top 3, etc.)
- City leaderboard showing your rank vs other commuters

### 👤 Profile & Settings
- Edit name and city
- Toggle preferences (reminders, leaderboard visibility)
- Sign out preserves all data — restored on next login via email key

---

## 🛠️ Tech Stack

| Layer | Technology |
|-------|-----------|
| Frontend | HTML5, CSS3, Vanilla JavaScript |
| Location | Browser Geolocation API (real GPS) |
| Distance | Haversine Formula |
| Reverse Geocoding | OpenStreetMap Nominatim API |
| Storage | localStorage (per-user, email-keyed) |
| Design | Custom dark UI with Inter font |
| Hosting | GitHub Pages |

**No backend. No database. No frameworks. No build tools.**
Pure HTML/CSS/JS — runs entirely in the browser.

---

## 📁 Project Structure

```
GreenKarma/
├── index.html          # Landing page + Login/Signup
└── pages/
    ├── trip.html       # GPS trip tracker
    ├── wallet.html     # Carbon credit wallet
    ├── redeem.html     # Rewards marketplace
    ├── dashboard.html  # Impact stats + leaderboard
    └── profile.html    # Settings + account management
```

---

## 🚀 Getting Started

### Option 1 — Live Demo
👉 **[https://pari767.github.io/GreenKarma/](https://pari767.github.io/GreenKarma/)**

### Option 2 — Run Locally
```bash
# Clone the repository
git clone https://github.com/yourusername/GreenKarma.git

# Open in browser — no server needed!
open index.html
```

---

## 📱 How It Works

```
1. Sign up with name, email & city
        ↓
2. Choose transport type (Metro / Bus / Cycle / Walk)
        ↓
3. Click "Start Trip" → allow GPS permission
        ↓
4. Travel normally — GPS tracks your route
        ↓
5. Click "End Trip" → credits calculated from real distance
        ↓
6. Redeem credits at partner brands → get coupon code
```

---

## 🌍 Impact Calculation

| Transport | CO₂ emitted | vs Car (200g/km) | Credits earned |
|-----------|-------------|------------------|----------------|
| 🚇 Metro  | 0.5g/km     | saves 199.5g/km  | ~1.0 per km    |
| 🚌 Bus    | 0.8g/km     | saves 199.2g/km  | ~1.0 per km    |
| 🚲 Cycle  | 0g/km       | saves 200g/km    | ~1.0 per km    |
| 🚶 Walk   | 0g/km       | saves 200g/km    | ~1.0 per km    |

**Formula:** `Credits = (CO₂ saved in kg) × 0.5 × 10`

---

## 🔒 Fraud Prevention

A core design principle of GreenKarma is that **users cannot self-report distance.**

- ✅ Distance is measured only from real GPS coordinates
- ✅ Haversine formula used — not odometer or self-entry
- ✅ GPS noise filtered (< 5m movements ignored)
- ✅ Minimum trip distance enforced (100m)
- ✅ Credits only awarded on trip completion, not during

---

Built with ❤️

| Name | Role |
|------|------|
| Parigna Chetan | Full Stack + Design |

---

## 📄 License

MIT License — feel free to fork and build on this!

---

<div align="center">

**🌿 Every green commute counts. Start earning today.**

[Live Demo](https://pari767.github.io/GreenKarma/) · [Report Bug](https://github.com/pari767/GreenKarma/issues) · [Request Feature](https://github.com/pari767/GreenKarma/issues)

</div>
