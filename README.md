# sms-gps-position
Android app. Send sms to get gps location<br>
Nice way to locate an Android phone that is out of reach from 4G/5G. This app uses sms to get the geolocation from the phone.<br>
You configure a password and send list in the app. Please make sure that you get all checkmarks green in the app. It will not work without these permissions.
Syntax:<b>
Position PASSWORD
<p></p>

No root needed.
Use Android platform-tools if you want to be able to turn on the GPS via sms
<p></p>
./adb devices<br>
./adb shell pm grant se.duelago.positionsms android.permission.WRITE_SECURE_SETTINGS
<p></p>

Installation instructions:
https://www.youtube.com/watch?v=35m-dkL-De8
