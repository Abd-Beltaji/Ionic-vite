# ionic-vite

## About ℹ:
A boilerplate for android develeopment with ionic with a default _tabs template_ as an example.

### Used technologies:
+ Vite
+ Ionic 
+ React-TS(v18)
+ Capacitor(android) 
+ yarn
+ PostCSS
+ Tailwindcss
+ Typescript paths
+ react-router-dom(v5.3.3)
> **!** Could'nt use `react-router-dom@6` since a required package (`@ionic/react-router`) is not updated to use v6 yet.
## Usage: 📃
To use this boilerplate configuration, run the following commands:
```ps1
git clone https://github.com/Abd-Beltaji/Ionic-vite.git
cd ./ionic-vite
yarn
yarn cap:android
```

## Scripts: 📜
> **Usage:** `yarn SCRIPT` or `npm run SCRIPT`

+ `dev`: Run the development server for the application.
+ `pre-build`: A script that will automatically run before the project build, it deletes the remains of previous builds if exists.
+ `build`: Generate a build verion of the application (a web version still).
+ `preview`: Runs vite preview script.
### `android:###`:
+ `android:pre-build`: A script that will automatically run before the project build, it deletes the remains of previous android builds if exists.
+ `android:build`: Generate an android project from the current vite build that can be opened with something like _Android Studio_ or run directly into an emulator or connected device.
+ `android:run`: Runs the current application into an emulator or a connected android device.
+ `android:open`: Opens the generated android application project into a suitable development environment (Android Studio).
### `cap:###`:
+ `cap:android`: Automates the processes of loading the application into a desired target, will build a vite version of the project then generate the android build using _capacitor_ and finally, it'll run the generated application.


## Typescript path aliases: 🗺
This configuration contains predefined path aliases that route to certain locations, they are defined inside `tsconfig.paths.json`, you can add or modify them as your project requires.

| **Path-aliase** |  **Routes to:** |
|:---------------:|:---------------:|
| @components     | src/components/ |
| @pages          | src/pages/      |
| @styles         | src/styles/     |
| @assets         | src/assets/     |
| @hooks          | src/hooks/      |