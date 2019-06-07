---
layout: post
title:  提供商支持覆盖易于构建吐司和内部通知
tag: Notification
date: 2019-06-08
---

# [提供商支持覆盖易于构建吐司和内部通知 ](http://github.com/boyan01/overlay_support) 



## [查看Github/boyan01/overlay_support](http://github.com/boyan01/overlay_support)
## [立即下载 ️⬇️ ](https://codeload.github.com/boyan01/overlay_support/zip/master) 


 
![](https://flutterawesome.com/content/images/2019/02/overlay_support.gif)
 
>
> 提供商支持叠加，易于构建的吐司和内部通知。
>

 
# overlay_support 
[![Pub](https://img.shields.io/pub/v/overlay_support.svg)](https://pub.dartlang.org/packages/overlay_support)
[![Build Status](https://travis-ci.com/boyan01/overlay_support.svg?branch=master)](https://travis-ci.com/boyan01/overlay_support)
[![codecov](https://codecov.io/gh/boyan01/overlay_support/branch/master/graph/badge.svg)](https://codecov.io/gh/boyan01/overlay_support)

provider support for overlay, easy to build **toast** and **internal notification**.

**this library support platform Android、iOS 、Linux、macOS、Windows and Web**

## Interation

If you want to see the ui effect of this library, then click here [https://boyan01.github.io/overlay_support/#/](https://boyan01.github.io/overlay_support/#/)

## How To Use

1. add dependencies into you project pubspec.yaml file
```
dependencies:
  overlay_support: latest_version
```
2. import package into your dart file

```dart
import 'package:overlay_support/overlay_support.dart';
```

3. use `showSimpleNotification` method to show a notification at top of screen

```dart
showSimpleNotification(context,
    Text("this is a message from simple notification"),
    background: Colors.green);
```

more instructions check here :  [example/readme.md](./example/)

## License 

see License File

## End

if you have some suggestion or advice, please open an issue to let me known. 
This will greatly help the improvement of the usability of this project.
Thanks.
