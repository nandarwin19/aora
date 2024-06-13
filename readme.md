# Aora

## Getting started

To create the project with jsx, use the following command:

```
npx create-expo-app@latest --template
```

When prompted, select the "blank (bare)" template.

### Installing tailwind css

To install and set up Tailwind CSS, follow the instructions in the [NativeWind quick start guide for Expo](https://www.nativewind.dev/quick-starts/expo).

## Running the project

Run the project,

```
npx expo start -c
```

`We use SafeAreaView to ensure that important content is visible on all devices, including those with notches or navigation bars.`

### The different push and replace

push: adds a new route to the stack, so that when the user presses the back button, they are taken to the previous screen.
replace: replaces the current route in the stack with a new one. This is useful for when you don't want the user to be able to go back to the previous screen.
