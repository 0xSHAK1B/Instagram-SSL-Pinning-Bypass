# 🔐 SSL Pinning Bypass Instagram App

Instagram SSL Pinning Bypass for Android – intercept Instagram traffic.

---

## 🎥 Evidence 

<img width="720" height="1640" alt="Image" src="https://github.com/user-attachments/assets/708523b8-8c27-4ca6-94c5-c295aaad5c7a" />



▶️ [Watch the Demonstration](https://github.com/user-attachments/assets/7a953ef1-61f7-4242-8d78-b9831bbc3e69)

---

## ⚙️ Supported Architectures
- **arm64-v8a**
- **x86_64**
---
## Instagram App Version 
- **414.0.0.40.83**
---

## 📱 Mobile Device Requirements
- Android device (**Rooted** or **Non-Rooted**)
- One of the following traffic interception tools:
  - [Proxypin](https://proxypin.com)
  - [Reqable](https://reqable.com)


## 💻 Emulator Setup
- Windows PC with:
  - **Reqable**, **Burp Suite**, or **Mitmproxy** installed
  - **Nox** or **LDPlayer** Android emulator
  - **Root access** enabled in the emulator


## 🚀 Bypass Procedure

1. Replace patched `libstartup.so with /data/data/com.instagram.android/lib-compressed/libstartup.so`
2. Replace the patched library file:
   ```bash
   adb push D:\patched\libstartup.so /data/data/com.instagram.android/lib-compressed/libstartup.so

3. Use Proxypin / Reqable / Burp Suite / Mitmproxy for capturing traffics.

## For latest patched libstartup.so contract with me.
<a href="https://t.me/MUH4MM4DSH4KIB" target="_blank">
  <img src="https://img.shields.io/badge/💬_Chat_on_Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white&labelColor=121212&color=26A5E4&logoWidth=20" alt="Telegram" style="border-radius: 8px;"/>
</a>
