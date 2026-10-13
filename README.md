<div align="center">

<img src="./icons/durga-maa-logo.png" alt="Durga Maa — Durga Puja Guide" width="110" />

# 🪔 Durga Puja Pandal Hopping Guide 2026

**Explore Kolkata's Durga Puja pandals, discover local food, and plan your route—all in one interactive guide.**

[![Live Website](https://img.shields.io/badge/Live_Website-Visit_Guide-ff8400?style=for-the-badge)](https://mehexgh.github.io/Durga-Puja-Guide-Website-2026/)
[![GitHub Pages](https://img.shields.io/badge/Hosted_on-GitHub_Pages-222?style=for-the-badge&logo=github)](https://github.com/MeheXGH/Durga-Puja-Guide-Website-2026)
[![PWA](https://img.shields.io/badge/Progressive_Web_App-PWA-2563eb?style=for-the-badge)](https://mehexgh.github.io/Durga-Puja-Guide-Website-2026/)

**[🌐 Open Live Guide](https://mehexgh.github.io/Durga-Puja-Guide-Website-2026/)** · **[📂 Source Code](https://github.com/MeheXGH/Durga-Puja-Guide-Website-2026)**

</div>

---

## 📖 Overview

**Durga Puja Pandal Hopping Guide 2026** is a mobile-friendly, map-based web application designed to help visitors explore **18 curated Durga Puja pandals in South Kolkata**. It combines pandal discovery, a visit checklist, local food recommendations, and practical transport information in one place.

The guide follows a suggested west-to-east pandal-hopping corridor and includes rail, metro, and auto-stand reference points to help visitors orient themselves during the festival.

## ✨ Features

- **🗺️ Interactive map:** Explore pandals, food hubs, train and metro stations, and auto stands with interactive markers.
- **🏮 18 curated pandals:** Browse the South Kolkata pandal-hopping checklist and suggested route.
- **✅ Visited tracker:** Mark pandals as visited and monitor your progress. Progress is saved locally in your browser.
- **🔎 Search and filters:** Find places and filter the map by pandals, food hubs, transit stops, and auto stands.
- **🍲 Food discoveries:** Find well-known food spots along the pandal-hopping corridor.
- **🚇 Transit guide:** See practical train, metro, and auto guidance, including a suggested arrival and return route.
- **📍 Location and directions:** Use supported browser location features and Google Maps links to help navigate.
- **➕ Custom spots:** Add personal spots in the guide.
- **📱 Responsive design:** Designed for desktop and mobile browsers.
- **📲 Installable PWA:** Includes a web app manifest, icons, and a service worker for app-shell caching.

## 🚀 Live Demo

Visit the published guide:

**https://mehexgh.github.io/Durga-Puja-Guide-Website-2026/**

No account is required to browse the guide.

## 🛠️ Technology Stack

| Technology | Purpose |
| --- | --- |
| HTML5 | Application structure and content |
| CSS3 | Styling and responsive layout |
| JavaScript | Map interactions, filters, checklist, and app behavior |
| Leaflet.js | Interactive map rendering |
| Browser localStorage | Saving checklist progress locally |
| Web App Manifest | PWA installation metadata |
| Service Worker | App-shell caching and offline fallback for local files |
| GitHub Pages | Static website hosting |

## 📁 Project Structure

```text
Durga-Puja-Guide-Website-2026/
├── index.html              # Main application: markup, styles, and scripts
├── manifest.webmanifest    # PWA metadata and icon definitions
├── sw.js                   # Service worker and app-shell caching
├── icons/                  # Logo, favicons, and installable app icons
│   ├── durga-maa-logo.png
│   ├── favicon.ico
│   ├── favicon-16.png
│   ├── favicon-32.png
│   ├── apple-touch-icon.png
│   ├── icon-192.png
│   ├── icon-512.png
│   └── icon-maskable-512.png
└── README.md
```

## 💻 Run Locally

You don't need a framework build step or package installation to get started.

1. Clone the repository:

   ```bash
   git clone https://github.com/MeheXGH/Durga-Puja-Guide-Website-2026.git
   ```

2. Enter the project directory:

   ```bash
   cd Durga-Puja-Guide-Website-2026
   ```

3. Open the folder in VS Code:

   ```bash
   code .
   ```

4. Serve the site from a local HTTP server (recommended for testing the PWA):

   ```bash
   python -m http.server 5500
   ```

5. Visit **http://localhost:5500/** in your browser.

> Opening `index.html` directly may display the page, but service workers and some browser features should be tested on `localhost` or HTTPS.

## 📲 Install as an App

The project includes PWA metadata and install icons.

- **Android:** Open the live website in a compatible browser and choose **Install app** or **Add to Home screen**, if offered.
- **iPhone/iPad:** Open the website in Safari, tap **Share**, then select **Add to Home Screen**.
- **Desktop:** Compatible browsers may offer an install option in the address bar or browser menu.

Installation options vary by browser and device.

### Offline Support

The service worker caches the local application shell and icons. **Map tiles and external CDN resources are not guaranteed to work offline**, so an internet connection may still be needed for the interactive map and external navigation.

## 🌍 Deployment

This site is deployed as a static project using **GitHub Pages**.

To publish updates:

```bash
git add .
git commit -m "Update Durga Puja guide"
git push
```

GitHub Pages will publish changes from the branch and directory configured under **Repository → Settings → Pages**. Deployment may take a short time.

If you don't see an updated version immediately, refresh the page and consider whether the service worker is serving cached content.

## 🧭 Travel and Map Disclaimer

This guide is intended for **festival exploration and general orientation**, not as an official navigation or transit service.

- Transit route lines are **schematic overlays**, not surveyed railway or metro track geometry.
- Verify current metro and train operations, station entrances, and local transport availability before travelling.
- Festival traffic, diversions, road closures, queue times, and pandal access arrangements can change.
- Use live navigation and official transport updates when making travel decisions.

## 🤝 Contributing

Suggestions, bug reports, and improvements are welcome. To contribute, open an [issue](https://github.com/MeheXGH/Durga-Puja-Guide-Website-2026/issues) or submit a pull request.

## 👨‍💻 Maintainer

Developed and maintained by **[MeheXGH](https://github.com/MeheXGH)**.

---

<div align="center">

**Made for Durga Puja 2026 in Kolkata.** 🪔

[Explore the Guide](https://mehexgh.github.io/Durga-Puja-Guide-Website-2026/) · [Back to Top](#-durga-puja-pandal-hopping-guide-2026)

</div>
