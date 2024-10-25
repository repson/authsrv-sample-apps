## Android Sample App

To run the sample first set the Callback URL in the Application Settings to

```
demo://{yourDomain}/android/com.auth0.androidsample/callback
```

To run the sample first set the Logout URL in the Application Settings to

```
demo://{yourDomain}/android/com.auth0.androidsample/callback
```

Then, to run it from the command line:

Make sure the target device is available and install the App running the next command:

```
# In Linux / macOS
./gradlew installDebug
# In Windows
gradlew installDebug
```

On the Android device, locate the App icon on the App Drawer and click it to launch it.

To run it from the Android Studio IDE:

Open the project on Android Studio.

Click the Run button (The green play) or select the menu option Run | Run 'app' and then choose a target device.