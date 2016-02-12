# Angular 1.x WebPack 2 + Babel workflow

[![Dependency Status](https://david-dm.org/Foxandxss/angular-webpack-workflow/status.svg)](https://david-dm.org/Foxandxss/angular-webpack-workflow#info=dependencies) [![devDependency Status](https://david-dm.org/Foxandxss/angular-webpack-workflow/dev-status.svg)](https://david-dm.org/Foxandxss/angular-webpack-workflow#info=devDependencies)

**NOTE: This workflow is now using Webpack 2 beta. There is a branch with the old workflow if you want to use it.**

**NOTE 2: THIS IS STILL WIP, I WILL REMOVE THIS CAPS WHEN I AM SURE IT WORKS PERFECTLY.**

This workflow serves as a starting point for building Angular 1.x applications using WebPack 2. Should be noted that apart from the pre-installed angular package, this workflow is pretty much generic.

## Features

* Heavily commented webpack configuration with reasonable defaults.
* ES6, and ES7 support with babel.
* Source maps included in all builds.
* Development server with live reload.
* Production builds with cache busting.
* Testing environment using karma to run tests and jasmine as the framework.
* Code coverage when tests are run.
* No gulp and no grunt, just npm scripts.

## Installation

To use it, just clone this repo and install the npm dependencies:

```shell
$ git clone https://github.com/Foxandxss/angular-webpack-workflow my_app
$ cd my_app
$ npm install
```

## Scripts

All scripts are run with `npm run [script]`, for example: `npm run test`.

* `build` - generate a minified build to dist folder
* `start` - start development server, try it by opening `http://localhost:8080/`
* `test` - run all tests
* `test-watch` - continuously run unit tests watching for changes

See what each script does by looking at the `scripts` section in [package.json](./package.json).

## Example and tutorial

To see how to structure an Angular 1.x application using this workflow, please check [this demo](https://github.com/Foxandxss/GermanWords-ng1-webpack).

Also, there is an article in [angular-tips](http://angular-tips.com/blog/2015/06/using-angular-1-dot-x-with-es6-and-webpack/). The article is based on the Webpack 1 version, but almost everything is applicable here.

## License

The license of this workflow is MIT.
