# react-native-open-source-board

[![Sponsored by Callstack][callstack-badge]][callstack]
[![tweet][tweet-badge]][tweet]

Open source board with "ready to pick up" issues from `react-native` and `react-native-community` repositories.

## Motivation

This repository aims to help developers interested in contributing to React Native open source repositories by providing them a list of triaged issues. It should decrease the entry level of writing RN OSS for beginners, but also allow more experienced contributors not to waste time scouring through the issues.

Every issue that lands on this list should be triaged and classified by the type of an issue and skillset required to pick it up.

This list is a living artifact, which means the state of the issue, might not always be up to date. It's an open source list, which means everyone can send a PR to remove or add issues.

I'll try to update this list as often as possible, if you want to stay up to date, click the button below.

[![tweet][michalchudziak-tweet]][michalchudziak]


## Issues

### react-native

Repo: https://github.com/facebook/react-native

#### Bugs 🐛

- **[JS]** [Image never reloads with same uri](https://github.com/facebook/react-native/issues/12606)
- **[JS]** [Large Flatlist is not rendering all items](https://github.com/facebook/react-native/issues/15990)
- **[JS]** [Modal component does not support SafeAreaView bottom margin](https://github.com/facebook/react-native/issues/18177)
- **[JS]** [FlatList item onPress not work the first time after refreshed](https://github.com/facebook/react-native/issues/20011)
- **[JS]** [FlatList item onPress not work the first time after refreshed](https://github.com/facebook/react-native/issues/23578)
- **[JS]** [Animated.Value does not have correct value after animation if component was re-mounted](https://github.com/facebook/react-native/issues/23712)
- **[JS][iOS][Android]** [Creating an instance of URL like: `new URL('http://facebook.com')` throws an exception.](https://github.com/facebook/react-native/issues/16434)
- **[Android]** [View will lost background color when set borderRadius and height is large enough on Android device](https://github.com/facebook/react-native/issues/15826)
- **[iOS]** [iOS: Multiple animations which use "useNativeDriver" do not work if preceded by a delay.](https://github.com/facebook/react-native/issues/18513)

### @react-native-community/slider

Repo: https://github.com/react-native-community/react-native-slider

#### Features 🛠

- **[Automation]** [Automate publishing with semantic-release](https://github.com/react-native-community/react-native-slider/issues/34)
- **[JS][Automation]** [Write e2e tests with Detox](https://github.com/react-native-community/react-native-slider/issues/33)
- **[iOS][Android]** [Multi-thumb option](https://github.com/react-native-community/react-native-slider/issues/25)

#### Bugs 🐛

- **[iOS]** [RCTSlider produces a line no matter even when all colors values match background color](https://github.com/react-native-community/react-native-slider/issues/10)
- **[Android]** [ReactSlider crash on Android release version](https://github.com/react-native-community/react-native-slider/issues/9)

### @react-native-community/geolocation

Repo: https://github.com/react-native-community/react-native-geolocation

#### Features 🛠

- **[JavaScript]** [Support web as target](https://github.com/react-native-community/react-native-geolocation)
- **[iOS][Android]** [Add missing configuration options](https://github.com/react-native-community/react-native-geolocation/issues/11)

### @react-native-community/cli

Repo: https://github.com/react-native-community/cli

#### Features 🛠

- **[JavaScript]** [Add verbose logging](https://github.com/react-native-community/cli/issues/96)
- **[JavaScript]** [react-native init should have a folder option in addition to the current ProjectName one](https://github.com/react-native-community/cli/issues/110)
- **[JavaScript]** [Show new version + upgrade help text in CLI](https://github.com/react-native-community/cli/issues/189)
- **[JavaScript]** [run-android should also open default simulator, like run-ios](https://github.com/react-native-community/cli/issues/142)

#### Bugs 🐛

- **[JavaScript][iOS][Android]** [run-android|run-ios do not support RNTester out of the box](https://github.com/react-native-community/cli/issues/143)

### @react-native-community/device-info

Repo: https://github.com/react-native-community/react-native-device-info

#### Features 🛠

- **[iOS][Android]** [Sync relevant methods from Google-authored flutter device-info package](https://github.com/react-native-community/react-native-device-info/issues/622)

#### Bugs 🐛

- **[Android]** [getBuildNumber() returns string in iOS and number in Android](https://github.com/react-native-community/react-native-device-info/issues/214)

### @react-native-community/async-storage

Repo: https://github.com/react-native-community/react-native-async-storage

#### Bugs 🐛

- **[Android]** [AsyncStorage Couldn't read row 0, col 0 from CursorWindow](https://github.com/react-native-community/react-native-async-storage/issues/10)

### @react-native-community/maps

Repo: https://github.com/react-native-community/react-native-maps

#### Features 🛠

- **[JavaScript]** [[Feature Request] Allow loadTileAtPath prop for LocalTile](https://github.com/react-native-community/react-native-maps/issues/2007)
- **[JavaScript]** [Add edgePadding to fitToElements also?](https://github.com/react-native-community/react-native-maps/issues/922)
- **[iOS][Android]** [API for determining if user manually moved the map](https://github.com/react-native-community/react-native-maps/issues/2756)
- **[iOS][Android]** [Feature reuest maxExtend & wrapDateLine](https://github.com/react-native-community/react-native-maps/issues/2043)
- **[iOS][Android]** [Get Map rotation](https://github.com/react-native-community/react-native-maps/issues/487)
- **[iOS]** [Feature Request: Provide `onUserLocationChange` for use with MapKit (iOS)](https://github.com/react-native-community/react-native-maps/issues/2055)

### @react-native-community/net-info

Repo: https://github.com/react-native-community/react-native-netinfo

#### Bugs 🐛

- **[Android]** [Android: NetworkCallbackConnectivityReceiver does not report "none" status correctly](https://github.com/react-native-community/react-native-netinfo/issues/44)
- **[Android]** [getConnectionInfo returns wrong info if network state changes while app is "sleeping" in background](https://github.com/react-native-community/react-native-netinfo/issues/32)

### react-native-tab-view

Repo: https://github.com/react-native-community/react-native-tab-view

#### Features 🛠

- **[JavaScript]** [RTL is not supported!](https://github.com/react-native-community/react-native-tab-view/issues/184)
- **[JavaScript][Automation]** [Setup infra for testing with detox](https://github.com/react-native-community/react-native-tab-view/issues/469)


<!-- badges -->
[tweet-badge]: https://img.shields.io/badge/tweet-%23ossboard-blue.svg?style=flat-square&colorB=1DA1F2&logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABgAAAAUCAYAAACXtf2DAAAAAXNSR0IArs4c6QAAAaRJREFUOBGtlM8rBGEYx3cWtRHJRaKcuMtBSitxkCQ3LtzkP9iUUu5ODspRHLhRLtq0FxeicEBC2cOivcge%2FMgan3fNM8bbzL4zm6c%2BPT%2Fe7%2FO8887svrFYBWbbtgWzsAt3sAcpqJFxxF1QV8oJFqFPFst5dLWQAT87oTgPB7DtziFRT1EA4yZolsFkhwjGYFRO8Op0KD8HVe7unoB6PRTBZG8IctAmG1xrHcfkQ2B55sfI%2ByGMXSBqV71xZ8CWdxBxN6ThFuECDEAL%2Bc9HIzDYumVZ966GZnX0SzCZvEqTbkaGywkyFE6hKAsBPhFQ18uPUqh2ggJ%2BUor%2F4M%2F%2FzOC8g6YzR1i%2F8g4vvSI%2ByD7FFNjexQrjHd8%2BnjABI3AU4Wl16TuF1qANGll81jsi5qu%2Bw6XIsCn4ijhU5FmCJpkV6BGNw410hfSf6JKBQ%2FUFxHGYBnWnmOwDwYQ%2BwzdHqO75HtiAMJfaC7ph32FSRJCENUhDHsLaJkL%2FX4wMF4%2BwA5bgAcrZE4sr0Cu9Jq9fxyrvBHWbNkMD5CEHWTjjT2m6r5D92jfmbbKJEWuMMAAAAABJRU5ErkJggg%3D%3D
[tweet]: https://twitter.com/intent/tweet?text=Check%20out%20linaria!%20https://github.com/callstack/linaria%20%F0%9F%91%8D

[callstack-badge]: https://callstack.com/images/callstack-badge.svg
[callstack]: https://callstack.com/open-source/?utm_source=github.com&utm_medium=referral&utm_campaign=linaria&utm_term=readme

[michalchudziak-tweet]: https://img.shields.io/twitter/follow/michalchudziak.svg?color=%231DA1F2&label=Follow%20%40michalchudziak%20on%20Twitter&logo=data%3Aimage%2Fpng%3Bbase64%2CiVBORw0KGgoAAAANSUhEUgAAABgAAAAUCAYAAACXtf2DAAAAAXNSR0IArs4c6QAAAaRJREFUOBGtlM8rBGEYx3cWtRHJRaKcuMtBSitxkCQ3LtzkP9iUUu5ODspRHLhRLtq0FxeicEBC2cOivcge%252FMgan3fNM8bbzL4zm6c%252BPT%252Fe7%252FO8887svrFYBWbbtgWzsAt3sAcpqJFxxF1QV8oJFqFPFst5dLWQAT87oTgPB7DtziFRT1EA4yZolsFkhwjGYFRO8Op0KD8HVe7unoB6PRTBZG8IctAmG1xrHcfkQ2B55sfI%252ByGMXSBqV71xZ8CWdxBxN6ThFuECDEAL%252Bc9HIzDYumVZ966GZnX0SzCZvEqTbkaGywkyFE6hKAsBPhFQ18uPUqh2ggJ%252BUor%252F4M%252F%252FzOC8g6YzR1i%252F8g4vvSI%252ByD7FFNjexQrjHd8%252BnjABI3AU4Wl16TuF1qANGll81jsi5qu%252Bw6XIsCn4ijhU5FmCJpkV6BGNw410hfSf6JKBQ%252FUFxHGYBnWnmOwDwYQ%252BwzdHqO75HtiAMJfaC7ph32FSRJCENUhDHsLaJkL%252FX4wMF4%252BwA5bgAcrZE4sr0Cu9Jq9fxyrvBHWbNkMD5CEHWTjjT2m6r5D92jfmbbKJEWuMMAAAAABJRU5ErkJggg%253D%253D&style=flat-square
[michalchudziak]: https://twitter.com/michalchudziak?ref_src=twsrc%5Etfw
