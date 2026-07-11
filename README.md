# 🌌 Intellects Club — Official Website
> The official digital ecosystem of the Intellects Club at SRM Institute of Science and Technology, Ramapuram.

<div align="center">
  
  [![Website Status](https://img.shields.io/website?down_message=offline&label=Live%20Website&up_message=online&url=https%3A%2F%2Fintellectsclub-srm.web.app)](https://intellectsclub-srm.web.app/)
  [![Tech Stack](https://img.shields.io/badge/Tech%20Stack-HTML%20%7C%20CSS%20%7C%20JS-purple.svg)](#-tech-stack)
  [![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
  
</div>

---

## 🌐 Live Application
You can view the fully deployed, interactive website live here:  
👉 **[https://intellectsclub-srm.web.app/](https://intellectsclub-srm.web.app/)**

---

## 🚀 Key Features

* **Cinematic Experience**: Letter-by-letter logo reveals, dynamic slide-up grids, and loading animations powered by **GSAP**.
* **3D Particle Background**: Immersive space backgrounds built using **Three.js** that react dynamically to mouse movement.
* **SPA Routing**: Single Page Application structure with dynamic view loading, avoiding page refreshes and maintaining smooth transitions.
* **3D Interactive Profile Cards**: Fluid 3D mouse-tilt hover effect on card overlays with instant glowing shadows.
* **Zero-Cache Database Layer**: Real-time Firebase/Supabase database integrations configured to bypass CDN caches so content edits go live instantly.

---

## 📂 Feature Rollouts & History

To keep the repository clean and protect sensitive configuration keys, the progression is archived in individual ZIP packages:

### 📦 Day 1: Team Section Rollout
* **Team Profile Cards**: Arranged all 12 core board members and mentors in clean leadership hierarchy grids.
* **Site Developer Badge**: Programmed a dynamic, highlighted pill badge system supporting custom tags (specifically your **Site Developer** tag).
* **Router & Animation Bug Fixes**:
  * Fixed a conflict where the browser's CSS transitions froze GSAP entrance opacity animations.
  * Cleared and killed old GSAP `ScrollTrigger` instances during route changes to prevent elements on other pages from locking invisibly.
  * Reset scroll-to-top *before* view renders to prevent premature animation triggers.

### 📦 Day 2: Social Media & Cache Rollout
* **Database Updates**: Replaced placeholder URLs with real GitHub and LinkedIn profiles for the core board.
* **Zero-Cache Hosting Configurations**:
  * Configured `firebase.json` headers to serve all main assets (`app.js`, `db.js`, and `style.css`) with `Cache-Control: no-cache, no-store, must-revalidate`.
  * Allows any future database additions or team profile edits to go live instantly on users' devices without requiring code version bumps!

---

## 🛠️ Tech Stack

| Category | Technologies Used |
| :--- | :--- |
| **Frontend Core** | HTML5, Vanilla CSS3 (Custom Variables), JavaScript ES6+ Modules |
| **Animations** | GSAP (GreenSock Animation Platform), ScrollTrigger, Three.js (WebGL) |
| **Icons & Fonts** | Lucide Icons, Google Fonts (Outfit, Space Grotesk) |
| **Database** | Firebase Realtime DB, Supabase Authentication & Storage |
| **Hosting** | Firebase Hosting (Configured with custom caching headers) |

---

## ⚙️ Running Locally

1. Clone or download either of the release zip packages (**Day 1** or **Day 2**).
2. Extract the files to a directory on your machine.
3. Add your Supabase and Firebase keys to `config.js` (or leave it blank to run in **Mock Database Mode** automatically using LocalStorage).
4. Run a local web server (e.g., using VS Code Live Server or `npx http-server`).
5. Open the local link in your browser!

---

<div align="center">
  <sub>Developed & Maintained by GUDIBANDI YASHWANTH REDDY (Technical & Innovation Department)</sub>
</div>
