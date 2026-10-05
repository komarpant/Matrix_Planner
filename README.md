# MATRIX // PLANNER

[![Build Android APK](https://github.com/komarpant/Matrix_Planner/actions/workflows/android.yml/badge.svg)](https://github.com/komarpant/Matrix_Planner/actions/workflows/android.yml)

Matrix Planner is a futuristic, highly functional task planner designed to organize complex tasks, roadmap projections, and daily logs in an efficient, distraction-free environment. 

Inspired by a cyberpunk aesthetic and designed for deep-focus work, it helps users manage their timelines systematically, combining calendar views with targeted roadmap planning and central datacore notes.

## Features

- **Calendar Matrix**: A streamlined monthly view to track daily focus and flag critical days.
- **Timeline Protocol**: A robust, editable roadmap projection to map out phases, goals, and focus areas across long periods.
- **Datacore Notes**: A central repository for logging project information, architecture decisions, and long-term insights.
- **Cyberpunk UI**: A highly polished, custom design system inspired by the Nexus System, featuring dark modes, neon accents (Volt), and monospaced typography.
- **Offline First**: All data is stored completely offline in your local storage. No cloud dependencies.
- **Theme Engine**: Built-in support for custom themes. Tweak the 6 core colors to your liking and save them.
- **Data Export & Import**: Built-in JSON backup system to export and restore your entire workspace.

## Platforms

Matrix Planner is built as a single-page web app but is packaged for native platforms:
- **Windows**: Packaged as a standalone desktop application using Electron and electron-builder.
- **Android**: Packaged as a native Android application using Capacitor, featuring full mobile responsiveness and safe-area notch support.

## 📥 Download

### Android APK (Direct Download)
You don't need to compile the app yourself! Every time the code is updated, a fresh Android `.apk` is automatically built and published.

👉 **[Download the Latest Android APK Directly Here](https://github.com/komarpant/Matrix_Planner/releases/download/latest/MatrixPlanner.apk)**
*(Clicking this link will immediately start the download. It does not require a GitHub account!)*

## Getting Started

### Prerequisites
- Node.js and npm

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/komarpant/Matrix_Planner.git
   cd Matrix_Planner
   ```
2. Install dependencies:
   ```bash
   npm install
   ```

### Building for Windows
To build a portable executable and an NSIS installer for Windows:
```bash
npm run build:win
```
The output `.exe` files will be located in the `dist/` directory.

### Building for Android
To sync the latest web assets and build a debug APK:
```bash
npm run build:android
```
The output `.apk` file will be located in `android/app/build/outputs/apk/debug/app-debug.apk`.

## Development
- **Web App**: The core UI is located in `www/index.html`.
- **Desktop Entry**: The Electron entry script is `main.js`.
- **Mobile Entry**: The Capacitor configuration is `capacitor.config.json`.

## Credits
- Conceptualized and Built by: **Harsh Komarpant**
- UI Inspiration: [Nexus System](https://templatemo.com/live/templatemo_629_nexus_system)
- Typography: [Plus Jakarta Sans](https://fonts.google.com/specimen/Plus+Jakarta+Sans) & [JetBrains Mono](https://fonts.google.com/specimen/JetBrains+Mono)
