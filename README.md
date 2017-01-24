# react-native-device-info

[![npm version](https://badge.fury.io/js/react-native-device-info.svg)](http://badge.fury.io/js/react-native-device-info)

Device Information for [React Native](https://github.com/facebook/react-native)

## Original project

This is a modification of the following repository

[`react-native-device-info`](https://github.com/rebeccahughes/react-native-device-info)

The only change is that I've removed the following method `getInstanceID()`

## Reason for modification

I've removed the Android only `DeviceInfo.getInstanceID()` option because it broke when used in a project that used FireBase as well.

This project is made public to be able to reference it in the package.json of my project.

Also: this is a copy of npm version 0.9.7 because the project i'm working on is using react-native < 0.40

I won't be making any changes or updates to this. Please use the [`orignial project`](https://github.com/rebeccahughes/react-native-device-info) for your own use:
