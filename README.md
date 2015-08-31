# Angular 1.x WebPack + Babel workflow

[![Dependency Status](https://david-dm.org/Foxandxss/angular-webpack-workflow/status.svg)](https://david-dm.org/Foxandxss/angular-webpack-workflow#info=dependencies) [![devDependency Status](https://david-dm.org/Foxandxss/angular-webpack-workflow/dev-status.svg)](https://david-dm.org/Foxandxss/angular-webpack-workflow#info=devDependencies)

This workflow serves as a starting point for building Angular 1.x applications using WebPack.

It is a direct port of the amazing [react workflow](https://github.com/cesarandreu/web-app) of [Cesar Andreu](https://github.com/cesarandreu). All the credits goes for him.

## Features

* Heavily commented webpack configuration with reasonable defaults.
* ES6, and ES7 support with babel.js.
* Source maps included in all builds.
* Development server with live reload.
* Production builds with cache busting and asset minification.
* Testing environment using karma to run tests and jasmine as the framework.
* Code coverage when tests are run.
* No gulp and no grunt, just npm run-scripts.

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
* `dev` - start development server, try it by opening `http://localhost:8080/`
* `test` - run all tests
* `test:live` - continuously run unit tests watching for changes

See what each script does by looking at the `scripts` section in [package.json](./package.json).

## Example

To see how to structure an Angular 1.x application using this workflow, please check [this demo](https://github.com/Foxandxss/GermanWords-ng1-webpack).
