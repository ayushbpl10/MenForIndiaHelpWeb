# ForMenIndiaHelp — Official Web Portal 🌐

![Version](https://img.shields.io/badge/version-3.0.0-0d3b5c?style=for-the-badge&logo=html5)
![Security](https://img.shields.io/badge/security-Ultra_Strict_CSP-0d9668?style=for-the-badge)
![Deployment](https://img.shields.io/badge/deployment-GitHub_Pages-1a7fa8?style=for-the-badge&logo=github)
![License](https://img.shields.io/badge/license-Registered%20Copyright-c0392b?style=for-the-badge)

This repository contains the official promotional web portal and legal policy hub for the **ForMenIndiaHelp** Android mobile application.

🌐 **Live Website:** https://ayushbpl10.github.io/MenForIndiaHelpWeb/

📱 **Google Play Store (Closed Testing):** https://play.google.com/apps/testing/com.formenindiahelp.app

---

## ✨ Web Portal Highlights

### 📱 1. Interactive Screenshot Showcase (`#showcase`)
A stunning glassmorphic phone frame preview section with interactive tab switching (`📊 Main Dashboard`, `🚨 Emergency Helplines`, `🛡️ Suicide Prevention`). Smooth JavaScript fade transitions dynamically load the corresponding real app screenshot inside the device frame.

### ⚡ 2. Published Features Grid (`#features`)
Showcases all v3.0 offline legal knowledge bases, AI emotional counselling bot, eCourts portal, Kanoon live search, and multi-lingual audio guides.

### 🚀 3. Innovation Pipeline / Roadmap (`#roadmap`)
Highlights upcoming v4.0+ features including the encrypted case evidence vault, pro-bono advocate network, and peer support community forums.

### 📜 4. Uniform Legal Policy Hub
Provides standardized, easily accessible web versions of all mandatory legal policies required by the Google Play Store and Indian regulatory authorities.

---

## 🔒 Enterprise Web Security & Hardening Architecture

To prevent automated scraping, bot harvesting, XSS, and clickjacking, every single page (`index.html`, `privacy.html`, `terms.html`, `copyright.html`) is fortified with uniform, ultra-strict security headers:

* **Ultra-Strict Content Security Policy (CSP):** `object-src 'none'; base-uri 'self'; form-action 'self'; upgrade-insecure-requests;`. Eliminates flash/plugin exploits, prevents unauthorized `<base>` tag injection, stops form hijacking, and forces secure HTTPS connections.
* **Clickjacking & MIME Protection:** `X-Frame-Options: DENY` (preventing site embedding in malicious iframes) and `X-Content-Type-Options: nosniff` (preventing MIME-sniffing XSS attacks).
* **Referrer Policy & Data Privacy:** `Referrer-Policy: strict-origin-when-cross-origin` ensures sensitive URL parameters or user paths are never leaked to external third-party domains.
* **Hardware Permissions Policy:** `Permissions-Policy: geolocation=(), microphone=(), camera=(), payment=(), usb=()` explicitly disables browser access to device hardware.
* **HSTS Configuration:** `Strict-Transport-Security` meta descriptions enforce strict HTTPS caching and sub-domain security.
* **Anti-Scraping Footer Notice:** Explicit legal notice prohibiting automated scraping, bot harvesting, or unauthorized reverse-engineering of web assets or legal databases.

---

## 📁 Directory Structure

| File | Purpose | Security Hardened |
|------|---------|:---:|
| `index.html` | Main promotional landing page | ✅ Yes |
| `styles.css` | Global stylesheet with modern glassmorphism | ✅ Yes |
| `privacy.html` | Privacy Policy (Zero external data collection) | ✅ Yes |
| `terms.html` | Terms of Service & Educational Disclaimers | ✅ Yes |
| `copyright.html` | Registered Copyright & IP Enforcement Policy | ✅ Yes |
| `screenshots/` | Real app screenshots used in interactive showcase | — |

---

## 🚀 Deployment Workflow

The web portal is configured for continuous delivery. It is automatically built and deployed to **GitHub Pages** via GitHub Actions on every push or merge to the `main` branch.

---

## ⚖️ License & Copyright

**Registered Copyright © 2026 ForMenIndiaHelp. All rights reserved.**

The ForMenIndiaHelp web assets, design system, brand architecture, and legal policy texts are the exclusive intellectual property of ForMenIndiaHelp. Unauthorized cloning, scraping, or commercial plagiarism will be met with immediate legal action under applicable copyright laws.
