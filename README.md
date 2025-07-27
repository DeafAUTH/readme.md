# introduction

DeafAUTH is still in active development, integrating:
	•	🔁 Clerk (frontend identity management + passkey)
	•	🔐 OAuth2 (for partner / VR-level SSO)
	•	🧩 Supabase Auth (initial quick access & admin control)
	•	🔥 Firebase Auth (for scalable, government-compliant identity systems)
	•	🧏‍♀️ Custom Deaf UI (no audio dependency, ASL-first UX)

⸻

🛠️ Here’s an updated, WIP-focused README that reflects that hybrid architecture:

# 🔐 DeafAUTH – Secure Identity for the Deaf-First Web

> Work-in-Progress | Deaf-led, multi-authentication system built for transparency, trust, and accessibility.

---

## ⚙️ In Development

**DeafAUTH** is a multi-tenant, passkey-compatible, government-compliant identity platform under active development — designed to empower:

- 🎯 Deaf Creators
- 🏛 Public & Government Platforms
- 🤝 Vocational Rehab & Partner Agencies
- 🧑‍💻 Developers in the MBTQ Universe

---

## 🌐 Vision

We’re building a **decentralized identity system** that:

- 🧏‍♀️ Works beautifully for Deaf users (no audio requirements)
- 🧿 Issues Fibonrose trust badges
- 🔐 Supports biometric, OAuth, and SSO auth
- 🧠 Connects with PinkSync for real-time agent triggers

---

## 🧱 Current Tech Stack (in process)

| Layer             | Tech                                         |
|------------------|----------------------------------------------|
| **Frontend Auth** | [Clerk.dev](https://clerk.mbtq.dev)              |
| **Backend Auth**  | Supabase Auth + Firebase Hybrid             |
| **SSO**           | Google SSO + OAuth2 for gov/enterprise      |
| **Infra**         | Vercel, Google Cloud Run                    |
| **UI/UX**         | Deaf-first design, ASL prompts, no CAPTCHAs |

---

## 📦 Modules Planned

- [x] Email/password login with Supabase
- [x] Google OAuth (manual + Clerk-native)
- [ ] Firebase fallback identity logic
- [ ] Passkey (WebAuthn via Clerk or custom)
- [ ] Role-based access (RBAC for agency vs client)
- [ ] Custom ASL onboarding experience

---

## 🚧 Status

✅ Initial setup done  
🔁 Auth providers being tested in dev/staging  
🔒 Working on compliance for public/government platforms  
🎨 Deaf-First UI is prototyped in MBTQ.dev's design repo  

---

## 🧪 Dev Preview

Live Preview: https://deafauth.mbtq.dev

---

## 🧏🏽 Why DeafAUTH?

Because most platforms fail Deaf users:

- ❌ CAPTCHA, audio verification = inaccessible
- ❌ No sign-language guidance
- ❌ No shared identity for creator/VR/client ecosystems

We’re fixing that — with **clarity**, **trust**, and **magician-level UX**.

---

## 💬 Contact

Want to co-develop, test, or integrate?

📩 pinky@mbtq.dev 
🌍 https://deafauth.mbtq.dev  
🔐 Repo: https://github.com/pinkycollie/deafauth  

---

 "_A login screen shouldn’t lock out a culture.”_ – Pinky Collie

