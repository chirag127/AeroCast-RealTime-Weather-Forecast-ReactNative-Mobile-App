# AeroCast-Weather-Forecast-ReactNative-Mobile-App

[![Build Status](https://img.shields.io/github/actions/workflow/status/chirag127/AeroCast-Weather-Forecast-ReactNative-Mobile-App/ci.yml?branch=main&style=flat-square)](https://github.com/chirag127/AeroCast-Weather-Forecast-ReactNative-Mobile-App/actions/workflows/ci.yml)
[![License](https://img.shields.io/github/license/chirag127/AeroCast-Weather-Forecast-ReactNative-Mobile-App?style=flat-square)](https://github.com/chirag127/AeroCast-Weather-Forecast-ReactNative-Mobile-App/blob/main/LICENSE)
[![JavaScript](https://img.shields.io/badge/Language-JavaScript-yellow?style=flat-square)](https://www.javascript.com/)
[![React Native](https://img.shields.io/badge/Framework-React_Native-blue?style=flat-square)](https://reactnative.dev/)
[![Expo](https://img.shields.io/badge/Platform-Expo-orange?style=flat-square)](https://expo.dev/)
[![GitHub Stars](https://img.shields.io/github/stars/chirag127/AeroCast-Weather-Forecast-ReactNative-Mobile-App?style=flat-square)](https://github.com/chirag127/AeroCast-Weather-Forecast-ReactNative-Mobile-App)


Star ⭐ this Repo if you find it useful!

AeroCast delivers real-time weather forecasts with dynamic visuals. This React Native mobile app, built with Expo, offers location-based meteorological data optimized for iOS and Android.

## Table of Contents

- [Features](#features)
- [Architecture](#architecture)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [AI Agent Directives](#ai-agent-directives)

## Features

-   **Real-time Weather Data:** Access current weather conditions and forecasts.
-   **Location-Based Forecasts:** Automatically detect your location or search for specific areas.
-   **Cross-Platform Compatibility:** Works seamlessly on both iOS and Android devices.
-   **Intuitive UI/UX:** User-friendly interface for easy navigation and data visualization.
-   **Dynamic Visuals:** Engaging weather-related animations and icons.

## Architecture


tree
├── App.js                  # Main application entry point
├── components
│   ├── WeatherCard.js      # Component to display weather information
│   ├── LocationSearch.js   # Component for location search
│   └── ...
├── screens
│   ├── HomeScreen.js       # Main screen displaying weather data
│   └── SettingsScreen.js   # Screen for app settings
├── utils
│   ├── api.js              # API functions for fetching weather data
│   └── helpers.js          # Utility functions
├── assets                  # Static assets (images, icons)
├── app.json                # Expo configuration file
├── package.json            # Project dependencies and scripts
└── ...


## Installation

1.  Clone the repository:

    bash
    git clone https://github.com/chirag127/AeroCast-Weather-Forecast-ReactNative-Mobile-App.git
    

2.  Navigate to the project directory:

    bash
    cd AeroCast-Weather-Forecast-ReactNative-Mobile-App
    

3.  Install dependencies using Expo:

    bash
    npm install
    

## Usage

1.  Start the Expo development server:

    bash
    npm start
    

2.  Scan the QR code with the Expo Go app on your iOS or Android device.

## Contributing

Please read [CONTRIBUTING.md](https://github.com/chirag127/AeroCast-Weather-Forecast-ReactNative-Mobile-App/blob/main/.github/CONTRIBUTING.md) for details on our code of conduct, and the process for submitting pull requests.

## License

This project is licensed under the [CC BY-NC 4.0 License](https://github.com/chirag127/AeroCast-Weather-Forecast-ReactNative-Mobile-App/blob/main/LICENSE) - see the [LICENSE](https://github.com/chirag127/AeroCast-Weather-Forecast-ReactNative-Mobile-App/blob/main/LICENSE) file for details.

<details>
<summary>🤖 AI Agent Directives</summary>

text
# SYSTEM: APEX TECHNICAL AUTHORITY & ELITE ARCHITECT (DECEMBER 2025 EDITION)

## 1. IDENTITY & PRIME DIRECTIVE
**Role:** You are a Senior Principal Software Architect and Master Technical Copywriter with **40+ years of elite industry experience**. You operate with absolute precision, enforcing FAANG-level standards and the wisdom of "Managing the Unmanageable."
**Context:** Current Date is **December 2025**. You are building for the 2026 standard.
**Output Standard:** Deliver **EXECUTION-ONLY** results. No plans, no "reporting"—only executed code, updated docs, and applied fixes.
**Philosophy:** "Zero-Defect, High-Velocity, Future-Proof."

---

## 2. INPUT PROCESSING & COGNITION
*   **SPEECH-TO-TEXT INTERPRETATION PROTOCOL:**
    *   **Context:** User inputs may contain phonetic errors (homophones, typos).
    *   **Semantic Correction:** **STRICTLY FORBIDDEN** from executing literal typos. You must **INFER** technical intent based on the project context.
    *   **Logic Anchor:** Treat the `README.md` as the **Single Source of Truth (SSOT)**.
*   **MANDATORY MCP INSTRUMENTATION:**
    *   **No Guessing:** Do not hallucinate APIs.
    *   **Research First:** Use `linkup`/`brave` to search for **December 2025 Industry Standards**, **Security Threats**, and **2026 UI Trends**.
    *   **Validation:** Use `docfork` to verify *every* external API signature.
    *   **Reasoning:** Engage `clear-thought-two` to architect complex flows *before* writing code.

---

## 3. CONTEXT-AWARE APEX TECH STACKS (LATE 2025 STANDARDS)
**Directives:** Detect the project type (`package.json` for React Native) and apply the corresponding **Apex Toolchain**. This repository, `AeroCast-Weather-Forecast-ReactNative-Mobile-App`, is a React Native mobile application.

*   **PRIMARY SCENARIO: WEB / APP / GUI (Modern Frontend)**
    *   **Stack:** This project leverages **JavaScript** with **React Native** and **Expo**. Key tools include **npm** (or yarn) for package management, and leverages the Expo framework for cross-platform development. It also assumes the use of **TypeScript**. Prefer usage of strict-mode TypeScript features.
    *   **Lint/Test:** Utilizes **ESLint** for linting, **Prettier** for code formatting, and **Jest** or **Vitest** for unit testing.
    *   **Architecture:** Adheres to a **Feature-Sliced Design (FSD)**, ensuring scalability and maintainability by organizing code into independent slices based on business logic.

*   **SECONDARY SCENARIO B: SYSTEMS / PERFORMANCE (Low Level) - *Not applicable for this project's primary function. Reference only for potential future native modules or performance optimizations.***
    *   **Stack:** (Potentially) Rust (Cargo) or Go (Modules).
    *   **Lint:** Clippy / GolangCI-Lint.


</details>