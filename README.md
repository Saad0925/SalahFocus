# SalahFocus 🕌 — Modern Android Prayer & Focus Application

Salah first. Distractions later. Remember Allah throughout the day.

A modern, functional, pure monochrome Android application designed to help Muslims pray all five daily prayers on time, overcome screen addiction (Ghaflah), and maintain spiritual mindfulness.

---

## Features

- **Pure Monochrome Theme**: Absolutely pure black (`#000000`) and white (`#FFFFFF`) palette for maximum serenity and anti-distraction.
- **5 Exact Canonical Salah Times**:
  - 🌅 Fajr — 5:30 AM
  - ☀️ Zuhr — 1:00 PM
  - 🌤️ Asr — 5:00 PM
  - 🌇 Maghrib — 6:20 PM
  - 🌙 Isha — 8:15 PM
  - Customizable in Settings with 1-tap reset to defaults.
- **Audible Adhan & Priority Alarm**:
  - Built-in Web Audio API synthesizer generates harmonic Adhan chimes (works 100% offline).
  - Fullscreen priority alarm and app shielding.
- **Distracting-App Interruption & Android Shielding**:
  - Monitors distracting applications (Instagram, TikTok, YouTube, Reddit, Mobile Games).
  - Displays full-screen interruption during prayer times.
  - Safe Emergency Exit: 112 / 911 / Essential Contacts are never blocked.
- **Customizable Interruption Reminders**:
  - Choose between authentic Quranic verses (with Arabic script & translations), Prophetic Hadiths, motivational principles, or your own custom reminder.
- **Salah Mat Photo Verification**:
  - Camera & Gallery accountability verification.
  - Local computer vision analysis (aspect ratio, bilateral symmetry, rug pattern detection).
  - Clear accountability disclaimer: *"Taking a photo does not prove worship; this is a motivational accountability tool."*
- **Ghaflah (غفلة) Daily Screen-Time Tracker**:
  - Measures device and app focus time.
  - Compares actual usage with onboarding estimate.
  - 7-day weekly history chart comparing screen time against prayers completed on time.
- **30-Minute Dhikr Reminders & 33-Count Dial**:
  - Automated prompts to recite Subhanallah, Alhamdulillah, Allahu Akbar, Astaghfirullah, or Salawat 33 times.
  - Dedicated tactile counter dial with sound, haptics (`navigator.vibrate`), undo, and reset.
- **Android APK & WebAPK Support**:
  - Instant 1-tap installation on Android phones via Google Chrome's native WebAPK engine.
  - Complete native Android Studio Kotlin/Compose project source blueprints included.

---

## Getting Started

### Prerequisites
- Node.js (v18 or higher)
- npm or bun

### Installation
```bash
# Install dependencies
npm install

# Start development server
npm run dev
```

Open `http://localhost:3000` in your browser.

### Building for Production
```bash
npm run build
```

---

## Installing on Android (WebAPK)
1. Open the app URL in **Google Chrome** on your Android device.
2. Tap the **3-dot menu (`⋮`)** in Chrome.
3. Tap **"Install app"** or **"Add to Home screen"**.
4. Android will automatically mint and install the native WebAPK into your phone's app drawer.
