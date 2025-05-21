# SHEILD - Women Safety App (Offline + Voice Activation)

**SHEILD** is a women’s safety mobile app built with **React Native**. It can send emergency alerts and location information even **without internet access**. It also supports **voice activation**, allowing users to trigger SOS silently and hands-free with a custom voice command.

--- 

## Features

- **Offline Emergency Alerts**  
  Sends SOS messages via SMS without needing internet.

- **Voice Activation**  
  Trigger emergency alerts with a predefined voice keyword for hands-free safety.

- **One-Tap SOS Button**  
  Instantly notifies emergency contacts and shares your location.

- **Location Sharing via SMS**  
  Uses GPS to send real-time coordinates during emergencies.

- **Built-in Safety Tools**
  - Flashlight toggle  
  - Loud siren sound  
  - Quick call to emergency number

---

## Tech Stack

- React Native
- [react-native-voice](https://github.com/react-native-voice/voice) (speech recognition)
- [react-native-sms](https://github.com/tkporter/react-native-sms) (offline SMS)
- React Native Geolocation / Location API
- React Native Sound / Vibration
- React Native Permissions

---

## Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/golishivaprasadreddy/SHEILD.git
   cd SHEILD
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **For iOS (Mac only):**
   ```bash
   cd ios && pod install
   cd ..
   ```

4. **Run the app:**
   ```bash
   npx react-native run-android
   # or for iOS
   npx react-native run-ios
   ```

> **Note:** Make sure to enable permissions (location, SMS, microphone) in both the app and device settings.

---

## Setup Voice Activation

1. Configure a keyword (e.g., “help” or “emergency”).
2. The app continuously listens for this command when enabled.
3. On detection, the SOS workflow is triggered.

---

## Permissions Required

- Location (GPS)
- Microphone (for voice commands)
- SMS (to send messages offline)
- Phone (to place emergency calls)

---

## Contributing

We welcome contributions! Please fork the repo, open issues, or submit pull requests to improve SHEILD.

---

## License

This project is licensed under the MIT License.

---

**Stay Safe. Be Empowered. Use SHEILD.**
