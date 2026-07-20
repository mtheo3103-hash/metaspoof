# 🕵️‍♂️ MetaSpoof — EXIF Metadata Editor & GPS Spoofer

MetaSpoof is a fast, privacy-focused web tool designed to inspect, fake (spoof), or completely wipe EXIF metadata and GPS location tags from JPEG images.

The main advantage: Your files never leave your device. All processing is done locally inside your browser using client-side JavaScript.

---

## ✨ Features

* 🛡️ 100% Client-Side & Private: No server uploads. Complete privacy by design.
* 🧹 1-Click Complete Wipe: Instantly strip all EXIF, GPS, and camera metadata from your photos.
* 🗺️ Interactive GPS Spoofer: Pick any location on an interactive world map or use quick presets (e.g., Tokyo, New York, Paris).
* 📸 Camera & Device Faker: Override image manufacturer and model details (e.g., spoof as iPhone 15 Pro, Canon EOS R5, or a classic Nokia 3310).
* 📅 Date & Time Editor: Modify the timestamp of when the image was taken.
* ⚡ Zero Server Costs: Runs as a pure static web app — perfectly suited for free hosting on Render, Netlify, or GitHub Pages.

---

## 🛠️ Tech Stack

* HTML5 & Vanilla JavaScript
* Tailwind CSS (via CDN)
* Piexifjs (for client-side EXIF parsing and writing)
* Leaflet.js (for the dark-mode GPS selector map)

---

## 🚀 How to Run Locally

Since MetaSpoof is a pure client-side application, no build process or node environment is required:

1. Clone or download this repository.
2. Simply double-click index.html to open it in any web browser!
