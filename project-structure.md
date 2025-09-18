EnvironmentTest/
├── android/ # Android native project files (Gradle build system, Java/Kotlin code)
│ └── app/build.gradle # Android build configuration (dependencies, SDK versions, signing configs)
│
├── ios/ # iOS native project files (Xcode project, Swift/Obj-C code)
│ └── EnvironmentTest/Info.plist # iOS app configuration (app name, permissions, metadata)
│
├── node_modules/ # Installed npm packages (external dependencies managed by npm)
│
├── src/ # (Empty by default — we will create this folder to organize custom components)
│
├── App.js # Main React Native component. Defines the UI and logic of the app.
│
├── index.js # Entry point of the app. Registers the App component with React Native.
│
├── package.json # Project configuration file. Lists dependencies, scripts, app metadata.
│
├── README.md # Project documentation. Used to describe the project and setup steps.


---

## Key Files Explained

- **App.js**  
  Contains the main React component of the application. This is where the UI is defined using JSX and React Native components. In Exercise 3, we will modify this file to show personal information and course goals.

- **index.js**  
  The true entry point of the app. It imports the `App` component and registers it using `AppRegistry.registerComponent()`. This is how React Native knows which component to run.

- **package.json**  
  A JSON file that stores metadata about the project (name, version, scripts) and all npm dependencies. It also contains useful npm scripts such as `npm start`, `npm run android`, and `npm run ios`.

- **android/app/build.gradle**  
  Gradle configuration file for the Android project. It defines Android SDK versions, app identifiers, dependencies, and build settings.

- **ios/Info.plist**  
  A property list file that configures the iOS application. It includes app name, permissions (e.g., camera, location), and app identifiers used by iOS.
