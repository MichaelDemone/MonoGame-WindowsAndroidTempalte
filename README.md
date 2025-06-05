# Overview
This is a Monogame template to enable developing a game on both Windows and Android.

# Prerequisites
- [.Net8.0](https://dotnet.microsoft.com/en-us/download/dotnet/8.0)
- Run `dotnet workload install android` from the CLI

# Building and Deploying Android
- Run `dotnet build` in `AndroidEntry` to build the android version
- Deploy to your android with `adb install -r -t ./bin/Debug/net8.0-android/AndroidEntry.AndroidEntry-Signed.apk`

# Building and Deploying Windows
- Run `dotnet run` in `WindowEntry` and it will launch the game.

# Debugging Windows
- Install Visual Studio Code
- Download C# Extension and C# Dev Kit extension
- Go to the debugger tab
- Run with ".Net Launch WindowsEntry"

# Debuggin Android 
- I haven't tried it yet, if you know please open a PR!
