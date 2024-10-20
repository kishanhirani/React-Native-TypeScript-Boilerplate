# React Native TypeScript Boilerplate

A comprehensive React Native TypeScript Boilerplate with core and advanced functionalities essential for modern mobile app development.

## 🚀 Features

### 1. Dynamic Font and Dimensions
- Automatically adjust font sizes and UI dimensions based on screen size
- Ensure consistent look across various devices

### 2. Theme Support
- Implement light and dark mode
- Easily customizable theme settings
- Smooth transitions between themes

### 3. Multilingual Localization
- Support multiple languages out of the box
- Easy-to-use translation system
- Runtime language switching

### 4. Navigation
- Drawer Navigation: For main menu and app sections
- Stack Navigation: For hierarchical screens
- Bottom Tabs: For quick access to primary features

### 5. State Management
- Integrated Redux for efficient state management
- Pre-configured store and reducers
- Easy-to-follow structure for adding new states

### 6. Custom Components
- Modal: Customizable modal component for pop-ups and alerts
- TextInput: Enhanced text input with built-in validation
- Buttons: Various button styles (primary, secondary, outline)
- Dropdown Picker: Custom dropdown for selections
- ImageRender: Optimized image rendering component

### 7. Toast Notifications
- Custom toast component for non-intrusive user feedback
- Multiple toast types (success, error, info, warning)
- Customizable duration and position
- Queue system for multiple toasts

### 8. Axios API Setup
- Pre-configured Axios instance for API calls
- Interceptors for request and response handling
- Global error handling for API requests
- Easy-to-use API service structure

## 🛠 Getting Started

1. Clone the repository:
   ```
   git clone https://github.com/yourusername/react-native-typescript-boilerplate.git
   ```

2. Rename the project:
   - Install the React Native Rename package globally:
     ```
     npm install -g react-native-rename
     ```
   - Navigate to the project directory:
     ```
     cd react-native-typescript-boilerplate
     ```
   - Rename the project (replace "YourNewAppName" with your desired app name):
     ```
     npx react-native-rename "YourNewAppName"
     ```
   - For iOS, you'll need to update the Podfile. Open `ios/Podfile` and replace all occurrences of 'react_native_typescript_boilerplate' with 'YourNewAppName'.
   - Re-install pods:
     ```
     cd ios && pod install && cd ..
     ```

3. Install dependencies:
   ```
   npm install
   ```

4. Run the app:
   - For iOS:
     ```
     npx react-native run-ios
     ```
   - For Android:
     ```
     npx react-native run-android
     ```

5. Update app display name (optional):
   - iOS: Open `ios/YourNewAppName/Info.plist` and modify the value for `CFBundleDisplayName`
   - Android: Open `android/app/src/main/res/values/strings.xml` and modify the value for `app_name`

## 📚 Documentation

We are currently working on comprehensive documentation for this boilerplate. Once completed, it will provide detailed information on how to use and customize each feature.

## 🌿 Branches

- **main**: This branch contains the stable, polished, and correctly working code. Use this branch for production-ready implementations.
- **dev**: This branch is for beta or experimental work. It may contain new features or changes that are still being tested and refined.

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! See [CONTRIBUTING.md](CONTRIBUTING.md) for how to get started.

## 📝 License

This project is [MIT](LICENSE) licensed.
