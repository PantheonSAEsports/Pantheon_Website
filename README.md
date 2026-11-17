# 🏛️ Pantheon Esports & Gaming Hub

> A high-performance, dark-and-gold themed multi-page digital ecosystem built for competitive esports tournaments, Minecraft server networks, developer studios, and community engagement.

---

## ✨ Overview

Pantheon is a centralized platform designed to manage competitive esports operations, community tournament brackets, custom software commissions, and in-game SMP store transactions. Engineered with a striking dark-burgundy and metallic gold aesthetic, the platform offers fully integrated user profiles, subscription-gated scouting intelligence, and responsive mobile-first navigation.

---

## 🚀 Key Features & Pages

* **🌐 Home & Landing Portal (`index.html`):** The primary gateway featuring organization highlights, live community feeds, and quick navigation.
* **⚔️ Tournaments Hub (`tournaments.html`):** Live bracket standings, match schedules, and tournament registration workflows.
* **📊 Player Dashboard & Scouting Intel (`dashboard.html`):** Real-time player statistics, active team roster tracking, and a **subscription-gated team/player database** exposing opponent KDAs, GPM metrics, and ban priorities.
* **👤 Player Profile & Customization (`profile.html`):** Personal account details, legal verification info, and live profile preview cards.
* **⚙️ Account Settings (`settings.html`):** Connected gaming accounts (Discord, Mobile Legends ID, Minecraft Java/Bedrock gamertag), 2FA security toggles, and notification preferences.
* **💎 Official Store (`store.html`):** Scouting Pass membership tiers (Free Community Scout vs. VIP Pro Pass), software commission quotes, and Minecraft SMP webstore links.
* **🛠️ Pantheon Studio (`studios.html`):** Custom Spigot/Fabric Minecraft plugins, esports web development, and Discord bot commissions.
* **💬 Community Hub (`community.html`):** Official Discord servers, WhatsApp groups, and allied partner organization networks (Waylander Gaming, LA Network).

---

## 🛠️ Tech Stack & Architecture

* **Framework & Styling:** [Tailwind CSS v4](https://tailwindcss.com/) (CDN utility-first styling with custom gold/burgundy color palette).
* **Typography:** [Google Fonts](https://fonts.googleapis.com) (`Cinzel` for majestic headers and `Inter` for clean body readability).
* **Interactivity:** Vanilla JavaScript (Slide-out profile drawers, dynamic database filtering, tier preview toggles, and reactive form validation).
* **Environment:** Local development stack optimized for Node.js, live-server workflows, and Linux (Fedora) environments.

---

## 📂 Project Directory Structure

```text
pantheon-esports/
├── index.html                  # Main landing portal
├── registration/
│   └── auth.html               # Sign-in & registration portal
├── pantheon/
│   ├── community.html          # Community Discord & WhatsApp hubs
│   ├── tournaments.html        # Tournament brackets & schedules
│   ├── store.html              # Scouting passes & software commissions
│   ├── dashboard.html          # Player stats, team roster & gated scouting DB
│   ├── profile.html            # Personal info & profile customization
│   └── settings.html           # Connected game IDs, 2FA & security
├── pantheonnetwork/
│   └── network.html            # Minecraft SMP server hub & live status
├── pantheonstudios/
│   └── studios.html            # Modding, web engineering & bot commissions
└── images/
    ├── logo.png                # Official Pantheon crest
    ├── WaylanderLOGO.jpg       # Partner organization logo
    └── LAlogo.png              # Affiliate network logo
