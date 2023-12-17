# ADBForwarder

Console application designed to handle forwarding TCP Ports (using [ADB](https://developer.android.com/studio/command-line/adb)) between your PC and Quest/Go HMDs, over USB

Specifically made for use with [ALVR](https://github.com/alvr-org/ALVR), for now. Supports the Oculus Go, Quest 1, 2, 3, and Pico 4/Neo 3.

### [Download here!](https://github.com/AtlasTheProto/ADBForwarder/releases/latest/download/ADBForwarder.zip)

## Usage

* [Download the latest release](https://github.com/AtlasTheProto/ADBForwarder/releases/latest/download/ADBForwarder.zip)
* Extract the archive somewhere convenient
* Run the program and ALVR, order does not matter
* ALVR may (or may not) restart
* You should see your device's serial ID show up in the console, if it says the following, all is well!
    * `Successfully forwarded device: 1WMHHXXXXXXXXX [hollywood]`
    * "eureka" is Quest 3 "hollywood" is Quest 2, "monterey" is Quest 1, "pacific" is Go
    * "a7h10" is pico 3 + link, "phoenix_ovs" is pico 4

# Support

|      VR Headset       |                                Support                                 |
| :-------------------: | :--------------------------------------------------------------------: |
|     Quest Go/1/2/3    |                           :heavy_check_mark:                           |
|       Quest Pro       |                           :x:                                          |
|     Pico 4/Neo 3      |                           :heavy_check_mark:                           |

## Windows

If the program won't run, try installing the [DotNet 4.6.1 Runtime](https://www.microsoft.com/en-us/download/details.aspx?id=49982)

## Linux

You need to use [Mono](https://www.mono-project.com/download/stable/)

## Problems?

Don't hesitate to raise an [issue](https://github.com/goodguy140/ADBForwarder/issues) if you encounter problems!

## Attributions

Thank you, [Mantas-2155X](https://github.com/Mantas-2155X), for iterating and refactoring my work, to bring Linux support!

Thank you, [Quamotion](https://github.com/quamotion), for [SharpADBClient](https://github.com/quamotion/madb)!

Thank you, [AtlasTheProto](https://github.com/AtlasTheProto), for adding newer headsets and other misc work.
