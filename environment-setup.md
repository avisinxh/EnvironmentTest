# Environment Setup for EnvironmentTest

## 1. System Specifications
- **Operating System:** Windows 10/11 64-bit
- **Processor (CPU):** Intel Core i5 / AMD Ryzen 5 (your CPU)
- **RAM:** 16 GB (example)
- **Disk Space:** 500 GB SSD
- **Graphics:** Intel UHD / NVIDIA / AMD (your GPU)

## 2. Software Versions Installed
- **Node.js:** 20.3.1
- **npm:** 10.3.0
- **React Native CLI:** 0.82.1
- **Java Development Kit (JDK):** 11
- **Android Studio:** Arctic Fox / Chipmunk (version)
- **Android SDK Platform:** 33
- **CMake:** 3.22.1
- **Gradle:** 9.0
- **VS Code:** 1.XX.X
- **Emulator:** Pixel 6 API 33

## 3. Setup Steps Followed
1 Installed Node.js and npm from [nodejs.org](https://nodejs.org/).  
2 Installed Yarn
  npm install -g yarn

3 Installed React Native CLI globally:  
   ```bash
   npm install -g react-native-cli 
...but this didnt work so

  npx @react-native-community/cli init EnvironmentTest
did this

and then it worked

4 Ran android Build
 cd android
.\gradlew.bat clean
cd ..
npx react-native run-android

