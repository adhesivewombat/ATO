# Mobile Application Design with Flutter
#### Randal Schwartz

## For a while smartphone vendors were like early computer vendors
* closed sourced widgets, gestures, apis, etc.
* traditionally releasing for multiple platforms was difficult
## Flutter
* mobile SDK complete with widgets, engine, framework, and tools
* Some people are using flutter for desktop apps
* Dart can be used for web and servers too
## What does flutter do?
* lowers barrier to entry
* speed up dev cycle (hot reaload)
* looks the same on both platforms (ios, and adroid)
* beautiful mobile UIs
* flutter uses Dart
    * strongly typed
> No prior mobile experience needed, even programming experience isn't very neccessary
* optimized for 2d mobile apps
* mimics stock platform look and feel
* Material UI team works closely with the flutter team to make sure flutter is always following MD
## Who makes and uses it?
* Google
    * replacement for android?
    * Used for "business critical" apps
* Open source
* Hunderdeds of apps already use it
## Is it prod ready?
* Almost
* They're working on v2 too
* needs more accessability options
* Google tracks github issues!
## How is flutter different from react-native?
* Flutter uses native code to use its own widgets
    * uses Canvas and Events
    * and platform channels to get to the service APIs
* Doesn't use webview or OEM widgets
* Looks the same on all devices
* Widgets are all in Dart
* Easily extendable
* The code is very compact
    * and app in 63 lines
* Hot reloading is _super_ quick
* [HUGE widget and animation library](https://docs.flutter.io/flutter/material/material-library.html#classes)
* Syntax is a little funny but not too bad
* State management???
* State is saved per class
* "reactive" style framework
* The framework is inspired by react and react-native
    * Widgets are extendable
* Test coverage publised for every commit
## Why does flutter exist?
* Using webview sucked
    * unoptimized
    * > _really really_ slow
* They started over from webviews
* Consistent behavior across all (mobile) platforms
## Technology
* Most of it is written in Dart
* Some of it is written in C++
* android copiled with android NDK
* ios is compiled with LLVM
* AOT-compiled to native code for deployment
* JITter is used for hot reload during dev
* ALL widgets are dart code
* can run in the background
## Performance
* ??
* Hot realoading is really fast
* Debugging seems 
## Vscode support
* yes :)
* ItelliJ too
    * community version
## Why Dart?
* JITter hot reload
    * dev speed
* AOT form ARM code
* can re-use code in Pub
* lowest possible latency
* strongly typed
## Questions
* How's the community?
    * > stackoverflow is very active
    * most of the work is done by google
* is there an API client lib (or is that built into dart)
    * how good is it?
* Desktop apps?
    * > something google's not committed to