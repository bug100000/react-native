# react-native
native
* 红屏的情况　[点击这里](https://ikda.cc/question/5980264eb3a5cd6ab565e2db)   
如下：   

1- Create a new folder => android/app/src/main/assets

2- Run this command =>

 react-native bundle --platform android --dev false --entry-file index.android.js --bundle-output android/app/src/main/assets/index.android.bundle --assets-dest android/app/src/main/res  
This command will create 2 files : index.android.bundle & index.android.bundle.meta

3- run command => react-native run-android
* 开启安卓开发平台自带的模拟器时，无法开启。
[点击这里](https://stackoverflow.com/questions/37063209/waiting-for-device-to-come-online-running-android-emulator-from-android-studi?rq=1)

