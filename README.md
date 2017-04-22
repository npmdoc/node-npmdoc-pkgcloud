# npmdoc-pkgcloud

#### api documentation for  [pkgcloud (v1.4.0)](https://github.com/pkgcloud/pkgcloud#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-pkgcloud.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-pkgcloud) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-pkgcloud.svg)](https://travis-ci.org/npmdoc/node-npmdoc-pkgcloud)

#### An infrastructure-as-a-service agnostic cloud library for node.js

[![NPM](https://nodei.co/npm/pkgcloud.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/pkgcloud)

- [https://npmdoc.github.io/node-npmdoc-pkgcloud/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-pkgcloud/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-pkgcloud/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-pkgcloud/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-pkgcloud/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-pkgcloud/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Charlie Robbins"
    },
    "bugs": {
        "url": "https://github.com/pkgcloud/pkgcloud/issues"
    },
    "config": {
        "blanket": {
            "pattern": "/lib/",
            "data-cover-never": "node_modules"
        }
    },
    "contributors": [
        {
            "name": "Nuno Job"
        },
        {
            "name": "Maciej Malecki"
        },
        {
            "name": "Daniel Aristizabal"
        },
        {
            "name": "Ken Perkins"
        },
        {
            "name": "Ross Kukulinski"
        }
    ],
    "dependencies": {
        "async": "0.9.x",
        "aws-sdk": "^2.2.43",
        "errs": "0.3.x",
        "eventemitter2": "0.4.x",
        "fast-json-patch": "0.5.x",
        "filed": "0.1.x",
        "gcloud": "^0.10.0",
        "ip": "0.3.x",
        "lodash": "^3.10.1",
        "mime": "1.2.x",
        "qs": "1.2.x",
        "request": "2.40.x",
        "s3-upload-stream": "~1.0.7",
        "through2": "0.6.x",
        "url-join": "0.0.x",
        "xml2js": "0.1.x"
    },
    "description": "An infrastructure-as-a-service agnostic cloud library for node.js",
    "devDependencies": {
        "blanket": "1.1.9",
        "coveralls": "^2.11.2",
        "hock": "~1.2.0",
        "jshint": "~2.7.0",
        "mocha": "1.21.x",
        "mocha-lcov-reporter": "0.0.1",
        "should": "4.0.x"
    },
    "directories": {},
    "dist": {
        "shasum": "7e438ee0f6c41aca63100e987dfe61ecae0c105b",
        "tarball": "https://registry.npmjs.org/pkgcloud/-/pkgcloud-1.4.0.tgz"
    },
    "engines": {
        "node": ">=0.10.x"
    },
    "gitHead": "997784bea0e21e4446ac52be511a431f85825ece",
    "homepage": "https://github.com/pkgcloud/pkgcloud#readme",
    "keywords": [
        "cloud",
        "cloud computing",
        "api",
        "rackspace",
        "joyent",
        "aws",
        "amazon",
        "azure",
        "google",
        "iaas",
        "servers",
        "compute",
        "storage",
        "databases",
        "client",
        "mongolab",
        "iriscouch",
        "mongohq",
        "openstack",
        "redistogo",
        "hpcloud",
        "hp",
        "helion"
    ],
    "main": "./lib/pkgcloud",
    "maintainers": [
        {
            "name": "cronopio"
        },
        {
            "name": "indexzero"
        },
        {
            "name": "jcrugzz"
        },
        {
            "name": "kperkins"
        },
        {
            "name": "mmalecki"
        }
    ],
    "name": "pkgcloud",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/pkgcloud/pkgcloud.git"
    },
    "scripts": {
        "cov": "make cov",
        "lint": "make lint",
        "test": "make test",
        "travis": "make travis"
    },
    "version": "1.4.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
