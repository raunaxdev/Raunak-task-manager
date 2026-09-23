# ⚡ Raunak Study World — Mission Control Core

[![GitHub Pages Deployment](https://img.shields.io/badge/GitHub%20Pages-Live%20Demo-06b6d4?style=for-the-badge&logo=github)](https://raunaxdev.github.io/raunak-s-task-manager/)
[![PWA Ready](https://img.shields.io/badge/PWA-Installable-6366f1?style=for-the-badge&logo=pwa)](https://raunaxdev.github.io/raunak-s-task-manager/)
[![Tech Stack](https://img.shields.io/badge/Tech%20Stack-HTML5%20%7C%20CSS3%20%7C%20JS%20%7C%20Supabase-ec4899?style=for-the-badge)](https://raunaxdev.github.io/raunak-s-task-manager/)

---

## 📌 Executive Summary
**Raunak Study World** is a high-tech, mobile-responsive **Mission Control Task & Study Management Engine** built with a Cyberpunk/JARVIS-inspired Glassmorphism user interface[cite: 1, 2, 4]. Designed for modern students, it combines **Voice Commands**, **AI Study Directives**, **Offline LocalStorage + Supabase Cloud Persistence**, and a **Fullscreen Standby Study Clock with Ambient Backgrounds**[cite: 1, 2, 3].

---

## 🔥 Key Features

* **🎙️ Voice Command System (JARVIS Core):**
  * Wake-word detection (`"JARVIS"`, `"System"`, `"Suno"`) with dual Hinglish & English voice synthesis (`en-IN` / `hi-IN`)[cite: 1, 2, 3].
  * Voice routing for external portals (Google, YouTube, ChatGPT, GitHub) and hands-free task creation[cite: 2, 3].
* **📝 Dynamic Mission Control (Task Manager):**
  * Categorized task deployment (YouTube Class, Handwritten Scans, PDF Documents, Self Study, Mock Quizzes)[cite: 1, 3, 4].
  * Real-time sync using local storage with Supabase cloud backup[cite: 1, 3].
* **⏳ Standby Focus Clock (Pomodoro Mode):**
  * Fullscreen high-focus timer with video backgrounds (Galaxy / Rain)[cite: 1, 3, 4].
  * Built-in ambient sound player (Lofi beats, Rain sound, White Noise) for distraction-free study sessions[cite: 1, 3, 4].
* **📱 Progressive Web App (PWA):**
  * Offline availability, `manifest.json` installation support, and persistent system telemetry alerts[cite: 1, 3, 4].
* **📊 Telemetry & Wellbeing:**
  * Real-time session time tracking and instant telemetry performance audits[cite: 3, 4].

---

## 🛠️ Tech Stack & Architecture

| Layer | Technology Used |
| :--- | :--- |
| **Frontend UI** | Native HTML5, Modern CSS3 (CSS Variables, Flexbox/Grid, Glassmorphism)[cite: 1, 4] |
| **Logic & Voice** | Vanilla JavaScript (ES6+), Web Speech API, Web Audio API[cite: 1, 3] |
| **Database** | Supabase REST API (Cloud Storage) + LocalStorage (Offline Cache)[cite: 1, 3] |
| **PWA & Hosting** | Service Worker, Manifest Spec, GitHub Pages Deployment[cite: 1, 3, 4] |

---

## 🚀 Live Demo & Installation

* **Web Portal:** [Raunak Study World Mission Control](https://raunaxdev.github.io/raunak-s-task-manager/)
* **PWA App Installation:**
  1. Open the live link in Mobile Chrome or Edge[cite: 4].
  2. Tap the browser menu (**⋮**) and select **"Add to Home screen"** or **"Install App"**[cite: 4].
  3. Launch directly from your home screen as a native application[cite: 1, 4].

---

## 💻 Local Setup

```bash
# 1. Clone the repository
git clone [https://github.com/raunaxdev/raunak-s-task-manager.git](https://github.com/raunaxdev/raunak-s-task-manager.git)

# 2. Navigate to project folder
cd raunak-s-task-manager

# 3. Open index.html in any browser or launch Live Server
