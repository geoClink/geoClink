![Banner](https://geoclink.github.io/portfolio/assets/images/site/banner.png)

![Profile Views](https://komarev.com/ghpvc/?username=geoClink&color=blue&style=for-the-badge)
[![Open to Work](https://img.shields.io/badge/Open_to_Work-iOS_%26_Full_Stack-green?style=for-the-badge)](https://linkedin.com/in/george-clinkscales)

![Swift](https://img.shields.io/badge/Swift-F54A2A?style=for-the-badge&logo=swift&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Xcode](https://img.shields.io/badge/Xcode-147EFB?style=for-the-badge&logo=xcode&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white)
![Core ML](https://img.shields.io/badge/Core_ML-000000?style=for-the-badge&logo=apple&logoColor=white)

### iOS Engineer · Full-Stack Developer · Detroit

[![GitHub Streak](https://streak-stats.demolab.com?user=geoClink&hide_border=true)](https://git.io/streak-stats)
![geoClink's GitHub activity](https://ghchart.rshah.org/geoClink)

MSU Apple Developer Academy graduate. Three shipped App Store
apps, three merged open source PRs, and a full business OS live
across four clients verticals. Co-founder of CH Studios LLC,
contracted by Tripsetta for iOS, Android, and web development.

---

## Shipped Apps

### CoastCast — Michigan Beach Conditions App
> SwiftUI · FastAPI · CoreML · XGBoost · WidgetKit · App Intents

Real-time conditions for 54 Michigan beaches. FastAPI backend
fans out parallel requests to NWS and NDBC buoy APIs.
ML-powered Crowd Meter via XGBoost, converted to CoreML for
on-device inference. WidgetKit widget, Siri Shortcuts via
App Intents, Live Activities, and dark mode. Built with a
team of 5 at the Apple Developer Academy.

[![App Store](https://developer.apple.com/assets/elements/badges/download-on-the-app-store.svg)](https://apps.apple.com/us/app/coastcast/id6760917476)
[![GitHub](https://img.shields.io/badge/View_on_GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/jaidenhenley/MichiganAPIWeather)

---

### Stamped! — A City Passport
> SwiftUI · UserDefaults · CI/CD · Accessibility · App Store

Architectural landmark discovery app for iOS. Users collect
digital passport stamps as they explore buildings across cities.
Offline-first with VoiceOver, high contrast, reduce motion, and
haptic feedback. Localized into 8 languages. Includes an Apple
Intelligence itinerary planner (iOS 26+) and a live currency
converter.

[![App Store](https://developer.apple.com/assets/elements/badges/download-on-the-app-store.svg)](https://apps.apple.com/us/app/stamped-a-city-passport/id6759680336)
[![GitHub](https://img.shields.io/badge/View_on_GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/geoClink/Stamped-A-City-Passport)

---

### TakeFlight — Bird Survival Game
> SwiftUI · SpriteKit · SwiftData · Game Center · AVFoundation

5-in-1 survival game set on Belle Isle, Detroit. Custom SwiftUI
joystick normalizes DragGesture input for cross-platform support.
Game Center leaderboards and achievements. Built with a team of
5 at the Apple Developer Academy.

[![App Store](https://developer.apple.com/assets/elements/badges/download-on-the-app-store.svg)](https://apps.apple.com/us/app/takeflight-a-bird-life/id6758803964)
[![GitHub](https://img.shields.io/badge/View_on_GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/jaidenhenley/TakeFlight)

---

## CH Studios — Small Business Suite

### Knot — Small Business Operating System
> Node.js · Express · Supabase · Stripe · SwiftUI · Resend · Twilio · MCP Server

A full business OS competing with Toast, Square, and 7shifts —
customer website, 17-module admin dashboard, iOS customer app,
iOS POS, and an iOS employee scheduling app, all on one
Node/Express API and one Supabase database. Multi-tenant from
day one: every table carries a `tenant_id`, so onboarding a new
business is one database row and a frontend deploy. Currently
live across four client deployments.

[![Live Demo](https://img.shields.io/badge/Live_Demo-000000?style=for-the-badge&logo=safari&logoColor=white)](https://knot-landing-page.vercel.app)

---

### The Bakery Co. — Full-Stack Ordering Platform
> Node.js · Express · Supabase · Stripe · Resend · Twilio · MCP Server · WebMCP

Five-surface ordering platform: customer website, admin CMS,
iOS POS, iOS customer app, and an AI ordering layer.
Webhook-first payment flow — Stripe confirms before the order
is written to the database. Admin covers menu CMS, inventory,
orders, revenue analytics, gift cards, subscriptions, loyalty,
coupons, prep list, and staff management. MCP server lets
customers order through Claude; WebMCP integration shipped the
same week Google announced the W3C WebMCP standard at I/O 2026.
Lighthouse: 100 Accessibility · 100 Best Practices · 100 SEO.

[![Live Demo](https://img.shields.io/badge/Live_Demo-000000?style=for-the-badge&logo=safari&logoColor=white)](https://the-bakery-co.vercel.app)

---

### The Wellness Co. — Booking Platform
> Node.js · Express · Supabase · Stripe · Resend · Vercel

Full-stack booking platform for acupuncture and energy healing
practices. Webhook-driven — Stripe fires after payment clears,
then writes the appointment and sends confirmation via Resend.
UUID cancel tokens in confirmation emails enable self-serve
cancellation with tiered refunds (full beyond 48h, 50% inside,
none for no-shows), all executed server-side via the Stripe API.
Supabase Auth with JWT validation on every admin route.
Lighthouse: 100 Performance · 100 Accessibility · 100 SEO.

[![Live Demo](https://img.shields.io/badge/Live_Demo-000000?style=for-the-badge&logo=safari&logoColor=white)](https://the-wellness-co.vercel.app)

---

### The Sports Bar Co. — Reservations & Events Platform
> HTML · CSS · JavaScript · Node.js · Express · Supabase · Resend · Vercel

Reservations and events platform built as a direct alternative
to Toast and OpenTable. Table booking writes to Supabase and
sends confirmation emails via Resend. Events calendar pulls from
the database — owner adds or cancels without touching code.
Party and buyout inquiries route to the owner's inbox.

[![Live Demo](https://img.shields.io/badge/Live_Demo-000000?style=for-the-badge&logo=safari&logoColor=white)](https://the-sports-bar.vercel.app)

---

### The Salon Co. — Luxury Service Business Website
> HTML · CSS · JavaScript · Node.js · Express · Supabase · Vercel

Multi-page website for a luxury hair studio with services,
stylist profiles, gallery, booking flow, employment page, and
privacy policy. Scroll-based sticky header via
IntersectionObserver, auto-rotating reviews carousel, CSS
gallery filter system. No framework, no CMS.
Lighthouse: 100 Performance · 100 Accessibility · 100 SEO.

[![Live Demo](https://img.shields.io/badge/Live_Demo-000000?style=for-the-badge&logo=safari&logoColor=white)](https://the-salon-co.vercel.app)

---

## Projects

### Tally — Time Tracker
> Swift · SwiftUI · Catalyst · Apple Watch · React · Vite · Supabase · StoreKit · Stripe

Cross-platform SaaS for freelancers and small teams — native
iOS app (iPhone, Apple Watch, Mac via Catalyst) paired with a
React web dashboard on a shared Supabase backend. Buying Pro on
iOS unlocks the web: StoreKit and Stripe both write to the same
`is_pro` flag. Sessions stored in SwiftData for offline use.
Stripe webhooks, transactional email, and team invites run in
Supabase Edge Functions (Deno) — no Node server required.
$9.99 one-time vs. $10–20/month competitors.

[![Web App](https://img.shields.io/badge/Web_App-000000?style=for-the-badge&logo=safari&logoColor=white)](https://tally-web-nu.vercel.app)
[![GitHub](https://img.shields.io/badge/View_on_GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/geoClink/tally-web)

---

### Detroit Sports Chatbot — AI Sports Assistant
> Python · Streamlit · Claude API · Groq · ESPN API

AI chatbot with 15 ESPN tool integrations — live scores,
standings, injuries, and schedules across all four major
Detroit sports teams. Dual AI provider support (Claude + Groq)
with a prompt evaluation pipeline. Deployed on Render.

---

### RateChecker — Personal Finance iOS App
> SwiftUI · Core ML · Swift Charts · WidgetKit · SwiftData · FRED API

iOS app that benchmarks savings rates against live T-Bill yields
and inflation. On-device Core ML model forecasts the next T-Bill
rate using 14 economic indicators fetched in parallel from the
Federal Reserve and Treasury APIs. "My Money" dashboard shows
how much you're leaving on the table at a low-rate bank.
Background App Refresh with local notifications when rates shift.
VoiceOver accessible, 30+ unit tests.

[![GitHub](https://img.shields.io/badge/View_on_GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/geoClink/Savings-Calculator)

---

### SlotParking — Detroit Parking App
> SwiftUI · Firebase · Firestore · MapKit · Combine

Multi-role parking app for Detroit. Drivers browse live lot
availability, owners onboard through a multi-step flow,
attendants update counts in real time, admins approve listings.

[![GitHub](https://img.shields.io/badge/View_on_GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/geoClink/SlotParking)

---

## Open Source

Three merged pull requests across active open source projects:

- **Streamlit** — CSS-in-JS border-radius and overflow fixes
  for video and chart components
  [![PR](https://img.shields.io/badge/PR_%2314864-181717?style=flat&logo=github&logoColor=white)](https://github.com/streamlit/streamlit/pull/14864)

- **Handmade Network** — Refined project blog index logic for
  single-post states; audited typography utility classes
  [![PR](https://img.shields.io/badge/PR_%2337-181717?style=flat&logo=github&logoColor=white)](https://github.com/HandmadeNetwork/hmn/pull/37)

- **Tandoor Recipes** — Added missing Back button to the
  Ingredient Editor page, matching navigation patterns used
  across the Vue 3 app
  [![PR](https://img.shields.io/badge/PR_%234650-181717?style=flat&logo=github&logoColor=white)](https://github.com/TandoorRecipes/recipes/pull/4650)

---

## Tech Stack

**Mobile**
Swift · SwiftUI · UIKit · SpriteKit · SwiftData · Swift Charts ·
WidgetKit · Core ML · App Intents · MapKit · Firebase · Combine ·
Catalyst

**Web & Backend**
Node.js · Express · FastAPI · Python · Supabase · HTML · CSS ·
JavaScript · React · Vite · HTTPX · asyncio

**AI / ML**
XGBoost · Core ML · Create ML · Tabular Regression ·
Feature Engineering · Anthropic Claude API · MCP · WebMCP

**Payments, Messaging & Infra**
Stripe · StoreKit · Twilio · Resend · Render · Vercel ·
GitHub Actions · TestFlight

---

## Currently

- MSU Apple Developer Academy graduate, May 2026
- Co-founder, CH Studios LLC: contracted by Tripsetta (iOS,
  Android, web) for bug fixes, maintenance, and customer
  feedback implementation
- Open to iOS and full-stack roles
- Building in public on [LinkedIn](https://linkedin.com/in/george-clinkscales)

---

## Connect

[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=safari&logoColor=white)](https://geoclink.github.io/portfolio)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/george-clinkscales)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:1lclink2@att.net)
