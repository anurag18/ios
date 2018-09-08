# Build Setting Using XCConfig

Hi, Today we'll learn, how to use custom build setting.

## Prerequisite (Basic understanding)
XCConfig
BuildSetting
BuildConfiguration
InfoPlist

## Approach (Steps)

1> Create Build Configuration as per project Requirement
Example :- Debug,Release,SIT,Production,Stub
2> Create XCConfig file (Name as per your project standard) which could be selected through different build configuration
Example :- Debug_Config,Release_Config,SIT_Config and so on.

3> Define key value pair inside xcconfig file
4> Now you can use those key inside info plist file for different setting like bundle identifier,icon and so on
5> you can create and use different key value pair with respect to different build configuration and use in our application


### Below Diagram can help you to understand flow and usage.

![alt text](https://github.com/anurag18/ios/blob/xcconfig/Xcode_BuildSetting.png)

