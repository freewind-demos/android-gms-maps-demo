# Android Google Maps 地图演示

## 简介

本 Demo 演示 Google Maps 的基本集成。

## 基本原理

Google Maps SDK 允许在 Android 应用中显示地图。

## 教程

### 1. 获取 API Key

1. 在 Google Cloud Platform 创建项目
2. 启用 Maps SDK for Android
3. 创建 API Key

### 2. 添加依赖

```gradle
implementation 'com.google.android.gms:play-services-maps:18.2.0'
```

### 3. 添加地图

```xml
<fragment
    android:name="com.google.android.gms.maps.SupportMapFragment"
    android:id="@+id/map"
    android:layout_width="match_parent"
    android:layout_height="match_parent" />
```

## 注意事项

1. 需要 Google Play Services
2. 需要有效的 API Key
3. 需要在真机或配置了 Google Play 的模拟器上测试
