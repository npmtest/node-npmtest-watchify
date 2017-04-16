# test coverage for  [watchify (v3.9.0)](https://github.com/substack/watchify)  [![npm package](https://img.shields.io/npm/v/npmtest-watchify.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-watchify) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-watchify.svg)](https://travis-ci.org/npmtest/node-npmtest-watchify)
#### watch mode for browserify builds

[![NPM](https://nodei.co/npm/watchify.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/watchify)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-watchify/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-watchify/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-watchify/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-watchify/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-watchify/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-watchify/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-watchify/tree/gh-pages/build)|

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-watchify/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-watchify/build/coverage.html/index.html)

[![test-report](https://npmtest.github.io/node-npmtest-watchify/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-watchify/build/test-report.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-watchify/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-watchify/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-watchify/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-watchify/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "James Halliday",
        "url": "http://substack.net"
    },
    "bin": {
        "watchify": "bin/cmd.js"
    },
    "bugs": {
        "url": "https://github.com/substack/watchify/issues"
    },
    "dependencies": {
        "anymatch": "^1.3.0",
        "browserify": "^14.0.0",
        "chokidar": "^1.0.0",
        "defined": "^1.0.0",
        "outpipe": "^1.1.0",
        "through2": "^2.0.0",
        "xtend": "^4.0.0"
    },
    "description": "watch mode for browserify builds",
    "devDependencies": {
        "brfs": "^1.0.1",
        "mkdirp": "~0.5.1",
        "split": "^1.0.0",
        "tape": "^4.2.2",
        "uglify-js": "^2.5.0",
        "win-spawn": "^2.0.0"
    },
    "directories": {},
    "dist": {
        "shasum": "f075fd2e8a86acde84cedba6e5c2a0bedd523d9e",
        "tarball": "https://registry.npmjs.org/watchify/-/watchify-3.9.0.tgz"
    },
    "gitHead": "f768b433774652d6b5257cd342e4353f81760637",
    "homepage": "https://github.com/substack/watchify",
    "keywords": [
        "browserify",
        "browserify-tool",
        "watch",
        "bundle",
        "build",
        "browser"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "feross"
        },
        {
            "name": "mafintosh"
        },
        {
            "name": "substack"
        },
        {
            "name": "zertosh"
        }
    ],
    "name": "watchify",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/substack/watchify.git"
    },
    "scripts": {
        "test": "tape test/*.js"
    },
    "version": "3.9.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
