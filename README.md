# CS-125-Group-26: AquaZenith

AquaZenith is a cross-platform wellness and health tracking app built with React Native for the CS 125 Group 26 project. It helps users monitor and improve their daily habits around hydration, sleep, exercise, and more, with personalized AI-powered recommendations.

---

## Project Structure

- **AquaZenith/**: Main React Native app source code and documentation
- Other files: Project-level configuration and documentation

---

## Features

- **User Authentication**: Secure sign in and sign up with Firebase
- **Onboarding**: Collects user info (name, weight, height, birth date) and personal goals (water intake, exercise, calories, sleep schedule)
- **Dashboard Summary**: Personalized greeting and summary of daily health metrics (calories, exercise, sleep, hydration)
- **Health Data Tracking**: Integrates with Apple HealthKit to track steps, exercise, hydration, and sleep
- **Visualizations**: Weekly charts for hydration, sleep, steps, and exercise
- **AI Recommendations**: Daily, personalized health suggestions powered by OpenAI (GPT-4)
- **Profile Page**: View and edit personal details and goals
- **Goal Setting**: Set and update daily targets for water, exercise, calories, and sleep
- **Modern UI**: Clean, mobile-friendly design with light/dark mode support

---

## Getting Started

> **Note:** The main app is in the `AquaZenith` directory. Complete the [React Native Environment Setup](https://reactnative.dev/docs/environment-setup) before proceeding.

### 1. Install Dependencies

From the `AquaZenith` directory:

```bash
cd AquaZenith
npm install
# or
yarn install
```

### 2. Start the Metro Server

```bash
npm start
# or
yarn start
```

### 3. Run the App

Open a new terminal in the same directory.

#### For Android
```bash
npm run android
# or
yarn android
```

#### For iOS
```bash
npm run ios
# or
yarn ios
```

---

## App Navigation

- **Welcome**: Onboarding and introduction
- **Sign In / Sign Up**: User authentication
- **User Info & Goals**: Collects user details and daily goals
- **Main Tabs**:
  - **Summary**: Dashboard with health metrics and AI recommendations
  - **Exercise**: Weekly exercise and step tracking
  - **Hydration**: Water intake tracking and visualization
  - **Sleep**: Sleep duration tracking and visualization
  - **Profile**: View/edit user info and goals

---

## Technology Stack
- React Native
- TypeScript
- Firebase Authentication
- Apple HealthKit (iOS)
- OpenAI GPT-4 (recommendations)
- React Navigation
- Chart visualizations

---

## Troubleshooting

If you encounter issues, see the [React Native Troubleshooting Guide](https://reactnative.dev/docs/troubleshooting).

---

## Learn More
- [React Native Docs](https://reactnative.dev)
- [React Navigation](https://reactnavigation.org/)
- [Firebase Docs](https://firebase.google.com/docs)
- [OpenAI API](https://platform.openai.com/docs)

---

## License

This project is for educational purposes (CS 125 Group 26).
