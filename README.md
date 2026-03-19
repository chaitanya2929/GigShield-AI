# GigShield AI 🛡️

## 🎥 Phase 1 Strategy Video

**[Watch our Strategy & Idea Pitch on Google Drive](https://drive.google.com/file/d/1wZEXMwtiGwuAiHDdw3YlAThXuXKnm6_3/view?usp=sharing)**

---

## AI-Powered Parametric Income Protection for Gig Delivery Workers

![Project Status](https://img.shields.io/badge/Project-Phase%201%20Ideation-blue)
![AI Powered](https://img.shields.io/badge/AI-Powered-green)
![Hackathon](https://img.shields.io/badge/Event-DEVTrails%202026-orange)

[cite_start]GigShield AI is an AI-powered parametric insurance platform designed to protect gig delivery workers from income loss caused by external disruptions such as heavy rain, pollution, floods, and curfews. [cite: 14]

[cite_start]Gig workers depend on daily earnings to sustain their livelihood. [cite: 15] [cite_start]When external disruptions occur, deliveries stop and workers instantly lose 20-30% of their income. [cite: 10] [cite_start]GigShield AI detects these disruptions using AI and external data sources and compensates workers through automated parametric insurance payouts. [cite: 15, 47]

Our mission is to build a financial safety net for the gig workforce.

---

# 📌 Project Overview

| Feature            | Description                                                               |
| :----------------- | :------------------------------------------------------------------------ |
| **Target Users**   | [cite_start]Food delivery workers (Swiggy / Zomato) [cite: 82]            |
| **Problem**        | [cite_start]Income loss due to weather, pollution, and curfews [cite: 80] |
| **Solution**       | [cite_start]AI-powered parametric insurance [cite: 79]                    |
| **Pricing Model**  | [cite_start]Weekly insurance plans [cite: 18, 85]                         |
| **AI Components**  | [cite_start]Risk prediction + fraud detection [cite: 34, 39]              |
| **Unique Feature** | Income Stability Score                                                    |
| **Architecture**   | MERN stack + Python AI engine                                             |

---

# 🛡️ MARKET CRASH: Adversarial Defense & Anti-Spoofing Strategy

_In response to the Phase 1 Market Crash identifying coordinated fraud rings and GPS spoofing._

To safeguard platform liquidity against sophisticated bad actors, GigShield AI implements a **Multi-Layered Validation Engine**:

- **Spatial-Temporal Fleet Coherence**: The AI cross-references an individual's GPS ping against the "Fleet Velocity" of 50+ other riders in the same 500-meter grid. If 95% of the fleet is moving while a claimant reports "halted deliveries," the claim is auto-flagged.
- [cite_start]**Hyper-Local Environmental Verification**: We utilize grid-based weather validation. [cite: 119] A "fake rainstorm" claim is instantly invalidated if our secondary high-resolution precipitation APIs (ClimaCell/OpenWeather) show rainfall below the 70mm threshold for that specific coordinate.
- **Hardware Sensor Fusion**: The system monitors device Accelerometer and Gyroscope data. While software can spoof coordinates, it rarely mimics the natural mechanical "jitter" and vibration of a moving vehicle, allowing the AI to distinguish between a real rider and a static fraud ring.
- **Behavioral Trust Scoring**: New accounts or devices with "Developer Options" enabled are subjected to a 24-hour verification delay, while veteran riders with high **Income Stability Scores** receive "Fast-Track" automated approval.

---

# 👤 Target Persona – Food Delivery Riders

[cite_start]We selected food delivery partners such as **Swiggy and Zomato** as our primary persona. [cite: 82]

### Worker Profile

- **Daily Earnings**: ₹800 – ₹1200
- **Deliveries per day**: 18–25
- **Working hours**: 8–10 hours

### Key Risks

- [cite_start]Heavy rain and flooding [cite: 25]
- [cite_start]Severe air pollution [cite: 25]
- [cite_start]Traffic shutdowns and curfews [cite: 25]

---

# 💰 Weekly Insurance Pricing Model

[cite_start]Gig workers operate on weekly earning cycles, so GigShield AI uses a weekly insurance model. [cite: 18, 85]

| Plan         | Weekly Premium | Income Protection |
| :----------- | :------------- | :---------------- |
| **Basic**    | ₹15/week       | ₹400 payout       |
| **Standard** | ₹25/week       | ₹700 payout       |
| **Premium**  | ₹40/week       | ₹1200 payout      |

[cite_start]**⚠ Coverage applies strictly to income loss only.** [cite: 17, 83]
[cite_start]The platform does **not** cover vehicle repairs, medical claims, or accident insurance. [cite: 17, 84]

---

# ⭐ Income Stability Score (Predictive AI)

GigShield AI introduces an **Income Stability Score**, an AI-generated metric (0–100) predicting income disruption risk.

**How the Score is Calculated:**

- Weather Risk (30%) + Traffic Risk (20%) + Demand Stability (30%) + Historical Disruptions (20%).

**Why This Feature Matters:**
Traditional systems react after disruptions occur. GigShield AI predicts risk **before disruptions happen**, allowing workers to proactively protect their income.

---

# 🏗 System Architecture

- **Frontend**: React / Next.js
- **Backend**: Node.js / Express
- **AI Engine**: Python (Scikit-learn)
- **Database**: MongoDB
- [cite_start]**External APIs**: Weather API, Traffic API, Platform Activity Mock, and Payment Sandbox. [cite: 52, 54, 59]

```mermaid
graph TD
A[Worker Mobile/Web App] --> B[Frontend - React / Next.js]
B --> C[Backend API - Node.js / Express]
C --> D[Database - MongoDB]
C --> E[AI Engine - Python ML Models]
C --> F[Weather API]
C --> G[Traffic API]
C --> H[Delivery Platform Activity Mock]
E --> I[Risk Prediction Model]
E --> J[Fraud Detection System]
C --> K[Claim Automation Engine]
K --> L[Payout System - Payment Sandbox]
L --> M[Worker Receives Compensation]
```
