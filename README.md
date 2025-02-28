<div align="center" style="margin-top: 10px; border-bottom: 2px solid #464646; margin-bottom: 40px;">

<img src="./.github/assets/openklub-logo.png" alt="OpenKlub Logo" width="350px" style="margin-bottom: 40px;" />

![GitHub License](https://img.shields.io/github/license/santychuycom/openklub)

</div>

<h2 style="border-bottom: 0px;">Resources</h2>

[🎨 Figma Design](https://www.figma.com/design/tncJUUUxVsG6UBOS4zW9rh/OpenKlub?node-id=55-285&t=47dfRjLrrbUJZ4tI-1)

<br />

<h2 style="border-bottom: 0px;">Getting Started</h2>

This guide will help you set up and run the OpenKlub mobile on your local development environment.

### Prerequisites

Before you begin, make sure you have the following installed:

- [Node.js](https://nodejs.org/) (LTS version recommended)
- [Bun](https://bun.sh/) (Package manager used in this project)
- Xcode (for iOS development, macOS only)
- Android Studio (for Android development)
- iOS Simulator or Android Emulator (or physical devices)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/santychuycom/openklub.git
   cd openklub-mobile
   ```

2. Install dependencies:
   ```bash
   bun install
   ```

### Running the Application

#### Start the Development Server

```bash
bun start
```

This will start the Expo development server and display a QR code in your terminal.

#### Run on iOS Simulator

```bash
bun ios
```

This command will build the iOS app and launch it in the iOS Simulator.

#### Run on Android Emulator

```bash
bun android
```

This command will build the Android app and launch it in the Android Emulator.

#### Run in Web Browser

```bash
bun web
```

This will start the application in your default web browser.

### Additional Commands

#### Reset Project

If you need to reset the project to a clean state:

```bash
bun reset-project
```

#### Run Tests

```bash
bun test
```

#### Lint Code

```bash
bun lint
```

### Troubleshooting

- If you encounter build issues, try clearing the cache:
  ```bash
  expo start -c
  ```

- For iOS specific issues, try cleaning the Pods:
  ```bash
  cd ios
  pod deintegrate
  pod install
  ```

- For Android specific issues, try cleaning the Gradle build:
  ```bash
  cd android
  ./gradlew clean
  ```

<br />

<h2 style="border-bottom: 0px;">Roadmap</h2>

- [ ] ...
