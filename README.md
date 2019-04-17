# react-native-fb-image-grid
### This is the very early alpha age of this library, and the code is very dirty, but all PRs are welcome.

<a href="https://twitter.com/intent/follow?screen_name=jibraniqbal666">
        <img src="https://img.shields.io/twitter/follow/jibraniqbal666.svg?style=social&logo=twitter"
            alt="follow on Twitter"></a>

## NPM

- stable release version: ![version](https://img.shields.io/badge/version-0.0.1-blue.svg?cacheSeconds=2592000)
- package downloads: ![downloads](https://img.shields.io/badge/downloads-22%2Fweek-brightgreen.svg?cacheSeconds=2592000)
- [![MIT license](http://img.shields.io/badge/license-MIT-brightgreen.svg)](http://opensource.org/licenses/MIT)

## Github
- [![GitHub stars](https://img.shields.io/github/stars/jibraniqbal666/react-native-fb-image-grid.svg?style=social&label=Star&maxAge=2592000)](https://GitHub.com/jibraniqbal666/react-native-fb-image-grid)

## Install

`npm i react-native-fb-image-grid`.

## Usage

__NOTE: Container that you are putting your FBGrid Width and Height must be calculated, or it will not appear.__

```javascript
     <FbGrid
            images={[
              "https://facebook.github.io/react-native/docs/assets/favicon.png",
              "https://facebook.github.io/react-native/docs/assets/favicon.png",
              "https://facebook.github.io/react-native/docs/assets/favicon.png",
              "https://facebook.github.io/react-native/docs/assets/favicon.png",
              "https://facebook.github.io/react-native/docs/assets/favicon.png",
              "https://facebook.github.io/react-native/docs/assets/favicon.png"
            ]}
            onPress={onPress}
          /> 
          
    const onPress = imageUrl => {
      // image Url is the image you have clicked.
    }
```
    
https://github.com/jibraniqbal666/react-native-fb-image-grid
