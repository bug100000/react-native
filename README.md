# react-native
native
* 红屏的情况　[点击这里]()   
如下：   

1- Create a new folder => android/app/src/main/assets

2- Run this command =>

 react-native bundle --platform android --dev false --entry-file index.android.js --bundle-output android/app/src/main/assets/index.android.bundle --assets-dest android/app/src/main/res  
This command will create 2 files : index.android.bundle & index.android.bundle.meta

3- run command => react-native run-android
