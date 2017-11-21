## PRE REQ
1-) Java 
2-) Android
3-) Nodejs
4-) Cordova
5-) Google Firebase Account

## INSTALLATION && BUILD

After setting up java && android ( 25 and later )

* create a new cordova app with 
```
cordova create samplepush com.samplepush.app
``` 
![ScreenShot](https://github.com/Lethea/cordova-android-firebase-push-notifications/blob/master/sampleimages/createProject.png?raw=true)

* register https://console.firebase.google.com 

![ScreenShot](https://github.com/Lethea/cordova-android-firebase-push-notifications/blob/master/sampleimages/Screenshot_1.png?raw=true)

* create a new project and add fcm to android project
![ScreenShot](https://github.com/Lethea/cordova-android-firebase-push-notifications/blob/master/sampleimages/Screenshot_2.png?raw=true)
( You need to change google json with yours at the project root) 
![ScreenShot](https://github.com/Lethea/cordova-android-firebase-push-notifications/blob/master/sampleimages/Screenshot_3.png?raw=true)

![ScreenShot](https://github.com/Lethea/cordova-android-firebase-push-notifications/blob/master/sampleimages/Screenshot_4.png?raw=true)

* Run in your project directory
``` 
cordova plugin add cordova-plugin-firebase@0.1.24 --save
```

* Add android platform to your project
``` 
cordova platform add android
```

* Build and Run your app
```
cordova run android 
```
Also you can consider of building debug.apk and install your mobile phone .

* Go to google fcm console and send your first message

![ScreenShot](https://github.com/Lethea/cordova-android-firebase-push-notifications/blob/master/sampleimages/Screenshot_7.png?raw=true)

![ScreenShot](https://github.com/Lethea/cordova-android-firebase-push-notifications/blob/master/sampleimages/Screenshot_8.png?raw=true)

![ScreenShot](https://github.com/Lethea/cordova-android-firebase-push-notifications/blob/master/sampleimages/Screenshot_9.png?raw=true)

![ScreenShot](https://github.com/Lethea/cordova-android-firebase-push-notifications/blob/master/sampleimages/Screenshot_10.png?raw=true)
