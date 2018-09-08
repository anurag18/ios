# Build Setting Using XCConfig

Hi, Today we'll learn, how to use custom build setting.

## Prerequisite (Basic understanding)
XCConfig
BuildSetting
BuildConfiguration
InfoPlist

## Approach

## Create Build Configuration as per project Requirement
Example :- Debug,Release,SIT,Production,Stub
## Create XCConfig file (Name as per your project standard) which could be selected through different build configuration
Example :- Debug_Config,Release_Config,SIT_Config and so on.

## Define key value pair inside xcconfig file
## Now you can use those key inside info plist file for different setting like bundle identifier,icon and so on
## you can create and use different key value pair with respect to different build configuration and use in our application


## Below Diagram can help you to understand flow and usage.
![alt text](https://github.com/anurag18/ios/blob/xcconfig/Xcode_BuildSetting.png)

