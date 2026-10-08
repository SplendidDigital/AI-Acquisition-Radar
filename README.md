## Flipnzee AI Acquisition Radar

**Flipnzee AI Acquisition Radar** is a WordPress plugin that discovers and ranks publicly available online businesses and websites for acquisition. It combines public marketplace and community sources with Google Gemini AI to help identify acquisition opportunities that match configurable criteria.

### Key Features

- 🔎 **Multi-source acquisition discovery**
  - Flippa
  - SideProjectors
  - Reddit
- 🤖 **AI-powered opportunity ranking** using Gemini
- 🌐 **WordPress-focused acquisition discovery**
- 💰 Configurable maximum asking price
- 📈 Optional minimum monthly revenue filter
- 🎯 Configurable preferred niches
- 🌱 **Strict animal-product exclusion filter**
  - Excludes businesses materially involving meat, dairy, eggs, leather, fur, wool, silk, feathers/down and other animal-derived products or exploitation.
- 🚫 Option to exclude uncertain opportunities
- ⚖️ **Balanced source selection** so Flippa's much larger marketplace does not overwhelm SideProjectors and Reddit
- 🔗 Separate direct listing and Flippa referral links
- 💾 Persistent acquisition feed stored in WordPress
- ⏱️ **Automatic 24-hour feed refresh**
- 🖱️ Manual refresh from the WordPress admin
- 🔐 Gemini API key stored in WordPress settings
- ⚙️ Configurable Gemini model
- 📊 Configurable number of opportunities displayed
- 🚀 Frontend shortcode support
- 🧩 No Gemini requests are made when visitors simply load the frontend page

### How It Works

The plugin follows this workflow:

**Public sources → Candidate collection → Price/WordPress filtering → Ethical filtering → Balanced source selection → Gemini analysis → Ranked opportunities → Persistent WordPress feed**

The plugin does **not** require Gemini to browse the internet. Public listing information is collected first, filtered locally, and then supplied to Gemini for analysis and ranking.

### Sources

The plugin can discover opportunities from:

- **Flippa** — broad marketplace discovery
- **SideProjectors** — side-project and website marketplace
- **Reddit** — publicly available acquisition and business-sale discussions

The discovery process intentionally gives each enabled source an opportunity to contribute candidates rather than allowing the largest marketplace to dominate the results.

### Frontend

Use the shortcode:

```text
[flipnzee_ai_acquisition_feed]
```

The frontend displays the curated acquisition opportunities without triggering a new Gemini request. Visitors therefore do not consume your Gemini API quota simply by viewing the page.

### Gemini

The plugin supports configurable Gemini models, with **`gemini-3.5-flash-lite`** as the default model.

The API key is preserved during plugin upgrades when the API-key field is left blank.

### Automation

The acquisition feed can automatically refresh approximately every **24 hours** using WordPress Cron, while retaining the previous feed if a refresh fails.

### Intended Use

Flipnzee AI Acquisition Radar is designed for:

- Website buyers
- Digital entrepreneurs
- Website investors
- SEO professionals
- WordPress developers
- Affiliate marketers
- Digital asset investors
- Entrepreneurs looking for small online businesses to acquire

**Important:** The plugin provides research and ranking assistance. Users should independently verify financial information, ownership, traffic, revenue, intellectual property, liabilities and other claims before acquiring any business.
