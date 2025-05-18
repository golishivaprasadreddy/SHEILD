---

# SHEILD - Women Safety App (Offline + Voice Activation)

*SHEILD* is a women safety mobile app built using *React Native, designed to send emergency alerts and location info even **without internet. It supports **voice activation*, allowing users to trigger SOS silently and hands-free using a custom voice command.

## Features

- *Offline Emergency Alerts*  
  Sends SOS messages via SMS without needing internet.

- *Voice Activation*  
  Trigger emergency alerts with a predefined voice keyword for hands-free safety.

- *One-Tap SOS Button*  
  Instantly notifies emergency contacts and shares your location.

- *Location Sharing via SMS*  
  Uses GPS to send real-time coordinates during emergencies.

- *Built-in Safety Tools*
  - Flashlight toggle  
  - Loud siren sound  
  - Quick call to emergency number

## Tech Stack

- *React Native*
- *React Native Voice* (for speech recognition)
- *React Native SMS / react-native-sms* (for offline SMS)
- *React Native Geolocation / Location API*
- *React Native Sound / Vibration*
- *React Native Permissions*

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/golishivaprasadreddy/SHEILD.git
   cd SHEILD

2. Install dependencies:

npm install


3. For iOS (Mac only):

cd ios && pod install
cd ..


4. Run the app:

npx react-native run-android
# or for iOS
npx react-native run-ios



> Note: Make sure to enable permissions (location, SMS, microphone) in both the app and device settings.



Setup Voice Activation

1. Configure a keyword (e.g., “help” or “emergency”).


2. The app continuously listens for this command when enabled.


3. On detection, the SOS workflow is triggered.



Permissions Required

Location (GPS)

Microphone (for voice commands)

SMS (to send messages offline)

Phone (to place emergency calls)


Contributing

We welcome contributions! Please fork the repo, open issues, or submit pull requests to improve SHEILD.

License

This project is licensed under the MIT License.


---

Stay Safe. Be Empowered. Use SHEILD.

---

Let me know if you want me to add specific usage instructions, sample screenshots, or Firebase setup if you're using it for background features.
