# @jmaen/react-native-picker-select
An extension to [`react-native-picker-select`](https://github.com/lawnstarter/react-native-picker-select) that adds methods to programmatically open and close the picker on iOS **and Android**.

All original features of `react-native-picker-select` remain.

## Installing
```
npm install @jmaen/react-native-picker-select

# React Native users
npm install @react-native-picker/picker
npx pod-install

# Expo
expo install @react-native-picker/picker
```

## Usage
See the `react-native-picker-select` [documentation](https://github.com/lawnstarter/react-native-picker-select/blob/master/README.md#basic-usage) for reference.

In addition to all existing features, two new methods have been added:

### `openPicker` (Android, iOS)
Programmatically opens picker

### `closePicker` (Android, iOS)
Programmatically closes picker