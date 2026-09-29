# 👑 Royale VIP Casino Studio

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![HTML5 / Vanilla JS](https://img.shields.io/badge/Tech-HTML5%20%7C%20Tailwind%20%7C%20WebAudio-emerald.svg)](#technology-stack)
[![GitHub Pages](https://img.shields.io/badge/Deploy-GitHub%20Pages-blue.svg)](#-how-to-publish-on-github-pages)

[Live Example](https://samsoupsauce.github.io/card-engine/)

An authentic, single-file luxury casino card gaming suite crafted with zero-dependency vanilla web standards. Features an expandable **Grand Salon Game Menu**, a certified **Baccarat Punto Banco** high-roller table with international third-card tableau rules, real-time Macau Bead Plate roadmaps, 8-deck shoe simulation, and synthesized Web Audio sound effects.

---

## ✨ Features

### 🎰 Grand Salon Main Menu
- **Multi-Game Architecture**: Central lobby hub designed to branch into multiple table games while maintaining a unified persistent bankroll.
- **Active Table Entry**: Instant launch into the Baccarat VIP Salon with custom table limits ($5 – $5,000).
- **Expansion Ready**: Pre-architected slots for **Blackjack (Vegas Strip)** and **Dragon Tiger (Macau Showdown)**.

### 🃏 Baccarat VIP Salon (Punto Banco)
- **Authentic 8-Deck Shoe**: Full 416-card shoe featuring Fisher-Yates shuffling, dynamic penetration tracker, and manual/automatic reshuffling.
- **Strict International Tableau**:
  - Automatic checks for natural 8s and 9s.
  - Player rule: Draws on 0–5, stands on 6–7.
  - Banker rule: Complete standard third-card matrix factoring Player's draw.
- **Side Bets & Payouts**:
  - Player (1:1)
  - Banker (0.95:1 with 5% house commission)
  - Tie (8:1 payout with push on main bets)
  - Player Pair & Banker Pair (11:1)
- **Automated Bet Sweeps & REBET**: Table bets cleanly resolve and reset between deals, with one-click **REBET** to repeat previous stakes.
- **Macau Bead Plate Roadmap**: Live chronological 6-row tracking grid showing Player (blue), Banker (red), Tie (green), scores, and cumulative win totals.
* **Macau Bead Plate Roadmap**: Live chronological 6-row tracking grid showing Player (blue), Banker (red), Tie (green), scores, and cumulative win totals.

### ♠️ Blackjack VIP Salon (Vegas Strip)

* **6-Deck Shoe**: Full 312-card continuous shoe with realistic penetration tracking and auto-reshuffle.
* **Vegas Strip Standard Rules**:
  * Dealer stands on all 17s (hard and soft 17).
  * Natural Blackjack pays **3:2**.
  * **Double Down**: Double your wager on initial two cards, receive exactly one card, and stand.
  * **Split Hands**: Split matching initial cards into two independent hands with individual wagers and actions.
  * **Insurance**: Offered when Dealer shows an Ace, paying **2:1** if Dealer has Blackjack.
* **Animated Hole Card Reveal**: Dealer draws one card face up and one card face down with authentic gold-filigree card back, revealed only on Dealer's turn.

### 🎨 Visual & Audio Polish

- **Procedural SVG Cards**: High-definition, scalable vector cards with custom pip placements, court face cards, and luxury card backs.
- **Macau Velvet Aesthetics**: Deep emerald felt with subtle lighting, gold inlays, wood trim rails, and tactile 3D chip racks ($5, $25, $100, $500, $1K).
- **Synthesized Web Audio**: In-browser audio engine generating chip tosses, card slide foley, and winning arpeggio chimes without external asset dependencies.
- **Fully Responsive**: Optimized for desktop, tablets, and mobile touchscreens.

---

## 🛠️ Technology Stack

- **Markup & Layout**: Semantic HTML5 & responsive layout via Tailwind CSS CDN.
- **Vector Graphics**: Procedurally generated SVG cards and FontAwesome 6 icons.
- **Typography**: Google Fonts (*Cinzel*, *Inter*, and *JetBrains Mono*).
- **Sound**: Native Web Audio API (`AudioContext`, synthetic oscillators, bandpass noise generators).
- **Zero Build Step**: No `node_modules`, bundlers, or build tools required—runs directly in any modern browser.

---

## 🚀 Quick Start (Local Setup)

Clone the repository and launch the app in your browser:

```bash
# 1. Clone the repository
git clone https://github.com/YOUR_USERNAME/royale-vip-casino.git

# 2. Enter the project directory
cd royale-vip-casino

# 3. Open index.html directly
# On macOS:
open index.html
# On Linux:
xdg-open index.html
# On Windows:
start index.html
```

Or run a lightweight local static server:
```bash
# Using Python
python3 -m http.server 8000

# Or using Node.js / npx
npx serve .
```

---

## 🌐 How to Publish on GitHub Pages

Because this project is built as a self-contained static application with `index.html` at the root, you can host it publicly on GitHub Pages in under a minute:

### 1. Initialize Git & Push to GitHub
```bash
git init
git add .
git commit -m "Initial commit: Royale VIP Casino Studio"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/royale-vip-casino.git
git push -u origin main
```

### 2. Enable GitHub Pages
1. Go to your repository on GitHub.
2. Click on **Settings** (top navigation tab).
3. Under the *Code and automation* section on the left sidebar, click **Pages**.
4. Under **Build and deployment** > **Source**, choose **Deploy from a branch**.
5. Set the branch to `main` and folder to `/(root)`, then click **Save**.
6. Wait 30–60 seconds, and GitHub will provide your live URL:
   `https://YOUR_USERNAME.github.io/royale-vip-casino/`

---

## 🗺️ Roadmap

* [x] Grand Salon Game Selection Menu
* [x] Baccarat Punto Banco with Macau Bead Plate Roadmap
* [x] 8-Deck Shoe & Penetration Tracking
* [x] REBET and automated chip resets
* [x] **Blackjack VIP**: Vegas Strip rules (Split, Double Down, Insurance, Dealer stands on 17)
* [ ] **Dragon Tiger**: Fast-paced single-card showdown table
* [ ] Big Road, Big Eye Boy, Small Road, and Cockroach Pig roadmaps

---

## 📄 License

This project is licensed under the [MIT License](LICENSE) - feel free to modify, expand, and use it in your own projects.
