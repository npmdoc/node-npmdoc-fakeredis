# npmdoc-fakeredis

#### api documentation for  fakeredis (v2.0.0)  [![npm package](https://img.shields.io/npm/v/npmdoc-fakeredis.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-fakeredis) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-fakeredis.svg)](https://travis-ci.org/npmdoc/node-npmdoc-fakeredis)

#### Fake redis for testing, works as a drop-in replacement for node_redis

[![NPM](https://nodei.co/npm/fakeredis.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/fakeredis)

- [https://npmdoc.github.io/node-npmdoc-fakeredis/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-fakeredis/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-fakeredis/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-fakeredis/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-fakeredis/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-fakeredis/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "fakeredis",
    "version": "2.0.0",
    "description": "Fake redis for testing, works as a drop-in replacement for node_redis",
    "keywords": [
        "test",
        "spec",
        "fake",
        "redis",
        "simulated",
        "implementation",
        "client"
    ],
    "author": "Hristo Dachev <tutini@gmail.com>",
    "main": "./main.js",
    "dependencies": {
        "redis": "2.6.0-0"
    },
    "license": "MIT",
    "bugs": {
        "mail": "tutini@gmail.com",
        "url": "http://github.com/hdachev/fakeredis/issues"
    },
    "repository": {
        "type": "git",
        "url": "git://github.com/hdachev/fakeredis.git"
    },
    "scripts": {
        "test": "./runtest",
        "coverage": "./covertest"
    },
    "devDependencies": {
        "coveralls": "^2.11.6",
        "istanbul": "^0.4.2",
        "lcov-result-merger": "^1.0.2"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
