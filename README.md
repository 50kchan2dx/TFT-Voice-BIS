# TFT Voice BIS (Minimum Viable Product)

## 🎯 Overview
TFT Voice BIS is a voice-controlled companion app for Teamfight Tactics designed as an Overwolf overlay. 
Our core value is providing players with optimal item compositions (Best In Slot) entirely hands-free. Unlike traditional stat websites, this app does not disrupt the player's APM (Actions Per Minute) or visual focus during intense gameplay.

## 🎥 Demo Video
[Watch the Demo on YouTube](https://youtu.be/9t6M66c75pc)

## ⚙️ How It Works
1. **Voice Activation:** The user inputs a champion name and items via microphone.
2. **Instant Overlay:** The app instantly unfolds a minimal overlay displaying the best statistical compositions (filtered for Master+ tier).
3. **Seamless Hide:** The overlay can be instantly toggled via a customizable hotkey, keeping the game screen clean and APM entirely uninterrupted without requiring arbitrary mouse clicks.
4. **Manual Fallback:** In addition to voice commands, the app fully supports manual unit and item selection for precise control.

## 📊 Data Architecture & Roadmap
- **Current Phase (MVP / Concept Validation):** We are currently validating the ultra-low latency voice UI and UX. For this phase, we are referencing third-party statistical data to ensure the UI behaves correctly with real-world TFT variance.
- **Production Phase:** Upon approval of the New Product Application and issuance of a Production API Key, the architecture will fully migrate. We will establish a dedicated backend to pull raw data directly from the Riot Match API and aggregate Master+ item statistics internally.

## ⚖️ Legal Disclaimer
TFT Voice BIS is not endorsed by Riot Games and does not reflect the views or opinions of Riot Games or anyone officially involved in producing or managing Riot Games properties. Riot Games and all associated properties are trademarks or registered trademarks of Riot Games, Inc.
