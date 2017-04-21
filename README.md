# npmtest-ember-cli-mocha

#### basic test coverage for  [ember-cli-mocha (v0.13.2)](https://github.com/ember-cli/ember-cli-mocha)  [![npm package](https://img.shields.io/npm/v/npmtest-ember-cli-mocha.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-ember-cli-mocha) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-ember-cli-mocha.svg)](https://travis-ci.org/npmtest/node-npmtest-ember-cli-mocha)

#### Mocha and Chai tests for ember-cli applications

[![NPM](https://nodei.co/npm/ember-cli-mocha.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/ember-cli-mocha)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-ember-cli-mocha/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-ember-cli-mocha/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-ember-cli-mocha/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-ember-cli-mocha/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-ember-cli-mocha/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-ember-cli-mocha/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-ember-cli-mocha/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-ember-cli-mocha/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-ember-cli-mocha/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-ember-cli-mocha/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-ember-cli-mocha/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-ember-cli-mocha/build/test-report.html](https://npmtest.github.io/node-npmtest-ember-cli-mocha/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-ember-cli-mocha/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-ember-cli-mocha/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-ember-cli-mocha/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-ember-cli-mocha/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-ember-cli-mocha/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-ember-cli-mocha/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-ember-cli-mocha/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-ember-cli-mocha/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "ember-cli-mocha",
    "version": "0.13.2",
    "description": "Mocha and Chai tests for ember-cli applications",
    "keywords": [
        "chai",
        "ember",
        "ember-addon",
        "mocha"
    ],
    "homepage": "https://github.com/ember-cli/ember-cli-mocha",
    "bugs": {
        "url": "https://github.com/ember-cli/ember-cli-mocha/issues"
    },
    "license": "Apache-2.0",
    "author": "Dan Gebhardt",
    "main": "index.js",
    "directories": {
        "doc": "doc",
        "test": "tests"
    },
    "repository": {
        "type": "git",
        "url": "https://github.com/ember-cli/ember-cli-mocha.git"
    },
    "scripts": {
        "build": "ember build",
        "start": "ember server",
        "test": "ember try:each"
    },
    "dependencies": {
        "broccoli-babel-transpiler": "^5.5.0",
        "broccoli-concat": "^2.1.0",
        "broccoli-funnel": "^1.0.1",
        "broccoli-merge-trees": "^1.1.1",
        "ember-cli-babel": "^5.1.7",
        "ember-cli-test-loader": "^1.1.0",
        "ember-cli-version-checker": "^1.1.6",
        "ember-mocha": "^0.11.0",
        "mocha": "^2.5.3",
        "resolve": "^1.1.7"
    },
    "devDependencies": {
        "ember-cli": "2.10.0",
        "ember-cli-chai": "^0.3.0",
        "ember-cli-dependency-checker": "^1.3.0",
        "ember-cli-eslint": "3.0.2",
        "ember-cli-htmlbars": "^1.0.10",
        "ember-cli-htmlbars-inline-precompile": "^0.3.3",
        "ember-cli-inject-live-reload": "^1.4.1",
        "ember-cli-sri": "^2.1.0",
        "ember-cli-uglify": "^1.2.0",
        "ember-export-application-global": "^1.0.5",
        "ember-load-initializers": "^0.6.0",
        "ember-resolver": "^2.0.3",
        "loader.js": "^4.0.10"
    },
    "engines": {
        "node": ">= 0.12.0"
    },
    "ember-addon": {
        "configPath": "tests/dummy/config",
        "main": "index.js"
    },
    "greenkeeper": {
        "ignore": [
            "mocha"
        ]
    },
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
