# 🎙️ VaaniSetu — Voice-First Welfare Navigator

> **"Speak in your language. Know your rights."**
> वाणी सेतु — आपकी भाषा में, आपके अधिकारों तक

Built for **Build for Good 2026** · AWAAZ Track · Government Schemes & Entitlements

---

## 🔴 The Problem

India has 500+ active welfare schemes worth ₹lakhs per eligible family.
Most people never claim them — not because they don't need help, but because:

- Information is in **English only**
- Portals require **smartphones and literacy**
- Eligibility criteria are **scattered across websites**
- No one explains **what documents to bring**

> In Karnataka alone, **$735 million** collected for worker welfare went unused due to lack of awareness.
> A survey across 7 states found **72% of rural households were unaware of MGNREGS** — India's largest employment scheme.

---

## ✅ Our Solution

VaaniSetu is a **WhatsApp voice agent** that:

1. Receives a voice note in the user's language (Hindi, Marathi, Tamil, Telugu…)
2. Transcribes it using **Sarvam AI** (Indic-native speech model)
3. Matches the user's profile against **24 central + state schemes**
4. Sends back a **spoken audio reply** naming matched schemes + benefit amounts
5. Sends a **document checklist card** the user can show at the CSC
6. Sends the **nearest CSC Google Maps pin**
7. Follows up 7 days later: *"Did you visit the CSC?"*

**No app. No English. No literacy required. Just WhatsApp.**

---

## 👥 Who It's For

| Person | Problem | VaaniSetu helps with |
|---|---|---|
| Rekha, 48 · Vidarbha widow farmer | Entitled to ₹36,000/yr, never claimed | PM Kisan + NSAP + PM-JAY + PM Awas |
| Suresh, 28 · Bihar migrant in Chennai | Hindi speaker, Tamil city, lost | Hindi voice → Tamil CSC navigation |

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| Voice delivery | WhatsApp Cloud API (Meta) |
| Speech-to-text | Sarvam AI — Indic STT (10+ languages) |
| Intelligence | GPT-4o / Gemini 1.5 + confidence scoring |
| Text-to-speech | Sarvam AI — Indic TTS |
| Scheme database | 24 central + state schemes (structured JSON) |
| CSC navigation | Google Maps API |
| Backend | Node.js + Express + Render |
| Fallback | IVRS phone call (for 2G / no-internet users) |

---

## 🎯 Key Features

- 🗣️ **Voice-first** — works for users who cannot read
- 🌐 **10+ Indian languages** — Hindi, Marathi, Tamil, Telugu, Bengali and more
- 📋 **Document checklist** — auto-generated, shareable at CSC
- 📍 **CSC locator** — Google Maps pin sent in WhatsApp
- 🔁 **Follow-up loop** — outcome tracking, not just discovery
- 📞 **IVRS fallback** — phone call mode for non-internet users
- 📊 **Confidence scoring** — borderline cases flagged for human review

---

## 🚀 Live Demo

👉 **[vaanisetu.demo — Click to experience it](https://sakshiwankhade026-coder.github.io/vaanisetu)**

---

## 👩‍💻 Team Hacktrix — Pune

| Member | Role |
|---|---|
| Sakshi Wankhade | Lead — Product & Submission |
| Sneha Telsang | Research — Scheme Database & Content |
| Varshita Chitkeshi | Design — UI & Presentation |

---

## 📌 Roadmap

**Now (MVP)**
- Voice intake in 4 languages
- 24 scheme matching with confidence scores
- Document checklist + CSC pin + follow-up

**Next**
- 10+ languages + IVRS phone fallback
- ASHA worker companion app
- Application status tracking

**Future**
- CSC white-label API
- State government integration
- Pilot with Gram Vaani NGO
- Scheme gap analytics dashboard

---

## 📜 License

MIT — Built with ❤️ for India's 450 million informal workers.
