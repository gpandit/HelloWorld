# HelloWorld

A minimal [Expo](https://expo.dev/) app configured to run the same React Native experience on Android, iOS, and the web.

## Prerequisites
- Node.js 18+
- [Expo CLI](https://docs.expo.dev/more/expo-cli/) (`npm install -g expo-cli`)
- Android Studio (for Android emulator) or Xcode (for iOS Simulator) if you want to run locally on devices/emulators.

## Scripts
- `npm install` — install dependencies.
- `npm start` — start the Expo development server (choose platform from the interactive menu).
- `npm run android` — launch on Android emulator or connected device.
- `npm run ios` — launch on iOS simulator or device (macOS with Xcode required).
- `npm run web` — launch the web portal in a browser.

## Known issues
- In this environment `npm install` fails with `403 Forbidden` responses from the public npm registry, which prevents dependency
  installation and causes the PR creation checks to fail. You may need to point npm to an accessible registry or run installs in
  a network-allowed environment.

## Project structure
- `App.js` — shared UI for all platforms.
- `app.json` — Expo app configuration for Android, iOS, and web outputs.
