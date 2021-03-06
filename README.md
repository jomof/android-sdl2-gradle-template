[![Build Status](https://travis-ci.org/jomof/cdep-android-studio-SDL2-sample.svg?branch=master)](https://travis-ci.org/jomof/cdep-android-studio-SDL2-sample)

# android-sdl2-gradle-template

## Synopsis

This is an example project for using libSDL2 (https://www.libsdl.org/) in an Android Gradle project using the [CDep](https://github.com/jomof/cdep)  dependency management tool to download the SDL2 package rather than building it. 

The latest version of CDep SDL2 package is here:

[![CDep Status](https://cdep-io.github.io/com.github.jomof/sdl2/latest/latest.svg)](https://github.com/jomof/sdl2/releases/latest)


## Instructions

All you need to do is clone this project, run CDep, and build.

```
git clone https://github.com/jomof/cdep-android-studio-SDL2-sample
cd cdep-android-studio-SDL2-sample
./cdep
./gradlew assemble
```
You can also open the project in Android Studio and run it.

## Thanks

This project is forked from https://github.com/stephen47/android-sdl2-gradle-template which was very helpful. 

### The author of that project also had these thanks.

The example libSDL2 program which draws the square on screen was found at https://stackoverflow.com/questions/21890627/drawing-a-rectangle-with-sdl2/21903973#21903973.

This guide was incredibly useful while I tried to figure out how to get this working: http://lazyfoo.net/tutorials/SDL/52_hello_mobile/android_linux/index.php

The Google NDK example projects were very helpful: https://github.com/googlesamples/android-ndk
