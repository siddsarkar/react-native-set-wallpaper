# react-native-set-wallpaper

Set wallpaper with react-native

## Install

```sh
npm install --save react-native-wallpaper-manager
```

## Link

```sh
react-native link react-native-wallpaper-manager
```

## Usage

```js
import WallPaperManager from "react-native-wallpaper-manager";

WallPaperManager.setWallpaper({ uri: "http://example.com/test.png" }, (res) => {
  console.log(res);
});
```
