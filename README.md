# rn-assignment5-11135953

## Overview

This project is a React Native mobile application that showcases a multi-screen interface with theme-switching capabilities between light and dark modes. The application is built to closely match the provided UI mockup, featuring customized components and styles.

## Features

- **Bottom Tab Navigation**: The application has a bottom tab navigator with the following screens:
  - **Home**
  - **My Cards**
  - **Statistics**
  - **Settings**
- **Theming**: Users can switch between light and dark themes, with styles and colors dynamically updating throughout the app.
- **Custom Components**: The application uses custom components and icons to align with the provided UI design.

## How I Built the Application

### Technologies and Libraries Used

- **React Native**: The core framework for building mobile applications.
- **React Navigation**: For managing navigation and tab bar.
- **AsyncStorage**: For persisting theme preferences.
- **Expo-Blur**: For adding a blur effect to certain UI components.
- **Custom Components**: Developed custom components to match the design requirements.
- **Context API**: Used for state management of theme switching.

### Steps Taken

1. **Project Setup**: Initialized a new React Native project and set up the folder structure.
2. **Context and State Management**: Created a `ThemeContext` to handle theme state and switching logic, with persistence using `AsyncStorage`.
3. **Navigation Setup**: Implemented bottom tab navigation using `react-navigation`, setting up screens for Home, My Cards, Statistics, and Settings.
4. **UI Design and Styling**: Styled each screen according to the provided mockup. Ensured dynamic theming and used custom icons and components.
5. **Theme Switching**: Implemented a toggle button in the Settings screen to switch between light and dark themes.
6. **Final Touches**: Refined styles and tested the application on different devices to ensure consistency.

### UI Components

- **Home Screen**: Displays a user greeting, profile picture, and several action buttons. Also includes a transaction history section.
- **My Cards Screen**: Placeholder screen for future card-related functionalities.
- **Statistics Screen**: Placeholder screen for displaying user statistics.
- **Settings Screen**: Contains options for navigating to other settings and a switch to toggle between light and dark themes.

### Screenshots

Here are some screenshots of the application demonstrating the light and dark themes:
![Screenshot 1](https://github.com/davidboateng451/rn-assignment5-11135953/assets/151746606/a17f52d2-3fd7-444a-95e6-27b821b7d2ee)
![Screenshot 2](https://github.com/davidboateng451/rn-assignment5-11135953/assets/151746606/f6d091e3-41d0-469a-8c9e-ba39a23cd1b5)
![Screenshot 3](https://github.com/davidboateng451/rn-assignment5-11135953/assets/151746606/c3b2dc8c-d12a-46a0-a9c3-677a4c2cd521)
![Screenshot 4](https://github.com/davidboateng451/rn-assignment5-11135953/assets/151746606/b8488cad-dca9-4fa7-82f8-1dd5fbdf3496)



