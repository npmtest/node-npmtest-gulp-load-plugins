# npmtest-gulp-load-plugins

#### basic test coverage for  [gulp-load-plugins (v1.5.0)](https://github.com/jackfranklin/gulp-load-plugins#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-gulp-load-plugins.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-gulp-load-plugins) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-gulp-load-plugins.svg)](https://travis-ci.org/npmtest/node-npmtest-gulp-load-plugins)

#### Automatically load any gulp plugins in your package.json

[![NPM](https://nodei.co/npm/gulp-load-plugins.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/gulp-load-plugins)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-gulp-load-plugins/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-gulp-load-plugins/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-gulp-load-plugins/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-gulp-load-plugins/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-gulp-load-plugins/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-gulp-load-plugins/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-gulp-load-plugins/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-gulp-load-plugins/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-gulp-load-plugins/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-gulp-load-plugins/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-gulp-load-plugins/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-gulp-load-plugins/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-gulp-load-plugins/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-gulp-load-plugins/build/test-report.html](https://npmtest.github.io/node-npmtest-gulp-load-plugins/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-gulp-load-plugins/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-gulp-load-plugins/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-gulp-load-plugins/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-gulp-load-plugins/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-gulp-load-plugins/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-gulp-load-plugins/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-gulp-load-plugins/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-gulp-load-plugins/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Jack Franklin"
    },
    "bugs": {
        "url": "https://github.com/jackfranklin/gulp-load-plugins/issues"
    },
    "contributors": [
        {
            "name": "Pascal Hartig"
        },
        {
            "name": "Ben Briggs"
        },
        {
            "name": "kombucha"
        },
        {
            "name": "Nicolas Froidure"
        },
        {
            "name": "Sindre Sorhus"
        },
        {
            "name": "Julien Fontanet"
        },
        {
            "name": "Callum Macrae"
        },
        {
            "name": "Hutson Betts"
        },
        {
            "name": "Christian Maniewski"
        },
        {
            "name": "Connor Peet"
        },
        {
            "name": "Dorian Camilleri"
        },
        {
            "name": "Carlos Henrique"
        },
        {
            "name": "iamfrontender"
        },
        {
            "name": "Brian Woodward"
        },
        {
            "name": "Zach Schnackel"
        },
        {
            "name": "Bret K. Ikehara"
        }
    ],
    "dependencies": {
        "array-unique": "^0.2.1",
        "fancy-log": "^1.2.0",
        "findup-sync": "^0.4.0",
        "gulplog": "^1.0.0",
        "has-gulplog": "^0.1.0",
        "micromatch": "^2.3.8",
        "resolve": "^1.1.7"
    },
    "description": "Automatically load any gulp plugins in your package.json",
    "devDependencies": {
        "capture-stream": "^0.1.2",
        "eslint": "2.13.1",
        "eslint-config-standard": "5.3.1",
        "eslint-plugin-promise": "1.3.2",
        "eslint-plugin-standard": "1.3.2",
        "mocha": "^2.1.0",
        "proxyquire": "^1.0.1",
        "sinon": "^1.9.1"
    },
    "directories": {},
    "dist": {
        "shasum": "4c419f7e5764d9a0e33061bab9618f81b73d4171",
        "tarball": "https://registry.npmjs.org/gulp-load-plugins/-/gulp-load-plugins-1.5.0.tgz"
    },
    "files": [
        "index.js"
    ],
    "gitHead": "55cf056777085fa2c647e1d0c650ace7382b3fa2",
    "homepage": "https://github.com/jackfranklin/gulp-load-plugins#readme",
    "keywords": [
        "gulpfriendly",
        "gulp",
        "require",
        "load",
        "plugins"
    ],
    "license": "MIT",
    "maintainers": [
        {
            "name": "jackfranklin"
        }
    ],
    "name": "gulp-load-plugins",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/jackfranklin/gulp-load-plugins.git"
    },
    "scripts": {
        "lint": "eslint **/*.js",
        "test": "npm run lint && NODE_PATH=test/global_modules mocha"
    },
    "version": "1.5.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
