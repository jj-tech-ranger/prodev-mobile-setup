# Prodev Mobile App 0x00

## Scaffolding Process
1. Created the directory `prodev-mobile-app-0x00`.
2. Initialized a new Expo project using `npx create-expo-app@latest .`.
3. Modified the boilerplate home screen in `app/(tabs)/index.tsx`, changing "Welcome!" to "First App Created".
4. Successfully tested the application on a physical device using the Expo Go app.

## Observations: reset-project
Running the `npm run reset-project` command resulted in the following:
- The original `app` directory containing the tab-based navigation template was moved to `app-example`.
- A fresh, minimal `app` directory was generated.
- The project structure was simplified to a single-screen entry point, removing the default tutorial components and styling constants.
- This allows for a clean start when building custom UI from scratch.