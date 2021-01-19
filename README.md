# flutter-appsize-testing-project
I created this project to find a way reducing app size.

How does Flutter contribute to build size?

I used this starter project to analysis the build size of an App that built as Flutter App.

## Android

![Android App Size Overview](flutter_empty_android_release_size.png)

The biggest space is placed by lib folder with 2 .so files for three architectures:
1. libapp.so
2. libflutter.so

The APK size is 15.3MB for an empty Flutter Starter project. It contains three architectures inside it:
1. x86_64
2. arm64-v8a
3. armeabi-v7a

## iOS

### The iOS archive file size

![Flutter.framework](flutter_empty_ios_archive_size.png)

### The Frameworks Folder.

![All Frameworks Size](flutter_empty_all_framework_size.png)

It includes 2 Flutter frameworks:
1. App.framework (8.8MB)
2. Flutter.framework (14MB)

### More details about App.framework

![App.framework](flutter_empty_app_framework_size.png)

### More details about Flutter.framework

![Flutter.framework](flutter_empty_flutter_framework_size.png)




