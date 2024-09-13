This is the boilerplate which i made it for easily build new project.
If you want to use this boilerplate please make sure your development environment setting should be simillar.
before use this boilerplate please check `package.json` for this is fit to your project.

# Author Development
```bash
System:
  OS: macOS 13.5
  CPU: (10) arm64 Apple M2 Pro
  Memory: 1.40 GB / 16.00 GB
  Shell:
    version: "5.9"
    path: /bin/zsh
Binaries:
  Node:
    version: 22.6.0
    path: /opt/homebrew/bin/node
  Yarn:
    version: 1.22.22
    path: /opt/homebrew/bin/yarn
  npm:
    version: 10.8.2
    path: /opt/homebrew/bin/npm
  Watchman:
    version: 2024.08.19.00
    path: /opt/homebrew/bin/watchman
Managers:
  CocoaPods:
    version: 1.15.2
    path: /Users/godong-gwan/.rbenv/shims/pod
SDKs:
  iOS SDK:
    Platforms:
      - DriverKit 23.0
      - iOS 17.0
      - macOS 14.0
      - tvOS 17.0
      - watchOS 10.0
  Android SDK: Not Found
IDEs:
  Android Studio: 2022.3 AI-223.8836.35.2231.10811636
  Xcode:
    version: 15.0/15A240d
    path: /usr/bin/xcodebuild
Languages:
  Java:
    version: 17.0.9
    path: /usr/bin/javac
  Ruby:
    version: 2.7.4
    path: /Users/godong-gwan/.rbenv/shims/ruby
npmPackages:
  "@react-native-community/cli": Not Found
  react:
    installed: 18.3.1
    wanted: 18.3.1
  react-native:
    installed: 0.75.3
    wanted: 0.75.3
  react-native-macos: Not Found
npmGlobalPackages:
  "*react-native*": Not Found
Android:
  hermesEnabled: true
  newArchEnabled: false
iOS:
  hermesEnabled: true
  newArchEnabled: false
```

This is a new [**React Native**](https://reactnative.dev) project, bootstrapped using [`@react-native-community/cli`](https://github.com/react-native-community/cli).

# Getting Started

>**Note**: Make sure you have completed the [React Native - Environment Setup](https://reactnative.dev/docs/environment-setup) instructions till "Creating a new application" step, before proceeding.

## Step 1: Start the Metro Server

First, you will need to start **Metro**, the JavaScript _bundler_ that ships _with_ React Native.

To start Metro, run the following command from the _root_ of your React Native project:

```bash
# using npm
npm start

# OR using Yarn
yarn start
```

## Step 2: Start your Application

Let Metro Bundler run in its _own_ terminal. Open a _new_ terminal from the _root_ of your React Native project. Run the following command to start your _Android_ or _iOS_ app:

### For Android

```bash
# using npm
npm run android

# OR using Yarn
yarn android
```

### For iOS

```bash
# using npm
npm run ios

# OR using Yarn
yarn ios
```

If everything is set up _correctly_, you should see your new app running in your _Android Emulator_ or _iOS Simulator_ shortly provided you have set up your emulator/simulator correctly.

This is one way to run your app — you can also run it directly from within Android Studio and Xcode respectively.

## Step 3: Modifying your App

Now that you have successfully run the app, let's modify it.

1. Open `App.tsx` in your text editor of choice and edit some lines.
2. For **Android**: Press the <kbd>R</kbd> key twice or select **"Reload"** from the **Developer Menu** (<kbd>Ctrl</kbd> + <kbd>M</kbd> (on Window and Linux) or <kbd>Cmd ⌘</kbd> + <kbd>M</kbd> (on macOS)) to see your changes!

   For **iOS**: Hit <kbd>Cmd ⌘</kbd> + <kbd>R</kbd> in your iOS Simulator to reload the app and see your changes!

## Congratulations! :tada:

You've successfully run and modified your React Native App. :partying_face:

### Now what?

- If you want to add this new React Native code to an existing application, check out the [Integration guide](https://reactnative.dev/docs/integration-with-existing-apps).
- If you're curious to learn more about React Native, check out the [Introduction to React Native](https://reactnative.dev/docs/getting-started).

# Troubleshooting

If you can't get this to work, see the [Troubleshooting](https://reactnative.dev/docs/troubleshooting) page.

# Learn More

To learn more about React Native, take a look at the following resources:

- [React Native Website](https://reactnative.dev) - learn more about React Native.
- [Getting Started](https://reactnative.dev/docs/environment-setup) - an **overview** of React Native and how setup your environment.
- [Learn the Basics](https://reactnative.dev/docs/getting-started) - a **guided tour** of the React Native **basics**.
- [Blog](https://reactnative.dev/blog) - read the latest official React Native **Blog** posts.
- [`@facebook/react-native`](https://github.com/facebook/react-native) - the Open Source; GitHub **repository** for React Native.
