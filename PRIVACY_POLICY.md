## RunningScore: Privacy policy

Welcome to the RunningScore app for Android!

As an avid Android user myself, I take privacy very seriously.
I know how frustrating it is when apps collect your data without your knowledge.

### Data collected by the app

I hereby state, to the best of my knowledge and belief, that I have not programmed this app to collect any personally identifiable information. All data (app preferences (like theme) and alarms) created by the you (the user) is stored locally in your device only, and can be simply erased by clearing the app's data or uninstalling it. No analytics software is present in the app either.

### Explanation of permissions requested in the app

The list of permissions required by the app can be found in the `AndroidManifest.xml` file:
 
         
    <uses-permission android:name="android.permission.ACCESS_FINE_LOCATION" />

    <uses-permission android:name="android.permission.ACCESS_COARSE_LOCATION" />

    <uses-permission android:name="android.permission.FOREGROUND_SERVICE" />
    <uses-permission android:name="android.permission.WAKE_LOCK" />
    <uses-permission android:name="android.permission.READ_EXTERNAL_STORAGE" />
    <uses-permission android:name="android.permission.WRITE_EXTERNAL_STORAGE" />



| Permission | Why it is required |
| :---: | --- |
| `android.permission.ACCESS_FINE_LOCATION` | Request foreground location access to get the running data(time, distance) |Permission automatically granted by the system; can't be revoked by user. |
| `android.permission.ACCESS_COARSE_LOCATION` | Request foreground location access to get the running data(time, distance) Permission automatically granted by the system; can't be revoked by user. |
| `android.permission.FOREGROUND_SERVICE` | Enables the app to create foreground services that will track the distance and time. Permission automatically granted by the system; can't be revoked by user. |
| `android.permission.WAKE_LOCK`  Required to the show running screen when finished the run . Automatically granted by the system; cannot be revoked by user. |
`android.permission.READ_EXTERNAL_STORAGE` | THis permission is used to read the running data (time, distance) 
`android.permission.WRITE_EXTERNAL_STORAGE` | This permission is used only to save the running data(time , distance) so user can track easily their running data  




If you find any security vulnerability that has been inadvertently caused by me, or have any question regarding how the app protectes your privacy, please send me an email and I will surely try to fix it/help you.

Yours sincerely,  
Btnisme123 

btnisme123@gmail.com
