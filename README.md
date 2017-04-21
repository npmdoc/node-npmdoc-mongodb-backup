# npmdoc-mongodb-backup

#### api documentation for  [mongodb-backup (v1.6.9)](https://github.com/hex7c0/mongodb-backup)  [![npm package](https://img.shields.io/npm/v/npmdoc-mongodb-backup.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-mongodb-backup) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-mongodb-backup.svg)](https://travis-ci.org/npmdoc/node-npmdoc-mongodb-backup)

#### backup for mongodb

[![NPM](https://nodei.co/npm/mongodb-backup.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/mongodb-backup)

- [https://npmdoc.github.io/node-npmdoc-mongodb-backup/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-mongodb-backup/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-mongodb-backup/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-mongodb-backup/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-mongodb-backup/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-mongodb-backup/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "version": "1.6.9",
    "name": "mongodb-backup",
    "description": "backup for mongodb",
    "keywords": [
        "mongodb",
        "backup",
        "dump"
    ],
    "preferGlobal": false,
    "homepage": "https://github.com/hex7c0/mongodb-backup",
    "author": {
        "name": "hex7c0",
        "url": "https://hex7c0.github.io/"
    },
    "repository": {
        "type": "git",
        "url": "https://github.com/hex7c0/mongodb-backup.git"
    },
    "bugs": {
        "url": "https://github.com/hex7c0/mongodb-backup/issues"
    },
    "main": "index.min.js",
    "dependencies": {
        "bson": "1.0.1",
        "fstream": "1.0.10",
        "graceful-fs": "4.1.11",
        "logger-request": "3.7.3",
        "mongodb": "2.2.16",
        "tar": "2.2.1"
    },
    "devDependencies": {
        "grunt": "~1.0",
        "grunt-contrib-uglify": "~2.0",
        "grunt-contrib-jshint": "~1.1",
        "grunt-endline": "~0.6",
        "grunt-safer-regex": "~0.0",
        "istanbul": "~0.4",
        "mocha": "~3.2",
        "mongodb-restore": "~1.6",
        "supertest": "~2.0"
    },
    "engines": {
        "node": ">=4"
    },
    "scripts": {
        "prepublish": "npm prune",
        "test": "mocha --bail --check-leaks --globals Promise --timeout 10000",
        "test-cov": "istanbul cover node_modules/mocha/bin/_mocha --report lcovonly -- --timeout 10000"
    },
    "license": "Apache-2.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
