1. Clone minimum reproducable example repo [https://github.com/BrandonYuen/expo-launch-args-issue](https://github.com/BrandonYuen/expo-launch-args-issue)
2. `npm install`
3. Create build `eas build --profile development --platform android` (did not test on iOS)
4. Launch the Android app with Launch Arguments
   a. Install [Maestro](https://maestro.mobile.dev/getting-started/installing-maestro) and run `maestro test -e APP_ID=com.brandonshiftbase.expolaunchargsissue .maestro`
   b. Any other method of launching the app with launch arguments
5. App will show Alert with Launch Arguments (empty with development build) on startup
