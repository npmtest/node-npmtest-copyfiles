# npmtest-copyfiles

#### basic test coverage for  [copyfiles (v1.2.0)](https://github.com/calvinmetcalf/copyfiles#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-copyfiles.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-copyfiles) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-copyfiles.svg)](https://travis-ci.org/npmtest/node-npmtest-copyfiles)

#### copy some files

[![NPM](https://nodei.co/npm/copyfiles.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/copyfiles)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-copyfiles/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-copyfiles/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-copyfiles/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-copyfiles/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-copyfiles/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-copyfiles/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-copyfiles/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-copyfiles/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-copyfiles/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-copyfiles/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-copyfiles/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-copyfiles/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-copyfiles/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-copyfiles/build/test-report.html](https://npmtest.github.io/node-npmtest-copyfiles/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-copyfiles/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-copyfiles/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-copyfiles/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-copyfiles/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-copyfiles/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-copyfiles/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-copyfiles/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-copyfiles/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": "",
    "bin": {
        "copyfiles": "./copyfiles",
        "copyup": "./copyup"
    },
    "bugs": {
        "url": "https://github.com/calvinmetcalf/copyfiles/issues"
    },
    "dependencies": {
        "glob": "^7.0.5",
        "ltcdr": "^2.2.1",
        "minimatch": "^3.0.3",
        "mkdirp": "^0.5.1",
        "noms": "0.0.0",
        "through2": "^2.0.1"
    },
    "description": "copy some files",
    "devDependencies": {
        "rimraf": "^2.2.6",
        "tap-spec": "^4.1.1",
        "tape": "^4.6.0"
    },
    "directories": {},
    "dist": {
        "shasum": "a8da3ac41aa2220ae29bd3c58b6984294f2c593c",
        "tarball": "https://registry.npmjs.org/copyfiles/-/copyfiles-1.2.0.tgz"
    },
    "gitHead": "2d971fabf6399ae5269873e73bb2ab73660f184c",
    "homepage": "https://github.com/calvinmetcalf/copyfiles#readme",
    "license": "ISC",
    "main": "index.js",
    "maintainers": [
        {
            "name": "cwmma"
        }
    ],
    "name": "copyfiles",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/calvinmetcalf/copyfiles.git"
    },
    "scripts": {
        "test": "tape test/test.*.js | tspec"
    },
    "version": "1.2.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
