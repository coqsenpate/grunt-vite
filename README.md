# grunt-vite

> Runs vite in grunt.

This task directly sends the provided config to the build function of [vite](https://esbuild.github.io/) (which you can provide).

## Install

```
$ npm install --save-dev vite grunt-vite
```

## Usage

```js
require('load-grunt-tasks')(grunt);

grunt.initConfig({
  vite: {
    dist: {
      build: require('./vite.config'),
    }
  }
});

grunt.registerTask('default', ['vite']);
```
