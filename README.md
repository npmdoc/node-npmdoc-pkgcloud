# api documentation for  [pkgcloud (v1.4.0)](https://github.com/pkgcloud/pkgcloud#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-pkgcloud.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-pkgcloud) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-pkgcloud.svg)](https://travis-ci.org/npmdoc/node-npmdoc-pkgcloud)
#### An infrastructure-as-a-service agnostic cloud library for node.js

[![NPM](https://nodei.co/npm/pkgcloud.png?downloads=true)](https://www.npmjs.com/package/pkgcloud)

[![apidoc](https://npmdoc.github.io/node-npmdoc-pkgcloud/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-pkgcloud_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-pkgcloud/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-pkgcloud/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-pkgcloud/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Charlie Robbins",
        "email": "charlie.robbins@gmail.com"
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
            "name": "Nuno Job",
            "email": "nuno@nodejitsu.com"
        },
        {
            "name": "Maciej Malecki",
            "email": "me@mmalecki.com"
        },
        {
            "name": "Daniel Aristizabal",
            "email": "daniel@nodejitsu.com"
        },
        {
            "name": "Ken Perkins",
            "email": "ken.perkins@rackspace.com"
        },
        {
            "name": "Ross Kukulinski",
            "email": "ross@getyodlr.com"
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
            "name": "cronopio",
            "email": "aristizabal.daniel@gmail.com"
        },
        {
            "name": "indexzero",
            "email": "charlie.robbins@gmail.com"
        },
        {
            "name": "jcrugzz",
            "email": "jcrugzz@gmail.com"
        },
        {
            "name": "kperkins",
            "email": "ken.perkins@rackspace.com"
        },
        {
            "name": "mmalecki",
            "email": "me@mmalecki.com"
        }
    ],
    "name": "pkgcloud",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
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
    "version": "1.4.0"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module pkgcloud](#apidoc.module.pkgcloud)
1.  [function <span class="apidocSignatureSpan">pkgcloud.</span>base.Client (options)](#apidoc.element.pkgcloud.base.Client)
1.  [function <span class="apidocSignatureSpan">pkgcloud.</span>base.Model (client, details)](#apidoc.element.pkgcloud.base.Model)
1.  [function <span class="apidocSignatureSpan">pkgcloud.</span>compute.Flavor (client, details)](#apidoc.element.pkgcloud.compute.Flavor)
1.  [function <span class="apidocSignatureSpan">pkgcloud.</span>compute.Image (client, details)](#apidoc.element.pkgcloud.compute.Image)
1.  [function <span class="apidocSignatureSpan">pkgcloud.</span>compute.Server (client, details)](#apidoc.element.pkgcloud.compute.Server)
1.  [function <span class="apidocSignatureSpan">pkgcloud.</span>storage.Container (client, details)](#apidoc.element.pkgcloud.storage.Container)
1.  [function <span class="apidocSignatureSpan">pkgcloud.</span>storage.File (client, details)](#apidoc.element.pkgcloud.storage.File)
1.  object <span class="apidocSignatureSpan">pkgcloud.</span>_base
1.  object <span class="apidocSignatureSpan">pkgcloud.</span>_common
1.  object <span class="apidocSignatureSpan">pkgcloud.</span>_compute
1.  object <span class="apidocSignatureSpan">pkgcloud.</span>_storage
1.  object <span class="apidocSignatureSpan">pkgcloud.</span>base
1.  object <span class="apidocSignatureSpan">pkgcloud.</span>base.Client.prototype
1.  object <span class="apidocSignatureSpan">pkgcloud.</span>base.Client.super_.prototype
1.  object <span class="apidocSignatureSpan">pkgcloud.</span>base.Model.prototype
1.  object <span class="apidocSignatureSpan">pkgcloud.</span>blockstorage
1.  object <span class="apidocSignatureSpan">pkgcloud.</span>cdn
1.  object <span class="apidocSignatureSpan">pkgcloud.</span>common
1.  object <span class="apidocSignatureSpan">pkgcloud.</span>compute
1.  object <span class="apidocSignatureSpan">pkgcloud.</span>compute.Flavor.prototype
1.  object <span class="apidocSignatureSpan">pkgcloud.</span>compute.Image.prototype
1.  object <span class="apidocSignatureSpan">pkgcloud.</span>compute.Server.prototype
1.  object <span class="apidocSignatureSpan">pkgcloud.</span>database
1.  object <span class="apidocSignatureSpan">pkgcloud.</span>dns
1.  object <span class="apidocSignatureSpan">pkgcloud.</span>loadbalancer
1.  object <span class="apidocSignatureSpan">pkgcloud.</span>network
1.  object <span class="apidocSignatureSpan">pkgcloud.</span>orchestration
1.  object <span class="apidocSignatureSpan">pkgcloud.</span>providers
1.  object <span class="apidocSignatureSpan">pkgcloud.</span>storage
1.  object <span class="apidocSignatureSpan">pkgcloud.</span>storage.Container.prototype
1.  object <span class="apidocSignatureSpan">pkgcloud.</span>storage.File.prototype
1.  string <span class="apidocSignatureSpan">pkgcloud.</span>version

#### [module pkgcloud.base](#apidoc.module.pkgcloud.base)
1.  [function <span class="apidocSignatureSpan">pkgcloud.base.</span>Client (options)](#apidoc.element.pkgcloud.base.Client)
1.  [function <span class="apidocSignatureSpan">pkgcloud.base.</span>Model (client, details)](#apidoc.element.pkgcloud.base.Model)

#### [module pkgcloud.base.Client](#apidoc.module.pkgcloud.base.Client)
1.  [function <span class="apidocSignatureSpan">pkgcloud.base.</span>Client (options)](#apidoc.element.pkgcloud.base.Client.Client)
1.  [function <span class="apidocSignatureSpan">pkgcloud.base.Client.</span>super_ (conf)](#apidoc.element.pkgcloud.base.Client.super_)

#### [module pkgcloud.base.Client.prototype](#apidoc.module.pkgcloud.base.Client.prototype)
1.  [function <span class="apidocSignatureSpan">pkgcloud.base.Client.prototype.</span>_defaultRequestHandler (callback)](#apidoc.element.pkgcloud.base.Client.prototype._defaultRequestHandler)
1.  [function <span class="apidocSignatureSpan">pkgcloud.base.Client.prototype.</span>_parseError (response, body)](#apidoc.element.pkgcloud.base.Client.prototype._parseError)
1.  [function <span class="apidocSignatureSpan">pkgcloud.base.Client.prototype.</span>_request (options, callback)](#apidoc.element.pkgcloud.base.Client.prototype._request)
1.  [function <span class="apidocSignatureSpan">pkgcloud.base.Client.prototype.</span>getUserAgent ()](#apidoc.element.pkgcloud.base.Client.prototype.getUserAgent)
1.  [function <span class="apidocSignatureSpan">pkgcloud.base.Client.prototype.</span>setCustomUserAgent (userAgent)](#apidoc.element.pkgcloud.base.Client.prototype.setCustomUserAgent)

#### [module pkgcloud.base.Client.super_.prototype](#apidoc.module.pkgcloud.base.Client.super_.prototype)
1.  [function <span class="apidocSignatureSpan">pkgcloud.base.Client.super_.prototype.</span>addListener (type, listener)](#apidoc.element.pkgcloud.base.Client.super_.prototype.addListener)
1.  [function <span class="apidocSignatureSpan">pkgcloud.base.Client.super_.prototype.</span>emit ()](#apidoc.element.pkgcloud.base.Client.super_.prototype.emit)
1.  [function <span class="apidocSignatureSpan">pkgcloud.base.Client.super_.prototype.</span>listeners (type)](#apidoc.element.pkgcloud.base.Client.super_.prototype.listeners)
1.  [function <span class="apidocSignatureSpan">pkgcloud.base.Client.super_.prototype.</span>listenersAny ()](#apidoc.element.pkgcloud.base.Client.super_.prototype.listenersAny)
1.  [function <span class="apidocSignatureSpan">pkgcloud.base.Client.super_.prototype.</span>many (event, ttl, fn)](#apidoc.element.pkgcloud.base.Client.super_.prototype.many)
1.  [function <span class="apidocSignatureSpan">pkgcloud.base.Client.super_.prototype.</span>off (type, listener)](#apidoc.element.pkgcloud.base.Client.super_.prototype.off)
1.  [function <span class="apidocSignatureSpan">pkgcloud.base.Client.super_.prototype.</span>offAny (fn)](#apidoc.element.pkgcloud.base.Client.super_.prototype.offAny)
1.  [function <span class="apidocSignatureSpan">pkgcloud.base.Client.super_.prototype.</span>on (type, listener)](#apidoc.element.pkgcloud.base.Client.super_.prototype.on)
1.  [function <span class="apidocSignatureSpan">pkgcloud.base.Client.super_.prototype.</span>onAny (fn)](#apidoc.element.pkgcloud.base.Client.super_.prototype.onAny)
1.  [function <span class="apidocSignatureSpan">pkgcloud.base.Client.super_.prototype.</span>once (event, fn)](#apidoc.element.pkgcloud.base.Client.super_.prototype.once)
1.  [function <span class="apidocSignatureSpan">pkgcloud.base.Client.super_.prototype.</span>removeAllListeners (type)](#apidoc.element.pkgcloud.base.Client.super_.prototype.removeAllListeners)
1.  [function <span class="apidocSignatureSpan">pkgcloud.base.Client.super_.prototype.</span>removeListener (type, listener)](#apidoc.element.pkgcloud.base.Client.super_.prototype.removeListener)
1.  [function <span class="apidocSignatureSpan">pkgcloud.base.Client.super_.prototype.</span>setMaxListeners (n)](#apidoc.element.pkgcloud.base.Client.super_.prototype.setMaxListeners)
1.  string <span class="apidocSignatureSpan">pkgcloud.base.Client.super_.prototype.</span>delimiter
1.  string <span class="apidocSignatureSpan">pkgcloud.base.Client.super_.prototype.</span>event

#### [module pkgcloud.base.Model](#apidoc.module.pkgcloud.base.Model)
1.  [function <span class="apidocSignatureSpan">pkgcloud.base.</span>Model (client, details)](#apidoc.element.pkgcloud.base.Model.Model)
1.  [function <span class="apidocSignatureSpan">pkgcloud.base.Model.</span>super_ (conf)](#apidoc.element.pkgcloud.base.Model.super_)

#### [module pkgcloud.base.Model.prototype](#apidoc.module.pkgcloud.base.Model.prototype)
1.  [function <span class="apidocSignatureSpan">pkgcloud.base.Model.prototype.</span>clearWait (intervalId)](#apidoc.element.pkgcloud.base.Model.prototype.clearWait)
1.  [function <span class="apidocSignatureSpan">pkgcloud.base.Model.prototype.</span>setWait (attributes, interval, timeLimit, callback)](#apidoc.element.pkgcloud.base.Model.prototype.setWait)
1.  [function <span class="apidocSignatureSpan">pkgcloud.base.Model.prototype.</span>until (attributes, interval, timeLimit, callback)](#apidoc.element.pkgcloud.base.Model.prototype.until)

#### [module pkgcloud.blockstorage](#apidoc.module.pkgcloud.blockstorage)
1.  [function <span class="apidocSignatureSpan">pkgcloud.blockstorage.</span>createClient (options)](#apidoc.element.pkgcloud.blockstorage.createClient)

#### [module pkgcloud.cdn](#apidoc.module.pkgcloud.cdn)
1.  [function <span class="apidocSignatureSpan">pkgcloud.cdn.</span>createClient (options)](#apidoc.element.pkgcloud.cdn.createClient)

#### [module pkgcloud.compute](#apidoc.module.pkgcloud.compute)
1.  [function <span class="apidocSignatureSpan">pkgcloud.compute.</span>Flavor (client, details)](#apidoc.element.pkgcloud.compute.Flavor)
1.  [function <span class="apidocSignatureSpan">pkgcloud.compute.</span>Image (client, details)](#apidoc.element.pkgcloud.compute.Image)
1.  [function <span class="apidocSignatureSpan">pkgcloud.compute.</span>Server (client, details)](#apidoc.element.pkgcloud.compute.Server)
1.  [function <span class="apidocSignatureSpan">pkgcloud.compute.</span>createClient (options)](#apidoc.element.pkgcloud.compute.createClient)
1.  [function <span class="apidocSignatureSpan">pkgcloud.compute.</span>isPrivate (addr)](#apidoc.element.pkgcloud.compute.isPrivate)
1.  [function <span class="apidocSignatureSpan">pkgcloud.compute.</span>isPublic (addr)](#apidoc.element.pkgcloud.compute.isPublic)
1.  [function <span class="apidocSignatureSpan">pkgcloud.compute.</span>serverIp (server, options)](#apidoc.element.pkgcloud.compute.serverIp)
1.  [function <span class="apidocSignatureSpan">pkgcloud.compute.</span>serverPass (server)](#apidoc.element.pkgcloud.compute.serverPass)

#### [module pkgcloud.compute.Flavor](#apidoc.module.pkgcloud.compute.Flavor)
1.  [function <span class="apidocSignatureSpan">pkgcloud.compute.</span>Flavor (client, details)](#apidoc.element.pkgcloud.compute.Flavor.Flavor)
1.  [function <span class="apidocSignatureSpan">pkgcloud.compute.Flavor.</span>super_ (client, details)](#apidoc.element.pkgcloud.compute.Flavor.super_)

#### [module pkgcloud.compute.Flavor.prototype](#apidoc.module.pkgcloud.compute.Flavor.prototype)
1.  [function <span class="apidocSignatureSpan">pkgcloud.compute.Flavor.prototype.</span>refresh (callback)](#apidoc.element.pkgcloud.compute.Flavor.prototype.refresh)

#### [module pkgcloud.compute.Image](#apidoc.module.pkgcloud.compute.Image)
1.  [function <span class="apidocSignatureSpan">pkgcloud.compute.</span>Image (client, details)](#apidoc.element.pkgcloud.compute.Image.Image)
1.  [function <span class="apidocSignatureSpan">pkgcloud.compute.Image.</span>super_ (client, details)](#apidoc.element.pkgcloud.compute.Image.super_)

#### [module pkgcloud.compute.Image.prototype](#apidoc.module.pkgcloud.compute.Image.prototype)
1.  [function <span class="apidocSignatureSpan">pkgcloud.compute.Image.prototype.</span>create (callback)](#apidoc.element.pkgcloud.compute.Image.prototype.create)
1.  [function <span class="apidocSignatureSpan">pkgcloud.compute.Image.prototype.</span>destroy (callback)](#apidoc.element.pkgcloud.compute.Image.prototype.destroy)
1.  [function <span class="apidocSignatureSpan">pkgcloud.compute.Image.prototype.</span>refresh (callback)](#apidoc.element.pkgcloud.compute.Image.prototype.refresh)

#### [module pkgcloud.compute.Server](#apidoc.module.pkgcloud.compute.Server)
1.  [function <span class="apidocSignatureSpan">pkgcloud.compute.</span>Server (client, details)](#apidoc.element.pkgcloud.compute.Server.Server)
1.  [function <span class="apidocSignatureSpan">pkgcloud.compute.Server.</span>super_ (client, details)](#apidoc.element.pkgcloud.compute.Server.super_)

#### [module pkgcloud.compute.Server.prototype](#apidoc.module.pkgcloud.compute.Server.prototype)
1.  [function <span class="apidocSignatureSpan">pkgcloud.compute.Server.prototype.</span>create (callback)](#apidoc.element.pkgcloud.compute.Server.prototype.create)
1.  [function <span class="apidocSignatureSpan">pkgcloud.compute.Server.prototype.</span>destroy (callback)](#apidoc.element.pkgcloud.compute.Server.prototype.destroy)
1.  [function <span class="apidocSignatureSpan">pkgcloud.compute.Server.prototype.</span>reboot (callback)](#apidoc.element.pkgcloud.compute.Server.prototype.reboot)
1.  [function <span class="apidocSignatureSpan">pkgcloud.compute.Server.prototype.</span>refresh (callback)](#apidoc.element.pkgcloud.compute.Server.prototype.refresh)
1.  [function <span class="apidocSignatureSpan">pkgcloud.compute.Server.prototype.</span>resize ()](#apidoc.element.pkgcloud.compute.Server.prototype.resize)
1.  object <span class="apidocSignatureSpan">pkgcloud.compute.Server.prototype.</span>STATUS

#### [module pkgcloud.database](#apidoc.module.pkgcloud.database)
1.  [function <span class="apidocSignatureSpan">pkgcloud.database.</span>createClient (options)](#apidoc.element.pkgcloud.database.createClient)

#### [module pkgcloud.dns](#apidoc.module.pkgcloud.dns)
1.  [function <span class="apidocSignatureSpan">pkgcloud.dns.</span>createClient (options)](#apidoc.element.pkgcloud.dns.createClient)

#### [module pkgcloud.loadbalancer](#apidoc.module.pkgcloud.loadbalancer)
1.  [function <span class="apidocSignatureSpan">pkgcloud.loadbalancer.</span>createClient (options)](#apidoc.element.pkgcloud.loadbalancer.createClient)

#### [module pkgcloud.network](#apidoc.module.pkgcloud.network)
1.  [function <span class="apidocSignatureSpan">pkgcloud.network.</span>createClient (options)](#apidoc.element.pkgcloud.network.createClient)

#### [module pkgcloud.orchestration](#apidoc.module.pkgcloud.orchestration)
1.  [function <span class="apidocSignatureSpan">pkgcloud.orchestration.</span>createClient (options)](#apidoc.element.pkgcloud.orchestration.createClient)

#### [module pkgcloud.storage](#apidoc.module.pkgcloud.storage)
1.  [function <span class="apidocSignatureSpan">pkgcloud.storage.</span>Container (client, details)](#apidoc.element.pkgcloud.storage.Container)
1.  [function <span class="apidocSignatureSpan">pkgcloud.storage.</span>File (client, details)](#apidoc.element.pkgcloud.storage.File)
1.  [function <span class="apidocSignatureSpan">pkgcloud.storage.</span>createClient (options)](#apidoc.element.pkgcloud.storage.createClient)

#### [module pkgcloud.storage.Container](#apidoc.module.pkgcloud.storage.Container)
1.  [function <span class="apidocSignatureSpan">pkgcloud.storage.</span>Container (client, details)](#apidoc.element.pkgcloud.storage.Container.Container)
1.  [function <span class="apidocSignatureSpan">pkgcloud.storage.Container.</span>super_ (client, details)](#apidoc.element.pkgcloud.storage.Container.super_)

#### [module pkgcloud.storage.Container.prototype](#apidoc.module.pkgcloud.storage.Container.prototype)
1.  [function <span class="apidocSignatureSpan">pkgcloud.storage.Container.prototype.</span>create (callback)](#apidoc.element.pkgcloud.storage.Container.prototype.create)
1.  [function <span class="apidocSignatureSpan">pkgcloud.storage.Container.prototype.</span>destroy (callback)](#apidoc.element.pkgcloud.storage.Container.prototype.destroy)
1.  [function <span class="apidocSignatureSpan">pkgcloud.storage.Container.prototype.</span>getFiles (download, callback)](#apidoc.element.pkgcloud.storage.Container.prototype.getFiles)
1.  [function <span class="apidocSignatureSpan">pkgcloud.storage.Container.prototype.</span>refresh (callback)](#apidoc.element.pkgcloud.storage.Container.prototype.refresh)
1.  [function <span class="apidocSignatureSpan">pkgcloud.storage.Container.prototype.</span>removeFile (file, callback)](#apidoc.element.pkgcloud.storage.Container.prototype.removeFile)
1.  [function <span class="apidocSignatureSpan">pkgcloud.storage.Container.prototype.</span>upload (file, local, options, callback)](#apidoc.element.pkgcloud.storage.Container.prototype.upload)

#### [module pkgcloud.storage.File](#apidoc.module.pkgcloud.storage.File)
1.  [function <span class="apidocSignatureSpan">pkgcloud.storage.</span>File (client, details)](#apidoc.element.pkgcloud.storage.File.File)
1.  [function <span class="apidocSignatureSpan">pkgcloud.storage.File.</span>super_ (client, details)](#apidoc.element.pkgcloud.storage.File.super_)

#### [module pkgcloud.storage.File.prototype](#apidoc.module.pkgcloud.storage.File.prototype)
1.  [function <span class="apidocSignatureSpan">pkgcloud.storage.File.prototype.</span>download (options, callback)](#apidoc.element.pkgcloud.storage.File.prototype.download)
1.  [function <span class="apidocSignatureSpan">pkgcloud.storage.File.prototype.</span>remove (callback)](#apidoc.element.pkgcloud.storage.File.prototype.remove)



# <a name="apidoc.module.pkgcloud"></a>[module pkgcloud](#apidoc.module.pkgcloud)

#### <a name="apidoc.element.pkgcloud.base.Client"></a>[function <span class="apidocSignatureSpan">pkgcloud.</span>base.Client (options)](#apidoc.element.pkgcloud.base.Client)
- description and source-code
```javascript
base.Client = function (options) {
  events.EventEmitter2.call(this, { delimiter: '::', wildcard: true });
  this.config = options || {};
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pkgcloud.base.Model"></a>[function <span class="apidocSignatureSpan">pkgcloud.</span>base.Model (client, details)](#apidoc.element.pkgcloud.base.Model)
- description and source-code
```javascript
base.Model = function (client, details) {
  events.EventEmitter2.call(this, { delimiter: '::', wildcard: true });
  this.client = client;

  if (details) {
    this._setProperties(details);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pkgcloud.compute.Flavor"></a>[function <span class="apidocSignatureSpan">pkgcloud.</span>compute.Flavor (client, details)](#apidoc.element.pkgcloud.compute.Flavor)
- description and source-code
```javascript
compute.Flavor = function (client, details) {
  model.Model.call(this, client, details);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pkgcloud.compute.Image"></a>[function <span class="apidocSignatureSpan">pkgcloud.</span>compute.Image (client, details)](#apidoc.element.pkgcloud.compute.Image)
- description and source-code
```javascript
compute.Image = function (client, details) {
  model.Model.call(this, client, details);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pkgcloud.compute.Server"></a>[function <span class="apidocSignatureSpan">pkgcloud.</span>compute.Server (client, details)](#apidoc.element.pkgcloud.compute.Server)
- description and source-code
```javascript
compute.Server = function (client, details) {
  model.Model.call(this, client, details);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pkgcloud.storage.Container"></a>[function <span class="apidocSignatureSpan">pkgcloud.</span>storage.Container (client, details)](#apidoc.element.pkgcloud.storage.Container)
- description and source-code
```javascript
storage.Container = function (client, details) {
  this.files = [];

  model.Model.call(this, client, details);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pkgcloud.storage.File"></a>[function <span class="apidocSignatureSpan">pkgcloud.</span>storage.File (client, details)](#apidoc.element.pkgcloud.storage.File)
- description and source-code
```javascript
storage.File = function (client, details) {
  model.Model.call(this, client, details);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.pkgcloud.base"></a>[module pkgcloud.base](#apidoc.module.pkgcloud.base)

#### <a name="apidoc.element.pkgcloud.base.Client"></a>[function <span class="apidocSignatureSpan">pkgcloud.base.</span>Client (options)](#apidoc.element.pkgcloud.base.Client)
- description and source-code
```javascript
Client = function (options) {
  events.EventEmitter2.call(this, { delimiter: '::', wildcard: true });
  this.config = options || {};
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pkgcloud.base.Model"></a>[function <span class="apidocSignatureSpan">pkgcloud.base.</span>Model (client, details)](#apidoc.element.pkgcloud.base.Model)
- description and source-code
```javascript
Model = function (client, details) {
  events.EventEmitter2.call(this, { delimiter: '::', wildcard: true });
  this.client = client;

  if (details) {
    this._setProperties(details);
  }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.pkgcloud.base.Client"></a>[module pkgcloud.base.Client](#apidoc.module.pkgcloud.base.Client)

#### <a name="apidoc.element.pkgcloud.base.Client.Client"></a>[function <span class="apidocSignatureSpan">pkgcloud.base.</span>Client (options)](#apidoc.element.pkgcloud.base.Client.Client)
- description and source-code
```javascript
Client = function (options) {
  events.EventEmitter2.call(this, { delimiter: '::', wildcard: true });
  this.config = options || {};
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pkgcloud.base.Client.super_"></a>[function <span class="apidocSignatureSpan">pkgcloud.base.Client.</span>super_ (conf)](#apidoc.element.pkgcloud.base.Client.super_)
- description and source-code
```javascript
function EventEmitter(conf) {
  this._events = {};
  this.newListener = false;
  configure.call(this, conf);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.pkgcloud.base.Client.prototype"></a>[module pkgcloud.base.Client.prototype](#apidoc.module.pkgcloud.base.Client.prototype)

#### <a name="apidoc.element.pkgcloud.base.Client.prototype._defaultRequestHandler"></a>[function <span class="apidocSignatureSpan">pkgcloud.base.Client.prototype.</span>_defaultRequestHandler (callback)](#apidoc.element.pkgcloud.base.Client.prototype._defaultRequestHandler)
- description and source-code
```javascript
_defaultRequestHandler = function (callback) {

  var self = this;

  return function (err, res, body) {
    if (err) {
      return callback(err);
    }

    var err2 = self._parseError(res, body);

    if (err2) {
      self.emit('log::error', 'Error during provider response', err2);
      return callback(errs.create(err2));
    }

    self.emit('log::trace', 'Provider Response', {
      href: res.request.uri.href,
      method: res.request.method,
      headers: res.headers,
      statusCode: res.statusCode
    });

    callback(err, body, res);
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pkgcloud.base.Client.prototype._parseError"></a>[function <span class="apidocSignatureSpan">pkgcloud.base.Client.prototype.</span>_parseError (response, body)](#apidoc.element.pkgcloud.base.Client.prototype._parseError)
- description and source-code
```javascript
_parseError = function (response, body) {
  var self = this,
    statusCode = response.statusCode.toString(),
    err;

  if (Object.keys(self.failCodes).indexOf(statusCode) !== -1) {
    //
    // TODO: Support more than JSON errors here
    //
    err = {
      provider: self.provider,
      failCode: self.failCodes[statusCode],
      statusCode: response.statusCode,
      message: self.provider + ' Error (' +
        statusCode + '): ' + self.failCodes[statusCode],
      href: response.request.uri.href,
      method: response.request.method,
      headers: response.headers
    };

    if (body) {
      try {
        err.result = typeof body === 'string' ? JSON.parse(body) : body;
      } catch (e) {
        err.result = { err: body };
      }
    }
  }

  return err;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pkgcloud.base.Client.prototype._request"></a>[function <span class="apidocSignatureSpan">pkgcloud.base.Client.prototype.</span>_request (options, callback)](#apidoc.element.pkgcloud.base.Client.prototype._request)
- description and source-code
```javascript
_request = function (options, callback) {
  var self = this;
  var requestOptions = {};

  requestOptions.method = options.method || 'GET';
  requestOptions.headers = options.headers || {};
  requestOptions.path = options.path;
  requestOptions.strictSSL = typeof self.config.strictSSL === 'boolean'
    ? self.config.strictSSL : true;

  if (options.qs) {
    requestOptions.qs = options.qs;
  }

  if (options.body) {
    requestOptions.body = options.body;
  }

  if (options.container) {
    requestOptions.signingUrl = '/' + options.container + '/';

    if (options.path) {
      requestOptions.signingUrl += options.path;
    }

    if (options.qs) {
      requestOptions.signingUrl += '?' + qs.stringify(options.qs);
    }
  }

  function sendRequest(opts) {

    //
    // Setup any specific request options before
    // making the request
    //
    if (self.before) {
      var errors = false;
      for (var i = 0; i < self.before.length; i++) {
        var fn = self.before[i];
        try {
          opts = fn.call(self, opts) || opts;
          // on errors do error handling, break.
        } catch (exc) {
          errs.handle(exc, callback);
          errors = true;
          break;
        }
      }
      if (errors) {
        return;
      }
    }

    opts.uri = options.uri || self._getUrl(options);

    // Clean up our polluted options
    //
    // TODO refactor the options used in Before methods
    // to not require polluting request options
    //
    delete opts.path;
    delete opts.signingUrl;

    // Set our User Agent
    opts.headers['User-Agent'] = self.getUserAgent();

    // If we are missing callback
    if (!callback) {
      try {
        self.emit('log::trace', 'Sending (non-callback) client request', opts);
        return request(opts);
      } // if request throws still return an EE
      catch (exc1) {
        self.emit('log::trace', 'Unable to create (non-callback) request', opts);
        return errs.handle(exc1);
      }
    } else {
      try {
        self.emit('log::trace', 'Sending client request', opts);
        self.emit('log::debug', opts.method + ': ' + opts.uri);
        return request(opts, self._defaultRequestHandler(callback));
      } catch (exc2) {
        self.emit('log::error', 'Unable to create request', opts);
        return errs.handle(exc2, callback);
      }
    }
  }

  return sendRequest(requestOptions);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pkgcloud.base.Client.prototype.getUserAgent"></a>[function <span class="apidocSignatureSpan">pkgcloud.base.Client.prototype.</span>getUserAgent ()](#apidoc.element.pkgcloud.base.Client.prototype.getUserAgent)
- description and source-code
```javascript
getUserAgent = function () {
  return util.format('%snodejs-pkgcloud/%s', this._customUserAgent ?
    this._customUserAgent + ' ' : '', pkgcloud.version);
}
```
- example usage
```shell
...

In our [Roadmap](#roadmap), we plan to add support for more services, such as Queueing, Monitoring, and more. Additionally, we plan
 to implement more providers for the *beta* services, thus moving them out of *beta*.

### User Agent

By default, all pkgcloud HTTP requests will have a user agent with the library and version: 'nodejs-pkgcloud/x.y.z' where 'x.y.z
' is the current version.

You can get this from a client at any time by calling 'client.getUserAgent();'. Some providers may have an additional suffix as
a function of the underlying HTTP stacks.

You can also set a custom User Agent prefix:

'''javascript
client.setCustomUserAgent('my-app/1.2.3');

// returns "my-app/1.2.3 nodejs-pkgcloud/1.1.0"
...
```

#### <a name="apidoc.element.pkgcloud.base.Client.prototype.setCustomUserAgent"></a>[function <span class="apidocSignatureSpan">pkgcloud.base.Client.prototype.</span>setCustomUserAgent (userAgent)](#apidoc.element.pkgcloud.base.Client.prototype.setCustomUserAgent)
- description and source-code
```javascript
setCustomUserAgent = function (userAgent) {
  this._customUserAgent = userAgent;
}
```
- example usage
```shell
...
By default, all pkgcloud HTTP requests will have a user agent with the library and version: 'nodejs-pkgcloud/x.y.z' where 'x.y.z
' is the current version.

You can get this from a client at any time by calling 'client.getUserAgent();'. Some providers may have an additional suffix as
a function of the underlying HTTP stacks.

You can also set a custom User Agent prefix:

'''javascript
client.setCustomUserAgent('my-app/1.2.3');

// returns "my-app/1.2.3 nodejs-pkgcloud/1.1.0"
client.getUserAgent();
'''

<a name="basic-apis"></a>
### Basic APIs for pkgcloud
...
```



# <a name="apidoc.module.pkgcloud.base.Client.super_.prototype"></a>[module pkgcloud.base.Client.super_.prototype](#apidoc.module.pkgcloud.base.Client.super_.prototype)

#### <a name="apidoc.element.pkgcloud.base.Client.super_.prototype.addListener"></a>[function <span class="apidocSignatureSpan">pkgcloud.base.Client.super_.prototype.</span>addListener (type, listener)](#apidoc.element.pkgcloud.base.Client.super_.prototype.addListener)
- description and source-code
```javascript
addListener = function (type, listener) {

  if (typeof type === 'function') {
    this.onAny(type);
    return this;
  }

  if (typeof listener !== 'function') {
    throw new Error('on only accepts instances of Function');
  }
  this._events || init.call(this);

  // To avoid recursion in the case that type == "newListeners"! Before
  // adding it to the listeners, first emit "newListeners".
  this.emit('newListener', type, listener);

  if(this.wildcard) {
    growListenerTree.call(this, type, listener);
    return this;
  }

  if (!this._events[type]) {
    // Optimize the case of one listener. Don't need the extra array object.
    this._events[type] = listener;
  }
  else if(typeof this._events[type] === 'function') {
    // Adding the second element, need to change to array.
    this._events[type] = [this._events[type], listener];
  }
  else if (isArray(this._events[type])) {
    // If we've already got an array, just append.
    this._events[type].push(listener);

    // Check for listener leak
    if (!this._events[type].warned) {

      var m = defaultMaxListeners;

      if (typeof this._events.maxListeners !== 'undefined') {
        m = this._events.maxListeners;
      }

      if (m > 0 && this._events[type].length > m) {

        this._events[type].warned = true;
        console.error('(node) warning: possible EventEmitter memory ' +
                      'leak detected. %d listeners added. ' +
                      'Use emitter.setMaxListeners() to increase limit.',
                      this._events[type].length);
        console.trace();
      }
    }
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pkgcloud.base.Client.super_.prototype.emit"></a>[function <span class="apidocSignatureSpan">pkgcloud.base.Client.super_.prototype.</span>emit ()](#apidoc.element.pkgcloud.base.Client.super_.prototype.emit)
- description and source-code
```javascript
emit = function () {

  this._events || init.call(this);

  var type = arguments[0];

  if (type === 'newListener' && !this.newListener) {
    if (!this._events.newListener) { return false; }
  }

  // Loop through the *_all* functions and invoke them.
  if (this._all) {
    var l = arguments.length;
    var args = new Array(l - 1);
    for (var i = 1; i < l; i++) args[i - 1] = arguments[i];
    for (i = 0, l = this._all.length; i < l; i++) {
      this.event = type;
      this._all[i].apply(this, args);
    }
  }

  // If there is no 'error' event listener then throw.
  if (type === 'error') {

    if (!this._all &&
      !this._events.error &&
      !(this.wildcard && this.listenerTree.error)) {

      if (arguments[1] instanceof Error) {
        throw arguments[1]; // Unhandled 'error' event
      } else {
        throw new Error("Uncaught, unspecified 'error' event.");
      }
      return false;
    }
  }

  var handler;

  if(this.wildcard) {
    handler = [];
    var ns = typeof type === 'string' ? type.split(this.delimiter) : type.slice();
    searchListenerTree.call(this, handler, ns, this.listenerTree, 0);
  }
  else {
    handler = this._events[type];
  }

  if (typeof handler === 'function') {
    this.event = type;
    if (arguments.length === 1) {
      handler.call(this);
    }
    else if (arguments.length > 1)
      switch (arguments.length) {
        case 2:
          handler.call(this, arguments[1]);
          break;
        case 3:
          handler.call(this, arguments[1], arguments[2]);
          break;
        // slower
        default:
          var l = arguments.length;
          var args = new Array(l - 1);
          for (var i = 1; i < l; i++) args[i - 1] = arguments[i];
          handler.apply(this, args);
      }
    return true;
  }
  else if (handler) {
    var l = arguments.length;
    var args = new Array(l - 1);
    for (var i = 1; i < l; i++) args[i - 1] = arguments[i];

    var listeners = handler.slice();
    for (var i = 0, l = listeners.length; i < l; i++) {
      this.event = type;
      listeners[i].apply(this, args);
    }
    return (listeners.length > 0) || !!this._all;
  }
  else {
    return !!this._all;
  }

}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pkgcloud.base.Client.super_.prototype.listeners"></a>[function <span class="apidocSignatureSpan">pkgcloud.base.Client.super_.prototype.</span>listeners (type)](#apidoc.element.pkgcloud.base.Client.super_.prototype.listeners)
- description and source-code
```javascript
listeners = function (type) {
  if(this.wildcard) {
    var handlers = [];
    var ns = typeof type === 'string' ? type.split(this.delimiter) : type.slice();
    searchListenerTree.call(this, handlers, ns, this.listenerTree, 0);
    return handlers;
  }

  this._events || init.call(this);

  if (!this._events[type]) this._events[type] = [];
  if (!isArray(this._events[type])) {
    this._events[type] = [this._events[type]];
  }
  return this._events[type];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pkgcloud.base.Client.super_.prototype.listenersAny"></a>[function <span class="apidocSignatureSpan">pkgcloud.base.Client.super_.prototype.</span>listenersAny ()](#apidoc.element.pkgcloud.base.Client.super_.prototype.listenersAny)
- description and source-code
```javascript
listenersAny = function () {

  if(this._all) {
    return this._all;
  }
  else {
    return [];
  }

}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pkgcloud.base.Client.super_.prototype.many"></a>[function <span class="apidocSignatureSpan">pkgcloud.base.Client.super_.prototype.</span>many (event, ttl, fn)](#apidoc.element.pkgcloud.base.Client.super_.prototype.many)
- description and source-code
```javascript
many = function (event, ttl, fn) {
  var self = this;

  if (typeof fn !== 'function') {
    throw new Error('many only accepts instances of Function');
  }

  function listener() {
    if (--ttl === 0) {
      self.off(event, listener);
    }
    fn.apply(this, arguments);
  }

  listener._origin = fn;

  this.on(event, listener);

  return self;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pkgcloud.base.Client.super_.prototype.off"></a>[function <span class="apidocSignatureSpan">pkgcloud.base.Client.super_.prototype.</span>off (type, listener)](#apidoc.element.pkgcloud.base.Client.super_.prototype.off)
- description and source-code
```javascript
off = function (type, listener) {
  if (typeof listener !== 'function') {
    throw new Error('removeListener only takes instances of Function');
  }

  var handlers,leafs=[];

  if(this.wildcard) {
    var ns = typeof type === 'string' ? type.split(this.delimiter) : type.slice();
    leafs = searchListenerTree.call(this, null, ns, this.listenerTree, 0);
  }
  else {
    // does not use listeners(), so no side effect of creating _events[type]
    if (!this._events[type]) return this;
    handlers = this._events[type];
    leafs.push({_listeners:handlers});
  }

  for (var iLeaf=0; iLeaf<leafs.length; iLeaf++) {
    var leaf = leafs[iLeaf];
    handlers = leaf._listeners;
    if (isArray(handlers)) {

      var position = -1;

      for (var i = 0, length = handlers.length; i < length; i++) {
        if (handlers[i] === listener ||
          (handlers[i].listener && handlers[i].listener === listener) ||
          (handlers[i]._origin && handlers[i]._origin === listener)) {
          position = i;
          break;
        }
      }

      if (position < 0) {
        continue;
      }

      if(this.wildcard) {
        leaf._listeners.splice(position, 1);
      }
      else {
        this._events[type].splice(position, 1);
      }

      if (handlers.length === 0) {
        if(this.wildcard) {
          delete leaf._listeners;
        }
        else {
          delete this._events[type];
        }
      }
      return this;
    }
    else if (handlers === listener ||
      (handlers.listener && handlers.listener === listener) ||
      (handlers._origin && handlers._origin === listener)) {
      if(this.wildcard) {
        delete leaf._listeners;
      }
      else {
        delete this._events[type];
      }
    }
  }

  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pkgcloud.base.Client.super_.prototype.offAny"></a>[function <span class="apidocSignatureSpan">pkgcloud.base.Client.super_.prototype.</span>offAny (fn)](#apidoc.element.pkgcloud.base.Client.super_.prototype.offAny)
- description and source-code
```javascript
offAny = function (fn) {
  var i = 0, l = 0, fns;
  if (fn && this._all && this._all.length > 0) {
    fns = this._all;
    for(i = 0, l = fns.length; i < l; i++) {
      if(fn === fns[i]) {
        fns.splice(i, 1);
        return this;
      }
    }
  } else {
    this._all = [];
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pkgcloud.base.Client.super_.prototype.on"></a>[function <span class="apidocSignatureSpan">pkgcloud.base.Client.super_.prototype.</span>on (type, listener)](#apidoc.element.pkgcloud.base.Client.super_.prototype.on)
- description and source-code
```javascript
on = function (type, listener) {

  if (typeof type === 'function') {
    this.onAny(type);
    return this;
  }

  if (typeof listener !== 'function') {
    throw new Error('on only accepts instances of Function');
  }
  this._events || init.call(this);

  // To avoid recursion in the case that type == "newListeners"! Before
  // adding it to the listeners, first emit "newListeners".
  this.emit('newListener', type, listener);

  if(this.wildcard) {
    growListenerTree.call(this, type, listener);
    return this;
  }

  if (!this._events[type]) {
    // Optimize the case of one listener. Don't need the extra array object.
    this._events[type] = listener;
  }
  else if(typeof this._events[type] === 'function') {
    // Adding the second element, need to change to array.
    this._events[type] = [this._events[type], listener];
  }
  else if (isArray(this._events[type])) {
    // If we've already got an array, just append.
    this._events[type].push(listener);

    // Check for listener leak
    if (!this._events[type].warned) {

      var m = defaultMaxListeners;

      if (typeof this._events.maxListeners !== 'undefined') {
        m = this._events.maxListeners;
      }

      if (m > 0 && this._events[type].length > m) {

        this._events[type].warned = true;
        console.error('(node) warning: possible EventEmitter memory ' +
                      'leak detected. %d listeners added. ' +
                      'Use emitter.setMaxListeners() to increase limit.',
                      this._events[type].length);
        console.trace();
      }
    }
  }
  return this;
}
```
- example usage
```shell
...

var readStream = fs.createReadStream('a-file.txt');
var writeStream = client.upload({
  container: 'a-container',
  remote: 'remote-file-name.txt'
});

writeStream.on('error', function(err) {
  // handle your error case
});

writeStream.on('success', function(file) {
  // success, file will be a File model
});
...
```

#### <a name="apidoc.element.pkgcloud.base.Client.super_.prototype.onAny"></a>[function <span class="apidocSignatureSpan">pkgcloud.base.Client.super_.prototype.</span>onAny (fn)](#apidoc.element.pkgcloud.base.Client.super_.prototype.onAny)
- description and source-code
```javascript
onAny = function (fn) {

  if (typeof fn !== 'function') {
    throw new Error('onAny only accepts instances of Function');
  }

  if(!this._all) {
    this._all = [];
  }

  // Add the function to the event listener collection.
  this._all.push(fn);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pkgcloud.base.Client.super_.prototype.once"></a>[function <span class="apidocSignatureSpan">pkgcloud.base.Client.super_.prototype.</span>once (event, fn)](#apidoc.element.pkgcloud.base.Client.super_.prototype.once)
- description and source-code
```javascript
once = function (event, fn) {
  this.many(event, 1, fn);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pkgcloud.base.Client.super_.prototype.removeAllListeners"></a>[function <span class="apidocSignatureSpan">pkgcloud.base.Client.super_.prototype.</span>removeAllListeners (type)](#apidoc.element.pkgcloud.base.Client.super_.prototype.removeAllListeners)
- description and source-code
```javascript
removeAllListeners = function (type) {
  if (arguments.length === 0) {
    !this._events || init.call(this);
    return this;
  }

  if(this.wildcard) {
    var ns = typeof type === 'string' ? type.split(this.delimiter) : type.slice();
    var leafs = searchListenerTree.call(this, null, ns, this.listenerTree, 0);

    for (var iLeaf=0; iLeaf<leafs.length; iLeaf++) {
      var leaf = leafs[iLeaf];
      leaf._listeners = null;
    }
  }
  else {
    if (!this._events[type]) return this;
    this._events[type] = null;
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pkgcloud.base.Client.super_.prototype.removeListener"></a>[function <span class="apidocSignatureSpan">pkgcloud.base.Client.super_.prototype.</span>removeListener (type, listener)](#apidoc.element.pkgcloud.base.Client.super_.prototype.removeListener)
- description and source-code
```javascript
removeListener = function (type, listener) {
  if (typeof listener !== 'function') {
    throw new Error('removeListener only takes instances of Function');
  }

  var handlers,leafs=[];

  if(this.wildcard) {
    var ns = typeof type === 'string' ? type.split(this.delimiter) : type.slice();
    leafs = searchListenerTree.call(this, null, ns, this.listenerTree, 0);
  }
  else {
    // does not use listeners(), so no side effect of creating _events[type]
    if (!this._events[type]) return this;
    handlers = this._events[type];
    leafs.push({_listeners:handlers});
  }

  for (var iLeaf=0; iLeaf<leafs.length; iLeaf++) {
    var leaf = leafs[iLeaf];
    handlers = leaf._listeners;
    if (isArray(handlers)) {

      var position = -1;

      for (var i = 0, length = handlers.length; i < length; i++) {
        if (handlers[i] === listener ||
          (handlers[i].listener && handlers[i].listener === listener) ||
          (handlers[i]._origin && handlers[i]._origin === listener)) {
          position = i;
          break;
        }
      }

      if (position < 0) {
        continue;
      }

      if(this.wildcard) {
        leaf._listeners.splice(position, 1);
      }
      else {
        this._events[type].splice(position, 1);
      }

      if (handlers.length === 0) {
        if(this.wildcard) {
          delete leaf._listeners;
        }
        else {
          delete this._events[type];
        }
      }
      return this;
    }
    else if (handlers === listener ||
      (handlers.listener && handlers.listener === listener) ||
      (handlers._origin && handlers._origin === listener)) {
      if(this.wildcard) {
        delete leaf._listeners;
      }
      else {
        delete this._events[type];
      }
    }
  }

  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pkgcloud.base.Client.super_.prototype.setMaxListeners"></a>[function <span class="apidocSignatureSpan">pkgcloud.base.Client.super_.prototype.</span>setMaxListeners (n)](#apidoc.element.pkgcloud.base.Client.super_.prototype.setMaxListeners)
- description and source-code
```javascript
setMaxListeners = function (n) {
  this._events || init.call(this);
  this._events.maxListeners = n;
  if (!this._conf) this._conf = {};
  this._conf.maxListeners = n;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.pkgcloud.base.Model"></a>[module pkgcloud.base.Model](#apidoc.module.pkgcloud.base.Model)

#### <a name="apidoc.element.pkgcloud.base.Model.Model"></a>[function <span class="apidocSignatureSpan">pkgcloud.base.</span>Model (client, details)](#apidoc.element.pkgcloud.base.Model.Model)
- description and source-code
```javascript
Model = function (client, details) {
  events.EventEmitter2.call(this, { delimiter: '::', wildcard: true });
  this.client = client;

  if (details) {
    this._setProperties(details);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pkgcloud.base.Model.super_"></a>[function <span class="apidocSignatureSpan">pkgcloud.base.Model.</span>super_ (conf)](#apidoc.element.pkgcloud.base.Model.super_)
- description and source-code
```javascript
function EventEmitter(conf) {
  this._events = {};
  this.newListener = false;
  configure.call(this, conf);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.pkgcloud.base.Model.prototype"></a>[module pkgcloud.base.Model.prototype](#apidoc.module.pkgcloud.base.Model.prototype)

#### <a name="apidoc.element.pkgcloud.base.Model.prototype.clearWait"></a>[function <span class="apidocSignatureSpan">pkgcloud.base.Model.prototype.</span>clearWait (intervalId)](#apidoc.element.pkgcloud.base.Model.prototype.clearWait)
- description and source-code
```javascript
function clear(intervalId) {
  clearInterval(intervalId);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pkgcloud.base.Model.prototype.setWait"></a>[function <span class="apidocSignatureSpan">pkgcloud.base.Model.prototype.</span>setWait (attributes, interval, timeLimit, callback)](#apidoc.element.pkgcloud.base.Model.prototype.setWait)
- description and source-code
```javascript
function setWait(attributes, interval, timeLimit, callback) {
  if (typeof timeLimit === 'function') {
    callback  = timeLimit;
    timeLimit = null;
  }

  var self  = this,
      start = Date.now(),
      fired = false,
      equalCheckId,
      current;

  equalCheckId = setInterval(function () {
    self.refresh(function (err, resource) {

      if (timeLimit) {
        current = Date.now();
        if (current - start > timeLimit) {
          clearInterval(equalCheckId);
          if (!fired) {
            fired = true;
            callback(err, resource);
            return;
          }
        }
      }

      if (err) {
        return;
      } // Ignore errors

      var equal = true,
          keys  = Object.keys(attributes);

      if (typeof attributes === 'function') {
        equal = attributes(resource);
      }
      else {
        for (var i = 0; i < keys.length; i++) {
          if (attributes[keys[i]] !== resource[keys[i]]) {
            equal = false;
            break;
          }
        }
      }

      if (equal) {
        clearInterval(equalCheckId);
        callback(null, resource);
      }
    });
  }, interval);

  return equalCheckId;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pkgcloud.base.Model.prototype.until"></a>[function <span class="apidocSignatureSpan">pkgcloud.base.Model.prototype.</span>until (attributes, interval, timeLimit, callback)](#apidoc.element.pkgcloud.base.Model.prototype.until)
- description and source-code
```javascript
function setWait(attributes, interval, timeLimit, callback) {
  if (typeof timeLimit === 'function') {
    callback  = timeLimit;
    timeLimit = null;
  }

  var self  = this,
      start = Date.now(),
      fired = false,
      equalCheckId,
      current;

  equalCheckId = setInterval(function () {
    self.refresh(function (err, resource) {

      if (timeLimit) {
        current = Date.now();
        if (current - start > timeLimit) {
          clearInterval(equalCheckId);
          if (!fired) {
            fired = true;
            callback(err, resource);
            return;
          }
        }
      }

      if (err) {
        return;
      } // Ignore errors

      var equal = true,
          keys  = Object.keys(attributes);

      if (typeof attributes === 'function') {
        equal = attributes(resource);
      }
      else {
        for (var i = 0; i < keys.length; i++) {
          if (attributes[keys[i]] !== resource[keys[i]]) {
            equal = false;
            break;
          }
        }
      }

      if (equal) {
        clearInterval(equalCheckId);
        callback(null, resource);
      }
    });
  }, interval);

  return equalCheckId;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.pkgcloud.blockstorage"></a>[module pkgcloud.blockstorage](#apidoc.module.pkgcloud.blockstorage)

#### <a name="apidoc.element.pkgcloud.blockstorage.createClient"></a>[function <span class="apidocSignatureSpan">pkgcloud.blockstorage.</span>createClient (options)](#apidoc.element.pkgcloud.blockstorage.createClient)
- description and source-code
```javascript
createClient = function (options) {
  if (!options.provider) {
    throw new Error('options.provider is required to create a new pkgcloud client.');
  }

  var provider = pkgcloud.providers[options.provider];

  if (!provider) {
    throw new Error(options.provider + ' is not a supported provider');
  }

  if (!provider[service]) {
    throw new Error(options.provider + ' does not expose a ' + service + ' service');
  }

  return new provider[service].createClient(options);
}
```
- example usage
```shell
...
### Basic APIs for pkgcloud

Services provided by 'pkgcloud' are exposed in two ways:

* **By service type:** For example, if you wanted to create an API client to communicate with a compute service you could simply
:

''' js
  var client = require('pkgcloud').compute.createClient({
//
// The name of the provider (e.g. "joyent")
//
provider: 'provider-name',

//
// ... Provider specific credentials
...
```



# <a name="apidoc.module.pkgcloud.cdn"></a>[module pkgcloud.cdn](#apidoc.module.pkgcloud.cdn)

#### <a name="apidoc.element.pkgcloud.cdn.createClient"></a>[function <span class="apidocSignatureSpan">pkgcloud.cdn.</span>createClient (options)](#apidoc.element.pkgcloud.cdn.createClient)
- description and source-code
```javascript
createClient = function (options) {
  if (!options.provider) {
    throw new Error('options.provider is required to create a new pkgcloud client.');
  }

  var provider = pkgcloud.providers[options.provider];

  if (!provider) {
    throw new Error(options.provider + ' is not a supported provider');
  }

  if (!provider[service]) {
    throw new Error(options.provider + ' does not expose a ' + service + ' service');
  }

  return new provider[service].createClient(options);
}
```
- example usage
```shell
...
### Basic APIs for pkgcloud

Services provided by 'pkgcloud' are exposed in two ways:

* **By service type:** For example, if you wanted to create an API client to communicate with a compute service you could simply
:

''' js
  var client = require('pkgcloud').compute.createClient({
//
// The name of the provider (e.g. "joyent")
//
provider: 'provider-name',

//
// ... Provider specific credentials
...
```



# <a name="apidoc.module.pkgcloud.compute"></a>[module pkgcloud.compute](#apidoc.module.pkgcloud.compute)

#### <a name="apidoc.element.pkgcloud.compute.Flavor"></a>[function <span class="apidocSignatureSpan">pkgcloud.compute.</span>Flavor (client, details)](#apidoc.element.pkgcloud.compute.Flavor)
- description and source-code
```javascript
Flavor = function (client, details) {
  model.Model.call(this, client, details);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pkgcloud.compute.Image"></a>[function <span class="apidocSignatureSpan">pkgcloud.compute.</span>Image (client, details)](#apidoc.element.pkgcloud.compute.Image)
- description and source-code
```javascript
Image = function (client, details) {
  model.Model.call(this, client, details);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pkgcloud.compute.Server"></a>[function <span class="apidocSignatureSpan">pkgcloud.compute.</span>Server (client, details)](#apidoc.element.pkgcloud.compute.Server)
- description and source-code
```javascript
Server = function (client, details) {
  model.Model.call(this, client, details);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pkgcloud.compute.createClient"></a>[function <span class="apidocSignatureSpan">pkgcloud.compute.</span>createClient (options)](#apidoc.element.pkgcloud.compute.createClient)
- description and source-code
```javascript
createClient = function (options) {
  if (!options.provider) {
    throw new Error('options.provider is required to create a new pkgcloud client.');
  }

  var provider = pkgcloud.providers[options.provider];

  if (!provider) {
    throw new Error(options.provider + ' is not a supported provider');
  }

  if (!provider[service]) {
    throw new Error(options.provider + ' does not expose a ' + service + ' service');
  }

  return new provider[service].createClient(options);
}
```
- example usage
```shell
...
### Basic APIs for pkgcloud

Services provided by 'pkgcloud' are exposed in two ways:

* **By service type:** For example, if you wanted to create an API client to communicate with a compute service you could simply
:

''' js
  var client = require('pkgcloud').compute.createClient({
//
// The name of the provider (e.g. "joyent")
//
provider: 'provider-name',

//
// ... Provider specific credentials
...
```

#### <a name="apidoc.element.pkgcloud.compute.isPrivate"></a>[function <span class="apidocSignatureSpan">pkgcloud.compute.</span>isPrivate (addr)](#apidoc.element.pkgcloud.compute.isPrivate)
- description and source-code
```javascript
function isPrivate(addr) {
  return addr.match(/^10\.([0-9]{1,3})\.([0-9]{1,3})\.([0-9]{1,3})/) != null ||
    addr.match(/^192\.168\.([0-9]{1,3})\.([0-9]{1,3})/) != null ||
    addr.match(
        /^172\.(1[6-9]|2\d|30|31)\.([0-9]{1,3})\.([0-9]{1,3})/) != null ||
    addr.match(/^127\.([0-9]{1,3})\.([0-9]{1,3})\.([0-9]{1,3})/) != null ||
    addr.match(/^169\.254\.([0-9]{1,3})\.([0-9]{1,3})/) != null ||
    addr.match(/^fc00:/) != null || addr.match(/^fe80:/) != null ||
    addr.match(/^::1$/) != null || addr.match(/^::$/) != null;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pkgcloud.compute.isPublic"></a>[function <span class="apidocSignatureSpan">pkgcloud.compute.</span>isPublic (addr)](#apidoc.element.pkgcloud.compute.isPublic)
- description and source-code
```javascript
function isPublic(addr) {
  return !ip.isPrivate(addr);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pkgcloud.compute.serverIp"></a>[function <span class="apidocSignatureSpan">pkgcloud.compute.</span>serverIp (server, options)](#apidoc.element.pkgcloud.compute.serverIp)
- description and source-code
```javascript
serverIp = function (server, options) {
  if (!server && !server.ips && !server.addresses) {
    return null;
  }

  options = options || {};

  var isPublic  = options.isPublic  || exports.isPublic,
      isPrivate = options.isPrivate || exports.isPrivate,
      interfaces,
      addresses,
      pub;

  if (server.ips) {
    //
    // Joyent uses the format:
    // * { ips: ['23.23.23.23', '10.0.0.1'] }
    // OR
    // * { ips: ['10.0.0.1', '23.23.23.23'] }
    //
    pub = server.ips.filter(function (addr) {
      return isPublic(addr);
    });

    return !pub.length
      ? server.ips[0]
      : pub[0];
  }
  else if (server.addresses.public || server.addresses.private) {
    //
    // Rackspace and most sane providers use:
    //
    // addresses: {
    //   public: ['23.23.23.23'],
    //   private: ['10.0.0.1']
    // }
    //
    // OR
    //
    // addresses: {
    //   public: [],
    //   private: ['10.0.0.1']
    // }
    //
    return server.addresses.public.length
      ? server.addresses.public[0]
      : server.addresses.private[0];
  }
  else if (server.addresses) {
    //
    // OpenStack uses a non-standard set of names
    //
    // addresses: {
    //   vlan01: [
    //     { version: 4, addr: '10.0.0.1' }
    //     { version: 4, addr: '23.23.23.23' }
    //   ]
    // }
    //
    interfaces = Object.keys(server.addresses);
    if (!interfaces.length) {
      return null;
    }

    addresses = interfaces.reduce(function (all, iface) {
      server.addresses[iface]
        .map(function (info) { return info.addr })
        .filter(Boolean)
        .forEach(function (addr) {
          if (isPublic(addr)) {
            all['public'].push(addr);
          }
          else if (isPrivate(addr)) {
            all['private'].push(addr);
          }
        });

      return all;
    }, { public: [], private: [] });

    return addresses['public'][0]
      || addresses['private'][0]
      || null;
  }

  return null;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pkgcloud.compute.serverPass"></a>[function <span class="apidocSignatureSpan">pkgcloud.compute.</span>serverPass (server)](#apidoc.element.pkgcloud.compute.serverPass)
- description and source-code
```javascript
serverPass = function (server) {
  if (server.adminPass) {
    return server.adminPass;
  }
  else if (server.metadata) {
    return server.metadata['root'];
  }

  return '';
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.pkgcloud.compute.Flavor"></a>[module pkgcloud.compute.Flavor](#apidoc.module.pkgcloud.compute.Flavor)

#### <a name="apidoc.element.pkgcloud.compute.Flavor.Flavor"></a>[function <span class="apidocSignatureSpan">pkgcloud.compute.</span>Flavor (client, details)](#apidoc.element.pkgcloud.compute.Flavor.Flavor)
- description and source-code
```javascript
Flavor = function (client, details) {
  model.Model.call(this, client, details);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pkgcloud.compute.Flavor.super_"></a>[function <span class="apidocSignatureSpan">pkgcloud.compute.Flavor.</span>super_ (client, details)](#apidoc.element.pkgcloud.compute.Flavor.super_)
- description and source-code
```javascript
super_ = function (client, details) {
  events.EventEmitter2.call(this, { delimiter: '::', wildcard: true });
  this.client = client;

  if (details) {
    this._setProperties(details);
  }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.pkgcloud.compute.Flavor.prototype"></a>[module pkgcloud.compute.Flavor.prototype](#apidoc.module.pkgcloud.compute.Flavor.prototype)

#### <a name="apidoc.element.pkgcloud.compute.Flavor.prototype.refresh"></a>[function <span class="apidocSignatureSpan">pkgcloud.compute.Flavor.prototype.</span>refresh (callback)](#apidoc.element.pkgcloud.compute.Flavor.prototype.refresh)
- description and source-code
```javascript
refresh = function (callback) {
  return this.client.getFlavor(this, callback);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.pkgcloud.compute.Image"></a>[module pkgcloud.compute.Image](#apidoc.module.pkgcloud.compute.Image)

#### <a name="apidoc.element.pkgcloud.compute.Image.Image"></a>[function <span class="apidocSignatureSpan">pkgcloud.compute.</span>Image (client, details)](#apidoc.element.pkgcloud.compute.Image.Image)
- description and source-code
```javascript
Image = function (client, details) {
  model.Model.call(this, client, details);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pkgcloud.compute.Image.super_"></a>[function <span class="apidocSignatureSpan">pkgcloud.compute.Image.</span>super_ (client, details)](#apidoc.element.pkgcloud.compute.Image.super_)
- description and source-code
```javascript
super_ = function (client, details) {
  events.EventEmitter2.call(this, { delimiter: '::', wildcard: true });
  this.client = client;

  if (details) {
    this._setProperties(details);
  }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.pkgcloud.compute.Image.prototype"></a>[module pkgcloud.compute.Image.prototype](#apidoc.module.pkgcloud.compute.Image.prototype)

#### <a name="apidoc.element.pkgcloud.compute.Image.prototype.create"></a>[function <span class="apidocSignatureSpan">pkgcloud.compute.Image.prototype.</span>create (callback)](#apidoc.element.pkgcloud.compute.Image.prototype.create)
- description and source-code
```javascript
create = function (callback) {
  return this.client.createImage(this, callback);
}
```
- example usage
```shell
...
* **MySQL**
  * [Rackspace](docs/providers/rackspace/databases.md)
* **Azure Tables**
  * [Azure](docs/providers/azure.md#database)

Due to the various differences in how these DBaaS providers provision databases only a small surface area of the API for instances
 of 'pkgcloud.database.Client' returned from 'pkgcloud.database.createClient' is consistent across all providers:

* 'client.create(options, callback)'

All of the individual methods are documented for each DBaaS provider listed above.

## DNS -- Beta

##### Note: DNS is considered Beta until there are multiple providers; presently only Rackspace are supported.
...
```

#### <a name="apidoc.element.pkgcloud.compute.Image.prototype.destroy"></a>[function <span class="apidocSignatureSpan">pkgcloud.compute.Image.prototype.</span>destroy (callback)](#apidoc.element.pkgcloud.compute.Image.prototype.destroy)
- description and source-code
```javascript
destroy = function (callback) {
  return this.client.destroyImage(this, callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pkgcloud.compute.Image.prototype.refresh"></a>[function <span class="apidocSignatureSpan">pkgcloud.compute.Image.prototype.</span>refresh (callback)](#apidoc.element.pkgcloud.compute.Image.prototype.refresh)
- description and source-code
```javascript
refresh = function (callback) {
  return this.client.getImage(this, callback);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.pkgcloud.compute.Server"></a>[module pkgcloud.compute.Server](#apidoc.module.pkgcloud.compute.Server)

#### <a name="apidoc.element.pkgcloud.compute.Server.Server"></a>[function <span class="apidocSignatureSpan">pkgcloud.compute.</span>Server (client, details)](#apidoc.element.pkgcloud.compute.Server.Server)
- description and source-code
```javascript
Server = function (client, details) {
  model.Model.call(this, client, details);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pkgcloud.compute.Server.super_"></a>[function <span class="apidocSignatureSpan">pkgcloud.compute.Server.</span>super_ (client, details)](#apidoc.element.pkgcloud.compute.Server.super_)
- description and source-code
```javascript
super_ = function (client, details) {
  events.EventEmitter2.call(this, { delimiter: '::', wildcard: true });
  this.client = client;

  if (details) {
    this._setProperties(details);
  }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.pkgcloud.compute.Server.prototype"></a>[module pkgcloud.compute.Server.prototype](#apidoc.module.pkgcloud.compute.Server.prototype)

#### <a name="apidoc.element.pkgcloud.compute.Server.prototype.create"></a>[function <span class="apidocSignatureSpan">pkgcloud.compute.Server.prototype.</span>create (callback)](#apidoc.element.pkgcloud.compute.Server.prototype.create)
- description and source-code
```javascript
create = function (callback) {
  return this.client.createServer(this, callback);
}
```
- example usage
```shell
...
* **MySQL**
  * [Rackspace](docs/providers/rackspace/databases.md)
* **Azure Tables**
  * [Azure](docs/providers/azure.md#database)

Due to the various differences in how these DBaaS providers provision databases only a small surface area of the API for instances
 of 'pkgcloud.database.Client' returned from 'pkgcloud.database.createClient' is consistent across all providers:

* 'client.create(options, callback)'

All of the individual methods are documented for each DBaaS provider listed above.

## DNS -- Beta

##### Note: DNS is considered Beta until there are multiple providers; presently only Rackspace are supported.
...
```

#### <a name="apidoc.element.pkgcloud.compute.Server.prototype.destroy"></a>[function <span class="apidocSignatureSpan">pkgcloud.compute.Server.prototype.</span>destroy (callback)](#apidoc.element.pkgcloud.compute.Server.prototype.destroy)
- description and source-code
```javascript
destroy = function (callback) {
  return this.client.destroyServer(this, callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pkgcloud.compute.Server.prototype.reboot"></a>[function <span class="apidocSignatureSpan">pkgcloud.compute.Server.prototype.</span>reboot (callback)](#apidoc.element.pkgcloud.compute.Server.prototype.reboot)
- description and source-code
```javascript
reboot = function (callback) {
  return this.client.rebootServer(this, callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pkgcloud.compute.Server.prototype.refresh"></a>[function <span class="apidocSignatureSpan">pkgcloud.compute.Server.prototype.</span>refresh (callback)](#apidoc.element.pkgcloud.compute.Server.prototype.refresh)
- description and source-code
```javascript
refresh = function (callback) {
  var self = this;
  return self.client.getServer(this, function (err, server) {
    if (!err) {
      self._setProperties(server.original);
    }

    return callback.apply(this, arguments);
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pkgcloud.compute.Server.prototype.resize"></a>[function <span class="apidocSignatureSpan">pkgcloud.compute.Server.prototype.</span>resize ()](#apidoc.element.pkgcloud.compute.Server.prototype.resize)
- description and source-code
```javascript
resize = function () {
  var args = [this].concat(Array.prototype.slice.call(arguments));
  this.client.resizeServer.apply(this.client, args);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.pkgcloud.database"></a>[module pkgcloud.database](#apidoc.module.pkgcloud.database)

#### <a name="apidoc.element.pkgcloud.database.createClient"></a>[function <span class="apidocSignatureSpan">pkgcloud.database.</span>createClient (options)](#apidoc.element.pkgcloud.database.createClient)
- description and source-code
```javascript
createClient = function (options) {
  if (!options.provider) {
    throw new Error('options.provider is required to create a new pkgcloud client.');
  }

  var provider = pkgcloud.providers[options.provider];

  if (!provider) {
    throw new Error(options.provider + ' is not a supported provider');
  }

  if (!provider[service]) {
    throw new Error(options.provider + ' does not expose a ' + service + ' service');
  }

  return new provider[service].createClient(options);
}
```
- example usage
```shell
...
### Basic APIs for pkgcloud

Services provided by 'pkgcloud' are exposed in two ways:

* **By service type:** For example, if you wanted to create an API client to communicate with a compute service you could simply
:

''' js
  var client = require('pkgcloud').compute.createClient({
//
// The name of the provider (e.g. "joyent")
//
provider: 'provider-name',

//
// ... Provider specific credentials
...
```



# <a name="apidoc.module.pkgcloud.dns"></a>[module pkgcloud.dns](#apidoc.module.pkgcloud.dns)

#### <a name="apidoc.element.pkgcloud.dns.createClient"></a>[function <span class="apidocSignatureSpan">pkgcloud.dns.</span>createClient (options)](#apidoc.element.pkgcloud.dns.createClient)
- description and source-code
```javascript
createClient = function (options) {
  if (!options.provider) {
    throw new Error('options.provider is required to create a new pkgcloud client.');
  }

  var provider = pkgcloud.providers[options.provider];

  if (!provider) {
    throw new Error(options.provider + ' is not a supported provider');
  }

  if (!provider[service]) {
    throw new Error(options.provider + ' does not expose a ' + service + ' service');
  }

  return new provider[service].createClient(options);
}
```
- example usage
```shell
...
### Basic APIs for pkgcloud

Services provided by 'pkgcloud' are exposed in two ways:

* **By service type:** For example, if you wanted to create an API client to communicate with a compute service you could simply
:

''' js
  var client = require('pkgcloud').compute.createClient({
//
// The name of the provider (e.g. "joyent")
//
provider: 'provider-name',

//
// ... Provider specific credentials
...
```



# <a name="apidoc.module.pkgcloud.loadbalancer"></a>[module pkgcloud.loadbalancer](#apidoc.module.pkgcloud.loadbalancer)

#### <a name="apidoc.element.pkgcloud.loadbalancer.createClient"></a>[function <span class="apidocSignatureSpan">pkgcloud.loadbalancer.</span>createClient (options)](#apidoc.element.pkgcloud.loadbalancer.createClient)
- description and source-code
```javascript
createClient = function (options) {
  if (!options.provider) {
    throw new Error('options.provider is required to create a new pkgcloud client.');
  }

  var provider = pkgcloud.providers[options.provider];

  if (!provider) {
    throw new Error(options.provider + ' is not a supported provider');
  }

  if (!provider[service]) {
    throw new Error(options.provider + ' does not expose a ' + service + ' service');
  }

  return new provider[service].createClient(options);
}
```
- example usage
```shell
...
### Basic APIs for pkgcloud

Services provided by 'pkgcloud' are exposed in two ways:

* **By service type:** For example, if you wanted to create an API client to communicate with a compute service you could simply
:

''' js
  var client = require('pkgcloud').compute.createClient({
//
// The name of the provider (e.g. "joyent")
//
provider: 'provider-name',

//
// ... Provider specific credentials
...
```



# <a name="apidoc.module.pkgcloud.network"></a>[module pkgcloud.network](#apidoc.module.pkgcloud.network)

#### <a name="apidoc.element.pkgcloud.network.createClient"></a>[function <span class="apidocSignatureSpan">pkgcloud.network.</span>createClient (options)](#apidoc.element.pkgcloud.network.createClient)
- description and source-code
```javascript
createClient = function (options) {
  if (!options.provider) {
    throw new Error('options.provider is required to create a new pkgcloud client.');
  }

  var provider = pkgcloud.providers[options.provider];

  if (!provider) {
    throw new Error(options.provider + ' is not a supported provider');
  }

  if (!provider[service]) {
    throw new Error(options.provider + ' does not expose a ' + service + ' service');
  }

  return new provider[service].createClient(options);
}
```
- example usage
```shell
...
### Basic APIs for pkgcloud

Services provided by 'pkgcloud' are exposed in two ways:

* **By service type:** For example, if you wanted to create an API client to communicate with a compute service you could simply
:

''' js
  var client = require('pkgcloud').compute.createClient({
//
// The name of the provider (e.g. "joyent")
//
provider: 'provider-name',

//
// ... Provider specific credentials
...
```



# <a name="apidoc.module.pkgcloud.orchestration"></a>[module pkgcloud.orchestration](#apidoc.module.pkgcloud.orchestration)

#### <a name="apidoc.element.pkgcloud.orchestration.createClient"></a>[function <span class="apidocSignatureSpan">pkgcloud.orchestration.</span>createClient (options)](#apidoc.element.pkgcloud.orchestration.createClient)
- description and source-code
```javascript
createClient = function (options) {
  if (!options.provider) {
    throw new Error('options.provider is required to create a new pkgcloud client.');
  }

  var provider = pkgcloud.providers[options.provider];

  if (!provider) {
    throw new Error(options.provider + ' is not a supported provider');
  }

  if (!provider[service]) {
    throw new Error(options.provider + ' does not expose a ' + service + ' service');
  }

  return new provider[service].createClient(options);
}
```
- example usage
```shell
...
### Basic APIs for pkgcloud

Services provided by 'pkgcloud' are exposed in two ways:

* **By service type:** For example, if you wanted to create an API client to communicate with a compute service you could simply
:

''' js
  var client = require('pkgcloud').compute.createClient({
//
// The name of the provider (e.g. "joyent")
//
provider: 'provider-name',

//
// ... Provider specific credentials
...
```



# <a name="apidoc.module.pkgcloud.storage"></a>[module pkgcloud.storage](#apidoc.module.pkgcloud.storage)

#### <a name="apidoc.element.pkgcloud.storage.Container"></a>[function <span class="apidocSignatureSpan">pkgcloud.storage.</span>Container (client, details)](#apidoc.element.pkgcloud.storage.Container)
- description and source-code
```javascript
Container = function (client, details) {
  this.files = [];

  model.Model.call(this, client, details);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pkgcloud.storage.File"></a>[function <span class="apidocSignatureSpan">pkgcloud.storage.</span>File (client, details)](#apidoc.element.pkgcloud.storage.File)
- description and source-code
```javascript
File = function (client, details) {
  model.Model.call(this, client, details);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pkgcloud.storage.createClient"></a>[function <span class="apidocSignatureSpan">pkgcloud.storage.</span>createClient (options)](#apidoc.element.pkgcloud.storage.createClient)
- description and source-code
```javascript
createClient = function (options) {
  if (!options.provider) {
    throw new Error('options.provider is required to create a new pkgcloud client.');
  }

  var provider = pkgcloud.providers[options.provider];

  if (!provider) {
    throw new Error(options.provider + ' is not a supported provider');
  }

  if (!provider[service]) {
    throw new Error(options.provider + ' does not expose a ' + service + ' service');
  }

  return new provider[service].createClient(options);
}
```
- example usage
```shell
...
### Basic APIs for pkgcloud

Services provided by 'pkgcloud' are exposed in two ways:

* **By service type:** For example, if you wanted to create an API client to communicate with a compute service you could simply
:

''' js
  var client = require('pkgcloud').compute.createClient({
//
// The name of the provider (e.g. "joyent")
//
provider: 'provider-name',

//
// ... Provider specific credentials
...
```



# <a name="apidoc.module.pkgcloud.storage.Container"></a>[module pkgcloud.storage.Container](#apidoc.module.pkgcloud.storage.Container)

#### <a name="apidoc.element.pkgcloud.storage.Container.Container"></a>[function <span class="apidocSignatureSpan">pkgcloud.storage.</span>Container (client, details)](#apidoc.element.pkgcloud.storage.Container.Container)
- description and source-code
```javascript
Container = function (client, details) {
  this.files = [];

  model.Model.call(this, client, details);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pkgcloud.storage.Container.super_"></a>[function <span class="apidocSignatureSpan">pkgcloud.storage.Container.</span>super_ (client, details)](#apidoc.element.pkgcloud.storage.Container.super_)
- description and source-code
```javascript
super_ = function (client, details) {
  events.EventEmitter2.call(this, { delimiter: '::', wildcard: true });
  this.client = client;

  if (details) {
    this._setProperties(details);
  }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.pkgcloud.storage.Container.prototype"></a>[module pkgcloud.storage.Container.prototype](#apidoc.module.pkgcloud.storage.Container.prototype)

#### <a name="apidoc.element.pkgcloud.storage.Container.prototype.create"></a>[function <span class="apidocSignatureSpan">pkgcloud.storage.Container.prototype.</span>create (callback)](#apidoc.element.pkgcloud.storage.Container.prototype.create)
- description and source-code
```javascript
create = function (callback) {
  this.client.createContainer(this.name, callback);
}
```
- example usage
```shell
...
* **MySQL**
  * [Rackspace](docs/providers/rackspace/databases.md)
* **Azure Tables**
  * [Azure](docs/providers/azure.md#database)

Due to the various differences in how these DBaaS providers provision databases only a small surface area of the API for instances
 of 'pkgcloud.database.Client' returned from 'pkgcloud.database.createClient' is consistent across all providers:

* 'client.create(options, callback)'

All of the individual methods are documented for each DBaaS provider listed above.

## DNS -- Beta

##### Note: DNS is considered Beta until there are multiple providers; presently only Rackspace are supported.
...
```

#### <a name="apidoc.element.pkgcloud.storage.Container.prototype.destroy"></a>[function <span class="apidocSignatureSpan">pkgcloud.storage.Container.prototype.</span>destroy (callback)](#apidoc.element.pkgcloud.storage.Container.prototype.destroy)
- description and source-code
```javascript
destroy = function (callback) {
  this.client.destroyContainer(this.name, callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pkgcloud.storage.Container.prototype.getFiles"></a>[function <span class="apidocSignatureSpan">pkgcloud.storage.Container.prototype.</span>getFiles (download, callback)](#apidoc.element.pkgcloud.storage.Container.prototype.getFiles)
- description and source-code
```javascript
getFiles = function (download, callback) {
  var self = this;

  // download can be omitted: (...).getFiles(callback);
  // In this case first argument will be a function
  if (typeof download === 'function' && !(download instanceof RegExp)) {
    callback = download;
    download = false;
  }

  this.client.getFiles(this.name, download, function (err, files) {
    if (err) {
      return callback(err);
    }

    self.files = files;
    callback(null, files);
  });
}
```
- example usage
```shell
...
* 'client.createContainer(options, function (err, container) { })'
* 'client.destroyContainer(containerName, function (err) { })'
* 'client.getContainer(containerName, function (err, container) { })'

### File
* 'client.upload(options)'
* 'client.download(options, function (err) { })'
* 'client.getFiles(container, function (err, files) { })'
* 'client.getFile(container, file, function (err, server) { })'
* 'client.removeFile(container, file, function (err) { })'

Both the '.upload(options)' and '.download(options)' have had **careful attention paid to make sure they are pipe and stream capable
:**

### Upload a File
''' js
...
```

#### <a name="apidoc.element.pkgcloud.storage.Container.prototype.refresh"></a>[function <span class="apidocSignatureSpan">pkgcloud.storage.Container.prototype.</span>refresh (callback)](#apidoc.element.pkgcloud.storage.Container.prototype.refresh)
- description and source-code
```javascript
refresh = function (callback) {
  this.client.getContainer(this, callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pkgcloud.storage.Container.prototype.removeFile"></a>[function <span class="apidocSignatureSpan">pkgcloud.storage.Container.prototype.</span>removeFile (file, callback)](#apidoc.element.pkgcloud.storage.Container.prototype.removeFile)
- description and source-code
```javascript
removeFile = function (file, callback) {
  this.client.removeFile(this.name, file, callback);
}
```
- example usage
```shell
...
* 'client.getContainer(containerName, function (err, container) { })'

### File
* 'client.upload(options)'
* 'client.download(options, function (err) { })'
* 'client.getFiles(container, function (err, files) { })'
* 'client.getFile(container, file, function (err, server) { })'
* 'client.removeFile(container, file, function (err) { })'

Both the '.upload(options)' and '.download(options)' have had **careful attention paid to make sure they are pipe and stream capable
:**

### Upload a File
''' js
var pkgcloud = require('pkgcloud'),
    fs = require('fs');
...
```

#### <a name="apidoc.element.pkgcloud.storage.Container.prototype.upload"></a>[function <span class="apidocSignatureSpan">pkgcloud.storage.Container.prototype.</span>upload (file, local, options, callback)](#apidoc.element.pkgcloud.storage.Container.prototype.upload)
- description and source-code
```javascript
upload = function (file, local, options, callback) {
  this.client.upload(this.name, file, local, options, callback);
}
```
- example usage
```shell
...
### Container
* 'client.getContainers(function (err, containers) { })'
* 'client.createContainer(options, function (err, container) { })'
* 'client.destroyContainer(containerName, function (err) { })'
* 'client.getContainer(containerName, function (err, container) { })'

### File
* 'client.upload(options)'
* 'client.download(options, function (err) { })'
* 'client.getFiles(container, function (err, files) { })'
* 'client.getFile(container, file, function (err, server) { })'
* 'client.removeFile(container, file, function (err) { })'

Both the '.upload(options)' and '.download(options)' have had **careful attention paid to make sure they are pipe and stream capable
:**
...
```



# <a name="apidoc.module.pkgcloud.storage.File"></a>[module pkgcloud.storage.File](#apidoc.module.pkgcloud.storage.File)

#### <a name="apidoc.element.pkgcloud.storage.File.File"></a>[function <span class="apidocSignatureSpan">pkgcloud.storage.</span>File (client, details)](#apidoc.element.pkgcloud.storage.File.File)
- description and source-code
```javascript
File = function (client, details) {
  model.Model.call(this, client, details);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pkgcloud.storage.File.super_"></a>[function <span class="apidocSignatureSpan">pkgcloud.storage.File.</span>super_ (client, details)](#apidoc.element.pkgcloud.storage.File.super_)
- description and source-code
```javascript
super_ = function (client, details) {
  events.EventEmitter2.call(this, { delimiter: '::', wildcard: true });
  this.client = client;

  if (details) {
    this._setProperties(details);
  }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.pkgcloud.storage.File.prototype"></a>[module pkgcloud.storage.File.prototype](#apidoc.module.pkgcloud.storage.File.prototype)

#### <a name="apidoc.element.pkgcloud.storage.File.prototype.download"></a>[function <span class="apidocSignatureSpan">pkgcloud.storage.File.prototype.</span>download (options, callback)](#apidoc.element.pkgcloud.storage.File.prototype.download)
- description and source-code
```javascript
download = function (options, callback) {
  this.client.download(options, callback);
}
```
- example usage
```shell
...
* 'client.getContainers(function (err, containers) { })'
* 'client.createContainer(options, function (err, container) { })'
* 'client.destroyContainer(containerName, function (err) { })'
* 'client.getContainer(containerName, function (err, container) { })'

### File
* 'client.upload(options)'
* 'client.download(options, function (err) { })'
* 'client.getFiles(container, function (err, files) { })'
* 'client.getFile(container, file, function (err, server) { })'
* 'client.removeFile(container, file, function (err) { })'

Both the '.upload(options)' and '.download(options)' have had **careful attention paid to make sure they are pipe and stream capable
:**

### Upload a File
...
```

#### <a name="apidoc.element.pkgcloud.storage.File.prototype.remove"></a>[function <span class="apidocSignatureSpan">pkgcloud.storage.File.prototype.</span>remove (callback)](#apidoc.element.pkgcloud.storage.File.prototype.remove)
- description and source-code
```javascript
remove = function (callback) {
  this.client.removeFile(this.containerName, this.name, callback);
}
```
- example usage
```shell
n/a
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
