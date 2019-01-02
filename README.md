![alt text](./assets/images/index_image.png "Welcome Screen of Successful Installation")

## Description

[![Greenkeeper badge](https://badges.greenkeeper.io/pitops/ng2-boilerplate.svg)](https://greenkeeper.io/)

This is an Angular 2 Boilerplate featuring Gulp, SystemJS and Typescript. This package is **Angular 2 Beta 9** compatible.

### Features

* Includes Sass/Scss to CSS preprocessor
* CSS Minification
* CSS Concatenation
* Autoprefixer
* Uglifier for JS
* Automatic **image optimization**
* Compile Typescript to JS
* Watch task to reload any changes on Save
* Lite Server for live-reload
* Uses SystemJS for handling modules
* Includes **bootstrap**
* Includes **Jquery**

### Usage

#### Global Dependencies

```
npm install -g gulp
```

#### Initially
```
npm install
gulp setup

```

#### Afterwards

```
# one command line window

npm run startup

# individual command line windows

npm run serve # load lite-server
gulp # for Gulp watcher
```
### Issues

gulp-uglify plugin breaks the app when mangle option is turned on (this is the default) thus in this boilerplate for time being it is turned off.

### Disclaimer

This boilerplate was originally made for Angular 2 First Look series on [youtube](https://www.youtube.com/channel/UCxhcaC1wjUuFq3fC95i48fA)

### Contribution

Feel free to fork the repo and make pull requests
