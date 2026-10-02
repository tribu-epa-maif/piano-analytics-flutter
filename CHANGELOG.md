## 1.1.3
* Fixed `lateinit property reportUrlProvider has not been initialized` error on Android when `init()` is called after the Flutter engine has been recreated or from another Flutter engine
* Updated Piano Analytics Android SDK to 3.6.0
* Android minSdk is now 23 (required by Piano Analytics Android SDK 3.6.0)

## 1.1.2
* Fixed crash when setting an empty array property on Android
* Fixed DateTime values being sent as microseconds instead of milliseconds to the native SDKs

## 1.1.1
* Added SPM support

## 1.1.0

* Calling init() multiple times with different site and collect domain will now update the site and collect domain

## 1.0.2

* Added feature to customize HTTP requests

## 1.0.1
* PianoConsents has been moved to the piano_consents package
* Added feature to specify property type via forceType argument
* Added new features for privacy customization
* Added new features for user customization
* Added feature for set visitorId

## 1.0.0

* Added plugins for PianoAnalytics and PianoConsents
