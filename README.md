# npmtest-wrtc

#### test coverage for  [wrtc (v0.0.61)](http://js-platform.github.io/node-webrtc/)  [![npm package](https://img.shields.io/npm/v/npmtest-wrtc.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-wrtc) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-wrtc.svg)](https://travis-ci.org/npmtest/node-npmtest-wrtc)

#### Standards-compliant WebRTC implementation for Node

[![NPM](https://nodei.co/npm/wrtc.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/wrtc)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-wrtc/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-wrtc/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-wrtc/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-wrtc/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-wrtc/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-wrtc/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-wrtc/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-wrtc/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-wrtc/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-wrtc/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-wrtc/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-wrtc/build/test-report.html](https://npmtest.github.io/node-npmtest-wrtc/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-wrtc/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-wrtc/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-wrtc/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-wrtc/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-wrtc/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-wrtc/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-wrtc/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-wrtc/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Alan K",
        "url": "http://blog.modeswitch.org"
    },
    "binary": {
        "module_name": "wrtc",
        "module_path": "./build/{module_name}/v{version}/{configuration}/{node_abi}-{platform}-{arch}/",
        "remote_path": "./{module_name}/v{version}/{configuration}/",
        "package_name": "{node_abi}-{platform}-{arch}.tar.gz",
        "host": "https://node-webrtc.s3.amazonaws.com"
    },
    "browser": "lib/browser.js",
    "bugs": {
        "url": "https://github.com/js-platform/node-webrtc/issues"
    },
    "contributors": [
        {
            "name": "Alan K",
            "url": "blog.modeswitch.org"
        },
        {
            "name": "Eric Rescorla"
        },
        {
            "name": "Pasquale Boemio"
        },
        {
            "name": "Damon Oehlman"
        },
        {
            "name": "Benjamin Byholm"
        },
        {
            "name": "Alex Londeree"
        },
        {
            "name": "Jesús Leganés Combarro \"piranna\""
        },
        {
            "name": "Dario Andrei"
        },
        {
            "name": "Matt Porritt"
        },
        {
            "name": "Mark Andrus Roberts"
        },
        {
            "name": "Arno Klein"
        },
        {
            "name": "Manu Raghavan"
        },
        {
            "name": "Ross Kukulinski"
        }
    ],
    "dependencies": {
        "download": "^5.0.0",
        "gunzip-maybe": "^1.3.1",
        "nan": "^2.3.2",
        "node-pre-gyp": "0.6.x",
        "tar-fs": "^1.13.0"
    },
    "description": "Standards-compliant WebRTC implementation for Node",
    "devDependencies": {
        "aws-sdk": "^2.2.10",
        "minimist": "0.0.8",
        "node-static-alias": "^0.1.2",
        "simple-peer": "^5.0.0",
        "tape": "~2.4.2",
        "ws": "^1.1.0"
    },
    "directories": {},
    "dist": {
        "shasum": "3243255be1c4fba03de08f21428b486625f4b627",
        "tarball": "https://registry.npmjs.org/wrtc/-/wrtc-0.0.61.tgz"
    },
    "engines": {
        "node": ">=4.0.0"
    },
    "gitHead": "71ef85f3f181ed831de7f163d411c1efe76edfe1",
    "homepage": "http://js-platform.github.io/node-webrtc/",
    "keywords": [
        "webrtc",
        "p2p",
        "peer"
    ],
    "license": "BSD",
    "main": "lib/index.js",
    "maintainers": [
        {
            "name": "modeswitch"
        }
    ],
    "name": "wrtc",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/js-platform/node-webrtc.git"
    },
    "scripts": {
        "download-webrtc-libraries-and-headers": "node scripts/download-webrtc-libraries-and-headers.js",
        "install": "node-pre-gyp install --fallback-to-build",
        "test": "node test/all.js"
    },
    "version": "0.0.61"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
