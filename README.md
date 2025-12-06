# AeroCast-Weather-Forecast-ReactNative-Mobile-App

[![Build Status](https://img.shields.io/github/actions/workflow/status/chirag127/AeroCast-Weather-Forecast-ReactNative-Mobile-App/ci.yml?branch=main&style=flat-square)](https://github.com/chirag127/AeroCast-Weather-Forecast-ReactNative-Mobile-App/actions/workflows/ci.yml)
[![License](https://img.shields.io/github/license/chirag127/AeroCast-Weather-Forecast-ReactNative-Mobile-App?style=flat-square)](https://github.com/chirag127/AeroCast-Weather-Forecast-ReactNative-Mobile-App/blob/main/LICENSE)
[![JavaScript](https://img.shields.io/badge/Language-JavaScript-yellow.svg?style=flat-square)](https://www.javascript.com/)
[![ReactNative](https://img.shields.io/badge/Framework-ReactNative-blue.svg?style=flat-square)](https://reactnative.dev/)
[![Expo](https://img.shields.io/badge/Platform-Expo-lightgrey.svg?style=flat-square)](https://expo.dev/)
[![GitHub Stars](https://img.shields.io/github/stars/chirag127/AeroCast-Weather-Forecast-ReactNative-Mobile-App?style=flat-square)](https://github.com/chirag127/AeroCast-Weather-Forecast-ReactNative-Mobile-App/stargazers)


Real-time weather forecasts at your fingertips. AeroCast delivers dynamic visuals and location-based meteorological data optimized for iOS & Android.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Architecture](#architecture)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [AI Agent Directives](#ai-agent-directives)

## Overview

AeroCast is a cross-platform mobile application built using React Native and Expo, providing users with up-to-date weather information. With a focus on intuitive UI/UX and performance, AeroCast offers a seamless experience for accessing weather forecasts on both iOS and Android devices.

## Features

-   **Real-time Weather Data:** Accurate and current weather information.
-   **Location-Based Forecasts:** Weather data tailored to the user's current location.
-   **Dynamic Visuals:** Engaging and informative weather visualizations.
-   **Cross-Platform Compatibility:** Optimized for both iOS and Android.
-   **Intuitive UI/UX:** User-friendly interface for easy navigation.

## Architecture


├── App.js                # Main application component
├── components/
│   ├── WeatherCard.js      # Displays weather information
│   └── Location.js         # Handles location services
├── screens/
│   ├── HomeScreen.js       # Main screen of the app
│   └── SettingsScreen.js   # App settings
├── utils/
│   ├── api.js            # API calls to weather services
│   └── helpers.js        # Helper functions
├── assets/
│   ├── icons/            # Weather icons
│   └── fonts/            # Custom fonts
├── app.json              # Expo configuration file
└── ...


## Getting Started

### Prerequisites

-   Node.js (version 18 or higher)
-   npm or yarn
-   Expo CLI (`npm install -g expo-cli`)

### Installation

1.  Clone the repository:

    bash
    git clone https://github.com/chirag127/AeroCast-Weather-Forecast-ReactNative-Mobile-App.git
    cd AeroCast-Weather-Forecast-ReactNative-Mobile-App
    

2.  Install dependencies:

    bash
    npm install
    # or
    yarn install
    

## Usage

1.  Start the Expo development server:

    bash
    npm start
    # or
    yarn start
    

2.  Scan the QR code with the Expo Go app (available on iOS and Android) to run the application on your mobile device or emulator.

## Contributing

Contributions are welcome! Please read the [contributing guidelines](https://github.com/chirag127/AeroCast-Weather-Forecast-ReactNative-Mobile-App/blob/main/.github/CONTRIBUTING.md) before submitting a pull request.

## License

This project is licensed under the [CC BY-NC 4.0 License](https://creativecommons.org/licenses/by-nc/4.0/).

## AI Agent Directives

<details>
  <summary>Expand for AI Agent Information</summary>

  ### SYSTEM: APEX TECHNICAL AUTHORITY & ELITE ARCHITECT (DECEMBER 2025 EDITION)

  #### 1. IDENTITY & PRIME DIRECTIVE
  **Role:** You are a Senior Principal Software Architect and Master Technical Copywriter with **40+ years of elite industry experience**. You operate with absolute precision, enforcing FAANG-level standards and the wisdom of "Managing the Unmanageable."
  **Context:** Current Date is **December 2025**. You are building for the 2026 standard.
  **Output Standard:** Deliver **EXECUTION-ONLY** results. No plans, no "reporting"—only executed code, updated docs, and applied fixes.
  **Philosophy:** "Zero-Defect, High-Velocity, Future-Proof."

  ### 2. INPUT PROCESSING & COGNITION
    *   **SPEECH-TO-TEXT INTERPRETATION PROTOCOL:**
        *   **Context:** User inputs may contain phonetic errors (homophones, typos).
        *   **Semantic Correction:** **STRICTLY FORBIDDEN** from executing literal typos. You must **INFER** technical intent based on the project context.
        *   **Logic Anchor:** Treat the `README.md` as the **Single Source of Truth (SSOT)**.
    *   **MANDATORY MCP INSTRUMENTATION:**
        *   **No Guessing:** Do not hallucinate APIs.
        *   **Research First:** Use `linkup`/`brave` to search for **December 2025 Industry Standards**, **Security Threats**, and **2026 UI Trends**.
        *   **Validation:** Use `docfork` to verify *every* external API signature.
        *   **Reasoning:** Engage `clear-thought-two` to architect complex flows *before* writing code.

  ### 3. CONTEXT-AWARE APEX TECH STACKS (LATE 2025 STANDARDS)
  **Directives:** Detect the project type (`app.json` and package.json indicate React Native/Expo) and apply the corresponding **Apex Toolchain**.

  *   **PRIMARY SCENARIO: WEB / APP / GUI (Modern Frontend)**
    *   **Stack:** This project leverages **JavaScript** with **React Native** and **Expo**. Future migrations should target **TypeScript (Strict), Vite, TailwindCSS v4, Tauri v2**.
    *   **Lint/Test:** Current projects use ESLint or similar. Future projects should leverage **Biome (Speed) + Vitest (Unit) + Playwright (E2E)** for robust testing.
    *   **Architecture:** Feature-Sliced Design (FSD).

  ### 4. DEVELOPMENT STANDARDS
  *   **Principles:** SOLID, DRY, YAGNI.
  *   **Verification Commands:**
    *   `npm install` to install dependencies.
    *   `npm start` to start the Expo development server.
  
</details>

Star ⭐ this repo if you found it helpful!
