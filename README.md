Cordova Game plugin
====================
```c
Modify Plugin with Fred Oliveira and Elmer Nanches for support Cordova Android 7.x.x and 8.x.x
```
 
[android, ios] [cordova cli]

Requires google play developer account https://play.google.com/apps/publish/<br>

# Install Platform Android 8#
```c
cordova platform add android@8.0.0
```

# Install plugin #
```c
cordova plugin add https://github.com/guimaraf/cordova-plugin-game --variable APP_ID="YOUR APP ID"

[Example:]
cordova plugin add https://github.com/guimaraf/cordova-plugin-game --variable APP_ID="123456789012"

You need to install the plugin from the repository in Github, to use the dependencies already configured and tested for the respective APIs 27 and API 28, with 28 being required for new APPs for the next month, August 2019.

Build your apps on API 28
```

# Remove Plugin#
```c
cordova plugin remove cordova-plugin-game --variable APP_ID="YOUR APP ID"

[Example:]
cordova plugin remove cordova-plugin-game --variable APP_ID="123456789012"
```