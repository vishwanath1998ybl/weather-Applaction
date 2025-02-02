# Metis Weather Extension [![Build Status](https://api.travis-ci.org/kasramp/weather-extension.svg?branch=master)](https://travis-ci.org/kasramp/weather-extension)

Metis is a Google Chrome weather extension which's built on top of [Eris API](http://eris.madadipouya.com/). It provides the current weather based on the user's geolocation.

## Screenshots

![Kuala Lumpur](https://user-images.githubusercontent.com/4501120/57571299-73a2f600-740c-11e9-8d31-23c5b1ecac09.jpg)
![Los Angeles](https://user-images.githubusercontent.com/4501120/57571326-d72d2380-740c-11e9-9623-fa4db36a1507.jpg)
![Dubai](https://user-images.githubusercontent.com/4501120/57571263-f081a000-740b-11e9-9a89-d754a3e86918.jpg)
![Sydney](https://user-images.githubusercontent.com/4501120/57571264-f1b2cd00-740b-11e9-854d-a1a58d80c5cf.jpg)

## Installation

Metis is compatible with both Google Chrome and Chromium. You can download it from [Chrome Web Store](https://chrome.google.com/webstore/category/extensions) at this link: TODO

## Developer installation (Beta)

To install the latest version, before it gets published to Chrome Web Store, download the latest zip file from [release](https://github.com/kasramp/weather-extension/releases) tab.
After that extract the zip file, then open the browser and go to [chrome://extensions/](chrome://extensions/). Enable developer mode. Lastly, click on load unpacked and point to the extracted path.

## Technology

Metis is built with HTML, CSS, [Weather Icon](https://erikflowers.github.io/weather-icons/) and Vue.js. The weather condition is acquired by making an background call to Eris api.

## Setting up the project

Just clone the repository and open in a editor like VS code.

### Run `dev`

```bash
$ npm run watch:dev
```

### Build `dev`

```bash
$ npm run build:dev
```

### Build `prod`

```bash
$ npm run build
```

### Build zip `prod`

```bash
$ npm run build-zip
```

## Release process

Metis is hooked up with Travis. To release a new version all needed is to make a commit and push it to upstream. The CI pipeline automatically picks up everything from there and creates a new release and tag.

To know more about the release process see `.travis.yml` and `.release-it.json` files.

## Contact

- vishchakia@gmail.com
