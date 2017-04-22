# npmtest-haxe

#### basic test coverage for  [haxe (v4.1.0)](http://haxe.org/)  [![npm package](https://img.shields.io/npm/v/npmtest-haxe.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-haxe) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-haxe.svg)](https://travis-ci.org/npmtest/node-npmtest-haxe)

#### Wrapper of Haxe, an open source toolkit based on a modern, high level, strictly typed programming language, a cross-compiler, a complete cross-platform standard library and ways to access each platform's native capabilities.

[![NPM](https://nodei.co/npm/haxe.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/haxe)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-haxe/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-haxe/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-haxe/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-haxe/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-haxe/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-haxe/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-haxe/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-haxe/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-haxe/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-haxe/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-haxe/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-haxe/build/test-report.html](https://npmtest.github.io/node-npmtest-haxe/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-haxe/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-haxe/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-haxe/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-haxe/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-haxe/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-haxe/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-haxe/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-haxe/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "clemos"
    },
    "bin": {
        "haxe": "bin/haxe",
        "haxelib": "bin/haxelib"
    },
    "bugs": {
        "url": "https://github.com/HaxeFoundation/npm-haxe/issues"
    },
    "config": {
        "version": "3.2.1",
        "nightly": "",
        "haxelib_version": "3.2.0-rc.1"
    },
    "cpu": [
        "x64",
        "ia32"
    ],
    "dependencies": {
        "download": "^4.2.1",
        "download-status": "^2.2.1",
        "rimraf": "^2.5.2"
    },
    "description": "Wrapper of Haxe, an open source toolkit based on a modern, high level, strictly typed programming language, a cross-compiler, a complete cross-platform standard library and ways to access each platform's native capabilities.",
    "devDependencies": {},
    "directories": {
        "bin": "./bin"
    },
    "dist": {
        "shasum": "10596beb27d5be8c4d6ca180f97ac1ab8c7a2650",
        "tarball": "https://registry.npmjs.org/haxe/-/haxe-4.1.0.tgz"
    },
    "gitHead": "86bc859a4acd68a951fe2b60099354b12b268b16",
    "homepage": "http://haxe.org/",
    "keywords": [
        "compiler",
        "language",
        "haxe",
        "wrapper"
    ],
    "license": "MIT",
    "maintainers": [
        {
            "name": "clemos"
        },
        {
            "name": "damoebius"
        },
        {
            "name": "haxelib.js"
        }
    ],
    "name": "haxe",
    "optionalDependencies": {},
    "os": [
        "win32",
        "win64",
        "darwin",
        "linux"
    ],
    "repository": {
        "type": "git",
        "url": "git+https://github.com/HaxeFoundation/npm-haxe.git"
    },
    "scripts": {
        "install": "node install.js",
        "test": "node test.js"
    },
    "version": "4.1.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
