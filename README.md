# ionic Google Map

## Screenshot

| iOS | Android |
|:------------:|:------------:|
|![Screenshot iOS](https://raw.githubusercontent.com/wiki/betchi/ionic-google-map/images/screenshot_ios.png) | ![Screenshot Android](https://raw.githubusercontent.com/wiki/betchi/ionic-google-map/images/screenshot_android.png) |

## Development

You will need to set up an API key for use Google API,
And you put your API Key in the URL.

*www/index.html*

```html:www/index.html
<script src="http://maps.google.com/maps/api/js?key=[Please input API KEY!]"></script>
```

### To run in the browser

```
npm install
bower install ngCordova
ionic setup sass
ionic serve
```

### To run in iOS device

In addition to the above

```
ionic plugin add cordova-plugin-geolocation

ionic platform add ios
ionic build ios
ionic run ios
```

### To run in Android device

In addition to the above

```
ionic platform add android
ionic build android
ionic run android
```

### Link

**Google Maps API**

https://developers.google.com/maps/documentation/javascript/

**icon**

https://icons8.com
