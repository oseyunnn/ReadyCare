# ReadyCare

**Naga Mayoral Hackathon Entry by O(1) Developers**

ReadyCare is an AI-powered health support and emergency assistance mobile application developed for the Naga Mayoral Hackathon.
It helps individuals quickly understand health concerns, connect with appropriate medical professionals, and respond effectively during emergencies—especially in communities with limited access to healthcare and low health literacy.

**Disclaimer:**
ReadyCare does not replace doctors or licensed medical professionals. It serves as a support system to help users decide what to do next, who to contact, and how to act during health-related situations.

---

## Problem Statement

Many people experience injuries, symptoms, or health emergencies but often:

* Do not know if their condition is serious
* Do not know which doctor to consult
* Delay seeking care due to confusion or lack of access
* Panic during emergencies and do not know what to do first

This problem is more common among:

* Seniors
* Low-income communities
* Users with low reading comprehension
* Areas with limited healthcare access

---

## Proposed Solution

ReadyCare combines AI-assisted health guidance, doctor access, and emergency support in one platform.

The app allows users to:

* Ask health-related questions using simple, easy-to-understand language
* Identify the appropriate medical professional
* Receive step-by-step emergency instructions
* Quickly access emergency hotlines

---

## Features

* AI health chatbot for symptom guidance
* Photo-based injury and wound analysis
* Doctor access, filtering, and appointment booking
* One-tap emergency hotline access
* Step-by-step emergency response guidance
* Online and offline functionality
* Multi-lingual support
* Recommendations for accessible pharmacies and health brands

---

## Tech Stack

### Front-end

* React Native (Expo)
  Used to build the mobile interface and access native device features such as camera and GPS.

### Back-end

* Firebase Authentication
  Handles secure login via phone number (OTP) or Google account.

* Firebase Cloud Functions
  Serverless backend logic connecting the app to AI services and emergency systems.

### Database

* Cloud Firestore
  NoSQL database with offline persistence to ensure usability during poor connectivity.

### AI & Intelligence

* Azure AI Foundry (GPT-4o)
  Powers the health chatbot and visual symptom analysis with built-in safety filters.

### DevOps & Deployment

* GitHub for version control and collaboration
* Expo Application Services (EAS) for APK builds
* Vercel for landing page and download portal hosting

---

## Getting Started

### Prerequisites

* Node.js
* Expo CLI
* Firebase project configuration

### Installation

```bash
git clone https://github.com/your-username/readycare.git
cd readycare
npm install
```

### Run the App

```bash
npx expo start
```

---

## Target Users

* Seniors
* Low-income communities
* Individuals with limited health literacy
* Areas with limited healthcare access


* Add a **demo/screenshots section**
* Tighten the wording even more
