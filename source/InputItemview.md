---
title: ItemView
date: 2020-5-26
tags:
---

#### 主要属性

| Name          | Type    | Description                  |
| ------------- | ------- | ---------------------------- |
| title         | string  | 左标题                       |
| hint          | string  | 提示                         |
| password      | boolean | 是否密码输入样式             |
| desc          | string  | 副标题提示                   |
| desc_gravity  | enum    | 副标题提示位置，[top,bottom] |
| lines         | integer | 输入行数                     |
| input_divider | boolean | 分割线                       |

#### 使用方法

##### 无标题

```xml
<com.viomi.vmui.VInputItem   
    android:layout_width="match_parent"   
	android:layout_height="wrap_content"    
    app:input_divider="true"   
    app:hint="提示语"
	app:lines="1" />
```

##### 密码

```xml
  <com.viomi.vmui.VInputItem
            android:id="@+id/item_password"
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:layout_marginTop="6dp"
            app:hint="提示语"
            app:lines="1"
            app:password="true"
            app:title="隐藏密码" />
```

##### 下标题

```xml
  <com.viomi.vmui.VInputItem
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:layout_gravity="bottom"
            android:layout_marginTop="6dp"
            app:desc="辅助说明文字不设字数限制"
            app:desc_gravity="bottom"
            app:hint="提示语"
            app:lines="1"
            app:title="单行输入" />
```

##### 多行输入

```xml
 <com.viomi.vmui.VInputItem
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:layout_marginTop="6dp"
            app:hint="提示语"
            app:title="多行输入" />
```

![InputItemView](images/inputitemview.gif)