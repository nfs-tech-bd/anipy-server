<p align="center">
  <img src="https://raw.githubusercontent.com/nfs-tech-bd/anipy-server/refs/heads/main/Screenshot%202025-07-29%20114255.png" width="800" height="600" alt="Anipy Server Screenshot">
</p>

<h1 align="center">🎥 Anipy Server</h1>
<p align="center">
  <strong>Ad-free anime streaming & downloads, powered by <a href="https://animepahe.com/">AnimePahe</a> and FavtAPI</strong><br>
  <a href="https://anipy.fun">🌐 Visit Live Site</a>
</p>

---

## 🚀 What is Anipy Server?
**Anipy Server** is your gateway to anime without ads. Enjoy ultra-fast streaming and direct downloads from AnimePahe — all through a blazing FastAPI backend. It’s modern, lightweight, and open-source, so you can deploy it anywhere and tweak it to your liking!

---

## ✨ Features

- 🎬 **Stream & Download Anime — 100% Ad-Free**
- 🏎️ **Ultra-fast & Async API** (FastAPI + Uvicorn)
- 🔍 **Powerful Search** (AnimePahe scrapper)
- 📥 **Direct Download Links** for all episodes
- ☁️ **Easy Deployment** (VPS, cloud, or locally)
- 🛠️ **Customizable & Open Source Frontend**
- 🚦 **MIT Licensed** — free for everyone!

---

## ⚡ Quick Start

### 1️⃣ Install
```bash
pip install anipy-server
```

### 2️⃣ Run
```bash
anipy
```

Your server starts at:
```
http://YOUR-SERVER-IP:8000 or http://localhost:8000
```

---

## 🔥 API Endpoints

| Method | Endpoint                        | Description                       |
|--------|---------------------------------|-----------------------------------|
| GET    | `/`                             | Welcome message                   |
| GET    | `/anime/search?q=naruto`        | Search anime by keyword           |
| GET    | `/anime/{id}`                   | Get anime details + episodes      |
| GET    | `/anime/{id}/{ep}`              | Get streaming & download links    |

---

## 💡 Contribute

We 💜 new ideas! Fork, hack, and submit PRs — or just open an issue to suggest a feature. Join us to build something awesome together.

---

## ⭐ Support & Spread the Word!

Loved Anipy Server? Give us a **⭐ Star** on GitHub, share with friends, and help us grow!  
Questions or feedback? [Open an Issue](https://github.com/nfs-tech-bd/anipy-server/issues) — we respond fast!

---

## 🛡️ License

Licensed under the [MIT License](LICENSE) — use, modify, and share freely.

---

<p align="center">
  <sub>
    Made with ❤️ by <a href="https://github.com/nfs-tech-bd">nfs-tech-bd</a> · <a href="https://anipy.fun">anipy.fun</a>
  </sub>
</p>
