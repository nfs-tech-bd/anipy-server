# 🎥 Anipy Server

> **Watch and download anime ad-free** — powered by AnimePahe scrapper API with FastAPI backend.

---

## 🚀 Overview
Anipy Server is a modern, lightweight, and high-performance server that lets you **scrape, watch, and download anime** directly from AnimePahe without ads. Built using **Python FastAPI**, it provides a clean REST API for anime data, streaming links, and downloads.

---

## ✨ Features
- 🔥 **Ad-free anime streaming & download links**
- ⚡ **Fast & asynchronous API** with FastAPI + Uvicorn
- 🔎 **Anime search endpoint** powered by AnimePahe scraping
- 📂 Fetch anime episodes and direct download links
- 🌐 Easy to deploy on VPS or cloud servers
- 🛠️ Open-source and customizable frontend


---

## ⚙️ Installation
```bash
pip install anipy-server
```
then you can run it just by entering "anipy"
Server will start on:
```
http://YOUR-SERVER-IP:8000 or localhost:8000
```

---

## 🔥 API Endpoints
| Method | Endpoint                  | Description                          |
|--------|--------------------------|--------------------------------------|
| GET    | `/`                      | Welcome message                     |
| GET    | `/anime/search?q=naruto` | Search anime from AnimePahe          |
| GET    | `/anime/{id}`            | Get anime details + episodes         |
| GET    | `/anime/{id}/{ep}`       | Get streaming and download links     |

---


## 🛡️ License
This project is licensed under the **MIT License** – free to use, modify, and distribute.

---

## 💡 Contribution
Pull requests and feature suggestions are welcome! Feel free to fork the repo and submit improvements.

---

## ⭐ Support
If you find this project useful, consider giving it a **⭐ star on GitHub** to support future development.
