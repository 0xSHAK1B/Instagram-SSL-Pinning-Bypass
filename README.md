<div align="center">

# 🔓 Instagram Android SSL Pinning Bypass

#### Intercept, capture & analyze Instagram HTTPS traffic on Android — no root required

<br>

[![Download APK](https://img.shields.io/badge/⬇_Download_APK_(v442.0.0)-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](../../releases/latest)
[![Telegram](https://img.shields.io/badge/Chat_on_Telegram-26A5E4?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/MUH4MM4DSH4KIB)

![Android](https://img.shields.io/badge/Android_10--14+-3DDC84?style=flat-square&logo=android&logoColor=white)
![ARM64](https://img.shields.io/badge/arm64--v8a-blue?style=flat-square)
![Version](https://img.shields.io/badge/Instagram-v442.0.0.46.79-E4405F?style=flat-square&logo=instagram&logoColor=white)
![Root](https://img.shields.io/badge/Root-Not_Required-brightgreen?style=flat-square)

</div>

---

<div align="center">

> **Bypass SSL/TLS certificate pinning** in Instagram for Android and pipe the full HTTPS stream — including login, API, and Direct flows — into **Burp Suite · mitmproxy · Reqable · Proxypin.**

</div>

---

## 🎥 Proof of Concept

<div align="center">

<img width="578" height="1280" alt="Instagram Android SSL Pinning Bypass PoC – Traffic Captured" src="https://github.com/user-attachments/assets/aa41bb20-cac7-41bb-bf88-5ad63a0b8d34" />

> Live capture — Instagram Android HTTPS traffic intercepted in cleartext. **v442.0.0.46.79**.

</div>

---

## 📦 Supported Version

| App | Package | Version | ABI | Status |
|-----|---------|:-------:|:---:|:------:|
| Instagram for Android | `com.instagram.android` | **442.0.0.46.79** | `arm64-v8a` | ✅ [**Download**](../../releases/latest) |

> Grab the patched APK from the [**Releases**](../../releases/latest) section. Need the newest build or another version? [Message me on Telegram](https://t.me/MUH4MM4DSH4KIB).

---

## 🎯 What You Can Capture

Full visibility into Meta's Instagram API surface:

- **Login & authentication** — `i.instagram.com/api/v1/accounts/login/`, 2FA, session tokens
- **REST & GraphQL API** — feed, explore, reels, stories, and profile endpoints
- **Direct (DMs)** — realtime/MQTT channels and thread endpoints
- **Media & CDN** — image/video delivery and the upload pipeline
- **Search & discovery** — search queries, hashtag and location lookups
- **Notifications & presence**
- **Analytics & telemetry** — device telemetry and A/B assignments

---

## ⚙️ Requirements

### Android Device — Android 10, 11, 12, 13, 14+

- 🟢 **No root required** — install the patched APK and go (rooted devices supported too)
- 📱 ARM device (`arm64-v8a`) — virtually all modern phones and tablets

### Emulator (PC)

- Nox / LDPlayer / MEmu / BlueStacks — **enable ARM translation**; this build ships `arm64` native libraries, so x86/x86_64 emulators need the ARM translation layer.

### MITM Proxy Tool

- [**Burp Suite**](https://portswigger.net/burp) — industry-standard security testing proxy
- [**mitmproxy**](https://mitmproxy.org/) — open-source, scriptable HTTPS proxy
- [**Reqable**](https://reqable.com) — modern cross-platform HTTP debugger
- [**Proxypin**](https://proxypin.com) — lightweight proxy with mobile support

---

## 🚀 How to Capture Traffic — Step by Step

1. **Uninstall** the official Instagram app (signatures conflict)
2. **Download** the patched APK from [**Releases**](../../releases/latest)
3. **Install** it on your device or emulator
4. **Install & trust your proxy's CA certificate** — Settings → Security → Encryption & credentials → **Install a certificate → CA certificate**
5. **Set the Wi-Fi proxy** — Settings → Wi-Fi → (your network) → **Proxy → Manual** → your PC's IP and port
6. **Launch Instagram** — decrypted HTTPS requests and responses stream into your proxy in real time

> 💡 Force-stop and relaunch the app if traffic doesn't appear immediately.

---

<div align="center">

## 💼 Need a Custom Bypass?

**Custom SSL pinning bypass · automated patching scripts · full reverse-engineering projects** — for any Android or iOS app.

[![Request Custom Work](https://img.shields.io/badge/Message_me_on_Telegram-26A5E4?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/MUH4MM4DSH4KIB)

</div>

---

## ⚠️ Disclaimer

This project is provided **for educational and security-research purposes only**. It is **not affiliated with, endorsed by, or connected to Meta, Instagram, or their subsidiaries**. All trademarks belong to their respective owners. You are solely responsible for complying with your local laws and the app's Terms of Service, and should only analyze traffic on **accounts and devices you own or are authorized to test**. Provided **"as is", without warranty of any kind**.

---

## 🔗 Related Projects

| App | Platform | Repository |
|-----|----------|------------|
| Instagram | iOS | [**Instagram iOS SSL Pinning Bypass**](https://github.com/0xSHAK1B/Instagram-iOS-SSL-Pinning-Bypass) |
| Threads | Android | [**Threads SSL Pinning Bypass**](https://github.com/0xSHAK1B/Threads-SSL-Pinning-Bypass) |
| Edits | Android | [**Edits SSL Pinning Bypass**](https://github.com/0xSHAK1B/Edits-SSL-Pinning-Bypass) |
| Facebook | Android | [**Facebook SSL Pinning Bypass**](https://github.com/0xSHAK1B/Facebook-SSL-Pinning-Bypass) |
| Instants | Android | [**Instants SSL Pinning Bypass**](https://github.com/0xSHAK1B/Instants-SSL-Pinning-Bypass) |
| TikTok | Android | [**TikTok SSL Pinning Bypass**](https://github.com/0xSHAK1B/TIKTOK-SSL-Pinning-Bypass) |
| X (Twitter) | Android | [**Twitter SSL Pinning Bypass**](https://github.com/0xSHAK1B/Twitter-SSL-Pinning-Bypass) |

---

## 💖 Support This Project

If this saved you time or helped your research, please **⭐ star the repo** — it helps others find it and keeps the builds coming. Contributions toward keeping bypasses updated as apps release new versions are appreciated:

| Currency | Address |
|:---------|:--------|
| **BTC** | `131NaAJooX2XYq5QUFmKsTuLQXcGNayYPJ` |
| **ETH** | `0xea9a566a5123c3a1b8d60f8bdd845835716668f0` |
| **USDT (TRC-20)** | `THssAZhUQEEsw15211rAaRLGRjSWXMX4PW` |

Thank you! 🙏

---

<div align="center">

### 📬 Contact & Latest Builds

Newest APKs · support · custom work

[![Telegram](https://img.shields.io/badge/@MUH4MM4DSH4KIB-26A5E4?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/MUH4MM4DSH4KIB)

⭐ **Star the repo if it helped your research!**

</div>

