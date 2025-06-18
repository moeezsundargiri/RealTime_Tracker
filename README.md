# 📍 RealTime Device Tracker

A real-time device location tracking application built using **Node.js**, **Express.js**, **Socket.io**, and **Leaflet.js**. This app visualizes device movements on an interactive map in real-time using WebSocket technology.

---

## 🚀 Features

- 📡 Real-time device location updates using **Socket.io**
- 🗺️ Interactive maps with **Leaflet.js CDN**
- 🖥️ Backend API built with **Node.js + Express.js**
- 🔄 Live marker movement without page refresh
- 💡 Lightweight and responsive design

---

## 🛠️ Tech Stack

- **Backend**: Node.js, Express.js
- **Real-time Communication**: Socket.io
- **Frontend Map**: Leaflet.js (via CDN)
- **Data Format**: JSON (for transmitting location data)

---

## 📂 Project Structure

```bash
real-time-device-tracker/
│
├── public/
│   └── index.html          # Frontend UI with Leaflet.js map
│
├── server.js               # Express + Socket.io backend
├── package.json
└── README.md
