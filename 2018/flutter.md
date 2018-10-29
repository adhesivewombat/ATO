# Mobile Application Design with Flutter
#### Randal Schwartz

## For a while smartphone vendors were like early computer vendors
* Closed sourced widgets, gestures, apis, etc.
* Traditionally releasing for multiple platforms was difficult
## Flutter
* Mobile SDK complete with widgets, engine, framework, and tools
* Some people are using flutter for desktop apps
* Dart can be used for web and servers too
## What does flutter do?
* Lowers barrier to entry
* Speed up dev cycle (hot reaload)
* Looks the same on both platforms (ios, and adroid)
* Beautiful mobile UIs
* Flutter uses Dart
    * Strongly typed
> No prior mobile experience needed, even programming experience isn't very neccessary
* Optimized for 2d mobile apps
* Mimics stock platform look and feel
* Material UI team works closely with the flutter team to make sure flutter is always following MD
## Who makes and uses it?
* Google
    * Replacement for android?
    * Used for "business critical" apps
* Open source
* Hunderdeds of apps already use it
## Is it prod ready?
* Almost
* They're working on v2 too
* Needs more accessability options
* Google tracks github issues!
## How is flutter different from react-native?
* Flutter uses native code to use its own widgets
    * Uses Canvas and Events
    * And platform channels to get to the service APIs
* Doesn't use webview or OEM widgets
* Looks the same on all devices
* Widgets are all in Dart
* Easily extendable
* The code is very compact
    * And app in 63 lines
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
    * Unoptimized
    * > _really really_ slow
* They started over from webviews
* Consistent behavior across all (mobile) platforms
## Technology
* Most of it is written in Dart
* Some of it is written in C++
* Android copiled with android NDK
* Ios is compiled with LLVM
* AOT-compiled to native code for deployment
* JITter is used for hot reload during dev
* ALL widgets are dart code
* Can run in the background
## Performance
* ??
* Hot realoading is really fast
* Debugging seems 
## Vscode support
* Yes :)
* ItelliJ too
    * Community version
## Why Dart?
* JITter hot reload
    * Dev speed
* AOT form ARM code
* Can re-use code in Pub
* Lowest possible latency
* Strongly typed
## Questions
* How's the community?
    * > stackoverflow is very active
    * Most of the work is done by google
* Is there an API client lib (or is that built into dart)
    * How good is it?
* Desktop apps?
    * > Something google's not committed to