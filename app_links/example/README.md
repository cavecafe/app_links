# app_links_example

Demonstrates how to use the app_links plugin.

## Test on Android

```sh
adb shell am start -a android.intent.action.VIEW \
  -d "callavo://callavo.dev/#/user/thomas"
```

## Test on iOS

```sh
/usr/bin/xcrun simctl openurl booted "callavo://callavo.dev/#/user/thomas"
```

## Test on windows & macOS
Open your browser and type in your address bar:
```
callavo://foo/#/user/thomas
```

