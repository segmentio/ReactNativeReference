# React Native Reference App

## Environment

This app has been tested with the following environment.

```bash
→ react-native info  
info 
  React Native Environment Info:
    System:
      OS: macOS 10.14.3
      CPU: (8) x64 Intel(R) Core(TM) i7-4870HQ CPU @ 2.50GHz
      Memory: 48.27 MB / 16.00 GB
      Shell: 5.3 - /bin/zsh
    Binaries:
      Node: 8.15.1 - /usr/local/bin/node
      Yarn: 1.13.0 - /usr/local/bin/yarn
      npm: 6.4.1 - /usr/local/bin/npm
      Watchman: 4.9.0 - /usr/local/bin/watchman
    SDKs:
      iOS SDK:
        Platforms: iOS 12.1, macOS 10.14, tvOS 12.1, watchOS 5.1
      Android SDK:
        API Levels: 23, 24, 25, 26, 27, 28, 8
        Build Tools: 23.0.1, 25.0.0, 25.0.2, 25.0.3, 26.0.1, 26.0.2, 27.0.2, 27.0.3, 28.0.2, 28.0.3
        System Images: android-25 | Google APIs ARM EABI v7a, android-25 | Google APIs Intel x86 Atom_64, android-26 | Google APIs Intel x86 Atom, android-27 | Google APIs Intel x86 Atom
    IDEs:
      Android Studio: 3.2 AI-181.5540.7.32.5056338
      Xcode: 10.1/10B61 - /usr/bin/xcodebuild
    npmPackages:
      react: 16.8.3 => 16.8.3 
      react-native: 0.59.1 => 0.59.1 
    npmGlobalPackages:
      react-native-cli: 2.0.1
```

## Setup

To recreate how this was app was setup, first follow the [React Native guide](https://facebook.github.io/react-native/docs/getting-started.html) to create your React Native app (do not use the Expo CLI as it doesn't native modules).

Then follow the [Segment React Native library guide](https://segment.com/docs/sources/mobile/react-native/#install-the-sdk) to install Segment. Be sure to setup [CocoaPods](https://github.com/segmentio/analytics-react-native#setup-cocoapods-in-an-existing-project) first.
