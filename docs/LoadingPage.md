---
title: LoadingPage
date: 2019-11-29 14:48:17
tags:
---
LoadingPage共用VEmptyPage

#### 使用方法

```xml
<com.viomi.vmui.VEmptyPage
        android:id="@+id/empty"
        android:layout_width="match_parent"
        android:layout_height="match_parent"
        app:empty_loading="true"
        app:empty_process="60"
        app:empty_button="操作描述"
        app:empty_subtitle="这里显示的是辅助文字，颜色可改"
        app:empty_title="标题文字" />
```
![LoadingPage](images/loadingpage.png)