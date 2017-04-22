# npmtest-unicode

#### basic test coverage for  [unicode (v9.0.1)](http://github.com/eversport/node-unicodetable)  [![npm package](https://img.shields.io/npm/v/npmtest-unicode.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-unicode) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-unicode.svg)](https://travis-ci.org/npmtest/node-npmtest-unicode)

#### unicode lookup table

[![NPM](https://nodei.co/npm/unicode.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/unicode)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-unicode/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-unicode/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-unicode/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-unicode/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-unicode/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-unicode/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-unicode/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-unicode/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-unicode/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-unicode/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-unicode/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-unicode/build/test-report.html](https://npmtest.github.io/node-npmtest-unicode/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-unicode/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-unicode/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-unicode/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-unicode/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-unicode/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-unicode/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-unicode/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-unicode/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "unicode",
    "description": "unicode lookup table",
    "version": "9.0.1",
    "author": "dodo (https://github.com/dodo)",
    "contributors": [
        "Mathias Bynens <mathias@qiwi.be> (http://mathiasbynens.be/)",
        "Thomas Danecker <thomas.danecker@eversports.com>"
    ],
    "homepage": "http://github.com/eversport/node-unicodetable",
    "repository": {
        "type": "git",
        "url": "git://github.com/eversport/node-unicodetable.git"
    },
    "engines": {
        "node": ">= 0.8.x"
    },
    "scripts": {
        "download": "curl \"http://unicode.org/Public/9.0.0/ucd/UnicodeData.txt\" > UnicodeData.txt",
        "generate": "node generate.js",
        "test": "node test.js",
        "np": "np"
    },
    "devDependencies": {
        "bufferstream": ">= 0.6.2",
        "np": "2.13.1"
    },
    "licenses": [
        {
            "type": "MIT",
            "url": "http://github.com/dodo/node-unicodetable/raw/master/LICENSE"
        }
    ],
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
