# npmdoc-resume-cli

#### api documentation for  resume-cli (v0.4.19)  [![npm package](https://img.shields.io/npm/v/npmdoc-resume-cli.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-resume-cli) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-resume-cli.svg)](https://travis-ci.org/npmdoc/node-npmdoc-resume-cli)

#### The JSON Resume command line interface

[![NPM](https://nodei.co/npm/resume-cli.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/resume-cli)

- [https://npmdoc.github.io/node-npmdoc-resume-cli/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-resume-cli/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-resume-cli/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-resume-cli/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-resume-cli/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-resume-cli/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "resume-cli",
    "version": "0.4.19",
    "description": "The JSON Resume command line interface",
    "main": "index.js",
    "scripts": {
        "test": "node node_modules/mocha/bin/mocha test test/*.js"
    },
    "repository": {
        "type": "git",
        "url": "https://github.com/rolandnsharp/resume-cli.git"
    },
    "license": "MIT",
    "bin": {
        "resume": "index.js"
    },
    "preferGlobal": true,
    "dependencies": {
        "async": "^1.5.0",
        "chalk": "^1.1.1",
        "char-spinner": "^1.0.1",
        "cli-spinner": "^0.2.1",
        "colors": "^1.1.2",
        "commander": "^2.9.0",
        "dotenv": "^2.0.0",
        "html-pdf": "^2.1.0",
        "jsonlint": "^1.6.2",
        "jsonresume-theme-crisp": "^0.2.12",
        "jsonresume-theme-flat": "^0.3.7",
        "jsonresume-theme-modern": "0.0.18",
        "jspdf": "^1.3.2",
        "node-static": "~0.7.7",
        "open": "0.0.5",
        "read": "~1.0.7",
        "resume-schema": "latest",
        "resume-to-html": "latest",
        "resume-to-text": "latest",
        "should": "^11.1.0",
        "superagent": "^2.0.0",
        "terminal-menu": "^2.1.1"
    },
    "devDependencies": {
        "mocha": "^3.0.2"
    },
    "engines": {
        "node": "^4"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
