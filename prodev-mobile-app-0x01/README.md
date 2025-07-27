# React Native Components and Styling

## 📱 Objective

Build a React Native app using the Expo Router template, exploring predefined components (`View`, `Text`) and applying styles using `StyleSheet`.

## 🧩 Steps Followed

1. **Initialized a new Expo project**  
   Used the latest Expo Router template:
   ```bash
   npx create-expo-app@latest prodev-mobile-app-0x01 --template with-router
Reset the application
Removed any default template content to start with a clean slate:

bash
Copy
Edit
npm run reset-project
Modified the app/index.tsx file

Replaced default <Text> content with "Entry Screen - Awesome"

Applied style={styles.container} to the root <View>

Inserted three additional <Text> components with custom styles inside a <View>

Defined custom styles
Created a StyleSheet containing styles for:

container

largeText

mediumText

smallText

🎨 Styling Summary
container:
Light blue background, full screen, centered content using Flexbox.

largeText:
fontSize: 30, bold, red (#f44336), small-caps style.

mediumText:
fontSize: 20, purple (#9c27b0), right-aligned, semi-bold.

smallText:
fontSize: 15, blue (#2196f3), centered, regular weight.