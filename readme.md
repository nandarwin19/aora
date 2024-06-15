# Aora

<div>
    <img src="https://img.shields.io/badge/-React_Native-black?style=for-the-badge&logoColor=white&logo=react&color=61DAFB" alt="react.js" />
    <img src="https://img.shields.io/badge/-Appwrite-black?style=for-the-badge&logoColor=white&logo=appwrite&color=FD366E" alt="appwrite" />
    <img src="https://img.shields.io/badge/NativeWind-black?style=for-the-badge&logoColor=white&logo=tailwindcss&color=06B6D4" alt="nativewind" />
  </div>
  
## Notes

1. **Create the Project**:
   Use the following command to create the project with JSX:

   ```
   npx create-expo-app@latest --template
   ```

   When prompted, select the "blank (bare)" template.

2. **Install Tailwind CSS**:
   Follow the instructions in the [NativeWind quick start guide for Expo](https://www.nativewind.dev/quick-starts/expo) to install and set up Tailwind CSS.

3. **Run the Project**:
   Use the following command to start the project:

   ```
   npx expo start -c
   ```

   We use `SafeAreaView` to ensure that important content is visible on all devices, including those with notches or navigation bars.

### Navigation: Push vs Replace

- **push**: Adds a new route to the stack, so that when the user presses the back button, they are taken to the previous screen.
- **replace**: Replaces the current route in the stack with a new one. This is useful when you don't want the user to be able to go back to the previous screen.

## Quick Start

Follow these steps to set up the project locally on your machine.

**Prerequisites**

Make sure you have the following installed on your machine:

- [Git](https://git-scm.com/)
- [Node.js](https://nodejs.org/en)
- [npm](https://www.npmjs.com/) (Node Package Manager)

**Cloning the Repository**

```bash
git clone https://github.com/nandarwin19/aora.git
cd aora
```

**Installation**

Install the project dependencies using npm:

```bash
npm install
```

**Running the Project**

```bash
npx expo start -c
```

**Expo Go**

Download the [Expo Go](https://expo.dev/go) app onto your device, then use it to scan the QR code from Terminal and run.

## Features

- **Onboarding Screen**: Engaging graphics and clear instructions welcome users to the app.
- **Robust Authentication & Authorization System**: Secure email login safeguards user accounts.
- **Dynamic Home Screen with Animated Flat List**: Smoothly animated flat list showcases the latest videos for seamless browsing.
- **Pull-to-Refresh Functionality**: Users can refresh content with a simple pull gesture for up-to-date information.
- **Full-Text Search Capability**: Efficiently search through videos with real-time suggestions and instant results.
- **Tab Navigation**: Navigate between sections like Home, Search, and Profile with ease using tab navigation.
- **Post Creation Screen for Uploading Media**: Upload video and image posts directly from the app with integrated media selection.
- **Profile Screen with Detailed Insights**: View account details and activity, including uploaded videos and follower count, for a personalized experience.
- **Responsiveness**: Smooth performance and adaptability across various devices and screen sizes for a consistent user experience.
- **Animations**: Dynamic animations using the Animatable library to enhance user interaction and engagement throughout the app's UI.
