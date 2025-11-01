# Welcome to your Expo app 👋

This is an [Expo](https://expo.dev) project created with [`create-expo-app`](https://www.npmjs.com/package/create-expo-app).

## Get started

1. Install dependencies

   ```bash
   npm install
   ```

2. Start the app

   ```bash
   npx expo start
   ```

In the output, you'll find options to open the app in a

- [development build](https://docs.expo.dev/develop/development-builds/introduction/)
- [Android emulator](https://docs.expo.dev/workflow/android-studio-emulator/)
- [iOS simulator](https://docs.expo.dev/workflow/ios-simulator/)
- [Expo Go](https://expo.dev/go), a limited sandbox for trying out app development with Expo

You can start developing by editing the files inside the **app** directory. This project uses [file-based routing](https://docs.expo.dev/router/introduction).

## Get a fresh project

When you're ready, run:

```bash
npm run reset-project
```

This command will move the starter code to the **app-example** directory and create a blank **app** directory where you can start developing.

prodev-mobile-app-0x00@1.0.0 reset-project

> node ./scripts/reset-project.js

Do you want to move existing files to /app-example instead of deleting them? (Y/n): Y
📁 /app-example directory created.
➡️ /app moved to /app-example/app.
➡️ /components moved to /app-example/components.
➡️ /hooks moved to /app-example/hooks.
➡️ /constants moved to /app-example/constants.
➡️ /scripts moved to /app-example/scripts.

📁 New /app directory created.
📄 app/index.tsx created.
📄 app/\_layout.tsx created.

## Learn more

To learn more about developing your project with Expo, look at the following resources:

- [Expo documentation](https://docs.expo.dev/): Learn fundamentals, or go into advanced topics with our [guides](https://docs.expo.dev/guides).
- [Learn Expo tutorial](https://docs.expo.dev/tutorial/introduction/): Follow a step-by-step tutorial where you'll create a project that runs on Android, iOS, and the web.

## Join the community

Join our community of developers creating universal apps.

- [Expo on GitHub](https://github.com/expo/expo): View our open source platform and contribute.
- [Discord community](https://chat.expo.dev): Chat with Expo users and ask questions.

---

## Project Setup and Observations

### Scaffolding Steps

1.  **Navigate to Project Directory**: Opened the terminal and navigated to `prodev-mobile-app-0x00`.
2.  **Initialize Expo Project**: Ran `npx create-expo-app@latest .` to initialize a new Expo project using the latest Expo Router template. (Note: This step was already completed by the user.)
3.  **Modify Home Screen**: Edited `app/index.tsx` to change the default text "Edit app/index.tsx to edit this screen." to "** First App Created**".
4.  **Configure JSX**: Added `"jsx": "react-native"` to `compilerOptions` in `tsconfig.json` to resolve JSX related TypeScript errors.
5.  **Run Application**: Started the Expo development server with `npx expo start --port 8082`.

### Observations from `reset-project` command

When `npm run reset-project` is executed, the following actions occur:

- The existing `app`, `components`, `hooks`, `constants`, and `scripts` directories are moved into a new `app-example` directory.
- A new, blank `app` directory is created.
- New `app/index.tsx` and `app/_layout.tsx` files are created within the new `app` directory, effectively resetting the project to a fresh state.
