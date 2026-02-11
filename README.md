# 🔐 SSL Pinning Bypass Instagram App

Instagram SSL Pinning Bypass for Android – intercept Instagram traffic.

---

## 🎥 Evidence 

<img width="720" height="1640" alt="Image" src="https://github.com/user-attachments/assets/535bcc37-53b0-4f15-9119-53f3ef235607" />


▶️ [Watch the Demonstration](https://github.com/user-attachments/assets/28c05c3c-bc8a-42ad-962d-e0c5241802b3)

---

## ⚙️ Supported Architectures
- **arm64-v8a**
- **x86_64**
---
## Instagram App Version 
- **416.0.0.47.66**
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
