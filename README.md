# baseframe

是Android项目的根目录用于设置公共的组件

## 项目结构图

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://flutter.dev/docs/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://flutter.dev/docs/cookbook)

For help getting started with Flutter, view our
[online documentation](https://flutter.dev/docs), which offers tutorials,
samples, guidance on mobile development, and a full API reference.

## 修改方式

##### 根据实际项目的路径修改 gradle.properties 对应的属性  
aar.baseframe=/Volumes/sdcard/project/t-arkAndroid/BaseFrame/baseframe/repository  
##### 修改版本号升级  
PUBLISH_VERSION = '0.0.2'

## 引用方法 
##### 在根目录的build.gradle中加入
allprojects {
        repositories {
            ...
            maven { url 'https://jitpack.io' }
        }
    }
##### 在所要引入的moudel加入
implementation 'androidx.core:core-ktx:1.1.0'

