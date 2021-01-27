# CliverRoutines

A cross-platform C# lib which provides the frequently needed routines:

- application settings module superseding the one of Visual Studio;
- logger with multi-threading and session support;
- auxiliary routines;

It has been developed on .NET Standard 2.0 and supposed to run on any platform. 

Tested on:
- Windows 7, 10 in C# projects of any configuration built in Visual Studio;
- macOS High Sierra 10.12 in Xamarin.Mac projects built in Visual Studio for Mac;

## Application settings
It is easy to use aplication settings engine which is more versatile and flexible than the Visual Studio's one.

Features:
- class fields/properties in your code can be automatically serialazed/deserialazed on disk;
- serializable types are tailored in your code according to your needs;

## Logger 
Features:
- thread-safe;
- writting thead logs;
- simultaneous multiple log sessions;
- automatic old log cleanup; 

## Auxiliary routines 
Anything handy that is needed in general development.


## [More details...](https://sergeystoyan.github.io/CliverRoutines/#1)

To see live usage examples, refer to CliverRoutinesExample project. Also review my C# projects in github.
