# 📱 Mobile Application (React Native + Expo)

A cross-platform mobile application built with **React Native** and **Expo**, developed as part of coursework at **King Mongkut's Institute of Technology Ladkrabang (KMITL)**. The app follows a clean architecture with separated screens, navigation, state management, and data models.

---

## 📌 Project Overview

| Detail | Info |
|---|---|
| **Project Name** | Mobile Project |
| **Type** | Cross-Platform Mobile Application |
| **Institution** | KMITL (King Mongkut's Institute of Technology Ladkrabang) |
| **Framework** | React Native (Expo) |
| **Language** | JavaScript (100%) |
| **State Management** | Redux (store/) |
| **Navigation** | React Navigation |
| **Animation** | react-native-reanimated |

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| **Framework** | React Native |
| **Development Tool** | Expo |
| **Language** | JavaScript (ES6+) |
| **Navigation** | React Navigation |
| **State Management** | Redux (store/) |
| **Animation** | react-native-reanimated |
| **Data Layer** | Local database + data/ models |

---

## 📁 Project Structure

```
Mobile-Project/
├── screens/          # Individual app screens (UI pages)
├── navigation/       # Navigation stack & tab configuration
├── store/            # Redux state management
├── models/           # Data models / structures
├── data/             # Local data / mock data
├── database/         # Database configuration
├── assets/           # Images, fonts, icons
├── App.js            # Root application entry point
├── app.json          # Expo app configuration
├── babel.config.js   # Babel configuration
└── package.json      # Dependencies
```

---

## ✨ Features

- 📲 **Cross-Platform** — Runs on both iOS and Android from a single codebase
- 🧭 **Multi-Screen Navigation** — Stack/Tab navigation with React Navigation
- 🗃️ **State Management** — Centralized app state with Redux store
- 🎞️ **Smooth Animations** — Using react-native-reanimated for fluid UI transitions
- 🗄️ **Local Database** — Persistent local data storage
- 🧩 **Component Architecture** — Clean separation between screens, models, and data layers

---

## 🚀 Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) v16+
- [Expo CLI](https://docs.expo.dev/get-started/installation/)
- Expo Go app on your phone (iOS/Android) — or an emulator

### Installation

```bash
# Clone the repository
git clone https://github.com/Pongpun1/Mobile-Project.git
cd Mobile-Project

# Install dependencies
npm install

# Install animation library (if not included)
npm install react-native-reanimated
```

### Run the App

```bash
# Start Expo development server
npm start

# If you encounter cache issues, reset cache
npm start -- --reset-cache
```

Then scan the QR code with the **Expo Go** app on your phone, or press:
- `a` to open Android emulator
- `i` to open iOS simulator

---

## 📦 Key Dependencies

```bash
npm install react-native-reanimated   # Smooth animations
```

Other core dependencies are defined in `package.json` and installed via `npm install`.

---

## 👨‍💻 Developer

**Pongpun** — Computer Engineering / IT Student at KMITL

- GitHub: [@Pongpun1](https://github.com/Pongpun1)

---

## 📚 Academic Context

This project was developed as part of the curriculum at **KMITL**, demonstrating skills in:

- Cross-platform mobile development (React Native + Expo)
- Component-based UI architecture
- Client-side state management with Redux
- Multi-screen navigation patterns
- Mobile UX/UI design principles
- Animation and gesture handling

---

## 📄 License

This project is for academic and portfolio purposes.
