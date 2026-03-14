# 🌿 Clean Madurai | சுத்தமான மதுரை

> A smart civic waste management application to transform Madurai into one of the cleanest cities in Tamil Nadu.

![Clean Madurai Banner](https://img.shields.io/badge/Clean_Madurai-Smart_Civic_App-22c55e?style=for-the-badge&logo=leaflet)
![HTML](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![License](https://img.shields.io/badge/License-MIT-green.svg)

## 🚀 Live Demo

👉 [https://YOUR_USERNAME.github.io/clean-madurai](https://YOUR_USERNAME.github.io/clean-madurai)

---

## 📋 Overview

**Clean Madurai** is a full-featured smart civic application connecting **Citizens**, **Municipal Officials**, and **Garbage Collection Teams** to improve waste management across all 72 wards of Madurai Municipal Corporation.

The app features:
- 🌐 **Bilingual support** — English & தமிழ்
- 👤 **3 user roles** — Citizen, Municipal Official, Sanitation Worker
- 📱 **Responsive design** — works on mobile, tablet & desktop

---

## ✨ Features

| Feature | Description |
|---|---|
| 🏠 **Dashboard** | Live activity feed, personal stats, weekly chart |
| 📸 **Garbage Reporting** | Photo upload + AI waste detection simulation |
| 🗺 **Waste Hotspot Map** | Live map with 🔴🟡🟢 status pins + truck markers |
| 🚛 **Truck Tracker** | Real-time GPS route tracking with ETA display |
| 📊 **Ward Rankings** | All 72 wards scored by cleanliness index |
| 📋 **Complaints Table** | Full complaint management with status tracking |
| ♻️ **Segregation Guide** | Wet / Dry / Plastic / E-Waste with Tamil labels |
| 🏆 **Rewards & Leaderboard** | Points, badges, and city-wide leaderboard |
| ⚙️ **Admin Panel** | Task assignment, analytics, ward dispatch |

---

## 🛠 Tech Stack

| Layer | Technology |
|---|---|
| Frontend | Vanilla HTML5, CSS3, JavaScript (ES6+) |
| Fonts | Plus Jakarta Sans, Noto Sans Tamil (Google Fonts) |
| Maps | SVG-based map simulation (production: Google Maps API) |
| AI Detection | Simulated (production: TensorFlow.js / OpenCV) |
| Hosting | GitHub Pages / Netlify |

---

## 📁 Project Structure

```
clean-madurai/
├── index.html              # Main app shell
├── css/
│   ├── tokens.css          # Design system variables
│   ├── layout.css          # App shell, sidebar, topbar, grid
│   ├── components.css      # Buttons, cards, badges, forms, map, table
│   ├── screens.css         # Screen-level overrides
│   └── animations.css      # Keyframes & transitions
├── js/
│   ├── data.js             # All static app data
│   ├── utils.js            # Shared helper functions (toast, modal, clock)
│   ├── lang.js             # EN / Tamil language switcher
│   ├── router.js           # Client-side screen router
│   ├── app.js              # App bootstrap & role switcher
│   └── screens/
│       ├── dashboard.js                    # Dashboard screen
│       ├── report.js                       # Report garbage screen
│       ├── map-trucks-wards-complaints.js  # Map, trucks, wards, complaints
│       └── segregation-rewards-admin.js    # Segregation, rewards, admin
└── README.md
```

---

## 🚀 Getting Started

### Option 1 — Open directly
Simply open `index.html` in any modern browser. No build step required.

### Option 2 — Local server (recommended)
```bash
# Using Python
python -m http.server 8000

# Using Node.js (npx)
npx serve .

# Then open: http://localhost:8000
```

### Option 3 — Deploy to GitHub Pages
```bash
git init
git add .
git commit -m "Initial commit — Clean Madurai"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/clean-madurai.git
git push -u origin main
```
Then go to **Settings → Pages → Deploy from branch → main**.

---

## 🗺 Screens & Navigation

```
Dashboard  →  Report Garbage  →  Waste Map
    ↓               ↓               ↓
Ward Rankings   Complaints      Truck Tracker
    ↓               ↓               ↓
Segregation    Rewards         Admin Panel
```

---

## 🌐 Bilingual Support

Switch between **English** and **தமிழ்** using the toggle in the sidebar.
All nav labels, section headings, and form labels are bilingual.

---

## 👥 User Roles

| Role | Access |
|---|---|
| 👤 Citizen | Report, View Map, Rewards, Segregation Guide |
| 🏛 Municipal Official | All Citizen features + Admin Panel |
| 🚛 Sanitation Worker | View assigned tasks, Update truck status |

---

## 📈 Expected Impact

- ✅ Faster garbage reporting (citizen → municipality in seconds)
- ✅ AI-assisted waste classification for smart prioritization
- ✅ Real-time truck tracking for citizens and admins
- ✅ Gamification to increase citizen participation
- ✅ Ward-level accountability through public rankings
- ✅ Bilingual accessibility for all of Madurai's residents

---

## 🤝 Contributing

Pull requests are welcome! For major changes, please open an issue first.

1. Fork the repo
2. Create your feature branch: `git checkout -b feature/my-feature`
3. Commit your changes: `git commit -m 'Add my feature'`
4. Push to the branch: `git push origin feature/my-feature`
5. Open a pull request

---

## 📄 License

MIT License — feel free to use, modify, and distribute.

---

## 👨‍💻 Built by

**Ranjan Kumar** — ECE Student, Madurai  
[Instagram](https://instagram.com/ranjan__kumar007) · [LinkedIn](#)

> *"சுத்தமான மதுரை — Clean Madurai!"*
