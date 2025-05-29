# CampusCrowd: Real-Time UBC Study Space Tracker

**CampusCrowd** is a student-built web app designed to help UBC students find available study spaces across campus in real time. It shows live or crowdsourced updates on how full different libraries, lounges, and study rooms are—saving time and reducing the stress of searching for a quiet spot, especially during exams.

---

## 🚀 Overview

With over 60,000 students on campus, UBC currently lacks a centralized, real-time system to monitor study space availability. CampusCrowd fills this gap by:

- Displaying live occupancy levels for study spaces
- Allowing students to check in/out via Google login
- Aggregating data for real-time insights

---

## 🔑 Key Features (MVP)

- **Live Occupancy Status:** Color-coded crowd levels (🟢 Empty, 🟡 Moderate, 🔴 Full)
- **Crowdsourced Check-Ins:** Simple check-in/check-out system with Google Sign-In
- **Location Filters:** Filter by buildings (Koerner, Irving, Forestry Lounge, etc.)
- **Live Auto-Refresh:** Updates every few minutes to reflect recent changes

---

## 🧰 Tech Stack (Planned)

- **Frontend:** React + Tailwind CSS
- **Backend:** Firebase Functions or Node.js
- **Database:** Firebase Firestore or Supabase
- **Authentication:** Firebase Auth (Google Login)
- **Hosting:** Vercel or Netlify
- **Optional Integration:** UBC Library API for scraping live data (if available)

---

## 🗺️ How It Works

1. User opens the app and views a list/map of study spaces.
2. Each space shows current status (Empty/Moderate/Full).
3. Students check in/out to contribute real-time data.
4. Occupancy data updates automatically and gets aggregated for display.

---

## 📆 MVP Timeline

| Week | Goal                                               |
|------|----------------------------------------------------|
| 1    | Setup project, Firebase config, basic UI scaffold  |
| 2    | Implement location cards & check-in logic          |
| 3    | Store and display real-time occupancy data         |
| 4    | UI polish, testing, deployment                     |
| 5+   | Expand locations, integrate scraping, community outreach |

---

## 💡 Future Enhancements

- **Predictive Analytics** – Forecast peak usage times from trends
- **Heat Maps** – Visual intensity map overlay
- **Study Tags** – Quiet, Group, Outdoor filters
- **Notifications** – Alerts when favorite spaces open up

---

## 🎨 UI Development

While backend functionality is being developed, **Jack** is leading frontend UI design in **Figma**. Once the designs are complete, we’ll integrate styling and finalize the user experience.

---

## 👥 Contributors

- Yogya & Billy (Backend & Firebase Setup)
- Jack (UI/UX Design - Figma)

---
