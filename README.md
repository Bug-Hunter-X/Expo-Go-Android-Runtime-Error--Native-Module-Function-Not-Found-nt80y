This repository demonstrates a bug encountered when using a custom native module within an Expo application running on an Android device via Expo Go. The issue arises specifically when the application is executed using Expo Go, resulting in a runtime error indicating that a method within the native module is not found. This problem does not manifest when a standalone APK is built. The bug.js file contains the problematic code, and bugSolution.js provides a resolution.

## Bug Reproduction Steps

1. Clone this repository.
2. Run `npm install` or `yarn install` to install dependencies.
3. Start the development server using `expo start`.
4. Run the application in Expo Go on an Android device.
5. Observe the runtime error.
6. Build a standalone APK using `expo prebuild` and `expo build:android`.
7. Run the standalone APK on the same Android device, and observe the successful execution.