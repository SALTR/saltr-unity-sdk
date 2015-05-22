#SALTR Unity SDK


This is the README file of the SALTR Unity SDK.

To clone the project from GitHub:
<a href="https://github.com/SALTR/saltr-unity-sdk.git">https://github.com/SALTR/saltr-unity-sdk.git</a>

To download the latest ZIP:
<a href="https://github.com/SALTR/saltr-unity-sdk/archive/master.zip">https://github.com/SALTR/saltr-unity-sdk/archive/master.zip</a>


1. INTRODUCTION
===============

SALTR Unity SDK is a library of classes which help to develop mobile 
games that are to be integrated with SALTR platform.

This SDK performs all necessary and possible action with SALTR REST API to connect, update, set 
and download data related to game's features or levels.

All data received from SALTR REST API is parsed and represented through set of instances of classes, 
each carrying specific objects and their properties.

Basically SDK, as the REST API, has few simple actions. The most important one is connecting (GetAppData), 
which loads the app data objects containing features, experiments and level headers.

This and other actions will be described in the sections below.


2. USAGE
========

To use the SDK you need to download/clone SDK repository and then import files to your
project.

To clone Git repository via command line:
```
$ git clone https://github.com/SALTR/SaltrUnitySdk.git
```

The entry point is the SaltrUnity clas. You should create an empty game object and attach SaltrUnity as a script component.

3. DIRECTORY STRUCTURE
======================

The SDK has the following directory structure:

- Saltr.UnitySdk - main namespace of library;
- Saltr.UnitySdk.Domain - all domain classes;
- Saltr.UnitySdk.Domain.InternalModel - internal model classes;
- Saltr.UnitySdk.Domain.Model - all user accessible model classes;
- Saltr.UnitySdk.Domain.Model.Canvas - model classes for canvas based games;
- Saltr.UnitySdk.Domain.Model.Matching - model classes for board based games;
- Saltr.UnitySdk.Network - network classes to communicate with SALTR REST API;
- Saltr.UnitySdk.Repository - repository classes to load and save data into temp or local storage;
- Saltr.UnitySdk.Utils - local data repository classes (implementation widely varies through platforms);
- Saltr.UnitySdk - status classes representing warnings and error statuses used within library code;
