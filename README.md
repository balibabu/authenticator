# 🔐 Authenticator - A Beautiful Offline TOTP Generator

[![Live Demo](https://img.shields.io/badge/Live-Demo-green?style=for-the-badge)](https://balibabu.github.io/authenticator)
[![Made with HTML/CSS/JS](https://img.shields.io/badge/Built%20with-HTML%20%7C%20TailwindCSS%20%7C%20JS-blue?style=for-the-badge)](#)
[![Secure Offline App](https://img.shields.io/badge/Secure-Offline%20First-lightgrey?style=for-the-badge)](#)

> ⚠️ Forget Google Authenticator. Try this sleek, privacy-first, open-source alternative!

---

## 🚀 What is this?

**Authenticator** is a secure, offline-ready web application that generates **Time-based One-Time Passwords (TOTP)** — a form of 2FA (two-factor authentication) used by platforms like Google, GitHub, and many more. Built using only HTML, TailwindCSS, and vanilla JavaScript (with some crypto magic), it's fast, lightweight, and requires **no internet connection** after initial load.

Whether you're a developer, privacy nut, or just tired of clunky mobile apps — this one's for you.

---

## ✨ Features

- 🔒 **Offline Support** – Works 100% offline after first load
- 📷 **QR Code Scanner** – Quickly import accounts by scanning TOTP-compatible QR codes
- ⚡ **Auto Code Refresh** – 6-digit tokens update every 30 seconds
- 🌈 **TailwindCSS UI** – Clean, responsive, mobile-friendly design
- 🔑 **Secure Token Generation** – Powered by `crypto-js`, no third-party backends
- 🌐 **PWA Ready** (optional upgrade) – Add it to your home screen like a native app

---

## 📸 Sneak Peek

![App Screenshot](https://raw.githubusercontent.com/balibabu/authenticator/main/screenshot.png)  
<sub>*Minimalist. Fast. Private.*</sub>

---

## 🌍 Try it Live

👉 **[Launch the App →](https://balibabu.github.io/authenticator)**  
No installs. No data collection. Just 2FA simplicity.

---

## 🛠 Tech Stack

- HTML5 + Vanilla JavaScript  
- [TailwindCSS](https://tailwindcss.com) for styling  
- [crypto-js](https://github.com/brix/crypto-js) for secure token generation  
- Native Web APIs (WebCrypto, Camera, etc.)

---

## 📦 How to Use

> This is a client-side only web app. No backend required.

### ✅ Add Your First TOTP

1. Click `+ Add` to enter your account info manually or scan a QR code.
2. The token will appear and refresh every 30 seconds.
3. Done! Use these codes to log in securely on supported platforms.

---

## 📁 Installation (Optional)

Want to run it locally?

```bash
git clone https://github.com/balibabu/authenticator.git
cd authenticator
open index.html
