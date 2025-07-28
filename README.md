# 🌿 MintQuote

**“MintQuote” is your sovereign, minimalist quoteboard and mobile-first learning app for Bitcoin education — in English, Español, and Naija Pidgin. Built for Nostr. Powered by Bitcoin.**

---

## ✨ Overview

MintQuote is an educational, social, and spiritual quote app designed to orange-pill the world — one quote at a time. It blends poetic Bitcoin literacy with real-time Block Height signatures and shareable quote cards, all in a stunning dark UI.

Designed to be ultra-light, sovereign, and mobile-first, MintQuote helps users learn, save, and share Bitcoin-inspired wisdom in 3 languages:  
- 🇬🇧 English  
- 🇳🇬 Naija Pidgin  
- 🇪🇸 Español

Built for the [Yakihonne Agentic Hackathon](https://yakihonne.com), MintQuote uses:
- **Vercel AI SDK**
- **V0.dev for UI**
- **Nostr protocol for social sharing**
- **Multilingual onboarding and AI quote agent**

---

## 🧠 What It Solves

Most Bitcoin education apps are complex, technical, or inaccessible to non-English speakers.  
MintQuote solves for:
- **Multilingual learning**: Localized experience in English, Pidgin, and Spanish.
- **Shareability**: Generates minimal quote cards for Nostr + social.
- **Trust**: Adds Bitcoin block height to every quote for provable timestamps.
- **Offline-first**: Designed to be light, sovereign, and usable even with low bandwidth.
- **Simplicity**: Minimal UI with spiritual and educational onboarding flow.

---

## 🏗️ Tech Stack

| Tool            | Purpose                              |
|-----------------|--------------------------------------|
| Vercel AI SDK   | Quote generation & local AI agent    |
| V0.dev UI       | Mobile-first frontend, deployed to Vercel |
| Convex / Upstash KV | Persistent storage for quotes, tokens |
| Nostr SDK       | Share quotes as signed notes         |
| TailwindCSS     | Styling and responsiveness           |
| Framer Motion   | Transitions and delight              |
| Wool Icons      | Minimal, expressive iconography      |

---

## 🧩 Features

- 🪷 **MintQuote Generator** – AI-augmented quote cards with real-time block height stamp
- ⚡ **Share to Nostr** – Tap to zap or post
- 🪪 **Onboarding Screens** – Explains Bitcoin, privacy, and Nostr in clear language
- 🌍 **Multilingual UI** – Language toggle across English, Español, and Pidgin
- 📱 **Mobile-First PWA** – Works beautifully on all devices
- 🌑 **Pitch Black Theme** – No white light, only mint green, forest, orange, and paper-white cardboards
- 🧠 **Agent-based AI** – Yakihonne-compatible agent available in smart widget JSON
- 🧾 **Block-Stamped Cards** – Every quote shows the current Bitcoin block height
- 🔲 **Card Signature** – Discreet MintQuote logo badge on shared quotes

---

## 🔧 Local Development

```bash
git clone https://github.com/yourname/MintQuote.git
cd MintQuote
pnpm install
pnpm dev
