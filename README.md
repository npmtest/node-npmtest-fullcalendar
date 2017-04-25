# npmtest-fullcalendar

#### basic test coverage for  [fullcalendar (v3.3.1)](https://fullcalendar.io/)  [![npm package](https://img.shields.io/npm/v/npmtest-fullcalendar.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-fullcalendar) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-fullcalendar.svg)](https://travis-ci.org/npmtest/node-npmtest-fullcalendar)

#### Full-sized drag & drop event calendar

[![NPM](https://nodei.co/npm/fullcalendar.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/fullcalendar)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-fullcalendar/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-fullcalendar/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-fullcalendar/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-fullcalendar/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-fullcalendar/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-fullcalendar/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-fullcalendar/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-fullcalendar/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-fullcalendar/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-fullcalendar/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-fullcalendar/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-fullcalendar/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-fullcalendar/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-fullcalendar/build/test-report.html](https://npmtest.github.io/node-npmtest-fullcalendar/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-fullcalendar/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-fullcalendar/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-fullcalendar/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-fullcalendar/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-fullcalendar/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-fullcalendar/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-fullcalendar/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-fullcalendar/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "fullcalendar",
    "title": "FullCalendar",
    "description": "Full-sized drag & drop event calendar",
    "keywords": [
        "calendar",
        "event",
        "full-sized",
        "jquery-plugin"
    ],
    "homepage": "https://fullcalendar.io/",
    "bugs": "https://fullcalendar.io/wiki/Reporting-Bugs/",
    "repository": {
        "type": "git",
        "url": "https://github.com/fullcalendar/fullcalendar.git"
    },
    "license": "MIT",
    "author": {
        "name": "Adam Shaw",
        "url": "http://arshaw.com/"
    },
    "copyright": "2017 Adam Shaw",
    "dependencies": {
        "jquery": "2 - 3",
        "moment": "^2.9.0"
    },
    "version": "3.3.1",
    "releaseDate": "2017-04-01",
    "devDependencies": {
        "bootstrap": "^3.3.7",
        "components-jqueryui": "github:components/jqueryui",
        "del": "^2.2.1",
        "gulp": "^3.9.1",
        "gulp-concat": "^2.6.0",
        "gulp-cssmin": "^0.1.7",
        "gulp-file": "^0.3.0",
        "gulp-filter": "^4.0.0",
        "gulp-jscs": "^4.0.0",
        "gulp-jshint": "^2.0.1",
        "gulp-modify": "^0.1.1",
        "gulp-plumber": "^1.1.0",
        "gulp-rename": "^1.2.2",
        "gulp-replace": "^0.5.4",
        "gulp-sourcemaps": "^1.6.0",
        "gulp-template": "^4.0.0",
        "gulp-uglify": "^2.0.0",
        "gulp-util": "^3.0.7",
        "gulp-zip": "^3.2.0",
        "jasmine-core": "^2.4.1",
        "jasmine-fixture": "^2.0.0",
        "jasmine-jquery": "^2.1.1",
        "jquery-mockjax": "^2.2.0",
        "jquery-simulate": "github:jquery/jquery-simulate",
        "jshint": "^2.9.2",
        "karma": "^0.13.22",
        "karma-jasmine": "^1.0.2",
        "karma-phantomjs-launcher": "^1.0.0",
        "lodash": "^4.14.1",
        "moment-timezone": "^0.5.5",
        "native-promise-only": "^0.8.1",
        "phantomjs-prebuilt": "^2.1.7",
        "socket.io": "1.4.5",
        "yargs": "^4.8.1"
    },
    "main": "dist/fullcalendar.js",
    "files": [
        "dist/*.js",
        "dist/*.css",
        "dist/locale/*.js",
        "README.*",
        "LICENSE.*",
        "CHANGELOG.*",
        "CONTRIBUTING.*"
    ],
    "scripts": {
        "test": "gulp test:single",
        "lint": "gulp lint"
    },
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
