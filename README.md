# npmdoc-json-schema-generator

#### api documentation for  [json-schema-generator (v2.0.3)](https://github.com/krg7880/json-schema-generator)  [![npm package](https://img.shields.io/npm/v/npmdoc-json-schema-generator.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-json-schema-generator) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-json-schema-generator.svg)](https://travis-ci.org/npmdoc/node-npmdoc-json-schema-generator)

#### JSON schema generator based on draft-v4.

[![NPM](https://nodei.co/npm/json-schema-generator.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/json-schema-generator)

- [https://npmdoc.github.io/node-npmdoc-json-schema-generator/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-json-schema-generator/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-json-schema-generator/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-json-schema-generator/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-json-schema-generator/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-json-schema-generator/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "json-schema-generator",
    "version": "2.0.3",
    "description": "JSON schema generator based on draft-v4.",
    "main": "./index.js",
    "directories": {
        "test": "test"
    },
    "bin": {
        "json-schema-generator": "./bin/cli.js"
    },
    "readmeFilename": "Readme.md",
    "bugs": {
        "url": "https://github.com/krg7880/json-schema-generator/issues"
    },
    "homepage": "https://github.com/krg7880/json-schema-generator",
    "dependencies": {
        "json-promise": "^1.1.8",
        "mkdirp": "^0.5.0",
        "optimist": "^0.6.1",
        "pretty-data": "^0.40.0",
        "request": "^2.47.0"
    },
    "devDependencies": {
        "chai": "^1.9.2",
        "chai-json-schema": "^1.1.0",
        "coveralls": "^2.11.2",
        "gulp": "^3.8.9",
        "gulp-concat": "^2.4.1",
        "gulp-markdox": "^0.1.0",
        "gulp-mocha": "^2.2.0",
        "mocha": "^1.21.4",
        "node-stubby-server-cli": "^1.0.0"
    },
    "scripts": {
        "test": "gulp"
    },
    "keywords": [
        "json schema",
        "json schema generator",
        "schema",
        "json",
        "generator",
        "draft",
        "v4"
    ],
    "author": "Kirk Gordon<kirk7880@gmail.com>",
    "license": "MIT"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
