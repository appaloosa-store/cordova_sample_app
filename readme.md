# Demo application to test Cordova Appaloosa Plugin

First of all set STORE_ID and STORE_TOKEN constants with your values from www.appaloosa-store.com inside the `cordova_sample_app/www/js/index.js` file at line #32-33.

## Run the application

To run the application open a terminal window, go to application's folder and run the following commands.
### Add the platform:

```
cordova platform add ios
```

### Add Cordova Appaloosa Plugin

To add cordova-plugin-appaloosa (that currently released (v1.1.1)) run:

```
cordova plugin add cordova-plugin-appaloosa
```

To add the updated cordova-plugin-appaloosa with iOS SDK 1.0.0 first, clone or download last changes of cordova-plugin-appaloosa from GitHub after merge and run the command below in demo application's folder. 

```
cordova plugin add --link %PATH TO DOWNLOADED%
```

> NOTE: In case of you have already added cordova-plugin-appaloosa (v1.1.1) remove it using the following command before adding the updated one:

```
cordova plugin rm cordova-plugin-appaloosa
```

Open Xcode project (%PATH TO THE PROJECT% /cordova_sample_app/platforms/ios/AppaloosaDemo.xcworkspaace) and choose development team.

### Deploy the application to Appaloosa store
1. Make *.ipa file and upload it to the Appaloosa store;
2. Download it to your device and run it.

After all of these steps will be done you'll see the alerts: about success authorization and info about having the update.
