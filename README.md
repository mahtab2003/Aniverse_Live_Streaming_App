<h1 align="center">🔥 Aniverse</h1>
<p align="center">
  <b>Full Stack Anime Live Streaming App</b> <br/>
  Built with Expo • React Native • MERN • WebSockets
</p>

<p align="center">
  <img src="https://img.shields.io/badge/platform-mobile-blue?style=flat&logo=react" />
  <img src="https://img.shields.io/badge/frontend-expo-green?style=flat&logo=expo" />
  <img src="https://img.shields.io/badge/realtime-websockets-purple?style=flat" />
  <img src="https://img.shields.io/badge/auth-google_oauth2-red?style=flat&logo=google" />
  <img src="https://img.shields.io/badge/notifications-expo-yellow?style=flat&logo=expo" />
</p>

## ✨ Overview

**Aniverse** is a full-featured anime streaming app built with **React Native + Expo**, backed by a **Node.js/MongoDB** server. It supports **HLS video playback**, **realtime reactions**, **Google Sign-In**, and **push notifications**, offering a smooth, interactive viewing experience for anime lovers.

## 🚀 Key Features

- 🎥 **HLS Video Streaming** with `react-native-video`
- 💬 **Live Comments & Reactions** using WebSockets
- 🔔 **Push Notifications** via Expo
- 🔐 **Google Sign-In** (OAuth2)
- 🌀 **Smooth Animations & Transitions**
- 🌙 **Anime-themed UI**


## 🛠 Tech Stack

| Layer        | Stack                                 |
|--------------|----------------------------------------|
| Frontend     | React Native (Expo)                    |
| Backend      | Node.js + Express                      |
| Database     | MongoDB (via Mongoose)                 |
| Video Player | `react-native-video` (HLS support)     |
| Realtime     | WebSocket (native / Socket.IO)         |
| Auth         | Google OAuth2 via Firebase             |
| Notifications| Expo Push Notifications                |
| Animations   | Reanimated 2 / Moti / Lottie           |

---

## 📦 Getting Started

### 1. Clone & Install

```bash
git clone https://github.com/mahtab2003/aniverse.git
cd aniverse
npm install
````

### 2. Start the Expo Project

```bash
npx expo start
```

> Scan the QR code using Expo Go on your mobile.


## 🧠 Backend Setup

```bash
cd backend
npm install
node server.js
```

Make sure your `.env` file includes:

```env
MONGODB_URI=your_mongodb_uri
GOOGLE_CLIENT_ID=your_firebase_web_client_id
```


## 🔐 Google Auth Setup

1. Create a Firebase project.
2. Enable **Google Sign-In** in Authentication.
3. Add your Web Client ID in Expo’s `authSession` config.


## 🔔 Push Notifications

* Register device using `ExpoPushToken`.
* Send notifications from your backend using Expo API.
* Or use [Expo Push Tool](https://expo.dev/notifications) to test.


## 📸 Screenshots & Demo

> *(Coming soon)*


## 🧑‍🏫 Learn Like a Senior Dev

This app is crafted with scalable practices and includes:

* Modular file structure
* Clean UI/UX
* Full-stack realtime integration
* Secure OAuth login
* Real-world notification system

Perfect for devs aiming to level up to **senior** mobile dev status 👨‍💻⚔️


<p align="center">
  🧡 <strong>Built with love for anime & code by Ritik Parsad, Forked by Mehtab (Leo)</strong><br/>
  <em>“Stream. React. Connect.”</em>
</p>
```
