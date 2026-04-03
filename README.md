# Instagram SSL Pinning Bypass for Android (2026) – Intercept & Capture HTTPS Traffic

[![Telegram](https://img.shields.io/badge/💬_Chat_on_Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white&labelColor=121212&color=26A5E4&logoWidth=20)](https://t.me/MUH4MM4DSH4KIB)
![Android](https://img.shields.io/badge/Android-3DDC84?style=for-the-badge&logo=android&logoColor=white)
![ARM64](https://img.shields.io/badge/ARM64--v8a-Supported-blue?style=for-the-badge)
![x86_64](https://img.shields.io/badge/x86__64-Supported-blue?style=for-the-badge)

> Bypass Instagram SSL certificate pinning on Android to intercept, inspect, and analyze HTTPS network traffic — works on both **rooted** and **non-rooted** devices.

---

## 📖 Overview

This project provides a pre-patched **Instagram APK** with SSL/TLS certificate pinning disabled, allowing security researchers and developers to capture and analyze Instagram's HTTPS traffic using standard MITM proxy tools. Inspect API endpoints, media delivery, authentication flows, GraphQL queries, and content recommendation mechanisms.

---

## 🎥 Proof of Concept


<img width="720" height="1640" alt="Image" src="https://github.com/user-attachments/assets/c69121da-b42a-42f7-8530-53af60c96de2" />

▶️ [**Watch the Full Video Demonstration**](https://github.com/user-attachments/assets/82c7397c-5603-464e-9bd7-c75e995369fd)

---

## 📋 Supported Instagram Version

| App | Version | Status |
|-----|---------|--------|
| Instagram | **423.0.0.47.66** | ✅ Bypassed ([contact me on Telegram](https://t.me/MUH4MM4DSH4KIB)) |
| Instagram | **370.1.0.43.96** | ✅ Bypassed (Demo — [available in Releases](../../releases)) |

> For the **latest bypassed version**, [contact me on Telegram](https://t.me/MUH4MM4DSH4KIB).

---

## ⚙️ Supported Architectures

| Architecture | Support |
|---|---|
| `arm64-v8a` | ✅ |
| `x86_64` | ✅ |

---

## 📱 Requirements

### Option A: Physical Android Device

- Android phone or tablet (**rooted or non-rooted**)
- One of the following traffic interception tools:
  - [Proxypin](https://proxypin.com) — free, lightweight
  - [Reqable](https://reqable.com) — feature-rich, modern UI

### Option B: Android Emulator (PC)

- Windows PC with one of the following emulators installed:
  - [Nox Player](https://www.bignox.com/)
  - [LDPlayer](https://www.ldplayer.net/)
  - [BlueStacks](https://www.bluestacks.com/)
- A desktop MITM proxy tool:
  - [Burp Suite](https://portswigger.net/burp) — industry standard
  - [Mitmproxy](https://mitmproxy.org/) — open source
  - [Reqable](https://reqable.com)
  - [Proxypin](https://proxypin.com)

---

## 🚀 Bypass Procedure

1. **Download** the SSL pinning bypassed Instagram APK from this repository.
2. **Install** the patched APK on your Android device or emulator.
3. **Configure** your proxy tool of choice (Proxypin, Reqable, Burp Suite, or Mitmproxy) to intercept traffic.
4. **Launch Instagram** and start capturing HTTPS requests and responses.

> **Tip:** Make sure to install and trust the proxy's CA certificate on your device for full HTTPS decryption.

---

## What you can inspect:

- **Feed & Reels** — API requests powering Instagram's content recommendation engine
- **GraphQL queries** — Structured API calls for profile data, posts, stories, and interactions
- **Media delivery** — CDN URLs, image/video quality negotiation, and caching behavior
- **Authentication** — Login flows, token management, and session handling
- **Direct messages** — DM API endpoints and message delivery mechanisms
- **Search & Explore** — How search queries, hashtag lookups, and discovery feeds are processed
- **Stories & Highlights** — Story upload pipeline, viewer tracking, and highlight management

---


## 📬 Contact & Latest Builds

For the **most up-to-date** SSL pinning bypassed Instagram APK, reach out directly:

[![Telegram](https://img.shields.io/badge/💬_Chat_on_Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white&labelColor=121212&color=26A5E4&logoWidth=20)](https://t.me/MUH4MM4DSH4KIB)

---

## 🏷️ Tags

`instagram ssl pinning bypass` · `instagram certificate pinning` · `instagram mitm` · `instagram traffic interception` · `instagram burp suite` · `instagram proxy android` · `instagram https decrypt` · `meta instagram security` · `android ssl bypass no root` · `instagram ssl bypass 2026` · `instagram apk patched` · `instagram graphql api` · `instagram private api` · `instagram api reverse engineering` · `instagram network analysis` · `com.instagram.android`
