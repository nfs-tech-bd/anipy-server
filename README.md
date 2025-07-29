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
- 🛠️ Open-source and customizable backend

---

## 📂 Project Structure
```
anipy-server/
│── main.py           # FastAPI entry point
│── app/
│   ├── routes.py     # API routes
│   ├── scraper.py    # AnimePahe scrapper module
│── requirements.txt  # Dependencies
│── README.md         # Project documentation
│── LICENSE           # Open-source license
```

---

## ⚙️ Installation
### 1️⃣ Clone the Repository
```bash
git clone https://github.com/YOUR-USERNAME/anipy-server.git
cd anipy-server
```
### 2️⃣ Setup Virtual Environment
```bash
python3 -m venv venv
source venv/bin/activate   # Linux / macOS
venv\Scripts\activate      # Windows
```
### 3️⃣ Install Requirements
```bash
pip install -r requirements.txt
```
### 4️⃣ Run Server
```bash
uvicorn main:app --host 0.0.0.0 --port 8000
```
Server will start on:
```
http://YOUR-SERVER-IP:8000
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

## 🌐 Deployment
Use `screen` to keep the server running:
```bash
screen -S anipy
uvicorn main:app --host 0.0.0.0 --port 8000
```
Detach session: **CTRL+A, D**  
Reattach session:
```bash
screen -r anipy
```

---

## 🛡️ License
This project is licensed under the **MIT License** – free to use, modify, and distribute.

---

## 💡 Contribution
Pull requests and feature suggestions are welcome! Feel free to fork the repo and submit improvements.

---

## ⭐ Support
If you find this project useful, consider giving it a **⭐ star on GitHub** to support future development.
