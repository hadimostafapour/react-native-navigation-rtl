
<h1 align="center">
  <img src=".logo.png"/><br>
  React Native Navigation (+RTL)
</h1>

React Native Navigation provides 100% native platform navigation on both iOS and Android for React Native apps. The JavaScript API is simple and cross-platform - just install it in your app and give your users the native feel they deserve. Ready to get started? Check out the [docs](https://wix.github.io/react-native-navigation/).

-----

This repo is a fork of [Wix / React Native Navigation](https://github.com/wix/react-native-navigation/)

__~~If you don't need RTL, I recommend to use main repo instead~~__
RTL PR got merged into main repo, but Android BottomTabs and iOS Back Button Options are available only in this repo.

> Based on `v2.21.0`.

#### RTL Layout
```javascript
{
    layout: {
      direction: 'rtl' // or ltr
    }
}
```

#### [Android] BottomTabs Selected Icon
also you can set bottom tabs selected icon, identical to iOS API.
```javascript
{
  bottomTab: {
    text: "Title",
    icon: "Default Icon",
    selectedIcon: "Selected Icon",
    selectedTextColor: "#888888",
    fontFamily: "Font Name",
    selectedFontSize: 10
  }
}
```

#### [iOS] Back Button Text Options

```javascript
{
  topBar: {
    backButton: {
      fontFamily: "Font Name",
      fontSize: 18,
      textColor: "#888888"
    }
  }
}
```
-----


# Quick Links
- [Documentation](https://wix.github.io/react-native-navigation/)
- [Stack Overflow](http://stackoverflow.com/questions/tagged/react-native-navigation)
- [Chat with us](https://discord.gg/DhkZjq2)
- [Contributing](/docs/docs/WorkingLocally.md)

# Installation
As `react-native-navigation-rtl` is a native navigation library - integrating it into your app will require editing native files. Follow the installation guides in the [documentation](https://wix.github.io/react-native-navigation/).


> Follow official installation instructions, but instead of `react-native-navigation` install `react-native-navigation-rtl` package.
