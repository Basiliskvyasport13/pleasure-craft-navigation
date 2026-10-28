# Pleasure Craft Navigation

![Header](https://capsule-render.vercel.app/api?type=waving&color=0:004e92,100:00C9FF&height=220&section=header&text=Pleasure%20Craft%20Navigation&fontSize=55&fontColor=ffffff&animation=twinkling&fontAlignY=35&desc=Master%20The%20Waves%20With%20Precision%20And%20Confidence&descAlignY=55&descSize=20)

<div align="center">

![Version](https://img.shields.io/badge/version-3.1.0-00C9FF?style=for-the-badge&logo=git&logoColor=black)
![Downloads](https://img.shields.io/badge/downloads-96.9K-004e92?style=for-the-badge&logo=download&logoColor=white)
![License](https://img.shields.io/badge/license-MIT-FFD700?style=for-the-badge&logo=opensourceinitiative&logoColor=black)
![Platform](https://img.shields.io/badge/platform-ios%20%7C%20android%20%7C%20web-FF3366?style=for-the-badge&logo=apple&logoColor=white)

</div>

---

## ⛵ The Ultimate Companion For Boaters

Whether you are an experienced sailor navigating open waters or a weekend enthusiast enjoying a day on the lake, having reliable navigation tools is not just a luxury—it's a necessity. **Pleasure Craft Navigation** is a comprehensive, open-source maritime navigation application designed specifically for recreational boaters, yacht owners, and water sports lovers.

Traditional marine GPS systems are expensive, clunky, and often outdated. This repository provides a modern, mobile-first alternative that runs on your phone or tablet. It features high-resolution nautical charts, real-time depth tracking, route planning, and a suite of safety tools to ensure your time on the water is both safe and enjoyable.

Built with performance and offline-first architecture in mind, the app caches all necessary map tiles and data, meaning you can navigate confidently even in areas without cellular coverage. It is the perfect companion for coastal cruising, inland waterway navigation, and offshore adventures.

<img width="1672" height="941" alt="1a6a68f3-afe3-4d83-8dfe-d46751dc27ad" src="https://github.com/user-attachments/assets/5f495308-e574-4cbb-8bad-bd59c40d0f62" />


---

## ✨ Core Features

| Feature | Description |
|---------|-------------|
| 🗺️ **Nautical Charts** | High-resolution, up-to-date charts for coastal and inland waters |
| 📍 **Real-Time GPS** | Accurate positioning with heading, speed, and course tracking |
| ⚓ **Route Planning** | Create, save, and follow waypoints with automatic alerts |
| 🛡️ **Safety Tools** | Man overboard button, anchor alarm, and weather warnings |
| 📊 **Depth Sounder** | Connect to your boat's sonar for live depth readings |
| 🔌 **Offline Mode** | Download charts for offline use in remote areas |
| ☁️ **Cloud Sync** | Sync your routes and favorite spots across all your devices |
| 🎨 **Customizable Dashboard** | Personalize your screen with the data that matters to you |

---

## 🚀 Quick Setup

To run the navigation app locally for development or testing, you will need Node.js 18+ and a modern mobile emulator.

```bash
# Clone the repository
git clone https://github.com/your-username/pleasure-craft-navigation.git

# Navigate into the directory
cd pleasure-craft-navigation

# Install the required dependencies
npm install

# Start the development server
npm run dev
```

Once the server is running, open your browser and navigate to `http://localhost:3000`. You will be greeted by the interactive map interface. To test the GPS features, you can simulate a location by using the browser's developer tools or by connecting your mobile device via USB for live testing.

---

<div align="center">

### 🔗 Ready to set sail?

[![Get App](https://img.shields.io/badge/⛵_GET_APP-004e92?style=for-the-badge&logoColor=white)](https://share.google/qwFxmSFBg3XDG5tkN)

</div>

---

## 🧠 How The Navigation Engine Works

Building a marine navigation app is fundamentally different from building a car GPS app. The biggest challenge is accuracy. On water, there are no roads; you must rely entirely on precise coordinates, chart data, and environmental factors.

The core of the app is built on top of the **MapLibre GL** library, which is a powerful, open-source rendering engine for vector tiles. The chart data is sourced from the **OpenSeaMap** project, which is a free, community-driven initiative to map the world's oceans and inland waterways. This data includes depth markers, navigational beacons, buoys, and safe channels.

The GPS tracking uses the device's native geolocation API, but we apply a **Kalman Filter** to smooth the raw data. This is critical because GPS signals on water can be noisy, causing the boat icon to jump around on the map. The Kalman Filter predicts the boat's future position based on its current speed and heading, resulting in a smooth, accurate, and reliable tracking line.

---

<div align="center">

### ⚙️ Need a detailed configuration guide?

[![Setup Guide](https://img.shields.io/badge/📖_VIEW_SETUP_GUIDE-00C9FF?style=for-the-badge&logoColor=black)](https://share.google/qwFxmSFBg3XDG5tkN)

</div>

---

## 🛠️ Tech Stack

<div align="center">

![React Native](https://img.shields.io/badge/React_Native-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![MapLibre](https://img.shields.io/badge/MapLibre-396C9A?style=flat-square&logo=maplibre&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=flat-square&logo=typescript&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=flat-square&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

</div>

---

## 🤝 Community & Contributing

Boating is a community-driven passion, and we believe that navigation tools should be open and accessible to everyone. If you have suggestions for new features, found a bug, or want to contribute to the chart data, we welcome your contributions!

1. **Fork** the repository.
2. **Create** your feature branch (`git checkout -b feature/new-safety-tool`).
3. **Commit** your changes (`git commit -m 'Add new safety tool'`).
4. **Push** to the branch (`git push origin feature/new-safety-tool`).
5. **Open** a Pull Request.

Please read our `CONTRIBUTING.md` for detailed coding standards and testing requirements. We also have an active Discord server where you can share your sailing routes, ask for help with chart configuration, and discuss the latest trends in marine navigation.

---

## 📬 Contact & Support

- 💬 **Discussions:** Join the conversation in the GitHub Discussions tab.
- 🐛 **Issues:** Found a bug? Let us know via the Issues tracker.
- 📧 **Email:** Reach out directly at support@pleasure-navigation.dev.

---

<div align="center">

### ⭐ If this app helps you navigate, give it a star! ⭐

[![Star](https://img.shields.io/badge/⭐_STAR_THIS_REPO-FFD700?style=for-the-badge&logo=github&logoColor=black)](https://github.com/your-username/pleasure-craft-navigation)

---

### 🚀 Start your maritime adventure today

[![Get Started](https://img.shields.io/badge/🚀_GET_STARTED_GUIDE-FF3366?style=for-the-badge&logoColor=white)](https://share.google/qwFxmSFBg3XDG5tkN)

<sub>Crafted with precision and ❤️ by the Pleasure Craft Navigation community</sub>

![Footer](https://capsule-render.vercel.app/api?type=waving&color=0:00C9FF,100:004e92&height=120&section=footer)

</div>
