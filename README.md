# 💡 Health Insurance AI Assistant — MedicalInsurance Frontend

A cross-platform, user-centric frontend that transforms health and fitness data into a seamless, gamified insurance journey. Built with Next.js (web) and React Native (mobile), it delivers instant, personalized insurance recommendations and rewards healthy users with real benefits.

## 🏷️ Overview

**MedicalInsurance** is the frontend for the Health Insurance AI Assistant platform, designed to:

- Personalize insurance onboarding using real-time fitness and health data.
- Offer dynamic policy recommendations and add-ons based on user lifestyle.
- Gamify the insurance experience, rewarding healthy behavior with tangible benefits.
- Seamlessly integrate with fitness APIs and insurance backend services.

This platform bridges the gap between digital health and insurance, empowering users to unlock better coverage and rewards through healthy living[1].

## ✨ Features

- **Next.js Web App:** Fast, statically rendered policy pages for instant load and SEO.
- **React Native Mobile App:** Unified codebase for Android and iOS.
- **Interactive Chatbot:** AI-powered assistant to guide users and answer insurance queries.
- **Fitness API Integration:** Syncs with Google Fit (mocked, easily swappable for Samsung Health/Fitbit).
- **Dynamic Policy Customization:** Add-ons like free check-ups or reduced PED waiting periods unlock as users improve their health score.
- **Gamified Insurance Journey:** Leaderboards, streaks, and coupon rewards for healthy activity.
- **Seamless Onboarding:** Minimal friction, maximizing engagement and conversion.

## 🏗️ Architecture

- **Frontend:** Next.js (web), React Native (mobile)
- **Backend:** ExpressBackend (auth, profile, fitness ingestion)
- **AI/ML:** GenAI FastAPI (chat, orchestration), ML microservices (health scoring)
- **Fitness Data:** Google Fit SDK (mocked for demo), ready for Samsung Health/Fitbit[1]

## ⚙️ Tech Stack

- **Next.js 14** (web)
- **React Native (Expo)** (mobile)
- **TypeScript** (shared logic)
- **Tailwind CSS** (web UI)
- **React Query, Zustand** (state management)
- **Custom UI Design System** (monorepo packages)
- **API Integration:** Axios/fetch for backend comms

## 🧭 User Journey

1. **Onboard:** Quick sign-up, sync fitness data with one tap.
2. **Chat & Explore:** Ask questions, get personalized policy advice from the GenAI chatbot.
3. **Customize Policy:** Adjust add-ons and see benefits update in real time.
4. **Gamify:** Earn rewards for healthy behavior—leaderboards, streaks, and coupon unlocks.
5. **Checkout:** Purchase or update policy with instant feedback.

## ⚡ Getting Started

Clone the repository:

```bash
git clone https://github.com/jaynabp/Health-insurance-AI-assistant-MedicalInsurance.git
cd Health-insurance-AI-assistant-MedicalInsurance
```

Install dependencies:

```bash
pnpm install  # or yarn / npm
```

### Web

```bash
pnpm run dev  # http://localhost:3000
```

### Mobile

```bash
pnpm expo start  # Scan QR with Expo Go
```

## 🗂️ Project Structure

```
apps/
 ├── web/        # Next.js 14 app
 └── mobile/     # React Native (Expo) app
packages/
 ├── ui/         # Shared design system components
 ├── hooks/      # React Query + Zustand stores
 └── utils/      # API clients, schema validators
```

## 🔧 Configuration

Create `.env.local` (web) or `.env` (mobile):

```
NEXT_PUBLIC_API_BASE=http://localhost:4000
EXPO_PUBLIC_API_BASE=http://:4000
```

- Point to your running backend for full-stack integration.

## 🚀 Deployment

### Web (Static Export)

```bash
pnpm run build && pnpm next export
```

### Mobile (Expo)

```bash
pnpm expo build:android   # or build:ios
```

## 🤝 Contributing

We welcome issues, pull requests, and design feedback!  
Please open an issue or submit a PR to help us improve.

## 📄 License

MIT License © 2025 [jaynabp](https://github.com/jaynabp)

> **Empowering a new era of personalized, preventive, and gamified health insurance — seamlessly connecting your fitness journey to real-world insurance benefits.**  
