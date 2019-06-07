---
layout: post
title:  100％共享代码Android-iOS登录示例
tag: Authentication
date: 2019-06-08
---

# [100％共享代码Android-iOS登录示例 ](http://github.com/AppleEducate/flutter_login) 



## [查看Github/AppleEducate/flutter_login](http://github.com/AppleEducate/flutter_login)
## [立即下载 ️⬇️ ](https://codeload.github.com/AppleEducate/flutter_login/zip/master) 


 
![](https://flutterawesome.com/content/images/2018/10/flutter_login.jpg)
 
>
> 此示例使用ScrollView，JSON Rest API，导航，警报弹出，进度指示器，全局，共享资源文件夹中的图像以及100％共享代码。
>

 
# Flutter Login Example

This example uses a ScrollView, JSON Rest API, Navigation, Alert Pop Up, Progress Indicator, Globals, Images in a shared asset folder, and 100% Shared Code. Now with the ability to login with FaceID, TouchID, and Fingerprint Reader on Android. 

### New Features
* Auto Login
* Enhanced Security with Bio
* Menu and Logout
* Dark Mode and True Black
* Settings Page
* Auth Service
* What's New Page
* Remember Me Toggle
* Custom Theme
* Scoped Model
* Automatic Json using [json_serializable](https://flutter.dev/docs/development/data-and-backend/json)

## Getting Started

Clone or Fork Project to get started.

### Prerequisites

Flutter SDK, Android Studio or Other Compatible IDE.

#### iOS Integration

Note that this plugin works with both TouchID and FaceID. However, to use the latter,
you need to also add:

```
<key>NSFaceIDUsageDescription</key>
<string>Why is my app authenticating using face id?</string>
```

to your Info.plist file. Failure to do so results in a dialog that tells the user your
app has not been updated to use TouchID.


#### Android Integration

Update your project's `AndroidManifest.xml` file to include the
`USE_FINGERPRINT` permissions:

```
<manifest xmlns:android="http://schemas.android.com/apk/res/android"
          package="com.example.app">
  <uses-permission android:name="android.permission.USE_FINGERPRINT"/>
<manifest>
```

#### Sticky Auth

You can set the `stickyAuth` option on the plugin to true so that plugin does not
return failure if the app is put to background by the system. This might happen
if the user receives a phone call before they get a chance to authenticate. With
`stickyAuth` set to false, this would result in plugin returning failure result
to the Dart app. If set to true, the plugin will retry authenticating when the
app resumes.

## screenshots
<p align="center">
  <img src="https://github.com/AppleEducate/flutter_login/blob/master/screenshots/home.png" width="350"/>
  <img src="https://github.com/AppleEducate/flutter_login/blob/master/screenshots/ios_screenshot.png" width="350"/>
</p>

### Settings Page and Menu (Including Dark Mode)
<p align="center">
  <img src="https://github.com/AppleEducate/flutter_login/blob/master/screenshots/menu.png" width="350"/>
  <img src="https://github.com/AppleEducate/flutter_login/blob/master/screenshots/settings.png" width="350"/>
</p>

## Built With

* [Flutter](https://flutter.io) - Crossplatform App Development Framework

## Contributing
Please submit a pull request if you want to help the project grow. The goal is to be able to fork the project and have a login module for your app complete so that a new project can be started quickly and customized to the user's needs.

Please read [CONTRIBUTING.md](https://gist.github.com/PurpleBooth/b24679402957c63ec426) for details on our code of conduct, and the process for submitting pull requests to us.

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/your/project/tags). 

## Authors

* **Rody Davis** - *Initial work* - [Rody Davis](https://github.com/AppleEducate)

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* https://flutter.io/networking/
* https://github.com/bramvbilsen/Flutter-HTTP-Requests-REST-api
* https://github.com/Solido/awesome-flutter
* https://reqres.in
* https://github.com/GeekyAnts/FlatApp-Flutter
