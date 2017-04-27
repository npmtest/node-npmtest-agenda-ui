# npmtest-agenda-ui

#### basic test coverage for  [agenda-ui (v0.0.7)](https://github.com/moudy/agenda-ui)  [![npm package](https://img.shields.io/npm/v/npmtest-agenda-ui.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-agenda-ui) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-agenda-ui.svg)](https://travis-ci.org/npmtest/node-npmtest-agenda-ui)

#### UI for Agenda

[![NPM](https://nodei.co/npm/agenda-ui.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/agenda-ui)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-agenda-ui/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-agenda-ui/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-agenda-ui/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-agenda-ui/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-agenda-ui/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-agenda-ui/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-agenda-ui/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-agenda-ui/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-agenda-ui/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-agenda-ui/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-agenda-ui/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-agenda-ui/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-agenda-ui/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-agenda-ui/build/test-report.html](https://npmtest.github.io/node-npmtest-agenda-ui/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-agenda-ui/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-agenda-ui/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-agenda-ui/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-agenda-ui/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-agenda-ui/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-agenda-ui/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-agenda-ui/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-agenda-ui/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Moudy"
    },
    "bugs": {
        "url": "https://github.com/moudy/agenda-ui/issues"
    },
    "dependencies": {
        "ejs": "^1.0.0",
        "express": "^4.3.2",
        "rsvp": "^3.0.9",
        "speakingurl": "^0.9.1"
    },
    "description": "UI for Agenda",
    "devDependencies": {
        "agenda": "^0.6.12",
        "broccoli": "^0.12.1",
        "broccoli-browserify": "^0.1.0",
        "broccoli-clean-css": "^0.1.5",
        "broccoli-cli": "0.0.1",
        "broccoli-merge-trees": "^0.1.3",
        "broccoli-middleware": "0.0.1",
        "broccoli-sass": "^0.1.4",
        "broccoli-template-builder": "0.0.4",
        "broccoli-uglify-js": "^0.1.3",
        "countdown": "^2.3.0",
        "ember-cli": "0.0.39",
        "ember-template-compiler": "^1.6.0-beta.5",
        "handlebars": "^1.1.0",
        "highlight.js": "^8.0.0",
        "jquery": "^2.1.1",
        "lodash": "^2.4.1",
        "moment": "^2.6.0",
        "moment-countdown": "0.0.1",
        "moment-duration-format": "^1.2.1"
    },
    "directories": {},
    "dist": {
        "shasum": "c7d1dc4898220539caa53b19ced011a07d13ecf7",
        "tarball": "https://registry.npmjs.org/agenda-ui/-/agenda-ui-0.0.7.tgz"
    },
    "gitHead": "3175d4d6a900318634d9797e834ddd8bc40d80c3",
    "homepage": "https://github.com/moudy/agenda-ui",
    "keywords": [
        "agenda"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "moudy"
        }
    ],
    "name": "agenda-ui",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/moudy/agenda-ui.git"
    },
    "scripts": {
        "dev": "nodemon --ignore tmp/ --ignore app/ --ignore node_modules/ dev.js",
        "prepublish": "./scripts/build",
        "test": "mocha"
    },
    "version": "0.0.7",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
