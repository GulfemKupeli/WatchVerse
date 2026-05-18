# 🎬 WatchVerse — Social Movie & Series Tracker

> *Track what you watch. Share what you love.*

![Status](https://img.shields.io/badge/status-in_development-yellow?style=flat-square)
![Platform](https://img.shields.io/badge/platform-iOS_%7C_Android-black?style=flat-square)
![Team](https://img.shields.io/badge/team-2_people-blue?style=flat-square)

---

## 📌 Problem

Keeping track of movies and series across dozens of streaming platforms is messy. Existing apps like Letterboxd are web-first and lack a native mobile social experience built around real-time activity.

## 💡 Solution

A mobile-first movie and series tracker where you can log what you've watched, rate it, and follow friends — seeing their activity in a social feed in real time.

---

## 📸 Screenshots

> *Coming soon — app in final development phase*

---

## ⚙️ Architecture

```
┌──────────────────────────────────────────┐
│            Flutter App                   │
│                                          │
│  ┌───────────┐  ┌────────┐  ┌─────────┐ │
│  │ Watchlist │  │ Ratings│  │  Social │ │
│  │  & Log    │  │        │  │  Feed   │ │
│  └─────┬─────┘  └───┬────┘  └────┬────┘ │
└────────┼────────────┼────────────┼───────┘
         │            │            │
         ▼            ▼            ▼
┌──────────────────────────────────────────┐
│               Firebase                   │
│    Auth · Firestore · Realtime DB        │
└────────────────────┬─────────────────────┘
                     │
                     ▼
┌──────────────────────────────────────────┐
│             TMDB API                     │
│   Movie & series metadata, posters       │
└──────────────────────────────────────────┘
```

## 🛠 Tech Stack

| Layer | Technology |
|---|---|
| Mobile | Flutter (Dart) |
| State Management | Provider / Bloc |
| Backend | Firebase (Auth, Firestore, Realtime DB) |
| Content Data | TMDB API |
| Distribution | App Store · Google Play |

---

## ✨ Key Features

- **Watchlist Management** — Add movies and series to watch, watching, or watched lists
- **Rating & Reviews** — Score and log personal notes for each title
- **Social Feed** — Follow friends, see their activity and ratings in real time
- **Profile Page** — Stats, watch history, and favorite genres at a glance
- **Search & Discover** — Browse and search millions of titles via TMDB

---

## 👥 Team

Built by a 2-person team.

| Member | Profile |
| :--- | :--- |
| **Gülfem Küpeli** | [@GulfemKupeli](https://github.com/GulfemKupeli) |
| **Hasan Hazırbulan** | [@hasanhazirbulan](https://github.com/hasanhazirbulan) |

---

## 🚀 Availability

Planned release on **App Store** and **Google Play**.
