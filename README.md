# npmtest-cloudflare

#### basic test coverage for  [cloudflare (v1.1.1)](https://github.com/cloudflare/node-cloudflare)  [![npm package](https://img.shields.io/npm/v/npmtest-cloudflare.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-cloudflare) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-cloudflare.svg)](https://travis-ci.org/npmtest/node-npmtest-cloudflare)

#### CloudFlare API client

[![NPM](https://nodei.co/npm/cloudflare.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/cloudflare)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-cloudflare/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-cloudflare/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-cloudflare/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-cloudflare/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-cloudflare/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-cloudflare/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-cloudflare/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-cloudflare/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-cloudflare/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-cloudflare/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-cloudflare/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-cloudflare/build/test-report.html](https://npmtest.github.io/node-npmtest-cloudflare/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-cloudflare/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-cloudflare/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-cloudflare/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-cloudflare/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-cloudflare/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-cloudflare/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-cloudflare/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-cloudflare/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Terin Stock"
    },
    "bugs": {
        "url": "https://github.com/cloudflare/node-cloudflare/issues"
    },
    "dependencies": {
        "es-class": "^2.1.1",
        "got": "^6.3.0",
        "lodash": "^4.13.1",
        "spdy": "^3.3.2",
        "url-join": "^1.1.0",
        "verymodel": "^3.6.0"
    },
    "description": "CloudFlare API client",
    "devDependencies": {
        "ava": "^0.17.0",
        "coveralls": "^2.11.9",
        "nock": "^9.0.2",
        "nyc": "^10.0.0",
        "semantic-release": "^6.3.2",
        "xo": "^0.17.1"
    },
    "directories": {},
    "dist": {
        "shasum": "d3c6175b6133dd8d1a70d4ee6be3672523f5bd26",
        "tarball": "https://registry.npmjs.org/cloudflare/-/cloudflare-1.1.1.tgz"
    },
    "files": [
        "index.js",
        "lib",
        "test"
    ],
    "gitHead": "3840803c3420ef94010e8ceddf78a4584deeec38",
    "homepage": "https://github.com/cloudflare/node-cloudflare",
    "keywords": [
        "cloudflare",
        "api"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "terinjokes"
        }
    ],
    "name": "cloudflare",
    "optionalDependencies": {},
    "release": {
        "branch": "1.x"
    },
    "repository": {
        "type": "git",
        "url": "git+https://github.com/cloudflare/node-cloudflare.git"
    },
    "scripts": {
        "coverage": "cat ./coverage/lcov.info | coveralls",
        "semantic-release": "semantic-release pre && npm publish && semantic-release post",
        "test": "xo && nyc --reporter=lcov -- ava"
    },
    "version": "1.1.1",
    "xo": {
        "space": true
    },
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
