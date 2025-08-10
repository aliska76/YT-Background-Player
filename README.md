# YT-Background-Player

A React Native mobile application that enables background audio playback of YouTube videos with built-in AdBlock support.  
Ideal for listening to YouTube content like audiobooks or music while using other apps.

---

## Features

- Play YouTube videos with audio continuing in the background  
- Block ads for uninterrupted playback using custom AdBlock filters  
- Simple UI with embedded WebView for browsing YouTube  
- Background media controls via notification shade and hardware buttons  
- Built with React Native and TypeScript for robust, maintainable code  
- Modular architecture with React hooks, Redux (optional), and native media player integration  

---

## Why React Native?

This app leverages React Native to combine the power of native mobile capabilities with the flexibility and familiarity of React and TypeScript.  
You get near-native performance, access to background audio APIs, and smooth media control integration.

---

## Getting Started

### Prerequisites

- Node.js (>=14.x) and npm or yarn  
- Android Studio with SDK and emulator or a physical Android device with USB debugging enabled  
- React Native CLI  

### Installation

```bash
git clone https://github.com/yourusername/yt-background-player.git
cd yt-background-player
npm install
# or
yarn install
```

### Running on Android

Start Android emulator or connect a physical device via USB (with USB Debugging enabled).

Run the app: 
```bash
npx react-native run-android
```

### Building a Release APK

Follow the Android Studio instructions or run:
```
cd android
./gradlew assembleRelease
```

The signed APK will be located at:
android/app/build/outputs/apk/release/app-release.apk

### Technologies Used
* React Native with TypeScript

* react-native-webview

* react-native-track-player for background audio

* Custom AdBlock filters (EasyList-based)

### Future Improvements
* Add iOS support with background playback

* Implement OAuth for authenticated YouTube access

* Enhanced UI/UX with playlists and history

* Automated CI/CD pipeline for building and releasing

