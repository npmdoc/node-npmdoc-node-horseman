# npmdoc-node-horseman

#### api documentation for  node-horseman (v3.3.0)  [![npm package](https://img.shields.io/npm/v/npmdoc-node-horseman.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-node-horseman) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-node-horseman.svg)](https://travis-ci.org/npmdoc/node-npmdoc-node-horseman)

#### Run PhantomJS from Node

[![NPM](https://nodei.co/npm/node-horseman.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/node-horseman)

- [https://npmdoc.github.io/node-npmdoc-node-horseman/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-node-horseman/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-node-horseman/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-node-horseman/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-node-horseman/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-node-horseman/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "node-horseman",
    "version": "3.3.0",
    "description": "Run PhantomJS from Node",
    "repository": {
        "type": "git",
        "url": "https://github.com/johntitus/node-horseman.git"
    },
    "main": "lib/index",
    "directories": {
        "test": "test"
    },
    "dependencies": {
        "bluebird": "^3.0.1",
        "clone": "^1.0.2",
        "cookies.txt": "^0.1.1",
        "data-uri-to-buffer": "0.0.4",
        "debug": "^2.1.1",
        "defaults": "~1.0.0",
        "node-phantom-simple": "^2.2.4"
    },
    "devDependencies": {
        "express": "^4.10.4",
        "hoxy": "^3.2.0",
        "mocha": "^2.2.5",
        "mocha.parallel": "^0.12.0",
        "request": "^2.69.0",
        "rmdir": "^1.2.0",
        "semver": "^5.1.0",
        "should": "^8.2.2"
    },
    "scripts": {
        "lint": "jshint .",
        "test": "mocha -R spec"
    },
    "keywords": [
        "phantomjs",
        "horseman",
        "headless",
        "browser"
    ],
    "author": "John Titus <john.titus@gmail.com>",
    "license": "MIT"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
