# Nisi

Nisi is a social network which shows posts from other social networks such as Twitter, Instagram and Facebook. Each post is organised in your feed and each one can be rated.
Users will be able to find users who are near and follow them, follow a user on Nisi will mean follow all his social networks as well.

Nisi is developed using Vue.js and even though it was started with Ionic, Android application is generated using [Capacitor](https://capacitor.ionicframework.com/).

Nisi development was made following a [tutorial](https://www.smashingmagazine.com/2018/07/mobile-apps-capacitor-vue-js/). Some steps may be necessary before running the app.

## Run app locally

> Once nodejs and vue is installed

```bash
git clone https://github.com/valntinaf/NisiApp
cd NisiApp
cd nisi
npm install
npm run serve
```

## Build app

> In order to build an Android app, Android Studio needs to be installed. For building an app for iOS, XCode must be installed. Environment variables must be set as well.

```bash
npx cap copy
npm run build
```

## Screenshots

![Screenshots](https://i.imgur.com/scKjxsV.png)



## Copyright
This app is inspired by the Episode 01 Season 03 (Nosedive) from Black Mirror. Designed, built and developed by Valentina Feruere.
