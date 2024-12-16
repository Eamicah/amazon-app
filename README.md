# Amazon App Clone

This project is a clone of the Amazon app, created using [React Native](https://reactnative.dev/) and [Expo](https://expo.dev/). The app replicates the core functionalities and user experience of the original Amazon app while serving as a platform to experiment with various mobile app development techniques.

## Features

- **Modern UI**: Clean and responsive design.
- **Navigation**: Smooth page transitions implemented with `@react-navigation`.
- **Reusable Components**: Modular and scalable component design.
- **Animations**: Seamless and smooth animations using `react-native-reanimated`.
- **Cross-Platform**: Runs on both Android and iOS.

## Tech Stack

- **Framework**: React Native
- **Expo SDK**: Used for rapid development and testing.
- **Navigation**: `@react-navigation/bottom-tabs` and `@react-navigation/native`
- **UI Libraries**:
  - `react-native-ui-lib` for rich UI components
  - `react-native-linear-gradient` for gradient effects
- **State Management**: Leveraged context or hooks where applicable.
- **Utilities**: `lodash` for functional programming utilities.

## Installation

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd amazonapp-clone
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Run the app:
   ```bash
   npx expo start
   ```

   This will open an Expo dev server where you can run the app on an emulator or physical device.

## Project Structure

```
.
├── assets/                    # Static assets like icons and splash screens
├── src/
│   ├── components/            # Reusable UI components
│   ├── screens/               # App screens
│   ├── infrastructure/
│       ├── navigation/        # Navigation configurations
│   ├── services/              # API services and external integrations
│   ├── utils/                 # Utility functions
├── App.js                     # Entry point
├── app.json                   # Expo configuration
├── package.json               # Project metadata
└── README.md                  # Documentation
```

## Dependencies

The app leverages the following key libraries:

- `expo`: For build and development
- `react-native`: Core framework
- `@react-navigation/*`: For handling navigation
- `react-native-reanimated`: For fluid animations
- `expo-linear-gradient`: For gradient designs
- And more listed in `package.json`

