<div align="center">

  <a href="https://anipirate.xyz">
    <img src="logo.png" alt="AniPirate Logo" width="140" height="140" style="border-radius: 28px; box-shadow: 0 12px 36px rgba(0,0,0,0.45);">
  </a>

  <h1 style="font-size: 2.4rem; font-weight: 800; margin-top: 16px; margin-bottom: 8px;">AniPirate</h1>
  <p style="font-size: 1.15rem; color: #a1a1aa; max-width: 620px; margin: 0 auto 18px;">
    <strong>Discover More. Search Less.</strong><br>
    The modern, curated discovery hub for the finest anime, streaming, manga, gaming, and digital platforms across the web.
  </p>

  <p>
    <a href="https://anipirate.xyz"><img src="https://img.shields.io/badge/Live_Platform-anipirate.xyz-6366f1?style=for-the-badge&logo=cloudflare&logoColor=white" alt="Live Platform"></a>
    <a href="https://discord.gg/thYVNs5gGA"><img src="https://img.shields.io/badge/Discord-Join_Community-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord Community"></a>
    <a href="https://t.me/anipirate_reall"><img src="https://img.shields.io/badge/Telegram-Announcements-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram Channel"></a>
  </p>

  <p>
    <img src="https://img.shields.io/badge/React_18-20232A?style=flat-square&logo=react&logoColor=61DAFB" alt="React 18">
    <img src="https://img.shields.io/badge/TypeScript-007ACC?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript">
    <img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=flat-square&logo=tailwind-css&logoColor=white" alt="Tailwind CSS">
    <img src="https://img.shields.io/badge/Cloudflare_Workers-F38020?style=flat-square&logo=cloudflare&logoColor=white" alt="Cloudflare Workers">
    <img src="https://img.shields.io/badge/Cloudflare_D1-F38020?style=flat-square&logo=sqlite&logoColor=white" alt="Cloudflare D1">
    <img src="https://img.shields.io/badge/Global_Edge_Cache-10B981?style=flat-square&logo=fastly&logoColor=white" alt="Edge Cache">
  </p>

</div>

---

## 🌟 The AniPirate Experience

Finding high-quality, trustworthy websites and apps across the internet has become harder than ever. Search engines are saturated with SEO spam, dead mirrors, aggressive ad networks, and misleading copies.

**AniPirate was engineered to cut through the noise.**

AniPirate is an ultra-fast, community-driven directory that hand-curates, vets, and categorizes digital platforms into one organized, beautiful portal. Every listing includes verified platform metadata, device compatibility, transparent safety statuses, and real community feedback—so you know exactly what to expect before you click.

---

## 🔥 Key Features & Capabilities

### ⚡ Sub-Millisecond Global Edge Infrastructure
Powered by **Cloudflare Workers** and **Cloudflare D1** serverless SQL. Built with multi-layer edge caching (`s-maxage=14400`, `stale-while-revalidate`, and ETag 304 validation), allowing public catalog browsing to load almost instantaneously anywhere in the world with zero origin lag.

### 🔍 Instant Multi-Dimensional Search & Filtering
- **Keyword & Name Search**: Instant client-side fuzzy search across all entries, descriptions, and metadata.
- **Deep Category & Tag Filtering**: Filter seamlessly across multiple tags simultaneously (e.g. `No Ads`, `Open Source`, `Dub`, `Sub`, `4K`, `Free`, `Offline`).
- **Platform & Device Badges**: Immediately see supported operating systems (Android, iOS, Windows, macOS, Linux, Web, Extensions).
- **Extension Indicators**: Dedicated badges for browser add-ons and specialized app plugins.

### ⭐ Transparent Community Ratings
Real-time 5-star rating system with aggregate scoring, total review counts, and instant rating submission for authenticated community members.

### 💬 Rich Discussion & Nested Comments
Dedicated comment sections on every single platform entry. Supports Markdown formatting, nested replies, user reactions (likes/dislikes), and community moderation.

### 🛡️ Safety & Verification Badges
Every platform listing undergoes continuous review and is tagged with clear safety statuses:
- 🟢 **Verified Platform** — Reviewed and verified for domain integrity and functionality.
- 🟡 **Community Reviewed** — Active service cataloged and maintained with community oversight.
- 🔴 **Caution / Warning** — Alerts users to aggressive advertising, recent domain changes, or security cautions.

### 📱 Modern Glassmorphic Dark UI
Designed with a sleek, dark-mode-first aesthetic, silky smooth micro-interactions, responsive touch ergonomics for smartphones, and keyboard navigation for power users.

### 🔗 One-Tap Quick Share & Verified Links
- **Corner Quick-Share**: One-click sharing to native OS sheets or instant clipboard link copy with visual confirmation.
- **Direct Repository Links**: Instant access to official open-source GitHub / GitLab repositories for transparent tools and clients.
- **Mirror Verification**: Direct, clean destination links without tracking parameters or middleman redirect screens.

---

## 🧭 Live Curated Categories

AniPirate organizes entries into 13 dedicated, actively maintained categories:

