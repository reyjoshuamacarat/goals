# Goals - Personal Goal Tracking App 🎯

A beautiful, cross-platform mobile app built with Expo React Native for tracking and managing personal goals. Features goal creation, progress tracking, image proof uploads, and subscription management.

## Prerequisites

Before getting started, make sure you have the following installed:

- **Node.js** (v18 or later) - [Download here](https://nodejs.org/)
- **Bun** - Fast JavaScript runtime and package manager - [Install here](https://bun.sh/)
- **Expo CLI** - Install globally with `bun add -g @expo/cli`

For mobile development:
- **iOS**: Xcode (macOS only) and iOS Simulator
- **Android**: Android Studio and Android Emulator
- **Mobile Testing**: Expo Go app on your phone ([iOS](https://apps.apple.com/app/expo-go/id982107779) | [Android](https://play.google.com/store/apps/details?id=host.exp.exponent))

## Installation & Setup

1. **Clone the repository** (if applicable)
   ```bash
   git clone <repository-url>
   cd goals
   ```

2. **Install dependencies**
   ```bash
   bun install
   ```

3. **Start the development server**
   ```bash
   bunx expo start
   # or
   bun start
   ```

4. **Run on your preferred platform**
   
   From the Expo CLI output, you can:
   - Press `i` to open iOS Simulator
   - Press `a` to open Android Emulator  
   - Scan QR code with Expo Go app on your phone
   - Press `w` to run in web browser

## Available Scripts

- `bun start` - Start the Expo development server
- `bun run android` - Build and run on Android device/emulator
- `bun run ios` - Build and run on iOS device/simulator
- `bun run web` - Start web version
- `bun run lint` - Run code linting with Biome

## Tech Stack & Architecture

### **Frontend Framework**
- **Expo** (~53.0) - React Native development platform with comprehensive tooling
- **React Native** (0.79) - Cross-platform mobile app framework
- **TypeScript** (5.8) - Type-safe JavaScript with enhanced developer experience

### **Navigation & Routing**
- **Expo Router** (5.1) - File-based routing system with typed routes
- **React Navigation** (7.1) - Navigation library with bottom tabs and stack navigation

### **State Management**
- **Redux Toolkit** (2.8) - Modern Redux with simplified syntax and built-in best practices
- **React Redux** (9.2) - React bindings for Redux
- **Redux Remember** (5.2) - Persistence layer for Redux state

### **Styling & UI**
- **NativeWind** (4.1) - Tailwind CSS for React Native with utility-first approach
- **Tailwind CSS** (3.4) - Utility-first CSS framework
- **Expo Linear Gradient** - Beautiful gradient backgrounds and effects
- **Lucide React Native** - Comprehensive icon library

### **Data & Storage**
- **AsyncStorage** (2.1) - Simple, persistent, key-value storage for React Native
- **Zod** (4.1) - TypeScript-first schema validation

### **Camera & Media**
- **Expo Image Picker** - Camera and photo library access for goal proof uploads
- **Expo Image** - Optimized image component with caching

### **Development Tools**
- **Biome** (2.2) - Fast formatter and linter for JavaScript/TypeScript
- **Expo Dev Client** - Custom development client for enhanced debugging

### **Fonts & Typography**
- **Inter** - Modern, clean sans-serif font family
- **DM Serif Display** - Elegant serif font for headers

## Known Limitations

### **Payment System**
- **PayPal Only**: Currently only supports PayPal payment simulation (not real payments)
- **Mock Processing**: Payment processing is simulated with 90% success rate for testing
- **No Real Billing**: No actual payment gateway integration or billing system

### **Data Storage**
- **AsyncStorage Only**: Uses local device storage only - no cloud sync or backup
- **Device Dependent**: Goals and data are lost if app is uninstalled or device is reset
- **No Multi-Device Sync**: Cannot access goals across multiple devices
- **Limited Storage**: Subject to device storage limitations

### **Platform Limitations**
- **Mobile First**: Optimized for mobile devices (iOS/Android)
- **Web Support**: Web version available but may have limited functionality
- **Offline Only**: No server-side storage or real-time sync capabilities

### **Feature Constraints**
- **No User Authentication**: No login/signup system or user accounts
- **No Social Features**: No sharing, collaboration, or social aspects
- **No Notifications**: No push notifications or reminders
- **No Analytics**: No goal completion analytics or progress insights

### **Development Status**
- **Beta Version**: Still in active development with potential breaking changes
- **Limited Testing**: May have untested edge cases or scenarios
- **iOS/Android Differences**: Some features may behave differently across platforms

## App Features

- ✅ Goal creation with customizable colors and icons
- ✅ Progress tracking and completion status
- ✅ Image proof upload for goal completion
- ✅ Beautiful, modern UI with smooth animations
- ✅ Cross-platform support (iOS, Android, Web)
- ✅ Subscription management with PayPal integration (simulated)
- ✅ Local data persistence
- ✅ Dark/Light theme support

## Contributing

This project uses Biome for code formatting and linting. Make sure to run `bun run lint` before submitting any changes.

## Learn More

- [Expo Documentation](https://docs.expo.dev/) - Learn about Expo features and APIs
- [React Native Documentation](https://reactnative.dev/) - Learn React Native fundamentals  
- [NativeWind Documentation](https://www.nativewind.dev/) - Tailwind CSS for React Native
