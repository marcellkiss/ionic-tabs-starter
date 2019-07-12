These are Cordova resources. You can replace icon.png and splash.png and run
`ionic cordova resources` to generate custom icons and splash screens for your
app. See `ionic cordova resources --help` for details.

Cordova reference documentation:

- Icons: https://cordova.apache.org/docs/en/latest/config_ref/images.html
- Splash Screens: https://cordova.apache.org/docs/en/latest/reference/cordova-plugin-splashscreen/

## Commands

### Debug in Browser
`ionic serve`

### List connected devices
`adb devices`

### Debug on Device
`ionic cordova run android --device -l --debug`

### Build unsigned apk
`ionic cordova run android --prod --release`

### Install apk to device
`adb install -r ${APK_PATH}`

### Publish
https://ionicframework.com/docs/v1/guide/publishing.html
