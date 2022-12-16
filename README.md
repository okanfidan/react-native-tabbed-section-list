# @glyw/react-native-tabs-section-list
[![npm version](https://badge.fury.io/js/@glyw/react-native-tabbed-section-list.svg)](https://github.com/okanfidan/react-native-tabbed-section-list)
[![license](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/okanfidan/react-native-tabbed-section-list/blob/master/LICENSE)

React Native Scrollable Tabbed SectionList.

## Installation

```bash
$ yarn add @glyw/react-native-tabbed-section-list
```

## Demo

<img src="https://raw.githubusercontent.com/okanfidan/react-native-tabbed-section-list/master/demo.gif" width="360">

## Installation

```bash
$ yarn add react-native-tabs-section-list
```

## Props

 Name | Description | Type | Default
------ | ------ | ------ | ------
`scrollToLocationOffset?` | Param is inserted into `scrollToLocation` as `viewOffset`  [See React Native Docs](https://facebook.github.io/react-native/docs/sectionlist#scrolltolocation) | `number` | 0
`tabBarStyle?` | Styles for tabBar | `ViewStyle` | undefined
`renderTab` | Callback which returns a custom React Element to use as the tab bar `(section: SectionListData<any>) ` | `React.ReactNode` | Required
`SectionList` [props...](https://facebook.github.io/react-native/docs/sectionlist#props) |  |  |

<br>
