<div align="center">
  <img src="https://img.shields.io/badge/Spotify-1ED760?style=for-the-badge&logo=spotify&logoColor=white" alt="Spotify Badge"/>
  <img src="https://img.shields.io/badge/Made%20With-Love-ff69b4?style=for-the-badge" alt="Made With Love"/>
  
  # 🎵 SpotOn

  **A Premium, Full-Feature Music Streaming Web Application Inspired by Spotify.**
  
  <p align="center">
    <a href="#-key-features">Key Features</a> •
    <a href="#-tech-stack">Tech Stack</a> •
    <a href="#-architecture--database-design">Architecture</a> •
    <a href="#-getting-started">Getting Started</a> •
    <a href="#-future-roadmap">Roadmap</a>
  </p>
</div>

---

## 📌 Project Overview

**SpotOn** is a high-performance, pixel-perfect music streaming platform built to replicate the core experience of Spotify. This project showcases the implementation of complex audio state management, responsive UI design, secure user authentication, and relational/non-relational data modeling. It provides users with a seamless environment to discover music, manage personal libraries, and stream audio without interruptions.

---

## ✨ Key Features

### 🎧 Audio & Playback Engine
* **Persistent Media Player:** Uninterrupted audio playback that persists seamlessly across page transitions and route changes.
* **Advanced Playback Controls:** Fully interactive seeker bar, volume control, mute toggle, shuffle, and repeat modes.
* **Queue Management:** Dynamic queue system allowing users to view, reorder, or add upcoming tracks on the fly.

### 📂 User Personalization
* **Custom Playlists:** Full CRUD functionality allowing users to create, rename, delete, and add/remove tracks from playlists.
* **Liked Songs Library:** A dedicated, automated smart-playlist for tracks a user saves.
* **Dynamic Search:** Real-time search functionality indexing tracks, albums, and artists instantly as you type.

### 🛡️ Core Infrastructure
* **Secure Authentication:** Secure user registration, login, and session persistence (using Supabase).
* **Responsive Layout:** A modern, beautiful dark-mode interface optimized flawlessly for Desktop, Tablet, and Mobile devices.
* **Payment Integration:** Built-in premium infrastructure handling subscription processing natively with Stripe.

---

## 🛠️ Tech Stack

| Layer | Technology | Purpose |
| :--- | :--- | :--- |
| **Framework** | Next.js 13.4 / React | Server-side rendering, component architecture, and routing |
| **Styling** | Tailwind CSS | Modern, maintainable utility-first design |
| **Backend / Auth** | Supabase | Real-time backend management, user authentication, and Postgres integration |
| **Database** | PostgreSQL | Storing structured user data, playlists, and track metadata |
| **Payments** | Stripe | Handling secure end-to-end premium subscriptions |

---

## 🏁 Getting Started

Follow these instructions to set up the project locally on your machine.

### Prerequisites
* Node.js installed (v16.x or higher recommended)
* A Supabase account and a Stripe developer account configured

### Installation & Setup

1. **Clone your repository:**
   ```bash
   git clone [https://github.com/Auranzeb05/SpotOn.git](https://github.com/Auranzeb05/SpotOn.git)
   cd SpotOn
