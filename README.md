#SALTR Unity SDK
* Modified: May 22th, 2015
* Unity Plug-in Version: 1.4.0

Other supported platforms:
* [iOS SDK Version: 1.3.3](https://github.com/SALTR/saltr-ios-sdk)
* [Android SDK Version: 1.1.1](https://github.com/SALTR/saltr-android-sdk)
* [AS3 SDK Version: 1.3.6](https://github.com/SALTR/saltr-as3-sdk)


##Getting Started with SALTR Unity
Please read [SALTR Unity SDK Setup](https://saltr.com/setup#/unity) doc.

###SALTR Package Contains:
* `Saltr.UnitySdk` - main namespace of library;
* `Saltr.UnitySdk.Domain` - all domain classes;
   * `Saltr.UnitySdk.Domain.InternalModel` - internal model classes;
   * `Saltr.UnitySdk.Domain.Model` - all user accessible model classes;
   * `Saltr.UnitySdk.Domain.Model.Canvas` - model classes for 2D canvas based games;
   * `Saltr.UnitySdk.Domain.Model.Matching` - model classes for board based games;
* `Saltr.UnitySdk.Network` - network classes to communicate with SALTR REST API;
* `Saltr.UnitySdk.Repository` - repository classes to load and save data into temp or local storage;
* `Saltr.UnitySdk.Utils` - utilities and extensions;


##To Download
The SALTR Unity SDK Package is [Available Here for download](https://github.com/SALTR/saltr-unity-sdk/raw/master/Packages/Saltr.unitypackage).

##To Install
SALTR Unity SDK is a standard .unitypackage that can be imported into your project.

To clone Git repository via command line:
```
$ git clone https://github.com/SALTR/saltr-unity-sdk.git
```

The entry point is the `SaltrUnity` class. You should create an empty game object and attach SaltrUnity as a script component.

##Introduction

Easily integrate SALTR Unity SDK into your games or apps to get real-time control over settings, user experience tweaking, customization and level design. 
With SALTR you and your team will have availability to:
* Update any app settings, prices and values for your users. 
* Target you most important users by delivering specific configuration only to them - again in real-time. Use segmenting with user filtering based on advances set of standard and custom criteria.
* Create experiments testing any feature and level modifications against each other. Manage intensity and type of user traffic flowing into your experiments partitions.
* Design levels in real-time. Connect team memeber devices and allow them to tweak levels, features and setting simultainously without interfeering with each other. Continue balancing your levels in real-time even after game is released, without ned to bother your dev team to deliver next app update.
* Measure your impact on each segment, experiment partition, and be able to take action right-away. 
* No updates needed on App Store, Google Play or etc.. 
* Much more...

This SDK performs all necessary and possible action with SALTR REST API to connect, update, set 
and download data related to game's features or levels.

All data received from SALTR REST API is parsed and represented through set of instances of classes, 
each carrying specific objects and their properties.

Basically SDK, as the REST API, has few simple actions. The most important one is connecting (GetAppData), 
which loads the app data objects containing features, experiments and level headers.


##Contact Us
For more information, please visit [saltr.com](https://saltr.com). For questions or assistance, please email us at support@saltr.com.


