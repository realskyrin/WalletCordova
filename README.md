## How to build on Android

 1. Install Android SDK and Cordova 3.5
 2. `cd` to the WalletCordova directory
 3. Run `android update project --path platforms/android --subprojects`
 4. Run `android update project --path facebook-android-sdk-3.7/facebook`
 5. Run `cordova build android`

After following these steps you should get a debug apk file in `platforms/android/ant-build/GreenAddressIt-debug.apk`.


## How to build on iOS

 1. Install Xcode and Cordova 3.5
 2. `cd` to the WalletCordova directory
 3. Run `cordova build ios`

After following these steps you should get an .app in platforms/ios/build/emulator/GreenAddress.It.app.