| Category | Icon | What You'll Find |
| :--- | :---: | :--- |
| **Anime** | 📺 | Premier streaming services, high-speed portals, release schedules, and anime hubs. |
| **Games** | 🎮 | Web and desktop gaming platforms, emulators, ROM archives, and gaming databases. |
| **Movie/TV** | 🎬 | General entertainment streaming, cinema discovery, television portals, and media archives. |
| **Music** | 🎵 | Lossless audio players, web streamers, music clients, and alternative music discovery. |
| **Tools** | 🔧 | Essential digital utilities, converters, scrapers, bypass tools, and web assistants. |
| **Manga/Manhwa** | 📖 | High-resolution manga, manhwa, and manhua readers, scanlations, and tracking platforms. |
| **Downloader** | ⬇️ | Dedicated media archivers, video/audio grabbers, and batch download utilities. |
| **App** | 📱 | Native Android APKs, desktop applications, iOS wrappers, and dedicated media clients. |
| **Trackers/DB** | 🌐 | Community release trackers, media indexers, API databases, and metadata registries. |
| **Live TV** | 📡 | Live television streams, IPTV playlists, sports portals, and real-time broadcasts. |
| **Asian Drama** | 🎭 | Specialized K-Drama, C-Drama, and J-Drama streaming platforms and fan communities. |
| **Media‑Tools** | 🎥 | Custom video players, media server software, streaming extensions, and playback tools. |
| **Donghua-Streaming** | 📻 | Dedicated Chinese animation (Donghua) portals, subtitled releases, and community channels. |

---

## 🛠️ Architecture & Tech Stack

```
               ┌────────────────────────────────────────────────┐
               │              Cloudflare Edge (CDN)             │
               │   • Static SPA Assets (Brotli / Immutable)    │
               │   • Edge Cache API (4-Hour TTL / ETag 304)     │
               └───────────────────────┬────────────────────────┘
                                       │
                        ┌──────────────┴──────────────┐
                        ▼                             ▼
              [ React 18 SPA Frontend ]     [ Cloudflare Worker API ]
              • TypeScript + Vite           • Serverless V8 Runtime
              • Tailwind CSS + Lucide       • Cloudflare D1 SQL Database
              • Glassmorphic Design         • Turnstile Bot Shield
              • Client-side Cache Store     • HMAC-SHA256 Privacy Hashing
```

- **Frontend:** [React 18](https://react.dev/), [TypeScript](https://www.typescriptlang.org/), [Tailwind CSS](https://tailwindcss.com/), [Lucide React](https://lucide.dev/), [Vite 6](https://vitejs.dev/)
- **Edge Runtime:** [Cloudflare Workers](https://workers.cloudflare.com/) (Node.js compatible V8 isolates)
- **Database:** [Cloudflare D1](https://developers.cloudflare.com/d1/) (Serverless distributed SQLite)
- **Edge Cache API:** Authoritative Cloudflare edge cache with custom SHA-256 ETag negotiation and stale-while-revalidate fallbacks
- **Security & Hardening:** Salted PBKDF2 / Bcrypt password hashing, Cloudflare Turnstile CAPTCHA, strict CSP, and parameterized SQL query protection

---

## 🔍 The AniPirate Quality Standard

AniPirate upholds a strict curation lifecycle:

1. **Discovery** — Quality candidates suggested by the community or discovered by curators.
2. **Review** — Verified for uptime, clean domain provenance, malware/spam absence, and usability.
3. **Classification** — Enriched with categories, device compatibility, feature tags, and safety advisories.
4. **Edge Distribution** — Deployed globally across Cloudflare edge data centers.
5. **Continuous Auditing** — Automated link monitoring and community reports ensure dead mirrors are promptly flagged or replaced.

---

## 🤝 Community & Submissions

AniPirate is built for the community, by the community. We welcome contributions:

- **Suggest a Platform:** Found a service that deserves a spot? Submit it directly on [anipirate.xyz](https://anipirate.xyz).
- **Report an Issue:** Flag broken mirrors, outdated domains, or problematic listings via the report button on any entry page.
- **Join the Conversation:** Chat with fellow members, suggest features, and get updates in our community channels:
  - 💬 **Discord:** [discord.gg/thYVNs5gGA](https://discord.gg/thYVNs5gGA)
  - ✈️ **Telegram:** [t.me/anipirate_reall](https://t.me/anipirate_reall)

---

## 🌐 Official Links

- 🌐 **Website:** [https://anipirate.xyz](https://anipirate.xyz)
- 💬 **Discord:** [https://discord.gg/thYVNs5gGA](https://discord.gg/thYVNs5gGA)
- ✈️ **Telegram:** [https://t.me/anipirate_reall](https://t.me/anipirate_reall)
- ⚖️ **DMCA & Copyright Policy:** [https://anipirate.xyz/dmca-policy](https://anipirate.xyz/dmca-policy)
- 🔒 **Privacy Policy:** [https://anipirate.xyz/privacy](https://anipirate.xyz/privacy)

---

## ⚖️ Legal Disclaimer

AniPirate operates strictly as an informational index and discovery directory. AniPirate does not host, upload, broadcast, or store media files or external third-party platform content. All external links and trademarks belong to their respective copyright holders. Users are advised to review terms of service and practice safe browsing when visiting any external domain.

---

<div align="center">
  <p><strong>AniPirate</strong> — Built with care for the global discovery community.</p>
  <p>© 2026 AniPirate. All rights reserved.</p>
</div>
