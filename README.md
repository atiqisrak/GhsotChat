# GhostChat
https://img.shields.io/badge/GhostBOT-Niloy-orange

## Framework7 CLI Options
![License](https://img.shields.io/github/license/atiqisrak/GhsotChat?logo=Ghostery&logoColor=orange)
Framework7 app created with following options:

```
{
  "cwd": "H:\\Web-Projects-by-Niloy\\GhsotChat",
  "type": [
    "cordova"
  ],
  "name": "GhostChat",
  "framework": "vue",
  "template": "tabs",
  "bundler": "webpack",
  "cssPreProcessor": false,
  "theming": {
    "customColor": true,
    "color": "#e36414",
    "darkTheme": true,
    "iconFonts": true,
    "fillBars": false
  },
  "customBuild": false,
  "webpack": {
    "developmentSourceMap": true,
    "productionSourceMap": true,
    "hashAssets": false,
    "preserveAssetsPaths": false,
    "inlineAssets": true
  },
  "pkg": "io.framework7.ghostchat",
  "cordova": {
    "folder": "cordova",
    "platforms": [
      "ios",
      "android"
    ],
    "plugins": [
      "cordova-plugin-statusbar",
      "cordova-plugin-keyboard",
      "cordova-plugin-splashscreen"
    ]
  }
}
```

## NPM Scripts

* 🔥 `start` - run development server
* 🔧 `dev` - run development server
* 🔧 `build` - build web app for production
* 📱 `build-cordova` - build cordova app
* 📱 `build-cordova-ios` - build cordova iOS app
* 📱 `cordova-ios` - run dev build cordova iOS app
* 📱 `build-cordova-android` - build cordova Android app
* 📱 `cordova-android` - run dev build cordova Android app

✔ Generating package.json
✔ Creating required folders structure
✔ Installing NPM Dependencies
✔ Installing NPM Dev Dependencies
✔ Executing NPM Scripts
✔ Creating Cordova project
✔ Creating project files
√ Done! 💪

i Next steps:
  - 🔥 Run "npm run start" - run development server
  - 🔧 Run "npm run dev" - run development server
  - 🔧 Run "npm run build" - build web app for production
  - 📱 Run "npm run build-cordova" - build cordova app
  - 📱 Run "npm run build-cordova-ios" - build cordova iOS app
  - 📱 Run "npm run cordova-ios" - run dev build cordova iOS app
  - 📱 Run "npm run build-cordova-android" - build cordova Android app
  - 📱 Run "npm run cordova-android" - run dev build cordova Android app
  - 📖 Visit documentation at https://framework7.io/docs/
  - 📖 Check README.md in project root folder with further instructions

Love Framework7? Support project by donating or pledging on patreon:
https://patreon.com/vladimirkharlampidi

## WebPack

There is a webpack bundler setup. It compiles and bundles all "front-end" resources. You should work only with files located in `/src` folder. Webpack config located in `build/webpack.config.js`.

Webpack has specific way of handling static assets (CSS files, images, audios). You can learn more about correct way of doing things on [official webpack documentation](https://webpack.js.org/guides/asset-management/).
## Cordova

Cordova project located in `cordova` folder. You shouldn't modify content of `cordova/www` folder. Its content will be correctly generated when you call `npm run cordova-build-prod`.





## Assets

Assets (icons, splash screens) source images located in `assets-src` folder. To generate your own icons and splash screen images, you will need to replace all assets in this directory with your own images (pay attention to image size and format), and run the following command in the project directory:

```
framework7 assets
```

Or launch UI where you will be able to change icons and splash screens:

```
framework7 assets --ui
```



## Documentation & Resources

* [Framework7 Core Documentation](https://framework7.io/docs/)
* [Framework7 Vue Documentation](https://framework7.io/vue/)


* [Framework7 Icons Reference](https://framework7.io/icons/)
* [Community Forum](https://forum.framework7.io)

## Support Framework7

Love Framework7? Support project by donating or pledging on patreon:
https://patreon.com/vladimirkharlampidi
