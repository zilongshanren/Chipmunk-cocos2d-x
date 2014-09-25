Chipmunk-cocos2d-x
==================
- This is NOT the official Chipmunk standalone project. Official website
  is [here](https://chipmunk-physics.net)
- the version of Chipmunk is 6.2.1

## Prerequisite

You must setup ANDROID_NDK environment in your ~/.bashrc file to point to your NDK directory.

##Build

###Build for Android
```cpp
./build_android.sh
```

###Build for iOS and Mac
Change the following line to match your own iOS SDK version

```cpp
IOS_SDK_VERSION="7.1"
```

```cpp
./build_iosmac.sh
```


##Build for Linux
```cpp
./build_linux.sh
```

##Build for Windows, WP8 and WinRT
1. Generate VS project file from CMakeLists.txt

2. Compile the static library.
