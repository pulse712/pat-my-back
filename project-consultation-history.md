# Project Consultation History — Pat Pal App

## Project Overview

A counselor-client communication marketplace where clients pay to connect with available "Pat Pals" (counselors) via text, audio, or video. Clients browse available Pat Pals and initiate all contact. Pat Pals cannot see or search for clients.

---

## Client Profile

- Musician based in Texas, originally from India
- No technical background, uses AI tools (ChatGPT) to generate specs
- Family man — wife and 8 children, currently between jobs
- Long-term vision: 6+ app ideas, wants a lifelong engineering partner, open to equity deals
- Budget: $1,000 firm for MVP
- Warm, collaborative, business-minded (understands Apple fee tiers, tax implications)

---

## Project Analysis

### What the Project Actually Is
A paid counselor marketplace (think BetterHelp lite), not a WhatsApp clone. Clients subscribe or buy minute bundles to connect with Pat Pals for text, audio, or video sessions.

### Core Tension
| Client expects | $1,000 reality |
|---|---|
| iOS + Android + Web | PWA only |
| Text, audio, video calls | Achievable with Agora free tier |
| Stripe subscriptions | Basic checkout only |
| Full admin dashboard | Simple user management |
| Zero bugs at launch | MVP quality, not production polish |

### Market Price vs. Agreed Price
| Scope | Market Price | Agreed Price |
|---|---|---|
| Phase 1 (PWA full) | $8,700 – $25,000 | $1,000 |
| Phase 2 (Native apps) | $5,000 – $20,000 | $500 |
| Combined | $15,000 – $45,000 | $1,500 |

---

## Agreed Plan

### Phase 1 — $1,000 / PWA

**Platform**
- PWA installable on iPhone, Android, and Desktop

**Authentication**
- Registration and login with phone number + email
- Email verification
- Password reset
- Role-based access (client / Pat Pal / admin)

**Pat Pal Discovery**
- Pat Pal sets availability status (Available / Busy / Offline)
- Clients browse available Pat Pals with name, photo, short bio
- Pat Pals cannot browse or search clients

**Communication**
- Real-time text chat
- One-to-one audio calls (Agora free tier)
- One-to-one video calls (Agora free tier)

**Payments**
- Stripe — one plan, subscription or bundle to unlock access

**Admin Panel**
- View and manage all users
- Activate / deactivate accounts

**Deployment**
- Vercel + Firebase hosting
- Custom domain + HTTPS

---

### Phase 2 — $500 / Native Apps

- Convert PWA to native iOS and Android apps
- App Store (Apple) submission
- Google Play Store submission
- Push notifications for messages and calls
- Basic call history
- View active subscriptions in admin

---

## Tech Stack

| Layer | Technology | Reason |
|---|---|---|
| Frontend | React Native + Expo | Single codebase for PWA and native apps |
| Backend | Firebase | Auth, real-time chat, push notifications, free tier |
| Audio/Video | Agora (free tier) | 10,000 free minutes/month, works on PWA and native |
| Payments | Stripe | Web checkout for PWA, SDK for native |
| Hosting | Vercel + Firebase Hosting | Free tier, fast deployment |
| Admin | React web app | Separate lightweight dashboard |

---

## Warranty & Pricing Terms

- **Warranty:** 30 days after delivery
- **Covers:** Bugs in agreed features, broken functionality at delivery
- **Excludes:** New features, third-party service outages, post-scope change requests
- **Ongoing rate:** $50/hour for new features after MVP
- **Fixed quotes** provided before starting any new feature

---

## Phase 3+ Roadmap (future, funded by revenue)

| Phase | Features | Est. Cost |
|---|---|---|
| Phase 3 | Live session countdown, minute bundles, Add Time mid-session Stripe top-up | $1,500 – $2,000 |
| Phase 4 | Promotions engine, discount codes, referral rewards | $1,000 – $1,500 |
| Phase 5 | Pat Pal payouts via Stripe Connect, multiple plans | $1,000 – $1,500 |
| Phase 6 | Full analytics dashboard, ratings, reviews, scheduling | $2,000 – $3,000 |

---

## Client Requirements Before Start

### Must Have on Day 1
- 50% deposit ($500)
- App name and logo
- Stripe account (business name, connected and ready)
- Agora account (free — agora.io)

### Needed Before Launch (not Day 1)
- Apple Developer account ($99/year)
- Google Play Developer account ($25 one-time)
- Firebase account (free — I'll help set up)
- Legal terms and privacy policy
- Final app color scheme or brand guidelines

---

## Key Decisions Log

| Decision | Detail |
|---|---|
| Platform name for counselors | "Pat Pals" throughout the app |
| Auth method | Phone number + email, both verified |
| Call provider | Agora free tier |
| Phase 1 platform | PWA (mobile-responsive, installable on home screen) |
| Phase 2 platform | Native iOS + Android, App Store + Play Store submission |
| Hosting | Vercel + Firebase (free tier) |
| No VPS | Adds 8–12 hrs setup cost, not worth it at MVP stage |
| Web-first strategy | Push users to web payments to avoid Apple 15–30% fee |
| Account ownership | All accounts (Stripe, Firebase, Agora, domains, stores) owned by client's business |

---

## Conversation Status

- Client verbally committed to working together
- Final agreement pending — client taking one more day to discuss with wife
- Budget confirmed at $1,000 for Phase 1 PWA
- Client to send logo and legal terms when ready to start
- Long-term partnership discussed — potential equity arrangement mentioned by client

---

*Last updated: Active consultation*
