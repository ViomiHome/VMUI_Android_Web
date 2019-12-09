---
title: VMUI-android
date: 2019-12-02 16:06:11
tags:
---

VMUI-Android:云米 Android app UI组件库  

demo源码：[VMUI-android](https://github.com/ViomiHome/VMUI_Android)  

demo apk :[demo apk](https://github.com/ViomiHome/VMUI_Android_Web/blob/gh-pages/vmui.apk?raw=true)

#### 集成步骤

1.在项目build.gradle中加入

```
allprojects {
   repositories {
       maven { url "https://raw.githubusercontent.com/ViomiHome/viomi_sdk/master" } 
    }
}
```

2.在dependencies中加入

```
api 'com.viomi.vmui_android:viomi-vmui_android-lib:1.0.1'
```