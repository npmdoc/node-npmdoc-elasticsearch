# api documentation for  [elasticsearch (v12.1.3)](http://www.elastic.co/guide/en/elasticsearch/client/javascript-api/current/index.html)  [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-elasticsearch.svg)](https://travis-ci.org/npmdoc/node-npmdoc-elasticsearch)
#### The official low-level Elasticsearch client for Node.js and the browser.

[![NPM](https://nodei.co/npm/elasticsearch.png?downloads=true)](https://www.npmjs.com/package/elasticsearch)

[![apidoc](https://npmdoc.github.io/node-npmdoc-elasticsearch/build/screen-capture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-elasticsearch_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-elasticsearch/build..beta..travis-ci.org/apidoc.html)

![package-listing](https://npmdoc.github.io/node-npmdoc-elasticsearch/build/screen-capture.npmPackageListing.svg)



# package.json

```json

{
    "author": {
        "name": "Spencer Alger"
    },
    "browser": {
        "./src/lib/connectors/index.js": "./src/lib/connectors/browser_index.js",
        "./src/lib/loggers/index.js": "./src/lib/loggers/browser_index.js",
        "./src/lib/apis/index.js": "./src/lib/apis/browser_index.js",
        "./test/mocks/server.js": "./test/mocks/browser_server.js"
    },
    "bugs": {
        "url": "https://github.com/elastic/elasticsearch-js/issues"
    },
    "config": {
        "blanket": {
            "pattern": "specified in test/unit/coverage.js"
        },
        "default_api_branch": "5.0",
        "supported_es_branches": [
            "5.0",
            "2.4",
            "2.3",
            "2.2",
            "2.1",
            "2.0",
            "1.7",
            "1.6",
            "1.5",
            "1.4",
            "1.3",
            "1.2",
            "1.1",
            "1.0",
            "0.90"
        ],
        "unstable_es_branches": [
            "5.x",
            "master"
        ]
    },
    "dependencies": {
        "chalk": "^1.0.0",
        "forever-agent": "^0.6.0",
        "lodash": "^4.12.0",
        "promise": "^7.1.1"
    },
    "description": "The official low-level Elasticsearch client for Node.js and the browser.",
    "devDependencies": {
        "@spalger/eslint-config-personal": "^0.4.0",
        "async": "~0.8.0",
        "babel-eslint": "^6.0.4",
        "blanket": "^1.2.3",
        "bluebird": "^2.9.14",
        "eslint": "^2.9.0",
        "eslint-config-airbnb": "^8.0.0",
        "eslint-plugin-import": "^1.6.1",
        "eslint-plugin-jsx-a11y": "^1.0.4",
        "eslint-plugin-react": "^5.0.1",
        "expect.js": "^0.3.1",
        "express": "~3.4.7",
        "find-root": "~0.1.1",
        "glob": "~3.2.7",
        "grunt": "^1.0.1",
        "grunt-cli": "^1.2.0",
        "grunt-contrib-clean": "^1.0.0",
        "grunt-contrib-compress": "^1.2.0",
        "grunt-contrib-concat": "^1.0.1",
        "grunt-contrib-copy": "^1.0.0",
        "grunt-contrib-uglify": "^1.0.1",
        "grunt-contrib-watch": "^1.0.0",
        "grunt-esvm": "^3.2.0",
        "grunt-mocha-cov": "^0.4.0",
        "grunt-open": "~0.2.2",
        "grunt-prompt": "^1.3.3",
        "grunt-run": "^0.6.0",
        "grunt-s3": "~0.2.0-alpha.3",
        "grunt-saucelabs": "^8.6.2",
        "grunt-webpack": "^1.0.11",
        "jquery": "^2.2.3",
        "js-yaml": "^3.6.0",
        "load-grunt-config": "^0.19.2",
        "load-grunt-tasks": "^3.5.0",
        "mocha": "^2.2.5",
        "mocha-lcov-reporter": "0.0.1",
        "mocha-screencast-reporter": "~0.1.4",
        "moment": "^2.13.0",
        "nock": "~0.28.3",
        "null-loader": "^0.1.1",
        "open": "0.0.5",
        "optimist": "~0.6.0",
        "semver": "^4.3.6",
        "sinon": "^1.17.4",
        "split": "~0.3.2",
        "through2": "~0.6.3",
        "through2-map": "~1.4.0",
        "webpack": "^1.13.0",
        "webpack-dev-server": "^1.14.1",
        "xmlbuilder": "~0.4.3"
    },
    "directories": {},
    "dist": {
        "shasum": "5108e67ae5d83e5e7f30d3d294fd7017df0e3771",
        "tarball": "https://registry.npmjs.org/elasticsearch/-/elasticsearch-12.1.3.tgz"
    },
    "engines": {
        "node": ">=0.8"
    },
    "gitHead": "222062695f336412b283b90f0407a03835b5ce9f",
    "homepage": "http://www.elastic.co/guide/en/elasticsearch/client/javascript-api/current/index.html",
    "license": "Apache-2.0",
    "main": "src/elasticsearch.js",
    "maintainers": [
        {
            "name": "lukasolson",
            "email": "olson.lukas@gmail.com"
        },
        {
            "name": "spalger",
            "email": "email@spalger.com"
        },
        {
            "name": "tylersmalley",
            "email": "tylersmalley@me.com"
        }
    ],
    "name": "elasticsearch",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/elastic/elasticsearch-js.git"
    },
    "scripts": {
        "eslint": "eslint src scripts test grunt Gruntfile.js",
        "generate": "node scripts/generate",
        "grunt": "grunt",
        "test": "grunt test"
    },
    "version": "12.1.3"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module elasticsearch](#apidoc.module.elasticsearch)
1.  [function <span class="apidocSignatureSpan">elasticsearch.</span>Client (config)](#apidoc.element.elasticsearch.Client)
1.  [function <span class="apidocSignatureSpan">elasticsearch.</span>ConnectionPool (config)](#apidoc.element.elasticsearch.ConnectionPool)
1.  [function <span class="apidocSignatureSpan">elasticsearch.</span>Transport (config)](#apidoc.element.elasticsearch.Transport)
1.  [function <span class="apidocSignatureSpan">elasticsearch.</span>errors.300 (msg, metadata)](#apidoc.element.elasticsearch.errors.300)
1.  [function <span class="apidocSignatureSpan">elasticsearch.</span>errors.301 (msg, metadata)](#apidoc.element.elasticsearch.errors.301)
1.  [function <span class="apidocSignatureSpan">elasticsearch.</span>errors.302 (msg, metadata)](#apidoc.element.elasticsearch.errors.302)
1.  [function <span class="apidocSignatureSpan">elasticsearch.</span>errors.303 (msg, metadata)](#apidoc.element.elasticsearch.errors.303)
1.  [function <span class="apidocSignatureSpan">elasticsearch.</span>errors.304 (msg, metadata)](#apidoc.element.elasticsearch.errors.304)
1.  [function <span class="apidocSignatureSpan">elasticsearch.</span>errors.305 (msg, metadata)](#apidoc.element.elasticsearch.errors.305)
1.  [function <span class="apidocSignatureSpan">elasticsearch.</span>errors.307 (msg, metadata)](#apidoc.element.elasticsearch.errors.307)
1.  [function <span class="apidocSignatureSpan">elasticsearch.</span>errors.308 (msg, metadata)](#apidoc.element.elasticsearch.errors.308)
1.  [function <span class="apidocSignatureSpan">elasticsearch.</span>errors.400 (msg, metadata)](#apidoc.element.elasticsearch.errors.400)
1.  [function <span class="apidocSignatureSpan">elasticsearch.</span>errors.401 (msg, metadata)](#apidoc.element.elasticsearch.errors.401)
1.  [function <span class="apidocSignatureSpan">elasticsearch.</span>errors.402 (msg, metadata)](#apidoc.element.elasticsearch.errors.402)
1.  [function <span class="apidocSignatureSpan">elasticsearch.</span>errors.403 (msg, metadata)](#apidoc.element.elasticsearch.errors.403)
1.  [function <span class="apidocSignatureSpan">elasticsearch.</span>errors.404 (msg, metadata)](#apidoc.element.elasticsearch.errors.404)
1.  [function <span class="apidocSignatureSpan">elasticsearch.</span>errors.405 (msg, metadata)](#apidoc.element.elasticsearch.errors.405)
1.  [function <span class="apidocSignatureSpan">elasticsearch.</span>errors.406 (msg, metadata)](#apidoc.element.elasticsearch.errors.406)
1.  [function <span class="apidocSignatureSpan">elasticsearch.</span>errors.407 (msg, metadata)](#apidoc.element.elasticsearch.errors.407)
1.  [function <span class="apidocSignatureSpan">elasticsearch.</span>errors.408 (msg, metadata)](#apidoc.element.elasticsearch.errors.408)
1.  [function <span class="apidocSignatureSpan">elasticsearch.</span>errors.409 (msg, metadata)](#apidoc.element.elasticsearch.errors.409)
1.  [function <span class="apidocSignatureSpan">elasticsearch.</span>errors.410 (msg, metadata)](#apidoc.element.elasticsearch.errors.410)
1.  [function <span class="apidocSignatureSpan">elasticsearch.</span>errors.411 (msg, metadata)](#apidoc.element.elasticsearch.errors.411)
1.  [function <span class="apidocSignatureSpan">elasticsearch.</span>errors.412 (msg, metadata)](#apidoc.element.elasticsearch.errors.412)
1.  [function <span class="apidocSignatureSpan">elasticsearch.</span>errors.413 (msg, metadata)](#apidoc.element.elasticsearch.errors.413)
1.  [function <span class="apidocSignatureSpan">elasticsearch.</span>errors.414 (msg, metadata)](#apidoc.element.elasticsearch.errors.414)
1.  [function <span class="apidocSignatureSpan">elasticsearch.</span>errors.415 (msg, metadata)](#apidoc.element.elasticsearch.errors.415)
1.  [function <span class="apidocSignatureSpan">elasticsearch.</span>errors.416 (msg, metadata)](#apidoc.element.elasticsearch.errors.416)
1.  [function <span class="apidocSignatureSpan">elasticsearch.</span>errors.417 (msg, metadata)](#apidoc.element.elasticsearch.errors.417)
1.  [function <span class="apidocSignatureSpan">elasticsearch.</span>errors.418 (msg, metadata)](#apidoc.element.elasticsearch.errors.418)
1.  [function <span class="apidocSignatureSpan">elasticsearch.</span>errors.421 (msg, metadata)](#apidoc.element.elasticsearch.errors.421)
1.  [function <span class="apidocSignatureSpan">elasticsearch.</span>errors.426 (msg, metadata)](#apidoc.element.elasticsearch.errors.426)
1.  [function <span class="apidocSignatureSpan">elasticsearch.</span>errors.429 (msg, metadata)](#apidoc.element.elasticsearch.errors.429)
1.  [function <span class="apidocSignatureSpan">elasticsearch.</span>errors.450 (msg, metadata)](#apidoc.element.elasticsearch.errors.450)
1.  [function <span class="apidocSignatureSpan">elasticsearch.</span>errors.494 (msg, metadata)](#apidoc.element.elasticsearch.errors.494)
1.  [function <span class="apidocSignatureSpan">elasticsearch.</span>errors.497 (msg, metadata)](#apidoc.element.elasticsearch.errors.497)
1.  [function <span class="apidocSignatureSpan">elasticsearch.</span>errors.499 (msg, metadata)](#apidoc.element.elasticsearch.errors.499)
1.  [function <span class="apidocSignatureSpan">elasticsearch.</span>errors.500 (msg, metadata)](#apidoc.element.elasticsearch.errors.500)
1.  [function <span class="apidocSignatureSpan">elasticsearch.</span>errors.501 (msg, metadata)](#apidoc.element.elasticsearch.errors.501)
1.  [function <span class="apidocSignatureSpan">elasticsearch.</span>errors.502 (msg, metadata)](#apidoc.element.elasticsearch.errors.502)
1.  [function <span class="apidocSignatureSpan">elasticsearch.</span>errors.503 (msg, metadata)](#apidoc.element.elasticsearch.errors.503)
1.  [function <span class="apidocSignatureSpan">elasticsearch.</span>errors.504 (msg, metadata)](#apidoc.element.elasticsearch.errors.504)
1.  [function <span class="apidocSignatureSpan">elasticsearch.</span>errors.505 (msg, metadata)](#apidoc.element.elasticsearch.errors.505)
1.  [function <span class="apidocSignatureSpan">elasticsearch.</span>errors.506 (msg, metadata)](#apidoc.element.elasticsearch.errors.506)
1.  [function <span class="apidocSignatureSpan">elasticsearch.</span>errors.510 (msg, metadata)](#apidoc.element.elasticsearch.errors.510)
1.  [function <span class="apidocSignatureSpan">elasticsearch.</span>errors.ConnectionFault (msg)](#apidoc.element.elasticsearch.errors.ConnectionFault)
1.  [function <span class="apidocSignatureSpan">elasticsearch.</span>errors.Generic (msg, metadata)](#apidoc.element.elasticsearch.errors.Generic)
1.  [function <span class="apidocSignatureSpan">elasticsearch.</span>errors.NoConnections (msg)](#apidoc.element.elasticsearch.errors.NoConnections)
1.  [function <span class="apidocSignatureSpan">elasticsearch.</span>errors.RequestTypeError (feature)](#apidoc.element.elasticsearch.errors.RequestTypeError)
1.  [function <span class="apidocSignatureSpan">elasticsearch.</span>errors.Serialization (msg)](#apidoc.element.elasticsearch.errors.Serialization)
1.  [function <span class="apidocSignatureSpan">elasticsearch.</span>errors._Abstract (msg, constructor, metadata)](#apidoc.element.elasticsearch.errors._Abstract)
1.  object <span class="apidocSignatureSpan">elasticsearch.</span>ConnectionPool.calcDeadTimeoutOptions
1.  object <span class="apidocSignatureSpan">elasticsearch.</span>ConnectionPool.connectionClasses
1.  object <span class="apidocSignatureSpan">elasticsearch.</span>ConnectionPool.connectionClasses.http.prototype
1.  object <span class="apidocSignatureSpan">elasticsearch.</span>ConnectionPool.prototype
1.  object <span class="apidocSignatureSpan">elasticsearch.</span>ConnectionPool.selectors
1.  object <span class="apidocSignatureSpan">elasticsearch.</span>Transport.connectionPools
1.  object <span class="apidocSignatureSpan">elasticsearch.</span>Transport.nodesToHostCallbacks
1.  object <span class="apidocSignatureSpan">elasticsearch.</span>Transport.prototype
1.  object <span class="apidocSignatureSpan">elasticsearch.</span>Transport.serializers
1.  object <span class="apidocSignatureSpan">elasticsearch.</span>Transport.serializers.angular.prototype
1.  object <span class="apidocSignatureSpan">elasticsearch.</span>Transport.serializers.json.prototype
1.  object <span class="apidocSignatureSpan">elasticsearch.</span>errors

#### [module elasticsearch.ConnectionPool](#apidoc.module.elasticsearch.ConnectionPool)
1.  [function <span class="apidocSignatureSpan">elasticsearch.</span>ConnectionPool (config)](#apidoc.element.elasticsearch.ConnectionPool.ConnectionPool)
1.  object <span class="apidocSignatureSpan">elasticsearch.ConnectionPool.</span>calcDeadTimeoutOptions
1.  object <span class="apidocSignatureSpan">elasticsearch.ConnectionPool.</span>connectionClasses
1.  object <span class="apidocSignatureSpan">elasticsearch.ConnectionPool.</span>selectors
1.  string <span class="apidocSignatureSpan">elasticsearch.ConnectionPool.</span>defaultConnectionClass
1.  string <span class="apidocSignatureSpan">elasticsearch.ConnectionPool.</span>defaultSelector

#### [module elasticsearch.ConnectionPool.calcDeadTimeoutOptions](#apidoc.module.elasticsearch.ConnectionPool.calcDeadTimeoutOptions)
1.  [function <span class="apidocSignatureSpan">elasticsearch.ConnectionPool.calcDeadTimeoutOptions.</span>exponential (attempt, baseTimeout)](#apidoc.element.elasticsearch.ConnectionPool.calcDeadTimeoutOptions.exponential)
1.  [function <span class="apidocSignatureSpan">elasticsearch.ConnectionPool.calcDeadTimeoutOptions.</span>flat (attempt, baseTimeout)](#apidoc.element.elasticsearch.ConnectionPool.calcDeadTimeoutOptions.flat)

#### [module elasticsearch.ConnectionPool.connectionClasses](#apidoc.module.elasticsearch.ConnectionPool.connectionClasses)
1.  [function <span class="apidocSignatureSpan">elasticsearch.ConnectionPool.connectionClasses.</span>http (host, config)](#apidoc.element.elasticsearch.ConnectionPool.connectionClasses.http)

#### [module elasticsearch.ConnectionPool.connectionClasses.http.prototype](#apidoc.module.elasticsearch.ConnectionPool.connectionClasses.http.prototype)
1.  [function <span class="apidocSignatureSpan">elasticsearch.ConnectionPool.connectionClasses.http.prototype.</span>createAgent (config)](#apidoc.element.elasticsearch.ConnectionPool.connectionClasses.http.prototype.createAgent)
1.  [function <span class="apidocSignatureSpan">elasticsearch.ConnectionPool.connectionClasses.http.prototype.</span>makeAgentConfig (config)](#apidoc.element.elasticsearch.ConnectionPool.connectionClasses.http.prototype.makeAgentConfig)
1.  [function <span class="apidocSignatureSpan">elasticsearch.ConnectionPool.connectionClasses.http.prototype.</span>makeReqParams (params)](#apidoc.element.elasticsearch.ConnectionPool.connectionClasses.http.prototype.makeReqParams)
1.  [function <span class="apidocSignatureSpan">elasticsearch.ConnectionPool.connectionClasses.http.prototype.</span>onStatusSet (status)](#apidoc.element.elasticsearch.ConnectionPool.connectionClasses.http.prototype.onStatusSet)
1.  [function <span class="apidocSignatureSpan">elasticsearch.ConnectionPool.connectionClasses.http.prototype.</span>request (params, cb)](#apidoc.element.elasticsearch.ConnectionPool.connectionClasses.http.prototype.request)

#### [module elasticsearch.ConnectionPool.prototype](#apidoc.module.elasticsearch.ConnectionPool.prototype)
1.  [function <span class="apidocSignatureSpan">elasticsearch.ConnectionPool.prototype.</span>_onConnectionDied (connection, alreadyWasDead)](#apidoc.element.elasticsearch.ConnectionPool.prototype._onConnectionDied)
1.  [function <span class="apidocSignatureSpan">elasticsearch.ConnectionPool.prototype.</span>_onConnectionRevived (connection)](#apidoc.element.elasticsearch.ConnectionPool.prototype._onConnectionRevived)
1.  [function <span class="apidocSignatureSpan">elasticsearch.ConnectionPool.prototype.</span>_selectDeadConnection (cb)](#apidoc.element.elasticsearch.ConnectionPool.prototype._selectDeadConnection)
1.  [function <span class="apidocSignatureSpan">elasticsearch.ConnectionPool.prototype.</span>addConnection (connection)](#apidoc.element.elasticsearch.ConnectionPool.prototype.addConnection)
1.  [function <span class="apidocSignatureSpan">elasticsearch.ConnectionPool.prototype.</span>close ()](#apidoc.element.elasticsearch.ConnectionPool.prototype.close)
1.  [function <span class="apidocSignatureSpan">elasticsearch.ConnectionPool.prototype.</span>empty ()](#apidoc.element.elasticsearch.ConnectionPool.prototype.empty)
1.  [function <span class="apidocSignatureSpan">elasticsearch.ConnectionPool.prototype.</span>getAllHosts ()](#apidoc.element.elasticsearch.ConnectionPool.prototype.getAllHosts)
1.  [function <span class="apidocSignatureSpan">elasticsearch.ConnectionPool.prototype.</span>getConnections (status, limit)](#apidoc.element.elasticsearch.ConnectionPool.prototype.getConnections)
1.  [function <span class="apidocSignatureSpan">elasticsearch.ConnectionPool.prototype.</span>onStatusSet (status, oldStatus, connection)](#apidoc.element.elasticsearch.ConnectionPool.prototype.onStatusSet)
1.  [function <span class="apidocSignatureSpan">elasticsearch.ConnectionPool.prototype.</span>removeConnection (connection)](#apidoc.element.elasticsearch.ConnectionPool.prototype.removeConnection)
1.  [function <span class="apidocSignatureSpan">elasticsearch.ConnectionPool.prototype.</span>select (cb)](#apidoc.element.elasticsearch.ConnectionPool.prototype.select)
1.  [function <span class="apidocSignatureSpan">elasticsearch.ConnectionPool.prototype.</span>setHosts (hosts)](#apidoc.element.elasticsearch.ConnectionPool.prototype.setHosts)

#### [module elasticsearch.ConnectionPool.selectors](#apidoc.module.elasticsearch.ConnectionPool.selectors)
1.  [function <span class="apidocSignatureSpan">elasticsearch.ConnectionPool.selectors.</span>random (connections)](#apidoc.element.elasticsearch.ConnectionPool.selectors.random)
1.  [function <span class="apidocSignatureSpan">elasticsearch.ConnectionPool.selectors.</span>roundRobin (connections)](#apidoc.element.elasticsearch.ConnectionPool.selectors.roundRobin)

#### [module elasticsearch.Transport](#apidoc.module.elasticsearch.Transport)
1.  [function <span class="apidocSignatureSpan">elasticsearch.</span>Transport (config)](#apidoc.element.elasticsearch.Transport.Transport)
1.  object <span class="apidocSignatureSpan">elasticsearch.Transport.</span>connectionPools
1.  object <span class="apidocSignatureSpan">elasticsearch.Transport.</span>nodesToHostCallbacks
1.  object <span class="apidocSignatureSpan">elasticsearch.Transport.</span>serializers

#### [module elasticsearch.Transport.connectionPools](#apidoc.module.elasticsearch.Transport.connectionPools)
1.  [function <span class="apidocSignatureSpan">elasticsearch.Transport.connectionPools.</span>main (config)](#apidoc.element.elasticsearch.Transport.connectionPools.main)

#### [module elasticsearch.Transport.nodesToHostCallbacks](#apidoc.module.elasticsearch.Transport.nodesToHostCallbacks)
1.  [function <span class="apidocSignatureSpan">elasticsearch.Transport.nodesToHostCallbacks.</span>main (nodes)](#apidoc.element.elasticsearch.Transport.nodesToHostCallbacks.main)

#### [module elasticsearch.Transport.prototype](#apidoc.module.elasticsearch.Transport.prototype)
1.  [function <span class="apidocSignatureSpan">elasticsearch.Transport.prototype.</span>_timeout (cb, delay)](#apidoc.element.elasticsearch.Transport.prototype._timeout)
1.  [function <span class="apidocSignatureSpan">elasticsearch.Transport.prototype.</span>close ()](#apidoc.element.elasticsearch.Transport.prototype.close)
1.  [function <span class="apidocSignatureSpan">elasticsearch.Transport.prototype.</span>defer ()](#apidoc.element.elasticsearch.Transport.prototype.defer)
1.  [function <span class="apidocSignatureSpan">elasticsearch.Transport.prototype.</span>request (params, cb)](#apidoc.element.elasticsearch.Transport.prototype.request)
1.  [function <span class="apidocSignatureSpan">elasticsearch.Transport.prototype.</span>setHosts (hostsConfigs)](#apidoc.element.elasticsearch.Transport.prototype.setHosts)
1.  [function <span class="apidocSignatureSpan">elasticsearch.Transport.prototype.</span>sniff (cb)](#apidoc.element.elasticsearch.Transport.prototype.sniff)

#### [module elasticsearch.Transport.serializers](#apidoc.module.elasticsearch.Transport.serializers)
1.  [function <span class="apidocSignatureSpan">elasticsearch.Transport.serializers.</span>angular ()](#apidoc.element.elasticsearch.Transport.serializers.angular)
1.  [function <span class="apidocSignatureSpan">elasticsearch.Transport.serializers.</span>json ()](#apidoc.element.elasticsearch.Transport.serializers.json)

#### [module elasticsearch.Transport.serializers.angular.prototype](#apidoc.module.elasticsearch.Transport.serializers.angular.prototype)
1.  [function <span class="apidocSignatureSpan">elasticsearch.Transport.serializers.angular.prototype.</span>encode (val)](#apidoc.element.elasticsearch.Transport.serializers.angular.prototype.encode)

#### [module elasticsearch.Transport.serializers.json.prototype](#apidoc.module.elasticsearch.Transport.serializers.json.prototype)
1.  [function <span class="apidocSignatureSpan">elasticsearch.Transport.serializers.json.prototype.</span>bulkBody (val)](#apidoc.element.elasticsearch.Transport.serializers.json.prototype.bulkBody)
1.  [function <span class="apidocSignatureSpan">elasticsearch.Transport.serializers.json.prototype.</span>deserialize (str)](#apidoc.element.elasticsearch.Transport.serializers.json.prototype.deserialize)
1.  [function <span class="apidocSignatureSpan">elasticsearch.Transport.serializers.json.prototype.</span>serialize (val, replacer, spaces)](#apidoc.element.elasticsearch.Transport.serializers.json.prototype.serialize)

#### [module elasticsearch.errors](#apidoc.module.elasticsearch.errors)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.</span>300 (msg, metadata)](#apidoc.element.elasticsearch.errors.300)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.</span>301 (msg, metadata)](#apidoc.element.elasticsearch.errors.301)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.</span>302 (msg, metadata)](#apidoc.element.elasticsearch.errors.302)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.</span>303 (msg, metadata)](#apidoc.element.elasticsearch.errors.303)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.</span>304 (msg, metadata)](#apidoc.element.elasticsearch.errors.304)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.</span>305 (msg, metadata)](#apidoc.element.elasticsearch.errors.305)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.</span>307 (msg, metadata)](#apidoc.element.elasticsearch.errors.307)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.</span>308 (msg, metadata)](#apidoc.element.elasticsearch.errors.308)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.</span>400 (msg, metadata)](#apidoc.element.elasticsearch.errors.400)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.</span>401 (msg, metadata)](#apidoc.element.elasticsearch.errors.401)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.</span>402 (msg, metadata)](#apidoc.element.elasticsearch.errors.402)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.</span>403 (msg, metadata)](#apidoc.element.elasticsearch.errors.403)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.</span>404 (msg, metadata)](#apidoc.element.elasticsearch.errors.404)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.</span>405 (msg, metadata)](#apidoc.element.elasticsearch.errors.405)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.</span>406 (msg, metadata)](#apidoc.element.elasticsearch.errors.406)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.</span>407 (msg, metadata)](#apidoc.element.elasticsearch.errors.407)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.</span>408 (msg, metadata)](#apidoc.element.elasticsearch.errors.408)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.</span>409 (msg, metadata)](#apidoc.element.elasticsearch.errors.409)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.</span>410 (msg, metadata)](#apidoc.element.elasticsearch.errors.410)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.</span>411 (msg, metadata)](#apidoc.element.elasticsearch.errors.411)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.</span>412 (msg, metadata)](#apidoc.element.elasticsearch.errors.412)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.</span>413 (msg, metadata)](#apidoc.element.elasticsearch.errors.413)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.</span>414 (msg, metadata)](#apidoc.element.elasticsearch.errors.414)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.</span>415 (msg, metadata)](#apidoc.element.elasticsearch.errors.415)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.</span>416 (msg, metadata)](#apidoc.element.elasticsearch.errors.416)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.</span>417 (msg, metadata)](#apidoc.element.elasticsearch.errors.417)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.</span>418 (msg, metadata)](#apidoc.element.elasticsearch.errors.418)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.</span>421 (msg, metadata)](#apidoc.element.elasticsearch.errors.421)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.</span>426 (msg, metadata)](#apidoc.element.elasticsearch.errors.426)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.</span>429 (msg, metadata)](#apidoc.element.elasticsearch.errors.429)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.</span>450 (msg, metadata)](#apidoc.element.elasticsearch.errors.450)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.</span>494 (msg, metadata)](#apidoc.element.elasticsearch.errors.494)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.</span>497 (msg, metadata)](#apidoc.element.elasticsearch.errors.497)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.</span>499 (msg, metadata)](#apidoc.element.elasticsearch.errors.499)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.</span>500 (msg, metadata)](#apidoc.element.elasticsearch.errors.500)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.</span>501 (msg, metadata)](#apidoc.element.elasticsearch.errors.501)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.</span>502 (msg, metadata)](#apidoc.element.elasticsearch.errors.502)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.</span>503 (msg, metadata)](#apidoc.element.elasticsearch.errors.503)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.</span>504 (msg, metadata)](#apidoc.element.elasticsearch.errors.504)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.</span>505 (msg, metadata)](#apidoc.element.elasticsearch.errors.505)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.</span>506 (msg, metadata)](#apidoc.element.elasticsearch.errors.506)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.</span>510 (msg, metadata)](#apidoc.element.elasticsearch.errors.510)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.</span>AuthenticationException (msg, metadata)](#apidoc.element.elasticsearch.errors.AuthenticationException)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.</span>AuthorizationException (msg, metadata)](#apidoc.element.elasticsearch.errors.AuthorizationException)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.</span>BadGateway (msg, metadata)](#apidoc.element.elasticsearch.errors.BadGateway)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.</span>BadRequest (msg, metadata)](#apidoc.element.elasticsearch.errors.BadRequest)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.</span>BlockedByWindowsParentalControls (msg, metadata)](#apidoc.element.elasticsearch.errors.BlockedByWindowsParentalControls)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.</span>ClientClosedRequest (msg, metadata)](#apidoc.element.elasticsearch.errors.ClientClosedRequest)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.</span>Conflict (msg, metadata)](#apidoc.element.elasticsearch.errors.Conflict)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.</span>ConnectionFault (msg)](#apidoc.element.elasticsearch.errors.ConnectionFault)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.</span>ExpectationFailed (msg, metadata)](#apidoc.element.elasticsearch.errors.ExpectationFailed)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.</span>Forbidden (msg, metadata)](#apidoc.element.elasticsearch.errors.Forbidden)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.</span>Found (msg, metadata)](#apidoc.element.elasticsearch.errors.Found)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.</span>GatewayTimeout (msg, metadata)](#apidoc.element.elasticsearch.errors.GatewayTimeout)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.</span>Generic (msg, metadata)](#apidoc.element.elasticsearch.errors.Generic)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.</span>Gone (msg, metadata)](#apidoc.element.elasticsearch.errors.Gone)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.</span>HTTPToHTTPS (msg, metadata)](#apidoc.element.elasticsearch.errors.HTTPToHTTPS)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.</span>HTTPVersionNotSupported (msg, metadata)](#apidoc.element.elasticsearch.errors.HTTPVersionNotSupported)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.</span>ImATeapot (msg, metadata)](#apidoc.element.elasticsearch.errors.ImATeapot)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.</span>InternalServerError (msg, metadata)](#apidoc.element.elasticsearch.errors.InternalServerError)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.</span>LengthRequired (msg, metadata)](#apidoc.element.elasticsearch.errors.LengthRequired)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.</span>MethodNotAllowed (msg, metadata)](#apidoc.element.elasticsearch.errors.MethodNotAllowed)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.</span>MovedPermanently (msg, metadata)](#apidoc.element.elasticsearch.errors.MovedPermanently)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.</span>MultipleChoices (msg, metadata)](#apidoc.element.elasticsearch.errors.MultipleChoices)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.</span>NoConnections (msg)](#apidoc.element.elasticsearch.errors.NoConnections)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.</span>NotAcceptable (msg, metadata)](#apidoc.element.elasticsearch.errors.NotAcceptable)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.</span>NotExtended (msg, metadata)](#apidoc.element.elasticsearch.errors.NotExtended)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.</span>NotFound (msg, metadata)](#apidoc.element.elasticsearch.errors.NotFound)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.</span>NotImplemented (msg, metadata)](#apidoc.element.elasticsearch.errors.NotImplemented)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.</span>NotModified (msg, metadata)](#apidoc.element.elasticsearch.errors.NotModified)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.</span>PaymentRequired (msg, metadata)](#apidoc.element.elasticsearch.errors.PaymentRequired)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.</span>PermanentRedirect (msg, metadata)](#apidoc.element.elasticsearch.errors.PermanentRedirect)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.</span>PreconditionFailed (msg, metadata)](#apidoc.element.elasticsearch.errors.PreconditionFailed)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.</span>ProxyAuthenticationRequired (msg, metadata)](#apidoc.element.elasticsearch.errors.ProxyAuthenticationRequired)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.</span>RequestEntityTooLarge (msg, metadata)](#apidoc.element.elasticsearch.errors.RequestEntityTooLarge)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.</span>RequestHeaderTooLarge (msg, metadata)](#apidoc.element.elasticsearch.errors.RequestHeaderTooLarge)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.</span>RequestTimeout (msg, metadata)](#apidoc.element.elasticsearch.errors.RequestTimeout)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.</span>RequestTypeError (feature)](#apidoc.element.elasticsearch.errors.RequestTypeError)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.</span>RequestURITooLong (msg, metadata)](#apidoc.element.elasticsearch.errors.RequestURITooLong)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.</span>RequestedRangeNotSatisfiable (msg, metadata)](#apidoc.element.elasticsearch.errors.RequestedRangeNotSatisfiable)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.</span>SeeOther (msg, metadata)](#apidoc.element.elasticsearch.errors.SeeOther)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.</span>Serialization (msg)](#apidoc.element.elasticsearch.errors.Serialization)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.</span>ServiceUnavailable (msg, metadata)](#apidoc.element.elasticsearch.errors.ServiceUnavailable)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.</span>TemporaryRedirect (msg, metadata)](#apidoc.element.elasticsearch.errors.TemporaryRedirect)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.</span>TooManyConnectionsFromThisIP (msg, metadata)](#apidoc.element.elasticsearch.errors.TooManyConnectionsFromThisIP)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.</span>TooManyRequests (msg, metadata)](#apidoc.element.elasticsearch.errors.TooManyRequests)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.</span>UnsupportedMediaType (msg, metadata)](#apidoc.element.elasticsearch.errors.UnsupportedMediaType)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.</span>UpgradeRequired (msg, metadata)](#apidoc.element.elasticsearch.errors.UpgradeRequired)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.</span>UseProxy (msg, metadata)](#apidoc.element.elasticsearch.errors.UseProxy)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.</span>VariantAlsoNegotiates (msg, metadata)](#apidoc.element.elasticsearch.errors.VariantAlsoNegotiates)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.</span>_Abstract (msg, constructor, metadata)](#apidoc.element.elasticsearch.errors._Abstract)

#### [module elasticsearch.errors.300](#apidoc.module.elasticsearch.errors.300)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.300.</span>super_ (msg, constructor, metadata)](#apidoc.element.elasticsearch.errors.300.super_)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.</span>300 (msg, metadata)](#apidoc.element.elasticsearch.errors.300.300)

#### [module elasticsearch.errors.301](#apidoc.module.elasticsearch.errors.301)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.301.</span>super_ (msg, constructor, metadata)](#apidoc.element.elasticsearch.errors.301.super_)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.</span>301 (msg, metadata)](#apidoc.element.elasticsearch.errors.301.301)

#### [module elasticsearch.errors.302](#apidoc.module.elasticsearch.errors.302)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.302.</span>super_ (msg, constructor, metadata)](#apidoc.element.elasticsearch.errors.302.super_)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.</span>302 (msg, metadata)](#apidoc.element.elasticsearch.errors.302.302)

#### [module elasticsearch.errors.303](#apidoc.module.elasticsearch.errors.303)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.303.</span>super_ (msg, constructor, metadata)](#apidoc.element.elasticsearch.errors.303.super_)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.</span>303 (msg, metadata)](#apidoc.element.elasticsearch.errors.303.303)

#### [module elasticsearch.errors.304](#apidoc.module.elasticsearch.errors.304)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.304.</span>super_ (msg, constructor, metadata)](#apidoc.element.elasticsearch.errors.304.super_)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.</span>304 (msg, metadata)](#apidoc.element.elasticsearch.errors.304.304)

#### [module elasticsearch.errors.305](#apidoc.module.elasticsearch.errors.305)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.305.</span>super_ (msg, constructor, metadata)](#apidoc.element.elasticsearch.errors.305.super_)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.</span>305 (msg, metadata)](#apidoc.element.elasticsearch.errors.305.305)

#### [module elasticsearch.errors.307](#apidoc.module.elasticsearch.errors.307)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.307.</span>super_ (msg, constructor, metadata)](#apidoc.element.elasticsearch.errors.307.super_)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.</span>307 (msg, metadata)](#apidoc.element.elasticsearch.errors.307.307)

#### [module elasticsearch.errors.308](#apidoc.module.elasticsearch.errors.308)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.308.</span>super_ (msg, constructor, metadata)](#apidoc.element.elasticsearch.errors.308.super_)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.</span>308 (msg, metadata)](#apidoc.element.elasticsearch.errors.308.308)

#### [module elasticsearch.errors.400](#apidoc.module.elasticsearch.errors.400)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.400.</span>super_ (msg, constructor, metadata)](#apidoc.element.elasticsearch.errors.400.super_)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.</span>400 (msg, metadata)](#apidoc.element.elasticsearch.errors.400.400)

#### [module elasticsearch.errors.401](#apidoc.module.elasticsearch.errors.401)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.401.</span>super_ (msg, constructor, metadata)](#apidoc.element.elasticsearch.errors.401.super_)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.</span>401 (msg, metadata)](#apidoc.element.elasticsearch.errors.401.401)

#### [module elasticsearch.errors.402](#apidoc.module.elasticsearch.errors.402)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.402.</span>super_ (msg, constructor, metadata)](#apidoc.element.elasticsearch.errors.402.super_)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.</span>402 (msg, metadata)](#apidoc.element.elasticsearch.errors.402.402)

#### [module elasticsearch.errors.403](#apidoc.module.elasticsearch.errors.403)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.403.</span>super_ (msg, constructor, metadata)](#apidoc.element.elasticsearch.errors.403.super_)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.</span>403 (msg, metadata)](#apidoc.element.elasticsearch.errors.403.403)

#### [module elasticsearch.errors.404](#apidoc.module.elasticsearch.errors.404)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.404.</span>super_ (msg, constructor, metadata)](#apidoc.element.elasticsearch.errors.404.super_)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.</span>404 (msg, metadata)](#apidoc.element.elasticsearch.errors.404.404)

#### [module elasticsearch.errors.405](#apidoc.module.elasticsearch.errors.405)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.405.</span>super_ (msg, constructor, metadata)](#apidoc.element.elasticsearch.errors.405.super_)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.</span>405 (msg, metadata)](#apidoc.element.elasticsearch.errors.405.405)

#### [module elasticsearch.errors.406](#apidoc.module.elasticsearch.errors.406)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.406.</span>super_ (msg, constructor, metadata)](#apidoc.element.elasticsearch.errors.406.super_)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.</span>406 (msg, metadata)](#apidoc.element.elasticsearch.errors.406.406)

#### [module elasticsearch.errors.407](#apidoc.module.elasticsearch.errors.407)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.407.</span>super_ (msg, constructor, metadata)](#apidoc.element.elasticsearch.errors.407.super_)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.</span>407 (msg, metadata)](#apidoc.element.elasticsearch.errors.407.407)

#### [module elasticsearch.errors.408](#apidoc.module.elasticsearch.errors.408)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.408.</span>super_ (msg, constructor, metadata)](#apidoc.element.elasticsearch.errors.408.super_)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.</span>408 (msg, metadata)](#apidoc.element.elasticsearch.errors.408.408)

#### [module elasticsearch.errors.409](#apidoc.module.elasticsearch.errors.409)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.409.</span>super_ (msg, constructor, metadata)](#apidoc.element.elasticsearch.errors.409.super_)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.</span>409 (msg, metadata)](#apidoc.element.elasticsearch.errors.409.409)

#### [module elasticsearch.errors.410](#apidoc.module.elasticsearch.errors.410)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.410.</span>super_ (msg, constructor, metadata)](#apidoc.element.elasticsearch.errors.410.super_)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.</span>410 (msg, metadata)](#apidoc.element.elasticsearch.errors.410.410)

#### [module elasticsearch.errors.411](#apidoc.module.elasticsearch.errors.411)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.411.</span>super_ (msg, constructor, metadata)](#apidoc.element.elasticsearch.errors.411.super_)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.</span>411 (msg, metadata)](#apidoc.element.elasticsearch.errors.411.411)

#### [module elasticsearch.errors.412](#apidoc.module.elasticsearch.errors.412)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.412.</span>super_ (msg, constructor, metadata)](#apidoc.element.elasticsearch.errors.412.super_)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.</span>412 (msg, metadata)](#apidoc.element.elasticsearch.errors.412.412)

#### [module elasticsearch.errors.413](#apidoc.module.elasticsearch.errors.413)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.413.</span>super_ (msg, constructor, metadata)](#apidoc.element.elasticsearch.errors.413.super_)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.</span>413 (msg, metadata)](#apidoc.element.elasticsearch.errors.413.413)

#### [module elasticsearch.errors.414](#apidoc.module.elasticsearch.errors.414)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.414.</span>super_ (msg, constructor, metadata)](#apidoc.element.elasticsearch.errors.414.super_)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.</span>414 (msg, metadata)](#apidoc.element.elasticsearch.errors.414.414)

#### [module elasticsearch.errors.415](#apidoc.module.elasticsearch.errors.415)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.415.</span>super_ (msg, constructor, metadata)](#apidoc.element.elasticsearch.errors.415.super_)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.</span>415 (msg, metadata)](#apidoc.element.elasticsearch.errors.415.415)

#### [module elasticsearch.errors.416](#apidoc.module.elasticsearch.errors.416)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.416.</span>super_ (msg, constructor, metadata)](#apidoc.element.elasticsearch.errors.416.super_)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.</span>416 (msg, metadata)](#apidoc.element.elasticsearch.errors.416.416)

#### [module elasticsearch.errors.417](#apidoc.module.elasticsearch.errors.417)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.417.</span>super_ (msg, constructor, metadata)](#apidoc.element.elasticsearch.errors.417.super_)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.</span>417 (msg, metadata)](#apidoc.element.elasticsearch.errors.417.417)

#### [module elasticsearch.errors.418](#apidoc.module.elasticsearch.errors.418)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.418.</span>super_ (msg, constructor, metadata)](#apidoc.element.elasticsearch.errors.418.super_)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.</span>418 (msg, metadata)](#apidoc.element.elasticsearch.errors.418.418)

#### [module elasticsearch.errors.421](#apidoc.module.elasticsearch.errors.421)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.421.</span>super_ (msg, constructor, metadata)](#apidoc.element.elasticsearch.errors.421.super_)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.</span>421 (msg, metadata)](#apidoc.element.elasticsearch.errors.421.421)

#### [module elasticsearch.errors.426](#apidoc.module.elasticsearch.errors.426)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.426.</span>super_ (msg, constructor, metadata)](#apidoc.element.elasticsearch.errors.426.super_)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.</span>426 (msg, metadata)](#apidoc.element.elasticsearch.errors.426.426)

#### [module elasticsearch.errors.429](#apidoc.module.elasticsearch.errors.429)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.429.</span>super_ (msg, constructor, metadata)](#apidoc.element.elasticsearch.errors.429.super_)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.</span>429 (msg, metadata)](#apidoc.element.elasticsearch.errors.429.429)

#### [module elasticsearch.errors.450](#apidoc.module.elasticsearch.errors.450)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.450.</span>super_ (msg, constructor, metadata)](#apidoc.element.elasticsearch.errors.450.super_)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.</span>450 (msg, metadata)](#apidoc.element.elasticsearch.errors.450.450)

#### [module elasticsearch.errors.494](#apidoc.module.elasticsearch.errors.494)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.494.</span>super_ (msg, constructor, metadata)](#apidoc.element.elasticsearch.errors.494.super_)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.</span>494 (msg, metadata)](#apidoc.element.elasticsearch.errors.494.494)

#### [module elasticsearch.errors.497](#apidoc.module.elasticsearch.errors.497)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.497.</span>super_ (msg, constructor, metadata)](#apidoc.element.elasticsearch.errors.497.super_)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.</span>497 (msg, metadata)](#apidoc.element.elasticsearch.errors.497.497)

#### [module elasticsearch.errors.499](#apidoc.module.elasticsearch.errors.499)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.499.</span>super_ (msg, constructor, metadata)](#apidoc.element.elasticsearch.errors.499.super_)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.</span>499 (msg, metadata)](#apidoc.element.elasticsearch.errors.499.499)

#### [module elasticsearch.errors.500](#apidoc.module.elasticsearch.errors.500)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.500.</span>super_ (msg, constructor, metadata)](#apidoc.element.elasticsearch.errors.500.super_)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.</span>500 (msg, metadata)](#apidoc.element.elasticsearch.errors.500.500)

#### [module elasticsearch.errors.501](#apidoc.module.elasticsearch.errors.501)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.501.</span>super_ (msg, constructor, metadata)](#apidoc.element.elasticsearch.errors.501.super_)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.</span>501 (msg, metadata)](#apidoc.element.elasticsearch.errors.501.501)

#### [module elasticsearch.errors.502](#apidoc.module.elasticsearch.errors.502)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.502.</span>super_ (msg, constructor, metadata)](#apidoc.element.elasticsearch.errors.502.super_)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.</span>502 (msg, metadata)](#apidoc.element.elasticsearch.errors.502.502)

#### [module elasticsearch.errors.503](#apidoc.module.elasticsearch.errors.503)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.503.</span>super_ (msg, constructor, metadata)](#apidoc.element.elasticsearch.errors.503.super_)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.</span>503 (msg, metadata)](#apidoc.element.elasticsearch.errors.503.503)

#### [module elasticsearch.errors.504](#apidoc.module.elasticsearch.errors.504)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.504.</span>super_ (msg, constructor, metadata)](#apidoc.element.elasticsearch.errors.504.super_)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.</span>504 (msg, metadata)](#apidoc.element.elasticsearch.errors.504.504)

#### [module elasticsearch.errors.505](#apidoc.module.elasticsearch.errors.505)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.505.</span>super_ (msg, constructor, metadata)](#apidoc.element.elasticsearch.errors.505.super_)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.</span>505 (msg, metadata)](#apidoc.element.elasticsearch.errors.505.505)

#### [module elasticsearch.errors.506](#apidoc.module.elasticsearch.errors.506)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.506.</span>super_ (msg, constructor, metadata)](#apidoc.element.elasticsearch.errors.506.super_)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.</span>506 (msg, metadata)](#apidoc.element.elasticsearch.errors.506.506)

#### [module elasticsearch.errors.510](#apidoc.module.elasticsearch.errors.510)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.510.</span>super_ (msg, constructor, metadata)](#apidoc.element.elasticsearch.errors.510.super_)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.</span>510 (msg, metadata)](#apidoc.element.elasticsearch.errors.510.510)

#### [module elasticsearch.errors.ConnectionFault](#apidoc.module.elasticsearch.errors.ConnectionFault)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.</span>ConnectionFault (msg)](#apidoc.element.elasticsearch.errors.ConnectionFault.ConnectionFault)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.ConnectionFault.</span>super_ (msg, constructor, metadata)](#apidoc.element.elasticsearch.errors.ConnectionFault.super_)

#### [module elasticsearch.errors.Generic](#apidoc.module.elasticsearch.errors.Generic)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.</span>Generic (msg, metadata)](#apidoc.element.elasticsearch.errors.Generic.Generic)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.Generic.</span>super_ (msg, constructor, metadata)](#apidoc.element.elasticsearch.errors.Generic.super_)

#### [module elasticsearch.errors.NoConnections](#apidoc.module.elasticsearch.errors.NoConnections)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.</span>NoConnections (msg)](#apidoc.element.elasticsearch.errors.NoConnections.NoConnections)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.NoConnections.</span>super_ (msg, constructor, metadata)](#apidoc.element.elasticsearch.errors.NoConnections.super_)

#### [module elasticsearch.errors.RequestTypeError](#apidoc.module.elasticsearch.errors.RequestTypeError)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.</span>RequestTypeError (feature)](#apidoc.element.elasticsearch.errors.RequestTypeError.RequestTypeError)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.RequestTypeError.</span>super_ (msg, constructor, metadata)](#apidoc.element.elasticsearch.errors.RequestTypeError.super_)

#### [module elasticsearch.errors.Serialization](#apidoc.module.elasticsearch.errors.Serialization)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.</span>Serialization (msg)](#apidoc.element.elasticsearch.errors.Serialization.Serialization)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.Serialization.</span>super_ (msg, constructor, metadata)](#apidoc.element.elasticsearch.errors.Serialization.super_)

#### [module elasticsearch.errors._Abstract](#apidoc.module.elasticsearch.errors._Abstract)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors.</span>_Abstract (msg, constructor, metadata)](#apidoc.element.elasticsearch.errors._Abstract._Abstract)
1.  [function <span class="apidocSignatureSpan">elasticsearch.errors._Abstract.</span>super_ ()](#apidoc.element.elasticsearch.errors._Abstract.super_)



# <a name="apidoc.module.elasticsearch"></a>[module elasticsearch](#apidoc.module.elasticsearch)

#### <a name="apidoc.element.elasticsearch.Client"></a>[function <span class="apidocSignatureSpan">elasticsearch.</span>Client (config)](#apidoc.element.elasticsearch.Client)
- description and source-code
```javascript
function Client(config) {
  config = config || {};

  if (config.__reused) {
    throw new Error('Do not reuse objects to configure the elasticsearch Client class: ' +
      'https://github.com/elasticsearch/elasticsearch-js/issues/33');
  } else {
    config.__reused = true;
  }

  function EsApiClient() {
    // our client will log minimally by default
    if (!config.hasOwnProperty('log')) {
      config.log = 'warning';
    }

    if (!config.hosts && !config.host) {
      config.host = 'http://localhost:9200';
    }

    this.close = function () {
      this.transport.close();
    };

    this.transport = new Transport(config);

    _.each(EsApiClient.prototype, _.bind(function (Fn, prop) {
      if (Fn.prototype instanceof clientAction.ApiNamespace) {
        this[prop] = new Fn(this.transport, this);
      }
    }, this));

    delete this._namespaces;
  }


  EsApiClient.prototype = _.funcEnum(config, 'apiVersion', Client.apis, '_default');
  if (!config.sniffEndpoint && EsApiClient.prototype === Client.apis['0.90']) {
    config.sniffEndpoint = '/_cluster/nodes';
  }

  var Constructor = EsApiClient;

  if (config.plugins) {
    Constructor.prototype = _.cloneDeep(Constructor.prototype);

    _.each(config.plugins, function (setup) {
      Constructor = setup(Constructor, config, {
        apis: require('./apis'),
        connectors: require('./connectors'),
        loggers: require('./loggers'),
        selectors: require('./selectors'),
        serializers: require('./serializers'),
        Client: require('./client'),
        clientAction: clientAction,
        Connection: require('./connection'),
        ConnectionPool: require('./connection_pool'),
        Errors: require('./errors'),
        Host: require('./host'),
        Log: require('./log'),
        Logger: require('./logger'),
        NodesToHost: require('./nodes_to_host'),
        Transport: require('./transport'),
        utils: require('./utils')
      }) || Constructor;
    });
  }

  return new Constructor();
}
```
- example usage
```shell
...
Elasticsearch.js provides support for, and is regularly tested against, Elasticsearch releases 0.90.12 and greater. We also test
 against the latest changes in several branches in the Elasticsearch repository. To tell the client which version of Elastisearch
 you are using, and therefore the API it should provide, set the 'apiVersion' config param. [More info](http://www.elastic.co/guide
/en/elasticsearch/client/javascript-api/current/configuration.html#config-options)

## Examples

Create a client instance
'''js
var elasticsearch = require('elasticsearch');
var client = new elasticsearch.Client({
  host: 'localhost:9200',
  log: 'trace'
});
'''

Send a HEAD request to '/' and allow up to 1 second for it to complete.
'''js
...
```

#### <a name="apidoc.element.elasticsearch.ConnectionPool"></a>[function <span class="apidocSignatureSpan">elasticsearch.</span>ConnectionPool (config)](#apidoc.element.elasticsearch.ConnectionPool)
- description and source-code
```javascript
function ConnectionPool(config) {
  config = config || {};
  _.makeBoundMethods(this);

  if (!config.log) {
    this.log = new Log();
    config.log = this.log;
  } else {
    this.log = config.log;
  }

  // we will need this when we create connections down the road
  this._config = config;

  // get the selector config var
  this.selector = _.funcEnum(config, 'selector', ConnectionPool.selectors, ConnectionPool.defaultSelector);

  // get the connection class
  this.Connection = _.funcEnum(config, 'connectionClass', ConnectionPool.connectionClasses,
    ConnectionPool.defaultConnectionClass);

  // time that connections will wait before being revived
  this.deadTimeout = config.hasOwnProperty('deadTimeout') ? config.deadTimeout : 60000;
  this.maxDeadTimeout = config.hasOwnProperty('maxDeadTimeout') ? config.maxDeadTimeout : 18e5;
  this.calcDeadTimeout = _.funcEnum(config, 'calcDeadTimeout', ConnectionPool.calcDeadTimeoutOptions, 'exponential');

  // a map of connections to their "id" property, used when sniffing
  this.index = {};

  this._conns = {
    alive: [],
    dead: []
  };

  // information about timeouts for dead connections
  this._timeouts = [];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.Transport"></a>[function <span class="apidocSignatureSpan">elasticsearch.</span>Transport (config)](#apidoc.element.elasticsearch.Transport)
- description and source-code
```javascript
function Transport(config) {
  var self = this;
  config = self._config = config || {};

  var LogClass = (typeof config.log === 'function') ? config.log : require('./log');
  config.log = self.log = new LogClass(config);

  // setup the connection pool
  var ConnectionPool = _.funcEnum(config, 'connectionPool', Transport.connectionPools, 'main');
  self.connectionPool = new ConnectionPool(config);

  // setup the serializer
  var Serializer = _.funcEnum(config, 'serializer', Transport.serializers, 'json');
  self.serializer = new Serializer(config);

  // setup the nodesToHostCallback
  self.nodesToHostCallback = _.funcEnum(config, 'nodesToHostCallback', Transport.nodesToHostCallbacks, 'main');

  // setup max retries
  self.maxRetries = config.hasOwnProperty('maxRetries') ? config.maxRetries : 3;

  // setup endpoint to use for sniffing
  self.sniffEndpoint = config.hasOwnProperty('sniffEndpoint') ? config.sniffEndpoint : '/_nodes/_all/clear';

  // setup requestTimeout default
  self.requestTimeout = config.hasOwnProperty('requestTimeout') ? config.requestTimeout : 30000;

  if (config.hasOwnProperty('defer')) {
    self.defer = config.defer;
  }

  // randomizeHosts option
  var randomizeHosts = config.hasOwnProperty('randomizeHosts') ? !!config.randomizeHosts : true;

  if (config.host) {
    config.hosts = config.host;
  }

  if (config.hosts) {
    var hostsConfig = _.createArray(config.hosts, function (val) {
      if (_.isPlainObject(val) || _.isString(val) || val instanceof Host) {
        return val;
      }
    });

    if (!hostsConfig) {
      throw new TypeError('Invalid hosts config. Expected a URL, an array of urls, a host config object, ' +
        'or an array of host config objects.');
    }

    if (randomizeHosts) {
      hostsConfig = _.shuffle(hostsConfig);
    }

    self.setHosts(hostsConfig);
  }

  if (config.hasOwnProperty('sniffedNodesProtocol')) {
    self.sniffedNodesProtocol = config.sniffedNodesProtocol || null;
  } else {
    self.sniffedNodesProtocol = findCommonProtocol(self.connectionPool.getAllHosts()) || null;
  }

  if (config.sniffOnStart) {
    self.sniff();
  }

  if (config.sniffInterval) {
    self._timeout(function doSniff() {
      self.sniff();
      self._timeout(doSniff, config.sniffInterval);
    }, config.sniffInterval);
  }

  if (config.sniffOnConnectionFault) {
    patchSniffOnConnectionFault(self);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.300"></a>[function <span class="apidocSignatureSpan">elasticsearch.</span>errors.300 (msg, metadata)](#apidoc.element.elasticsearch.errors.300)
- description and source-code
```javascript
function StatusCodeError(msg, metadata) {
  this.status = status;
  this.displayName = className;

  var esErrObject = null;
  if (_.isPlainObject(msg)) {
    esErrObject = msg;
    msg = null;
  }

  if (!esErrObject) {
    // errors from es now come in two forms, an error string < 2.0 and
    // an object >= 2.0
    // TODO: remove after dropping support for < 2.0
    ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
    return this;
  }

  msg = [].concat(esErrObject.root_cause || []).reduce(function (memo, cause) {
    if (memo) memo += ' (and) ';

    memo += '[' + cause.type + '] ' + cause.reason;

    var extraData = _.omit(cause, ['type', 'reason']);
    if (_.size(extraData)) {
      memo += ', with ' + prettyPrint(extraData);
    }

    return memo;
  }, '');

  if (!msg) {
    if (esErrObject.type) msg += '[' + esErrObject.type + '] ';
    if (esErrObject.reason) msg += esErrObject.reason;
  }

  ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.301"></a>[function <span class="apidocSignatureSpan">elasticsearch.</span>errors.301 (msg, metadata)](#apidoc.element.elasticsearch.errors.301)
- description and source-code
```javascript
function StatusCodeError(msg, metadata) {
  this.status = status;
  this.displayName = className;

  var esErrObject = null;
  if (_.isPlainObject(msg)) {
    esErrObject = msg;
    msg = null;
  }

  if (!esErrObject) {
    // errors from es now come in two forms, an error string < 2.0 and
    // an object >= 2.0
    // TODO: remove after dropping support for < 2.0
    ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
    return this;
  }

  msg = [].concat(esErrObject.root_cause || []).reduce(function (memo, cause) {
    if (memo) memo += ' (and) ';

    memo += '[' + cause.type + '] ' + cause.reason;

    var extraData = _.omit(cause, ['type', 'reason']);
    if (_.size(extraData)) {
      memo += ', with ' + prettyPrint(extraData);
    }

    return memo;
  }, '');

  if (!msg) {
    if (esErrObject.type) msg += '[' + esErrObject.type + '] ';
    if (esErrObject.reason) msg += esErrObject.reason;
  }

  ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.302"></a>[function <span class="apidocSignatureSpan">elasticsearch.</span>errors.302 (msg, metadata)](#apidoc.element.elasticsearch.errors.302)
- description and source-code
```javascript
function StatusCodeError(msg, metadata) {
  this.status = status;
  this.displayName = className;

  var esErrObject = null;
  if (_.isPlainObject(msg)) {
    esErrObject = msg;
    msg = null;
  }

  if (!esErrObject) {
    // errors from es now come in two forms, an error string < 2.0 and
    // an object >= 2.0
    // TODO: remove after dropping support for < 2.0
    ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
    return this;
  }

  msg = [].concat(esErrObject.root_cause || []).reduce(function (memo, cause) {
    if (memo) memo += ' (and) ';

    memo += '[' + cause.type + '] ' + cause.reason;

    var extraData = _.omit(cause, ['type', 'reason']);
    if (_.size(extraData)) {
      memo += ', with ' + prettyPrint(extraData);
    }

    return memo;
  }, '');

  if (!msg) {
    if (esErrObject.type) msg += '[' + esErrObject.type + '] ';
    if (esErrObject.reason) msg += esErrObject.reason;
  }

  ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.303"></a>[function <span class="apidocSignatureSpan">elasticsearch.</span>errors.303 (msg, metadata)](#apidoc.element.elasticsearch.errors.303)
- description and source-code
```javascript
function StatusCodeError(msg, metadata) {
  this.status = status;
  this.displayName = className;

  var esErrObject = null;
  if (_.isPlainObject(msg)) {
    esErrObject = msg;
    msg = null;
  }

  if (!esErrObject) {
    // errors from es now come in two forms, an error string < 2.0 and
    // an object >= 2.0
    // TODO: remove after dropping support for < 2.0
    ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
    return this;
  }

  msg = [].concat(esErrObject.root_cause || []).reduce(function (memo, cause) {
    if (memo) memo += ' (and) ';

    memo += '[' + cause.type + '] ' + cause.reason;

    var extraData = _.omit(cause, ['type', 'reason']);
    if (_.size(extraData)) {
      memo += ', with ' + prettyPrint(extraData);
    }

    return memo;
  }, '');

  if (!msg) {
    if (esErrObject.type) msg += '[' + esErrObject.type + '] ';
    if (esErrObject.reason) msg += esErrObject.reason;
  }

  ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.304"></a>[function <span class="apidocSignatureSpan">elasticsearch.</span>errors.304 (msg, metadata)](#apidoc.element.elasticsearch.errors.304)
- description and source-code
```javascript
function StatusCodeError(msg, metadata) {
  this.status = status;
  this.displayName = className;

  var esErrObject = null;
  if (_.isPlainObject(msg)) {
    esErrObject = msg;
    msg = null;
  }

  if (!esErrObject) {
    // errors from es now come in two forms, an error string < 2.0 and
    // an object >= 2.0
    // TODO: remove after dropping support for < 2.0
    ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
    return this;
  }

  msg = [].concat(esErrObject.root_cause || []).reduce(function (memo, cause) {
    if (memo) memo += ' (and) ';

    memo += '[' + cause.type + '] ' + cause.reason;

    var extraData = _.omit(cause, ['type', 'reason']);
    if (_.size(extraData)) {
      memo += ', with ' + prettyPrint(extraData);
    }

    return memo;
  }, '');

  if (!msg) {
    if (esErrObject.type) msg += '[' + esErrObject.type + '] ';
    if (esErrObject.reason) msg += esErrObject.reason;
  }

  ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.305"></a>[function <span class="apidocSignatureSpan">elasticsearch.</span>errors.305 (msg, metadata)](#apidoc.element.elasticsearch.errors.305)
- description and source-code
```javascript
function StatusCodeError(msg, metadata) {
  this.status = status;
  this.displayName = className;

  var esErrObject = null;
  if (_.isPlainObject(msg)) {
    esErrObject = msg;
    msg = null;
  }

  if (!esErrObject) {
    // errors from es now come in two forms, an error string < 2.0 and
    // an object >= 2.0
    // TODO: remove after dropping support for < 2.0
    ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
    return this;
  }

  msg = [].concat(esErrObject.root_cause || []).reduce(function (memo, cause) {
    if (memo) memo += ' (and) ';

    memo += '[' + cause.type + '] ' + cause.reason;

    var extraData = _.omit(cause, ['type', 'reason']);
    if (_.size(extraData)) {
      memo += ', with ' + prettyPrint(extraData);
    }

    return memo;
  }, '');

  if (!msg) {
    if (esErrObject.type) msg += '[' + esErrObject.type + '] ';
    if (esErrObject.reason) msg += esErrObject.reason;
  }

  ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.307"></a>[function <span class="apidocSignatureSpan">elasticsearch.</span>errors.307 (msg, metadata)](#apidoc.element.elasticsearch.errors.307)
- description and source-code
```javascript
function StatusCodeError(msg, metadata) {
  this.status = status;
  this.displayName = className;

  var esErrObject = null;
  if (_.isPlainObject(msg)) {
    esErrObject = msg;
    msg = null;
  }

  if (!esErrObject) {
    // errors from es now come in two forms, an error string < 2.0 and
    // an object >= 2.0
    // TODO: remove after dropping support for < 2.0
    ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
    return this;
  }

  msg = [].concat(esErrObject.root_cause || []).reduce(function (memo, cause) {
    if (memo) memo += ' (and) ';

    memo += '[' + cause.type + '] ' + cause.reason;

    var extraData = _.omit(cause, ['type', 'reason']);
    if (_.size(extraData)) {
      memo += ', with ' + prettyPrint(extraData);
    }

    return memo;
  }, '');

  if (!msg) {
    if (esErrObject.type) msg += '[' + esErrObject.type + '] ';
    if (esErrObject.reason) msg += esErrObject.reason;
  }

  ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.308"></a>[function <span class="apidocSignatureSpan">elasticsearch.</span>errors.308 (msg, metadata)](#apidoc.element.elasticsearch.errors.308)
- description and source-code
```javascript
function StatusCodeError(msg, metadata) {
  this.status = status;
  this.displayName = className;

  var esErrObject = null;
  if (_.isPlainObject(msg)) {
    esErrObject = msg;
    msg = null;
  }

  if (!esErrObject) {
    // errors from es now come in two forms, an error string < 2.0 and
    // an object >= 2.0
    // TODO: remove after dropping support for < 2.0
    ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
    return this;
  }

  msg = [].concat(esErrObject.root_cause || []).reduce(function (memo, cause) {
    if (memo) memo += ' (and) ';

    memo += '[' + cause.type + '] ' + cause.reason;

    var extraData = _.omit(cause, ['type', 'reason']);
    if (_.size(extraData)) {
      memo += ', with ' + prettyPrint(extraData);
    }

    return memo;
  }, '');

  if (!msg) {
    if (esErrObject.type) msg += '[' + esErrObject.type + '] ';
    if (esErrObject.reason) msg += esErrObject.reason;
  }

  ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.400"></a>[function <span class="apidocSignatureSpan">elasticsearch.</span>errors.400 (msg, metadata)](#apidoc.element.elasticsearch.errors.400)
- description and source-code
```javascript
function StatusCodeError(msg, metadata) {
  this.status = status;
  this.displayName = className;

  var esErrObject = null;
  if (_.isPlainObject(msg)) {
    esErrObject = msg;
    msg = null;
  }

  if (!esErrObject) {
    // errors from es now come in two forms, an error string < 2.0 and
    // an object >= 2.0
    // TODO: remove after dropping support for < 2.0
    ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
    return this;
  }

  msg = [].concat(esErrObject.root_cause || []).reduce(function (memo, cause) {
    if (memo) memo += ' (and) ';

    memo += '[' + cause.type + '] ' + cause.reason;

    var extraData = _.omit(cause, ['type', 'reason']);
    if (_.size(extraData)) {
      memo += ', with ' + prettyPrint(extraData);
    }

    return memo;
  }, '');

  if (!msg) {
    if (esErrObject.type) msg += '[' + esErrObject.type + '] ';
    if (esErrObject.reason) msg += esErrObject.reason;
  }

  ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.401"></a>[function <span class="apidocSignatureSpan">elasticsearch.</span>errors.401 (msg, metadata)](#apidoc.element.elasticsearch.errors.401)
- description and source-code
```javascript
function StatusCodeError(msg, metadata) {
  this.status = status;
  this.displayName = className;

  var esErrObject = null;
  if (_.isPlainObject(msg)) {
    esErrObject = msg;
    msg = null;
  }

  if (!esErrObject) {
    // errors from es now come in two forms, an error string < 2.0 and
    // an object >= 2.0
    // TODO: remove after dropping support for < 2.0
    ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
    return this;
  }

  msg = [].concat(esErrObject.root_cause || []).reduce(function (memo, cause) {
    if (memo) memo += ' (and) ';

    memo += '[' + cause.type + '] ' + cause.reason;

    var extraData = _.omit(cause, ['type', 'reason']);
    if (_.size(extraData)) {
      memo += ', with ' + prettyPrint(extraData);
    }

    return memo;
  }, '');

  if (!msg) {
    if (esErrObject.type) msg += '[' + esErrObject.type + '] ';
    if (esErrObject.reason) msg += esErrObject.reason;
  }

  ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.402"></a>[function <span class="apidocSignatureSpan">elasticsearch.</span>errors.402 (msg, metadata)](#apidoc.element.elasticsearch.errors.402)
- description and source-code
```javascript
function StatusCodeError(msg, metadata) {
  this.status = status;
  this.displayName = className;

  var esErrObject = null;
  if (_.isPlainObject(msg)) {
    esErrObject = msg;
    msg = null;
  }

  if (!esErrObject) {
    // errors from es now come in two forms, an error string < 2.0 and
    // an object >= 2.0
    // TODO: remove after dropping support for < 2.0
    ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
    return this;
  }

  msg = [].concat(esErrObject.root_cause || []).reduce(function (memo, cause) {
    if (memo) memo += ' (and) ';

    memo += '[' + cause.type + '] ' + cause.reason;

    var extraData = _.omit(cause, ['type', 'reason']);
    if (_.size(extraData)) {
      memo += ', with ' + prettyPrint(extraData);
    }

    return memo;
  }, '');

  if (!msg) {
    if (esErrObject.type) msg += '[' + esErrObject.type + '] ';
    if (esErrObject.reason) msg += esErrObject.reason;
  }

  ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.403"></a>[function <span class="apidocSignatureSpan">elasticsearch.</span>errors.403 (msg, metadata)](#apidoc.element.elasticsearch.errors.403)
- description and source-code
```javascript
function StatusCodeError(msg, metadata) {
  this.status = status;
  this.displayName = className;

  var esErrObject = null;
  if (_.isPlainObject(msg)) {
    esErrObject = msg;
    msg = null;
  }

  if (!esErrObject) {
    // errors from es now come in two forms, an error string < 2.0 and
    // an object >= 2.0
    // TODO: remove after dropping support for < 2.0
    ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
    return this;
  }

  msg = [].concat(esErrObject.root_cause || []).reduce(function (memo, cause) {
    if (memo) memo += ' (and) ';

    memo += '[' + cause.type + '] ' + cause.reason;

    var extraData = _.omit(cause, ['type', 'reason']);
    if (_.size(extraData)) {
      memo += ', with ' + prettyPrint(extraData);
    }

    return memo;
  }, '');

  if (!msg) {
    if (esErrObject.type) msg += '[' + esErrObject.type + '] ';
    if (esErrObject.reason) msg += esErrObject.reason;
  }

  ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.404"></a>[function <span class="apidocSignatureSpan">elasticsearch.</span>errors.404 (msg, metadata)](#apidoc.element.elasticsearch.errors.404)
- description and source-code
```javascript
function StatusCodeError(msg, metadata) {
  this.status = status;
  this.displayName = className;

  var esErrObject = null;
  if (_.isPlainObject(msg)) {
    esErrObject = msg;
    msg = null;
  }

  if (!esErrObject) {
    // errors from es now come in two forms, an error string < 2.0 and
    // an object >= 2.0
    // TODO: remove after dropping support for < 2.0
    ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
    return this;
  }

  msg = [].concat(esErrObject.root_cause || []).reduce(function (memo, cause) {
    if (memo) memo += ' (and) ';

    memo += '[' + cause.type + '] ' + cause.reason;

    var extraData = _.omit(cause, ['type', 'reason']);
    if (_.size(extraData)) {
      memo += ', with ' + prettyPrint(extraData);
    }

    return memo;
  }, '');

  if (!msg) {
    if (esErrObject.type) msg += '[' + esErrObject.type + '] ';
    if (esErrObject.reason) msg += esErrObject.reason;
  }

  ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.405"></a>[function <span class="apidocSignatureSpan">elasticsearch.</span>errors.405 (msg, metadata)](#apidoc.element.elasticsearch.errors.405)
- description and source-code
```javascript
function StatusCodeError(msg, metadata) {
  this.status = status;
  this.displayName = className;

  var esErrObject = null;
  if (_.isPlainObject(msg)) {
    esErrObject = msg;
    msg = null;
  }

  if (!esErrObject) {
    // errors from es now come in two forms, an error string < 2.0 and
    // an object >= 2.0
    // TODO: remove after dropping support for < 2.0
    ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
    return this;
  }

  msg = [].concat(esErrObject.root_cause || []).reduce(function (memo, cause) {
    if (memo) memo += ' (and) ';

    memo += '[' + cause.type + '] ' + cause.reason;

    var extraData = _.omit(cause, ['type', 'reason']);
    if (_.size(extraData)) {
      memo += ', with ' + prettyPrint(extraData);
    }

    return memo;
  }, '');

  if (!msg) {
    if (esErrObject.type) msg += '[' + esErrObject.type + '] ';
    if (esErrObject.reason) msg += esErrObject.reason;
  }

  ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.406"></a>[function <span class="apidocSignatureSpan">elasticsearch.</span>errors.406 (msg, metadata)](#apidoc.element.elasticsearch.errors.406)
- description and source-code
```javascript
function StatusCodeError(msg, metadata) {
  this.status = status;
  this.displayName = className;

  var esErrObject = null;
  if (_.isPlainObject(msg)) {
    esErrObject = msg;
    msg = null;
  }

  if (!esErrObject) {
    // errors from es now come in two forms, an error string < 2.0 and
    // an object >= 2.0
    // TODO: remove after dropping support for < 2.0
    ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
    return this;
  }

  msg = [].concat(esErrObject.root_cause || []).reduce(function (memo, cause) {
    if (memo) memo += ' (and) ';

    memo += '[' + cause.type + '] ' + cause.reason;

    var extraData = _.omit(cause, ['type', 'reason']);
    if (_.size(extraData)) {
      memo += ', with ' + prettyPrint(extraData);
    }

    return memo;
  }, '');

  if (!msg) {
    if (esErrObject.type) msg += '[' + esErrObject.type + '] ';
    if (esErrObject.reason) msg += esErrObject.reason;
  }

  ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.407"></a>[function <span class="apidocSignatureSpan">elasticsearch.</span>errors.407 (msg, metadata)](#apidoc.element.elasticsearch.errors.407)
- description and source-code
```javascript
function StatusCodeError(msg, metadata) {
  this.status = status;
  this.displayName = className;

  var esErrObject = null;
  if (_.isPlainObject(msg)) {
    esErrObject = msg;
    msg = null;
  }

  if (!esErrObject) {
    // errors from es now come in two forms, an error string < 2.0 and
    // an object >= 2.0
    // TODO: remove after dropping support for < 2.0
    ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
    return this;
  }

  msg = [].concat(esErrObject.root_cause || []).reduce(function (memo, cause) {
    if (memo) memo += ' (and) ';

    memo += '[' + cause.type + '] ' + cause.reason;

    var extraData = _.omit(cause, ['type', 'reason']);
    if (_.size(extraData)) {
      memo += ', with ' + prettyPrint(extraData);
    }

    return memo;
  }, '');

  if (!msg) {
    if (esErrObject.type) msg += '[' + esErrObject.type + '] ';
    if (esErrObject.reason) msg += esErrObject.reason;
  }

  ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.408"></a>[function <span class="apidocSignatureSpan">elasticsearch.</span>errors.408 (msg, metadata)](#apidoc.element.elasticsearch.errors.408)
- description and source-code
```javascript
function StatusCodeError(msg, metadata) {
  this.status = status;
  this.displayName = className;

  var esErrObject = null;
  if (_.isPlainObject(msg)) {
    esErrObject = msg;
    msg = null;
  }

  if (!esErrObject) {
    // errors from es now come in two forms, an error string < 2.0 and
    // an object >= 2.0
    // TODO: remove after dropping support for < 2.0
    ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
    return this;
  }

  msg = [].concat(esErrObject.root_cause || []).reduce(function (memo, cause) {
    if (memo) memo += ' (and) ';

    memo += '[' + cause.type + '] ' + cause.reason;

    var extraData = _.omit(cause, ['type', 'reason']);
    if (_.size(extraData)) {
      memo += ', with ' + prettyPrint(extraData);
    }

    return memo;
  }, '');

  if (!msg) {
    if (esErrObject.type) msg += '[' + esErrObject.type + '] ';
    if (esErrObject.reason) msg += esErrObject.reason;
  }

  ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.409"></a>[function <span class="apidocSignatureSpan">elasticsearch.</span>errors.409 (msg, metadata)](#apidoc.element.elasticsearch.errors.409)
- description and source-code
```javascript
function StatusCodeError(msg, metadata) {
  this.status = status;
  this.displayName = className;

  var esErrObject = null;
  if (_.isPlainObject(msg)) {
    esErrObject = msg;
    msg = null;
  }

  if (!esErrObject) {
    // errors from es now come in two forms, an error string < 2.0 and
    // an object >= 2.0
    // TODO: remove after dropping support for < 2.0
    ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
    return this;
  }

  msg = [].concat(esErrObject.root_cause || []).reduce(function (memo, cause) {
    if (memo) memo += ' (and) ';

    memo += '[' + cause.type + '] ' + cause.reason;

    var extraData = _.omit(cause, ['type', 'reason']);
    if (_.size(extraData)) {
      memo += ', with ' + prettyPrint(extraData);
    }

    return memo;
  }, '');

  if (!msg) {
    if (esErrObject.type) msg += '[' + esErrObject.type + '] ';
    if (esErrObject.reason) msg += esErrObject.reason;
  }

  ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.410"></a>[function <span class="apidocSignatureSpan">elasticsearch.</span>errors.410 (msg, metadata)](#apidoc.element.elasticsearch.errors.410)
- description and source-code
```javascript
function StatusCodeError(msg, metadata) {
  this.status = status;
  this.displayName = className;

  var esErrObject = null;
  if (_.isPlainObject(msg)) {
    esErrObject = msg;
    msg = null;
  }

  if (!esErrObject) {
    // errors from es now come in two forms, an error string < 2.0 and
    // an object >= 2.0
    // TODO: remove after dropping support for < 2.0
    ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
    return this;
  }

  msg = [].concat(esErrObject.root_cause || []).reduce(function (memo, cause) {
    if (memo) memo += ' (and) ';

    memo += '[' + cause.type + '] ' + cause.reason;

    var extraData = _.omit(cause, ['type', 'reason']);
    if (_.size(extraData)) {
      memo += ', with ' + prettyPrint(extraData);
    }

    return memo;
  }, '');

  if (!msg) {
    if (esErrObject.type) msg += '[' + esErrObject.type + '] ';
    if (esErrObject.reason) msg += esErrObject.reason;
  }

  ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.411"></a>[function <span class="apidocSignatureSpan">elasticsearch.</span>errors.411 (msg, metadata)](#apidoc.element.elasticsearch.errors.411)
- description and source-code
```javascript
function StatusCodeError(msg, metadata) {
  this.status = status;
  this.displayName = className;

  var esErrObject = null;
  if (_.isPlainObject(msg)) {
    esErrObject = msg;
    msg = null;
  }

  if (!esErrObject) {
    // errors from es now come in two forms, an error string < 2.0 and
    // an object >= 2.0
    // TODO: remove after dropping support for < 2.0
    ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
    return this;
  }

  msg = [].concat(esErrObject.root_cause || []).reduce(function (memo, cause) {
    if (memo) memo += ' (and) ';

    memo += '[' + cause.type + '] ' + cause.reason;

    var extraData = _.omit(cause, ['type', 'reason']);
    if (_.size(extraData)) {
      memo += ', with ' + prettyPrint(extraData);
    }

    return memo;
  }, '');

  if (!msg) {
    if (esErrObject.type) msg += '[' + esErrObject.type + '] ';
    if (esErrObject.reason) msg += esErrObject.reason;
  }

  ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.412"></a>[function <span class="apidocSignatureSpan">elasticsearch.</span>errors.412 (msg, metadata)](#apidoc.element.elasticsearch.errors.412)
- description and source-code
```javascript
function StatusCodeError(msg, metadata) {
  this.status = status;
  this.displayName = className;

  var esErrObject = null;
  if (_.isPlainObject(msg)) {
    esErrObject = msg;
    msg = null;
  }

  if (!esErrObject) {
    // errors from es now come in two forms, an error string < 2.0 and
    // an object >= 2.0
    // TODO: remove after dropping support for < 2.0
    ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
    return this;
  }

  msg = [].concat(esErrObject.root_cause || []).reduce(function (memo, cause) {
    if (memo) memo += ' (and) ';

    memo += '[' + cause.type + '] ' + cause.reason;

    var extraData = _.omit(cause, ['type', 'reason']);
    if (_.size(extraData)) {
      memo += ', with ' + prettyPrint(extraData);
    }

    return memo;
  }, '');

  if (!msg) {
    if (esErrObject.type) msg += '[' + esErrObject.type + '] ';
    if (esErrObject.reason) msg += esErrObject.reason;
  }

  ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.413"></a>[function <span class="apidocSignatureSpan">elasticsearch.</span>errors.413 (msg, metadata)](#apidoc.element.elasticsearch.errors.413)
- description and source-code
```javascript
function StatusCodeError(msg, metadata) {
  this.status = status;
  this.displayName = className;

  var esErrObject = null;
  if (_.isPlainObject(msg)) {
    esErrObject = msg;
    msg = null;
  }

  if (!esErrObject) {
    // errors from es now come in two forms, an error string < 2.0 and
    // an object >= 2.0
    // TODO: remove after dropping support for < 2.0
    ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
    return this;
  }

  msg = [].concat(esErrObject.root_cause || []).reduce(function (memo, cause) {
    if (memo) memo += ' (and) ';

    memo += '[' + cause.type + '] ' + cause.reason;

    var extraData = _.omit(cause, ['type', 'reason']);
    if (_.size(extraData)) {
      memo += ', with ' + prettyPrint(extraData);
    }

    return memo;
  }, '');

  if (!msg) {
    if (esErrObject.type) msg += '[' + esErrObject.type + '] ';
    if (esErrObject.reason) msg += esErrObject.reason;
  }

  ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.414"></a>[function <span class="apidocSignatureSpan">elasticsearch.</span>errors.414 (msg, metadata)](#apidoc.element.elasticsearch.errors.414)
- description and source-code
```javascript
function StatusCodeError(msg, metadata) {
  this.status = status;
  this.displayName = className;

  var esErrObject = null;
  if (_.isPlainObject(msg)) {
    esErrObject = msg;
    msg = null;
  }

  if (!esErrObject) {
    // errors from es now come in two forms, an error string < 2.0 and
    // an object >= 2.0
    // TODO: remove after dropping support for < 2.0
    ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
    return this;
  }

  msg = [].concat(esErrObject.root_cause || []).reduce(function (memo, cause) {
    if (memo) memo += ' (and) ';

    memo += '[' + cause.type + '] ' + cause.reason;

    var extraData = _.omit(cause, ['type', 'reason']);
    if (_.size(extraData)) {
      memo += ', with ' + prettyPrint(extraData);
    }

    return memo;
  }, '');

  if (!msg) {
    if (esErrObject.type) msg += '[' + esErrObject.type + '] ';
    if (esErrObject.reason) msg += esErrObject.reason;
  }

  ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.415"></a>[function <span class="apidocSignatureSpan">elasticsearch.</span>errors.415 (msg, metadata)](#apidoc.element.elasticsearch.errors.415)
- description and source-code
```javascript
function StatusCodeError(msg, metadata) {
  this.status = status;
  this.displayName = className;

  var esErrObject = null;
  if (_.isPlainObject(msg)) {
    esErrObject = msg;
    msg = null;
  }

  if (!esErrObject) {
    // errors from es now come in two forms, an error string < 2.0 and
    // an object >= 2.0
    // TODO: remove after dropping support for < 2.0
    ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
    return this;
  }

  msg = [].concat(esErrObject.root_cause || []).reduce(function (memo, cause) {
    if (memo) memo += ' (and) ';

    memo += '[' + cause.type + '] ' + cause.reason;

    var extraData = _.omit(cause, ['type', 'reason']);
    if (_.size(extraData)) {
      memo += ', with ' + prettyPrint(extraData);
    }

    return memo;
  }, '');

  if (!msg) {
    if (esErrObject.type) msg += '[' + esErrObject.type + '] ';
    if (esErrObject.reason) msg += esErrObject.reason;
  }

  ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.416"></a>[function <span class="apidocSignatureSpan">elasticsearch.</span>errors.416 (msg, metadata)](#apidoc.element.elasticsearch.errors.416)
- description and source-code
```javascript
function StatusCodeError(msg, metadata) {
  this.status = status;
  this.displayName = className;

  var esErrObject = null;
  if (_.isPlainObject(msg)) {
    esErrObject = msg;
    msg = null;
  }

  if (!esErrObject) {
    // errors from es now come in two forms, an error string < 2.0 and
    // an object >= 2.0
    // TODO: remove after dropping support for < 2.0
    ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
    return this;
  }

  msg = [].concat(esErrObject.root_cause || []).reduce(function (memo, cause) {
    if (memo) memo += ' (and) ';

    memo += '[' + cause.type + '] ' + cause.reason;

    var extraData = _.omit(cause, ['type', 'reason']);
    if (_.size(extraData)) {
      memo += ', with ' + prettyPrint(extraData);
    }

    return memo;
  }, '');

  if (!msg) {
    if (esErrObject.type) msg += '[' + esErrObject.type + '] ';
    if (esErrObject.reason) msg += esErrObject.reason;
  }

  ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.417"></a>[function <span class="apidocSignatureSpan">elasticsearch.</span>errors.417 (msg, metadata)](#apidoc.element.elasticsearch.errors.417)
- description and source-code
```javascript
function StatusCodeError(msg, metadata) {
  this.status = status;
  this.displayName = className;

  var esErrObject = null;
  if (_.isPlainObject(msg)) {
    esErrObject = msg;
    msg = null;
  }

  if (!esErrObject) {
    // errors from es now come in two forms, an error string < 2.0 and
    // an object >= 2.0
    // TODO: remove after dropping support for < 2.0
    ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
    return this;
  }

  msg = [].concat(esErrObject.root_cause || []).reduce(function (memo, cause) {
    if (memo) memo += ' (and) ';

    memo += '[' + cause.type + '] ' + cause.reason;

    var extraData = _.omit(cause, ['type', 'reason']);
    if (_.size(extraData)) {
      memo += ', with ' + prettyPrint(extraData);
    }

    return memo;
  }, '');

  if (!msg) {
    if (esErrObject.type) msg += '[' + esErrObject.type + '] ';
    if (esErrObject.reason) msg += esErrObject.reason;
  }

  ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.418"></a>[function <span class="apidocSignatureSpan">elasticsearch.</span>errors.418 (msg, metadata)](#apidoc.element.elasticsearch.errors.418)
- description and source-code
```javascript
function StatusCodeError(msg, metadata) {
  this.status = status;
  this.displayName = className;

  var esErrObject = null;
  if (_.isPlainObject(msg)) {
    esErrObject = msg;
    msg = null;
  }

  if (!esErrObject) {
    // errors from es now come in two forms, an error string < 2.0 and
    // an object >= 2.0
    // TODO: remove after dropping support for < 2.0
    ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
    return this;
  }

  msg = [].concat(esErrObject.root_cause || []).reduce(function (memo, cause) {
    if (memo) memo += ' (and) ';

    memo += '[' + cause.type + '] ' + cause.reason;

    var extraData = _.omit(cause, ['type', 'reason']);
    if (_.size(extraData)) {
      memo += ', with ' + prettyPrint(extraData);
    }

    return memo;
  }, '');

  if (!msg) {
    if (esErrObject.type) msg += '[' + esErrObject.type + '] ';
    if (esErrObject.reason) msg += esErrObject.reason;
  }

  ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.421"></a>[function <span class="apidocSignatureSpan">elasticsearch.</span>errors.421 (msg, metadata)](#apidoc.element.elasticsearch.errors.421)
- description and source-code
```javascript
function StatusCodeError(msg, metadata) {
  this.status = status;
  this.displayName = className;

  var esErrObject = null;
  if (_.isPlainObject(msg)) {
    esErrObject = msg;
    msg = null;
  }

  if (!esErrObject) {
    // errors from es now come in two forms, an error string < 2.0 and
    // an object >= 2.0
    // TODO: remove after dropping support for < 2.0
    ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
    return this;
  }

  msg = [].concat(esErrObject.root_cause || []).reduce(function (memo, cause) {
    if (memo) memo += ' (and) ';

    memo += '[' + cause.type + '] ' + cause.reason;

    var extraData = _.omit(cause, ['type', 'reason']);
    if (_.size(extraData)) {
      memo += ', with ' + prettyPrint(extraData);
    }

    return memo;
  }, '');

  if (!msg) {
    if (esErrObject.type) msg += '[' + esErrObject.type + '] ';
    if (esErrObject.reason) msg += esErrObject.reason;
  }

  ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.426"></a>[function <span class="apidocSignatureSpan">elasticsearch.</span>errors.426 (msg, metadata)](#apidoc.element.elasticsearch.errors.426)
- description and source-code
```javascript
function StatusCodeError(msg, metadata) {
  this.status = status;
  this.displayName = className;

  var esErrObject = null;
  if (_.isPlainObject(msg)) {
    esErrObject = msg;
    msg = null;
  }

  if (!esErrObject) {
    // errors from es now come in two forms, an error string < 2.0 and
    // an object >= 2.0
    // TODO: remove after dropping support for < 2.0
    ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
    return this;
  }

  msg = [].concat(esErrObject.root_cause || []).reduce(function (memo, cause) {
    if (memo) memo += ' (and) ';

    memo += '[' + cause.type + '] ' + cause.reason;

    var extraData = _.omit(cause, ['type', 'reason']);
    if (_.size(extraData)) {
      memo += ', with ' + prettyPrint(extraData);
    }

    return memo;
  }, '');

  if (!msg) {
    if (esErrObject.type) msg += '[' + esErrObject.type + '] ';
    if (esErrObject.reason) msg += esErrObject.reason;
  }

  ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.429"></a>[function <span class="apidocSignatureSpan">elasticsearch.</span>errors.429 (msg, metadata)](#apidoc.element.elasticsearch.errors.429)
- description and source-code
```javascript
function StatusCodeError(msg, metadata) {
  this.status = status;
  this.displayName = className;

  var esErrObject = null;
  if (_.isPlainObject(msg)) {
    esErrObject = msg;
    msg = null;
  }

  if (!esErrObject) {
    // errors from es now come in two forms, an error string < 2.0 and
    // an object >= 2.0
    // TODO: remove after dropping support for < 2.0
    ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
    return this;
  }

  msg = [].concat(esErrObject.root_cause || []).reduce(function (memo, cause) {
    if (memo) memo += ' (and) ';

    memo += '[' + cause.type + '] ' + cause.reason;

    var extraData = _.omit(cause, ['type', 'reason']);
    if (_.size(extraData)) {
      memo += ', with ' + prettyPrint(extraData);
    }

    return memo;
  }, '');

  if (!msg) {
    if (esErrObject.type) msg += '[' + esErrObject.type + '] ';
    if (esErrObject.reason) msg += esErrObject.reason;
  }

  ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.450"></a>[function <span class="apidocSignatureSpan">elasticsearch.</span>errors.450 (msg, metadata)](#apidoc.element.elasticsearch.errors.450)
- description and source-code
```javascript
function StatusCodeError(msg, metadata) {
  this.status = status;
  this.displayName = className;

  var esErrObject = null;
  if (_.isPlainObject(msg)) {
    esErrObject = msg;
    msg = null;
  }

  if (!esErrObject) {
    // errors from es now come in two forms, an error string < 2.0 and
    // an object >= 2.0
    // TODO: remove after dropping support for < 2.0
    ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
    return this;
  }

  msg = [].concat(esErrObject.root_cause || []).reduce(function (memo, cause) {
    if (memo) memo += ' (and) ';

    memo += '[' + cause.type + '] ' + cause.reason;

    var extraData = _.omit(cause, ['type', 'reason']);
    if (_.size(extraData)) {
      memo += ', with ' + prettyPrint(extraData);
    }

    return memo;
  }, '');

  if (!msg) {
    if (esErrObject.type) msg += '[' + esErrObject.type + '] ';
    if (esErrObject.reason) msg += esErrObject.reason;
  }

  ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.494"></a>[function <span class="apidocSignatureSpan">elasticsearch.</span>errors.494 (msg, metadata)](#apidoc.element.elasticsearch.errors.494)
- description and source-code
```javascript
function StatusCodeError(msg, metadata) {
  this.status = status;
  this.displayName = className;

  var esErrObject = null;
  if (_.isPlainObject(msg)) {
    esErrObject = msg;
    msg = null;
  }

  if (!esErrObject) {
    // errors from es now come in two forms, an error string < 2.0 and
    // an object >= 2.0
    // TODO: remove after dropping support for < 2.0
    ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
    return this;
  }

  msg = [].concat(esErrObject.root_cause || []).reduce(function (memo, cause) {
    if (memo) memo += ' (and) ';

    memo += '[' + cause.type + '] ' + cause.reason;

    var extraData = _.omit(cause, ['type', 'reason']);
    if (_.size(extraData)) {
      memo += ', with ' + prettyPrint(extraData);
    }

    return memo;
  }, '');

  if (!msg) {
    if (esErrObject.type) msg += '[' + esErrObject.type + '] ';
    if (esErrObject.reason) msg += esErrObject.reason;
  }

  ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.497"></a>[function <span class="apidocSignatureSpan">elasticsearch.</span>errors.497 (msg, metadata)](#apidoc.element.elasticsearch.errors.497)
- description and source-code
```javascript
function StatusCodeError(msg, metadata) {
  this.status = status;
  this.displayName = className;

  var esErrObject = null;
  if (_.isPlainObject(msg)) {
    esErrObject = msg;
    msg = null;
  }

  if (!esErrObject) {
    // errors from es now come in two forms, an error string < 2.0 and
    // an object >= 2.0
    // TODO: remove after dropping support for < 2.0
    ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
    return this;
  }

  msg = [].concat(esErrObject.root_cause || []).reduce(function (memo, cause) {
    if (memo) memo += ' (and) ';

    memo += '[' + cause.type + '] ' + cause.reason;

    var extraData = _.omit(cause, ['type', 'reason']);
    if (_.size(extraData)) {
      memo += ', with ' + prettyPrint(extraData);
    }

    return memo;
  }, '');

  if (!msg) {
    if (esErrObject.type) msg += '[' + esErrObject.type + '] ';
    if (esErrObject.reason) msg += esErrObject.reason;
  }

  ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.499"></a>[function <span class="apidocSignatureSpan">elasticsearch.</span>errors.499 (msg, metadata)](#apidoc.element.elasticsearch.errors.499)
- description and source-code
```javascript
function StatusCodeError(msg, metadata) {
  this.status = status;
  this.displayName = className;

  var esErrObject = null;
  if (_.isPlainObject(msg)) {
    esErrObject = msg;
    msg = null;
  }

  if (!esErrObject) {
    // errors from es now come in two forms, an error string < 2.0 and
    // an object >= 2.0
    // TODO: remove after dropping support for < 2.0
    ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
    return this;
  }

  msg = [].concat(esErrObject.root_cause || []).reduce(function (memo, cause) {
    if (memo) memo += ' (and) ';

    memo += '[' + cause.type + '] ' + cause.reason;

    var extraData = _.omit(cause, ['type', 'reason']);
    if (_.size(extraData)) {
      memo += ', with ' + prettyPrint(extraData);
    }

    return memo;
  }, '');

  if (!msg) {
    if (esErrObject.type) msg += '[' + esErrObject.type + '] ';
    if (esErrObject.reason) msg += esErrObject.reason;
  }

  ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.500"></a>[function <span class="apidocSignatureSpan">elasticsearch.</span>errors.500 (msg, metadata)](#apidoc.element.elasticsearch.errors.500)
- description and source-code
```javascript
function StatusCodeError(msg, metadata) {
  this.status = status;
  this.displayName = className;

  var esErrObject = null;
  if (_.isPlainObject(msg)) {
    esErrObject = msg;
    msg = null;
  }

  if (!esErrObject) {
    // errors from es now come in two forms, an error string < 2.0 and
    // an object >= 2.0
    // TODO: remove after dropping support for < 2.0
    ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
    return this;
  }

  msg = [].concat(esErrObject.root_cause || []).reduce(function (memo, cause) {
    if (memo) memo += ' (and) ';

    memo += '[' + cause.type + '] ' + cause.reason;

    var extraData = _.omit(cause, ['type', 'reason']);
    if (_.size(extraData)) {
      memo += ', with ' + prettyPrint(extraData);
    }

    return memo;
  }, '');

  if (!msg) {
    if (esErrObject.type) msg += '[' + esErrObject.type + '] ';
    if (esErrObject.reason) msg += esErrObject.reason;
  }

  ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.501"></a>[function <span class="apidocSignatureSpan">elasticsearch.</span>errors.501 (msg, metadata)](#apidoc.element.elasticsearch.errors.501)
- description and source-code
```javascript
function StatusCodeError(msg, metadata) {
  this.status = status;
  this.displayName = className;

  var esErrObject = null;
  if (_.isPlainObject(msg)) {
    esErrObject = msg;
    msg = null;
  }

  if (!esErrObject) {
    // errors from es now come in two forms, an error string < 2.0 and
    // an object >= 2.0
    // TODO: remove after dropping support for < 2.0
    ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
    return this;
  }

  msg = [].concat(esErrObject.root_cause || []).reduce(function (memo, cause) {
    if (memo) memo += ' (and) ';

    memo += '[' + cause.type + '] ' + cause.reason;

    var extraData = _.omit(cause, ['type', 'reason']);
    if (_.size(extraData)) {
      memo += ', with ' + prettyPrint(extraData);
    }

    return memo;
  }, '');

  if (!msg) {
    if (esErrObject.type) msg += '[' + esErrObject.type + '] ';
    if (esErrObject.reason) msg += esErrObject.reason;
  }

  ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.502"></a>[function <span class="apidocSignatureSpan">elasticsearch.</span>errors.502 (msg, metadata)](#apidoc.element.elasticsearch.errors.502)
- description and source-code
```javascript
function StatusCodeError(msg, metadata) {
  this.status = status;
  this.displayName = className;

  var esErrObject = null;
  if (_.isPlainObject(msg)) {
    esErrObject = msg;
    msg = null;
  }

  if (!esErrObject) {
    // errors from es now come in two forms, an error string < 2.0 and
    // an object >= 2.0
    // TODO: remove after dropping support for < 2.0
    ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
    return this;
  }

  msg = [].concat(esErrObject.root_cause || []).reduce(function (memo, cause) {
    if (memo) memo += ' (and) ';

    memo += '[' + cause.type + '] ' + cause.reason;

    var extraData = _.omit(cause, ['type', 'reason']);
    if (_.size(extraData)) {
      memo += ', with ' + prettyPrint(extraData);
    }

    return memo;
  }, '');

  if (!msg) {
    if (esErrObject.type) msg += '[' + esErrObject.type + '] ';
    if (esErrObject.reason) msg += esErrObject.reason;
  }

  ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.503"></a>[function <span class="apidocSignatureSpan">elasticsearch.</span>errors.503 (msg, metadata)](#apidoc.element.elasticsearch.errors.503)
- description and source-code
```javascript
function StatusCodeError(msg, metadata) {
  this.status = status;
  this.displayName = className;

  var esErrObject = null;
  if (_.isPlainObject(msg)) {
    esErrObject = msg;
    msg = null;
  }

  if (!esErrObject) {
    // errors from es now come in two forms, an error string < 2.0 and
    // an object >= 2.0
    // TODO: remove after dropping support for < 2.0
    ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
    return this;
  }

  msg = [].concat(esErrObject.root_cause || []).reduce(function (memo, cause) {
    if (memo) memo += ' (and) ';

    memo += '[' + cause.type + '] ' + cause.reason;

    var extraData = _.omit(cause, ['type', 'reason']);
    if (_.size(extraData)) {
      memo += ', with ' + prettyPrint(extraData);
    }

    return memo;
  }, '');

  if (!msg) {
    if (esErrObject.type) msg += '[' + esErrObject.type + '] ';
    if (esErrObject.reason) msg += esErrObject.reason;
  }

  ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.504"></a>[function <span class="apidocSignatureSpan">elasticsearch.</span>errors.504 (msg, metadata)](#apidoc.element.elasticsearch.errors.504)
- description and source-code
```javascript
function StatusCodeError(msg, metadata) {
  this.status = status;
  this.displayName = className;

  var esErrObject = null;
  if (_.isPlainObject(msg)) {
    esErrObject = msg;
    msg = null;
  }

  if (!esErrObject) {
    // errors from es now come in two forms, an error string < 2.0 and
    // an object >= 2.0
    // TODO: remove after dropping support for < 2.0
    ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
    return this;
  }

  msg = [].concat(esErrObject.root_cause || []).reduce(function (memo, cause) {
    if (memo) memo += ' (and) ';

    memo += '[' + cause.type + '] ' + cause.reason;

    var extraData = _.omit(cause, ['type', 'reason']);
    if (_.size(extraData)) {
      memo += ', with ' + prettyPrint(extraData);
    }

    return memo;
  }, '');

  if (!msg) {
    if (esErrObject.type) msg += '[' + esErrObject.type + '] ';
    if (esErrObject.reason) msg += esErrObject.reason;
  }

  ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.505"></a>[function <span class="apidocSignatureSpan">elasticsearch.</span>errors.505 (msg, metadata)](#apidoc.element.elasticsearch.errors.505)
- description and source-code
```javascript
function StatusCodeError(msg, metadata) {
  this.status = status;
  this.displayName = className;

  var esErrObject = null;
  if (_.isPlainObject(msg)) {
    esErrObject = msg;
    msg = null;
  }

  if (!esErrObject) {
    // errors from es now come in two forms, an error string < 2.0 and
    // an object >= 2.0
    // TODO: remove after dropping support for < 2.0
    ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
    return this;
  }

  msg = [].concat(esErrObject.root_cause || []).reduce(function (memo, cause) {
    if (memo) memo += ' (and) ';

    memo += '[' + cause.type + '] ' + cause.reason;

    var extraData = _.omit(cause, ['type', 'reason']);
    if (_.size(extraData)) {
      memo += ', with ' + prettyPrint(extraData);
    }

    return memo;
  }, '');

  if (!msg) {
    if (esErrObject.type) msg += '[' + esErrObject.type + '] ';
    if (esErrObject.reason) msg += esErrObject.reason;
  }

  ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.506"></a>[function <span class="apidocSignatureSpan">elasticsearch.</span>errors.506 (msg, metadata)](#apidoc.element.elasticsearch.errors.506)
- description and source-code
```javascript
function StatusCodeError(msg, metadata) {
  this.status = status;
  this.displayName = className;

  var esErrObject = null;
  if (_.isPlainObject(msg)) {
    esErrObject = msg;
    msg = null;
  }

  if (!esErrObject) {
    // errors from es now come in two forms, an error string < 2.0 and
    // an object >= 2.0
    // TODO: remove after dropping support for < 2.0
    ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
    return this;
  }

  msg = [].concat(esErrObject.root_cause || []).reduce(function (memo, cause) {
    if (memo) memo += ' (and) ';

    memo += '[' + cause.type + '] ' + cause.reason;

    var extraData = _.omit(cause, ['type', 'reason']);
    if (_.size(extraData)) {
      memo += ', with ' + prettyPrint(extraData);
    }

    return memo;
  }, '');

  if (!msg) {
    if (esErrObject.type) msg += '[' + esErrObject.type + '] ';
    if (esErrObject.reason) msg += esErrObject.reason;
  }

  ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.510"></a>[function <span class="apidocSignatureSpan">elasticsearch.</span>errors.510 (msg, metadata)](#apidoc.element.elasticsearch.errors.510)
- description and source-code
```javascript
function StatusCodeError(msg, metadata) {
  this.status = status;
  this.displayName = className;

  var esErrObject = null;
  if (_.isPlainObject(msg)) {
    esErrObject = msg;
    msg = null;
  }

  if (!esErrObject) {
    // errors from es now come in two forms, an error string < 2.0 and
    // an object >= 2.0
    // TODO: remove after dropping support for < 2.0
    ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
    return this;
  }

  msg = [].concat(esErrObject.root_cause || []).reduce(function (memo, cause) {
    if (memo) memo += ' (and) ';

    memo += '[' + cause.type + '] ' + cause.reason;

    var extraData = _.omit(cause, ['type', 'reason']);
    if (_.size(extraData)) {
      memo += ', with ' + prettyPrint(extraData);
    }

    return memo;
  }, '');

  if (!msg) {
    if (esErrObject.type) msg += '[' + esErrObject.type + '] ';
    if (esErrObject.reason) msg += esErrObject.reason;
  }

  ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.ConnectionFault"></a>[function <span class="apidocSignatureSpan">elasticsearch.</span>errors.ConnectionFault (msg)](#apidoc.element.elasticsearch.errors.ConnectionFault)
- description and source-code
```javascript
function ConnectionFault(msg) {
  ErrorAbstract.call(this, msg || 'Connection Failure', errors.ConnectionFault);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.Generic"></a>[function <span class="apidocSignatureSpan">elasticsearch.</span>errors.Generic (msg, metadata)](#apidoc.element.elasticsearch.errors.Generic)
- description and source-code
```javascript
function Generic(msg, metadata) {
  ErrorAbstract.call(this, msg || 'Generic Error', errors.Generic, metadata);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.NoConnections"></a>[function <span class="apidocSignatureSpan">elasticsearch.</span>errors.NoConnections (msg)](#apidoc.element.elasticsearch.errors.NoConnections)
- description and source-code
```javascript
function NoConnections(msg) {
  ErrorAbstract.call(this, msg || 'No Living connections', errors.NoConnections);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.RequestTypeError"></a>[function <span class="apidocSignatureSpan">elasticsearch.</span>errors.RequestTypeError (feature)](#apidoc.element.elasticsearch.errors.RequestTypeError)
- description and source-code
```javascript
function RequestTypeError(feature) {
  ErrorAbstract.call(this, 'Cross-domain AJAX requests ' + feature + ' are not supported', errors.RequestTypeError);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.Serialization"></a>[function <span class="apidocSignatureSpan">elasticsearch.</span>errors.Serialization (msg)](#apidoc.element.elasticsearch.errors.Serialization)
- description and source-code
```javascript
function Serialization(msg) {
  ErrorAbstract.call(this, msg || 'Unable to parse/serialize body', errors.Serialization);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors._Abstract"></a>[function <span class="apidocSignatureSpan">elasticsearch.</span>errors._Abstract (msg, constructor, metadata)](#apidoc.element.elasticsearch.errors._Abstract)
- description and source-code
```javascript
function ErrorAbstract(msg, constructor, metadata) {
  this.message = msg;

  Error.call(this, this.message);

  if (canCapture) {
    Error.captureStackTrace(this, constructor);
  }
  else if (canStack) {
    this.stack = (new Error()).stack;
  }
  else {
    this.stack = '';
  }

  if (metadata) {
    _.assign(this, metadata);

    this.toString = function () {
      return msg + ' :: ' + JSON.stringify(metadata);
    };

    this.toJSON = function () {
      return _.assign({
        msg: msg
      }, metadata);
    };
  }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.elasticsearch.ConnectionPool"></a>[module elasticsearch.ConnectionPool](#apidoc.module.elasticsearch.ConnectionPool)

#### <a name="apidoc.element.elasticsearch.ConnectionPool.ConnectionPool"></a>[function <span class="apidocSignatureSpan">elasticsearch.</span>ConnectionPool (config)](#apidoc.element.elasticsearch.ConnectionPool.ConnectionPool)
- description and source-code
```javascript
function ConnectionPool(config) {
  config = config || {};
  _.makeBoundMethods(this);

  if (!config.log) {
    this.log = new Log();
    config.log = this.log;
  } else {
    this.log = config.log;
  }

  // we will need this when we create connections down the road
  this._config = config;

  // get the selector config var
  this.selector = _.funcEnum(config, 'selector', ConnectionPool.selectors, ConnectionPool.defaultSelector);

  // get the connection class
  this.Connection = _.funcEnum(config, 'connectionClass', ConnectionPool.connectionClasses,
    ConnectionPool.defaultConnectionClass);

  // time that connections will wait before being revived
  this.deadTimeout = config.hasOwnProperty('deadTimeout') ? config.deadTimeout : 60000;
  this.maxDeadTimeout = config.hasOwnProperty('maxDeadTimeout') ? config.maxDeadTimeout : 18e5;
  this.calcDeadTimeout = _.funcEnum(config, 'calcDeadTimeout', ConnectionPool.calcDeadTimeoutOptions, 'exponential');

  // a map of connections to their "id" property, used when sniffing
  this.index = {};

  this._conns = {
    alive: [],
    dead: []
  };

  // information about timeouts for dead connections
  this._timeouts = [];
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.elasticsearch.ConnectionPool.calcDeadTimeoutOptions"></a>[module elasticsearch.ConnectionPool.calcDeadTimeoutOptions](#apidoc.module.elasticsearch.ConnectionPool.calcDeadTimeoutOptions)

#### <a name="apidoc.element.elasticsearch.ConnectionPool.calcDeadTimeoutOptions.exponential"></a>[function <span class="apidocSignatureSpan">elasticsearch.ConnectionPool.calcDeadTimeoutOptions.</span>exponential (attempt, baseTimeout)](#apidoc.element.elasticsearch.ConnectionPool.calcDeadTimeoutOptions.exponential)
- description and source-code
```javascript
exponential = function (attempt, baseTimeout) {
  return Math.min(baseTimeout * 2 * Math.pow(2, (attempt * 0.5 - 1)), this.maxDeadTimeout);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.ConnectionPool.calcDeadTimeoutOptions.flat"></a>[function <span class="apidocSignatureSpan">elasticsearch.ConnectionPool.calcDeadTimeoutOptions.</span>flat (attempt, baseTimeout)](#apidoc.element.elasticsearch.ConnectionPool.calcDeadTimeoutOptions.flat)
- description and source-code
```javascript
flat = function (attempt, baseTimeout) {
  return baseTimeout;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.elasticsearch.ConnectionPool.connectionClasses"></a>[module elasticsearch.ConnectionPool.connectionClasses](#apidoc.module.elasticsearch.ConnectionPool.connectionClasses)

#### <a name="apidoc.element.elasticsearch.ConnectionPool.connectionClasses.http"></a>[function <span class="apidocSignatureSpan">elasticsearch.ConnectionPool.connectionClasses.</span>http (host, config)](#apidoc.element.elasticsearch.ConnectionPool.connectionClasses.http)
- description and source-code
```javascript
function HttpConnector(host, config) {
  ConnectionAbstract.call(this, host, config);

  this.hand = handles[this.host.protocol];
  if (!this.hand) {
    throw new TypeError('Invalid protocol "' + this.host.protocol +
      '", expected one of ' + _.keys(handles).join(', '));
  }

  this.useSsl = this.host.protocol === 'https';

  config = _.defaults(config || {}, {
    keepAlive: true,
    minSockets: 10,
    // 10 makes sense but 11 actually keeps 10 sockets around
    // https://github.com/mikeal/forever-agent/issues/8
    maxSockets: 11
  });

  this.agent = config.createNodeAgent ? config.createNodeAgent(this, config) : this.createAgent(config);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.elasticsearch.ConnectionPool.connectionClasses.http.prototype"></a>[module elasticsearch.ConnectionPool.connectionClasses.http.prototype](#apidoc.module.elasticsearch.ConnectionPool.connectionClasses.http.prototype)

#### <a name="apidoc.element.elasticsearch.ConnectionPool.connectionClasses.http.prototype.createAgent"></a>[function <span class="apidocSignatureSpan">elasticsearch.ConnectionPool.connectionClasses.http.prototype.</span>createAgent (config)](#apidoc.element.elasticsearch.ConnectionPool.connectionClasses.http.prototype.createAgent)
- description and source-code
```javascript
createAgent = function (config) {
  var Agent = this.hand.Agent; // the class

  if (config.forever) {
    config.keepAlive = config.forever;
  }

  if (config.keepAlive) {
    Agent = this.useSsl ? KeepAliveAgent.SSL : KeepAliveAgent;
    this.on('status set', this.bound.onStatusSet);
  }

  return new Agent(this.makeAgentConfig(config));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.ConnectionPool.connectionClasses.http.prototype.makeAgentConfig"></a>[function <span class="apidocSignatureSpan">elasticsearch.ConnectionPool.connectionClasses.http.prototype.</span>makeAgentConfig (config)](#apidoc.element.elasticsearch.ConnectionPool.connectionClasses.http.prototype.makeAgentConfig)
- description and source-code
```javascript
makeAgentConfig = function (config) {
  var agentConfig = {
<span class="apidocCodeCommentSpan">    /*
     * As HTTP/HTTPS Agent defaults keepAlive to false, in the case where we
     * desire HTTP keep-alive, we need to set it appropriately. This could be
     * done in the wrapper, but I don't see any good reason not to simply set
     * it here. ¯\_(ツ)_/¯
     *
     * https://github.com/elastic/elasticsearch-js/issues/107
     */
</span>    keepAlive: config.keepAlive,
    maxSockets: config.maxSockets,
    minSockets: config.minSockets
  };

  if (this.useSsl) {
    _.merge(agentConfig, this.host.ssl);
  }

  return agentConfig;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.ConnectionPool.connectionClasses.http.prototype.makeReqParams"></a>[function <span class="apidocSignatureSpan">elasticsearch.ConnectionPool.connectionClasses.http.prototype.</span>makeReqParams (params)](#apidoc.element.elasticsearch.ConnectionPool.connectionClasses.http.prototype.makeReqParams)
- description and source-code
```javascript
makeReqParams = function (params) {
  params = params || {};
  var host = this.host;

  var reqParams = {
    method: params.method || 'GET',
    protocol: host.protocol + ':',
    hostname: host.host,
    port: host.port,
    path: (host.path || '') + (params.path || ''),
    headers: host.getHeaders(params.headers),
    agent: this.agent
  };

  if (!reqParams.path) {
    reqParams.path = '/';
  }

  var query = host.getQuery(params.query);
  if (query) {
    reqParams.path = reqParams.path + '?' + qs.stringify(query);
  }

  return reqParams;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.ConnectionPool.connectionClasses.http.prototype.onStatusSet"></a>[function <span class="apidocSignatureSpan">elasticsearch.ConnectionPool.connectionClasses.http.prototype.</span>onStatusSet (status)](#apidoc.element.elasticsearch.ConnectionPool.connectionClasses.http.prototype.onStatusSet)
- description and source-code
```javascript
onStatusSet = function (status) {
  if (status === 'closed') {
    var agent = this.agent;
    var toRemove = [];
    var collectSockets = function (sockets, host) {
      _.each(sockets, function (s) {
        if (s) toRemove.push([host, s]);
      });
    };

    agent.minSockets = agent.maxSockets = 0;
    agent.requests = {};

    _.each(agent.sockets, collectSockets);
    _.each(agent.freeSockets, collectSockets);
    _.each(toRemove, function (args) {
      var host = args[0], socket = args[1];
      agent.removeSocket(socket, host);
      socket.destroy();
    });
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.ConnectionPool.connectionClasses.http.prototype.request"></a>[function <span class="apidocSignatureSpan">elasticsearch.ConnectionPool.connectionClasses.http.prototype.</span>request (params, cb)](#apidoc.element.elasticsearch.ConnectionPool.connectionClasses.http.prototype.request)
- description and source-code
```javascript
request = function (params, cb) {
  var incoming;
  var timeoutId;
  var request;
  var status = 0;
  var headers = {};
  var log = this.log;
  var response;

  var reqParams = this.makeReqParams(params);

  // general clean-up procedure to run after the request
  // completes, has an error, or is aborted.
  var cleanUp = _.bind(function (err) {
    clearTimeout(timeoutId);

    request && request.removeAllListeners();
    incoming && incoming.removeAllListeners();

    if ((err instanceof Error) === false) {
      err = void 0;
    }

    log.trace(params.method, reqParams, params.body, response, status);
    if (err) {
      cb(err);
    } else {
      cb(err, response, status, headers);
    }
  }, this);

  request = this.hand.request(reqParams, function (_incoming) {
    incoming = _incoming;
    status = incoming.statusCode;
    headers = incoming.headers;
    response = '';

    var encoding = (headers['content-encoding'] || '').toLowerCase();
    if (encoding === 'gzip' || encoding === 'deflate') {
      incoming = incoming.pipe(zlib.createUnzip());
    }

    incoming.setEncoding('utf8');
    incoming.on('data', function (d) {
      response += d;
    });

    incoming.on('error', cleanUp);
    incoming.on('end', cleanUp);
  });

  request.on('error', cleanUp);

  request.setNoDelay(true);
  request.setSocketKeepAlive(true);

  if (params.body) {
    request.setHeader('Content-Length', Buffer.byteLength(params.body, 'utf8'));
    request.end(params.body);
  } else {
    request.setHeader('Content-Length', 0);
    request.end();
  }

  return function () {
    request.abort();
  };
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.elasticsearch.ConnectionPool.prototype"></a>[module elasticsearch.ConnectionPool.prototype](#apidoc.module.elasticsearch.ConnectionPool.prototype)

#### <a name="apidoc.element.elasticsearch.ConnectionPool.prototype._onConnectionDied"></a>[function <span class="apidocSignatureSpan">elasticsearch.ConnectionPool.prototype.</span>_onConnectionDied (connection, alreadyWasDead)](#apidoc.element.elasticsearch.ConnectionPool.prototype._onConnectionDied)
- description and source-code
```javascript
_onConnectionDied = function (connection, alreadyWasDead) {
  var timeout;
  if (alreadyWasDead) {
    for (var i = 0; i < this._timeouts.length; i++) {
      if (this._timeouts[i].conn === connection) {
        timeout = this._timeouts[i];
        break;
      }
    }
  } else {
    timeout = {
      conn: connection,
      attempt: 0,
      revive: function (cb) {
        timeout.attempt++;
        connection.ping(function (err) {
          connection.setStatus(err ? 'dead' : 'alive');
          if (cb && typeof cb === 'function') {
            cb(err);
          }
        });
      }
    };
    this._timeouts.push(timeout);
  }

  if (timeout.id) {
    clearTimeout(timeout.id);
  }

  var ms = this.calcDeadTimeout(timeout.attempt, this.deadTimeout);
  timeout.id = setTimeout(timeout.revive, ms);
  timeout.runAt = _.now() + ms;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.ConnectionPool.prototype._onConnectionRevived"></a>[function <span class="apidocSignatureSpan">elasticsearch.ConnectionPool.prototype.</span>_onConnectionRevived (connection)](#apidoc.element.elasticsearch.ConnectionPool.prototype._onConnectionRevived)
- description and source-code
```javascript
_onConnectionRevived = function (connection) {
  var timeout;
  for (var i = 0; i < this._timeouts.length; i++) {
    if (this._timeouts[i].conn === connection) {
      timeout = this._timeouts[i];
      if (timeout.id) {
        clearTimeout(timeout.id);
      }
      this._timeouts.splice(i, 1);
      break;
    }
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.ConnectionPool.prototype._selectDeadConnection"></a>[function <span class="apidocSignatureSpan">elasticsearch.ConnectionPool.prototype.</span>_selectDeadConnection (cb)](#apidoc.element.elasticsearch.ConnectionPool.prototype._selectDeadConnection)
- description and source-code
```javascript
_selectDeadConnection = function (cb) {
  var orderedTimeouts = _.sortBy(this._timeouts, 'runAt');
  var log = this.log;

  process.nextTick(function next() {
    var timeout = orderedTimeouts.shift();
    if (!timeout) {
      cb(void 0);
      return;
    }

    if (!timeout.conn) {
      next();
      return;
    }

    if (timeout.conn.status === 'dead') {
      timeout.revive(function (err) {
        if (err) {
          log.warning('Unable to revive connection: ' + timeout.conn.id);
          process.nextTick(next);
        } else {
          cb(void 0, timeout.conn);
        }
      });
    } else {
      cb(void 0, timeout.conn);
    }
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.ConnectionPool.prototype.addConnection"></a>[function <span class="apidocSignatureSpan">elasticsearch.ConnectionPool.prototype.</span>addConnection (connection)](#apidoc.element.elasticsearch.ConnectionPool.prototype.addConnection)
- description and source-code
```javascript
addConnection = function (connection) {
  if (!connection.id) {
    connection.id = connection.host.toString();
  }

  if (!this.index[connection.id]) {
    this.log.info('Adding connection to', connection.id);
    this.index[connection.id] = connection;
    connection.on('status set', this.bound.onStatusSet);
    connection.setStatus('alive');
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.ConnectionPool.prototype.close"></a>[function <span class="apidocSignatureSpan">elasticsearch.ConnectionPool.prototype.</span>close ()](#apidoc.element.elasticsearch.ConnectionPool.prototype.close)
- description and source-code
```javascript
close = function () {
  this.setHosts([]);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.ConnectionPool.prototype.empty"></a>[function <span class="apidocSignatureSpan">elasticsearch.ConnectionPool.prototype.</span>empty ()](#apidoc.element.elasticsearch.ConnectionPool.prototype.empty)
- description and source-code
```javascript
empty = function () {
  this.setHosts([]);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.ConnectionPool.prototype.getAllHosts"></a>[function <span class="apidocSignatureSpan">elasticsearch.ConnectionPool.prototype.</span>getAllHosts ()](#apidoc.element.elasticsearch.ConnectionPool.prototype.getAllHosts)
- description and source-code
```javascript
getAllHosts = function () {
  return _.values(this.index).map(function (connection) {
    return connection.host;
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.ConnectionPool.prototype.getConnections"></a>[function <span class="apidocSignatureSpan">elasticsearch.ConnectionPool.prototype.</span>getConnections (status, limit)](#apidoc.element.elasticsearch.ConnectionPool.prototype.getConnections)
- description and source-code
```javascript
getConnections = function (status, limit) {
  var list;
  if (status) {
    list = this._conns[status];
  } else {
    list = this._conns[this._conns.alive.length ? 'alive' : 'dead'];
  }

  if (limit == null) {
    return list.slice(0);
  } else {
    return _.shuffle(list).slice(0, limit);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.ConnectionPool.prototype.onStatusSet"></a>[function <span class="apidocSignatureSpan">elasticsearch.ConnectionPool.prototype.</span>onStatusSet (status, oldStatus, connection)](#apidoc.element.elasticsearch.ConnectionPool.prototype.onStatusSet)
- description and source-code
```javascript
onStatusSet = function (status, oldStatus, connection) {
  var index;

  var died = (status === 'dead');
  var wasAlreadyDead = (died && oldStatus === 'dead');
  var revived = (!died && oldStatus === 'dead');
  var noChange = (oldStatus === status);
  var from = this._conns[oldStatus];
  var to = this._conns[status];

  if (noChange && !died) {
    return true;
  }

  if (from !== to) {
    if (_.isArray(from)) {
      index = from.indexOf(connection);
      if (index !== -1) {
        from.splice(index, 1);
      }
    }

    if (_.isArray(to)) {
      index = to.indexOf(connection);
      if (index === -1) {
        to.push(connection);
      }
    }
  }

  if (died) {
    this._onConnectionDied(connection, wasAlreadyDead);
  }

  if (revived) {
    this._onConnectionRevived(connection);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.ConnectionPool.prototype.removeConnection"></a>[function <span class="apidocSignatureSpan">elasticsearch.ConnectionPool.prototype.</span>removeConnection (connection)](#apidoc.element.elasticsearch.ConnectionPool.prototype.removeConnection)
- description and source-code
```javascript
removeConnection = function (connection) {
  if (!connection.id) {
    connection.id = connection.host.toString();
  }

  if (this.index[connection.id]) {
    delete this.index[connection.id];
    connection.setStatus('closed');
    connection.removeListener('status set', this.bound.onStatusSet);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.ConnectionPool.prototype.select"></a>[function <span class="apidocSignatureSpan">elasticsearch.ConnectionPool.prototype.</span>select (cb)](#apidoc.element.elasticsearch.ConnectionPool.prototype.select)
- description and source-code
```javascript
select = function (cb) {
  if (this._conns.alive.length) {
    if (this.selector.length > 1) {
      this.selector(this._conns.alive, cb);
    } else {
      try {
        _.nextTick(cb, void 0, this.selector(this._conns.alive));
      } catch (e) {
        cb(e);
      }
    }
  } else if (this._timeouts.length) {
    this._selectDeadConnection(cb);
  } else {
    _.nextTick(cb, void 0);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.ConnectionPool.prototype.setHosts"></a>[function <span class="apidocSignatureSpan">elasticsearch.ConnectionPool.prototype.</span>setHosts (hosts)](#apidoc.element.elasticsearch.ConnectionPool.prototype.setHosts)
- description and source-code
```javascript
setHosts = function (hosts) {
  var connection;
  var i;
  var id;
  var host;
  var toRemove = _.clone(this.index);

  for (i = 0; i < hosts.length; i++) {
    host = hosts[i];
    id = host.toString();
    if (this.index[id]) {
      delete toRemove[id];
    } else {
      connection = new this.Connection(host, this._config);
      connection.id = id;
      this.addConnection(connection);
    }
  }

  var removeIds = _.keys(toRemove);
  for (i = 0; i < removeIds.length; i++) {
    this.removeConnection(this.index[removeIds[i]]);
  }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.elasticsearch.ConnectionPool.selectors"></a>[module elasticsearch.ConnectionPool.selectors](#apidoc.module.elasticsearch.ConnectionPool.selectors)

#### <a name="apidoc.element.elasticsearch.ConnectionPool.selectors.random"></a>[function <span class="apidocSignatureSpan">elasticsearch.ConnectionPool.selectors.</span>random (connections)](#apidoc.element.elasticsearch.ConnectionPool.selectors.random)
- description and source-code
```javascript
function RandomSelector(connections) {
  return connections[Math.floor(Math.random() * connections.length)];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.ConnectionPool.selectors.roundRobin"></a>[function <span class="apidocSignatureSpan">elasticsearch.ConnectionPool.selectors.</span>roundRobin (connections)](#apidoc.element.elasticsearch.ConnectionPool.selectors.roundRobin)
- description and source-code
```javascript
roundRobin = function (connections) {
  var connection = connections[0];
  connections.push(connections.shift());
  return connection;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.elasticsearch.Transport"></a>[module elasticsearch.Transport](#apidoc.module.elasticsearch.Transport)

#### <a name="apidoc.element.elasticsearch.Transport.Transport"></a>[function <span class="apidocSignatureSpan">elasticsearch.</span>Transport (config)](#apidoc.element.elasticsearch.Transport.Transport)
- description and source-code
```javascript
function Transport(config) {
  var self = this;
  config = self._config = config || {};

  var LogClass = (typeof config.log === 'function') ? config.log : require('./log');
  config.log = self.log = new LogClass(config);

  // setup the connection pool
  var ConnectionPool = _.funcEnum(config, 'connectionPool', Transport.connectionPools, 'main');
  self.connectionPool = new ConnectionPool(config);

  // setup the serializer
  var Serializer = _.funcEnum(config, 'serializer', Transport.serializers, 'json');
  self.serializer = new Serializer(config);

  // setup the nodesToHostCallback
  self.nodesToHostCallback = _.funcEnum(config, 'nodesToHostCallback', Transport.nodesToHostCallbacks, 'main');

  // setup max retries
  self.maxRetries = config.hasOwnProperty('maxRetries') ? config.maxRetries : 3;

  // setup endpoint to use for sniffing
  self.sniffEndpoint = config.hasOwnProperty('sniffEndpoint') ? config.sniffEndpoint : '/_nodes/_all/clear';

  // setup requestTimeout default
  self.requestTimeout = config.hasOwnProperty('requestTimeout') ? config.requestTimeout : 30000;

  if (config.hasOwnProperty('defer')) {
    self.defer = config.defer;
  }

  // randomizeHosts option
  var randomizeHosts = config.hasOwnProperty('randomizeHosts') ? !!config.randomizeHosts : true;

  if (config.host) {
    config.hosts = config.host;
  }

  if (config.hosts) {
    var hostsConfig = _.createArray(config.hosts, function (val) {
      if (_.isPlainObject(val) || _.isString(val) || val instanceof Host) {
        return val;
      }
    });

    if (!hostsConfig) {
      throw new TypeError('Invalid hosts config. Expected a URL, an array of urls, a host config object, ' +
        'or an array of host config objects.');
    }

    if (randomizeHosts) {
      hostsConfig = _.shuffle(hostsConfig);
    }

    self.setHosts(hostsConfig);
  }

  if (config.hasOwnProperty('sniffedNodesProtocol')) {
    self.sniffedNodesProtocol = config.sniffedNodesProtocol || null;
  } else {
    self.sniffedNodesProtocol = findCommonProtocol(self.connectionPool.getAllHosts()) || null;
  }

  if (config.sniffOnStart) {
    self.sniff();
  }

  if (config.sniffInterval) {
    self._timeout(function doSniff() {
      self.sniff();
      self._timeout(doSniff, config.sniffInterval);
    }, config.sniffInterval);
  }

  if (config.sniffOnConnectionFault) {
    patchSniffOnConnectionFault(self);
  }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.elasticsearch.Transport.connectionPools"></a>[module elasticsearch.Transport.connectionPools](#apidoc.module.elasticsearch.Transport.connectionPools)

#### <a name="apidoc.element.elasticsearch.Transport.connectionPools.main"></a>[function <span class="apidocSignatureSpan">elasticsearch.Transport.connectionPools.</span>main (config)](#apidoc.element.elasticsearch.Transport.connectionPools.main)
- description and source-code
```javascript
function ConnectionPool(config) {
  config = config || {};
  _.makeBoundMethods(this);

  if (!config.log) {
    this.log = new Log();
    config.log = this.log;
  } else {
    this.log = config.log;
  }

  // we will need this when we create connections down the road
  this._config = config;

  // get the selector config var
  this.selector = _.funcEnum(config, 'selector', ConnectionPool.selectors, ConnectionPool.defaultSelector);

  // get the connection class
  this.Connection = _.funcEnum(config, 'connectionClass', ConnectionPool.connectionClasses,
    ConnectionPool.defaultConnectionClass);

  // time that connections will wait before being revived
  this.deadTimeout = config.hasOwnProperty('deadTimeout') ? config.deadTimeout : 60000;
  this.maxDeadTimeout = config.hasOwnProperty('maxDeadTimeout') ? config.maxDeadTimeout : 18e5;
  this.calcDeadTimeout = _.funcEnum(config, 'calcDeadTimeout', ConnectionPool.calcDeadTimeoutOptions, 'exponential');

  // a map of connections to their "id" property, used when sniffing
  this.index = {};

  this._conns = {
    alive: [],
    dead: []
  };

  // information about timeouts for dead connections
  this._timeouts = [];
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.elasticsearch.Transport.nodesToHostCallbacks"></a>[module elasticsearch.Transport.nodesToHostCallbacks](#apidoc.module.elasticsearch.Transport.nodesToHostCallbacks)

#### <a name="apidoc.element.elasticsearch.Transport.nodesToHostCallbacks.main"></a>[function <span class="apidocSignatureSpan">elasticsearch.Transport.nodesToHostCallbacks.</span>main (nodes)](#apidoc.element.elasticsearch.Transport.nodesToHostCallbacks.main)
- description and source-code
```javascript
main = function (nodes) {
  return _.transform(nodes, function (hosts, node, id) {
    var address = node[hostProp]
    if (!address) return;

    var host = {
      host: undefined,
      port: undefined,
      _meta: {
        id: id,
        name: node.name,
        hostname: node.hostname,
        version: node.version
      }
    };

    var malformedError = new Error(
      'Malformed ' + hostProp + '.' +
      ' Got ' + JSON.stringify(node[hostProp]) +
      ' and expected it to match "{hostname?}/{ip}:{port}".'
    );

    var matches1x = extractHostPartsRE1x.exec(address);
    if (matches1x) {
      host.host = matches1x[1];
      host.port = parseInt(matches1x[2], 10);
      hosts.push(host);
      return;
    }

    if (address.indexOf('/') > -1) {
      var withHostParts = address.split('/');
      if (withHostParts.length !== 2) throw malformedError;

      host.host = withHostParts.shift();
      address = withHostParts.shift();
    }

    if (address.indexOf(':') < 0) {
      throw malformedError;
    }

    var addressParts = address.split(':');
    if (addressParts.length !== 2) {
      throw malformedError;
    }

    host.host = host.host || addressParts[0];
    host.port = parseInt(addressParts[1], 10);
    hosts.push(host);
  }, []);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.elasticsearch.Transport.prototype"></a>[module elasticsearch.Transport.prototype](#apidoc.module.elasticsearch.Transport.prototype)

#### <a name="apidoc.element.elasticsearch.Transport.prototype._timeout"></a>[function <span class="apidocSignatureSpan">elasticsearch.Transport.prototype.</span>_timeout (cb, delay)](#apidoc.element.elasticsearch.Transport.prototype._timeout)
- description and source-code
```javascript
_timeout = function (cb, delay) {
  if (this.closed) return;

  var id;
  var timers = this._timers || (this._timers = []);

  if ('function' !== typeof cb) {
    id = cb;
    cb = void 0;
  }

  if (cb) {
    // set the timer
    id = setTimeout(function () {
      _.pull(timers, id);
      cb();
    }, delay);

    timers.push(id);
    return id;
  }

  if (id) {
    clearTimeout(id);

    var i = this._timers.indexOf(id);
    if (i !== -1) {
      this._timers.splice(i, 1);
    }
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.Transport.prototype.close"></a>[function <span class="apidocSignatureSpan">elasticsearch.Transport.prototype.</span>close ()](#apidoc.element.elasticsearch.Transport.prototype.close)
- description and source-code
```javascript
close = function () {
  this.log.close();
  this.closed = true;
  _.each(this._timers, clearTimeout);
  this._timers = null;
  this.connectionPool.close();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.Transport.prototype.defer"></a>[function <span class="apidocSignatureSpan">elasticsearch.Transport.prototype.</span>defer ()](#apidoc.element.elasticsearch.Transport.prototype.defer)
- description and source-code
```javascript
defer = function () {
  var defer = {};
  defer.promise = new Promise(function (resolve, reject) {
    defer.resolve = resolve;
    defer.reject = reject;
  });
  return defer;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.Transport.prototype.request"></a>[function <span class="apidocSignatureSpan">elasticsearch.Transport.prototype.</span>request (params, cb)](#apidoc.element.elasticsearch.Transport.prototype.request)
- description and source-code
```javascript
request = function (params, cb) {
  var self = this;
  var remainingRetries = this.maxRetries;
  var requestTimeout = this.requestTimeout;

  var connection; // set in sendReqWithConnection
  var aborted = false; // several connector will respond with an error when the request is aborted
  var requestAborter; // an abort function, returned by connection#request()
  var requestTimeoutId; // the id of the ^timeout
  var ret; // the object returned to the user, might be a promise
  var defer; // the defer object, will be set when we are using promises.

  var body = params.body;
  var headers = !params.headers ? {} : _.transform(params.headers, function (headers, val, name) {
    headers[String(name).toLowerCase()] = val;
  });

  self.log.debug('starting request', params);

  // determine the response based on the presense of a callback
  if (typeof cb === 'function') {
    // handle callbacks within a domain
    if (process.domain) {
      cb = process.domain.bind(cb);
    }
    ret = {
      abort: abortRequest
    };
  } else {
    defer = this.defer();
    ret = defer.promise;
    ret.abort = abortRequest;
  }

  if (body && params.method === 'GET') {
    _.nextTick(respond, new TypeError('Body can not be sent with method "GET"'));
    return ret;
  }

  // serialize the body
  if (body) {
    var serializer = self.serializer;
    var serializeFn = serializer[params.bulkBody ? 'bulkBody' : 'serialize'];

    body = serializeFn.call(serializer, body);
    if (!headers['content-type']) {
      headers['content-type'] = serializeFn.contentType;
    }
  }

  if (params.hasOwnProperty('maxRetries')) {
    remainingRetries = params.maxRetries;
  }

  if (params.hasOwnProperty('requestTimeout')) {
    requestTimeout = params.requestTimeout;
  }

  params.req = {
    method: params.method,
    path: params.path || '/',
    query: params.query,
    body: body,
    headers: headers
  };

  function sendReqWithConnection(err, _connection) {
    if (aborted) {
      return;
    }

    if (err) {
      respond(err);
    } else if (_connection) {
      connection = _connection;
      requestAborter = connection.request(params.req, checkRespForFailure);
    } else {
      self.log.warning('No living connections');
      respond(new errors.NoConnections());
    }
  }

  function checkRespForFailure(err, body, status, headers) {
    if (aborted) {
      return;
    }

    requestAborter = void 0;

    if (err instanceof errors.RequestTypeError) {
      self.log.error('Connection refused to execute the request', err);
      respond(err, body, status, headers);
      return;
    }

    if (err) {
      connection.setStatus('dead');

      var errMsg = err.message || '';

      errMsg =
        '\n' +
        params.req.method +
        ' ' +
        connection.host.makeUrl(params.req) +
        (errMsg.length ? ' => ' : '') +
        errMsg
      ;

      if (remainingRetries) {
        remainingRetries--;
        self.log.error('Request error, retrying' + errMsg);
        self.connectionPool.select(sendReqWithConnection);
      } else {
        self.log.error('Request complete with error' + errMsg);
        respond(new errors.ConnectionFault(err));
      }
    } else {
      self.log.debug('Request complete');
      respond(void 0, body, status, headers);
    }
  }

  function respond(err, body, status, headers) {
    if (aborted) {
      return;
    }

    self._timeout(requestTimeoutId);
    var parsedBody;
    var isJson = !headers || (headers['content-type'] && ~headers['content-type'].indexOf('application/json'));

    if (!err && body) {
      if (isJson) {
        parsedBody = self.serializer.deserialize(body);
        if (parsedBody == null) {
          err = new errors.Serialization();
          parsedBody = body;
        }
      } else {
        parsedBody = body;
      }
    }

    // does the response represent an error?
    if (
      (!err || err instanceof errors.Serialization)
      && (status < 200 || status >= 300)
      && (!params.ignore || !_.includes(params.ignore, status))
    ) {

      var errorMetadata = _.pick(params.re ...
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.Transport.prototype.setHosts"></a>[function <span class="apidocSignatureSpan">elasticsearch.Transport.prototype.</span>setHosts (hostsConfigs)](#apidoc.element.elasticsearch.Transport.prototype.setHosts)
- description and source-code
```javascript
setHosts = function (hostsConfigs) {
  var globalConfig = this._config;
  this.connectionPool.setHosts(_.map(hostsConfigs, function (conf) {
    return (conf instanceof Host) ? conf : new Host(conf, globalConfig);
  }));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.Transport.prototype.sniff"></a>[function <span class="apidocSignatureSpan">elasticsearch.Transport.prototype.</span>sniff (cb)](#apidoc.element.elasticsearch.Transport.prototype.sniff)
- description and source-code
```javascript
sniff = function (cb) {
  var self = this;
  var nodesToHostCallback = this.nodesToHostCallback;
  var log = this.log;
  var sniffedNodesProtocol = this.sniffedNodesProtocol;

  // make cb a function if it isn't
  cb = typeof cb === 'function' ? cb : _.noop;

  this.request({
    path: this.sniffEndpoint,
    method: 'GET'
  }, function (err, resp, status) {
    if (!err && resp && resp.nodes) {
      var hostsConfigs;

      try {
        hostsConfigs = nodesToHostCallback(resp.nodes);
      } catch (e) {
        log.error(new Error('Unable to convert node list from ' + this.sniffEndpoint +
          ' to hosts durring sniff. Encountered error:\n' + (e.stack || e.message)));
        return;
      }

      _.forEach(hostsConfigs, function (hostConfig) {
        if (sniffedNodesProtocol) hostConfig.protocol = sniffedNodesProtocol;
      });

      self.setHosts(hostsConfigs);
    }
    cb(err, resp, status);
  });
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.elasticsearch.Transport.serializers"></a>[module elasticsearch.Transport.serializers](#apidoc.module.elasticsearch.Transport.serializers)

#### <a name="apidoc.element.elasticsearch.Transport.serializers.angular"></a>[function <span class="apidocSignatureSpan">elasticsearch.Transport.serializers.</span>angular ()](#apidoc.element.elasticsearch.Transport.serializers.angular)
- description and source-code
```javascript
function AngularSerializer() {}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.Transport.serializers.json"></a>[function <span class="apidocSignatureSpan">elasticsearch.Transport.serializers.</span>json ()](#apidoc.element.elasticsearch.Transport.serializers.json)
- description and source-code
```javascript
function Json() {}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.elasticsearch.Transport.serializers.angular.prototype"></a>[module elasticsearch.Transport.serializers.angular.prototype](#apidoc.module.elasticsearch.Transport.serializers.angular.prototype)

#### <a name="apidoc.element.elasticsearch.Transport.serializers.angular.prototype.encode"></a>[function <span class="apidocSignatureSpan">elasticsearch.Transport.serializers.angular.prototype.</span>encode (val)](#apidoc.element.elasticsearch.Transport.serializers.angular.prototype.encode)
- description and source-code
```javascript
encode = function (val) {
  switch (typeof val) {
    case 'string':
      return val;
    case 'object':
      if (val) return angular.toJson(val);
<span class="apidocCodeCommentSpan">    /* falls through */
</span>    default:
      return;
  }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.elasticsearch.Transport.serializers.json.prototype"></a>[module elasticsearch.Transport.serializers.json.prototype](#apidoc.module.elasticsearch.Transport.serializers.json.prototype)

#### <a name="apidoc.element.elasticsearch.Transport.serializers.json.prototype.bulkBody"></a>[function <span class="apidocSignatureSpan">elasticsearch.Transport.serializers.json.prototype.</span>bulkBody (val)](#apidoc.element.elasticsearch.Transport.serializers.json.prototype.bulkBody)
- description and source-code
```javascript
bulkBody = function (val) {
  var body = '', i;

  if (_.isArray(val)) {
    for (i = 0; i < val.length; i++) {
      body += this.serialize(val[i]) + '\n';
    }
  } else if (typeof val === 'string') {
    // make sure the string ends in a new line
    body = val + (val[val.length - 1] === '\n' ? '' : '\n');
  } else {
    throw new TypeError('Bulk body should either be an Array of commands/string, or a String');
  }

  return body;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.Transport.serializers.json.prototype.deserialize"></a>[function <span class="apidocSignatureSpan">elasticsearch.Transport.serializers.json.prototype.</span>deserialize (str)](#apidoc.element.elasticsearch.Transport.serializers.json.prototype.deserialize)
- description and source-code
```javascript
deserialize = function (str) {
  if (typeof str === 'string') {
    try {
      return JSON.parse(str);
    } catch (e) {}
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.Transport.serializers.json.prototype.serialize"></a>[function <span class="apidocSignatureSpan">elasticsearch.Transport.serializers.json.prototype.</span>serialize (val, replacer, spaces)](#apidoc.element.elasticsearch.Transport.serializers.json.prototype.serialize)
- description and source-code
```javascript
serialize = function (val, replacer, spaces) {
  switch (typeof val) {
    case 'string':
      return val;
    case 'object':
      if (val) {
        return JSON.stringify(val, replacer, spaces);
      }
<span class="apidocCodeCommentSpan">    /* falls through */
</span>    default:
      return;
  }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.elasticsearch.errors"></a>[module elasticsearch.errors](#apidoc.module.elasticsearch.errors)

#### <a name="apidoc.element.elasticsearch.errors.300"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.</span>300 (msg, metadata)](#apidoc.element.elasticsearch.errors.300)
- description and source-code
```javascript
function StatusCodeError(msg, metadata) {
  this.status = status;
  this.displayName = className;

  var esErrObject = null;
  if (_.isPlainObject(msg)) {
    esErrObject = msg;
    msg = null;
  }

  if (!esErrObject) {
    // errors from es now come in two forms, an error string < 2.0 and
    // an object >= 2.0
    // TODO: remove after dropping support for < 2.0
    ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
    return this;
  }

  msg = [].concat(esErrObject.root_cause || []).reduce(function (memo, cause) {
    if (memo) memo += ' (and) ';

    memo += '[' + cause.type + '] ' + cause.reason;

    var extraData = _.omit(cause, ['type', 'reason']);
    if (_.size(extraData)) {
      memo += ', with ' + prettyPrint(extraData);
    }

    return memo;
  }, '');

  if (!msg) {
    if (esErrObject.type) msg += '[' + esErrObject.type + '] ';
    if (esErrObject.reason) msg += esErrObject.reason;
  }

  ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.301"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.</span>301 (msg, metadata)](#apidoc.element.elasticsearch.errors.301)
- description and source-code
```javascript
function StatusCodeError(msg, metadata) {
  this.status = status;
  this.displayName = className;

  var esErrObject = null;
  if (_.isPlainObject(msg)) {
    esErrObject = msg;
    msg = null;
  }

  if (!esErrObject) {
    // errors from es now come in two forms, an error string < 2.0 and
    // an object >= 2.0
    // TODO: remove after dropping support for < 2.0
    ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
    return this;
  }

  msg = [].concat(esErrObject.root_cause || []).reduce(function (memo, cause) {
    if (memo) memo += ' (and) ';

    memo += '[' + cause.type + '] ' + cause.reason;

    var extraData = _.omit(cause, ['type', 'reason']);
    if (_.size(extraData)) {
      memo += ', with ' + prettyPrint(extraData);
    }

    return memo;
  }, '');

  if (!msg) {
    if (esErrObject.type) msg += '[' + esErrObject.type + '] ';
    if (esErrObject.reason) msg += esErrObject.reason;
  }

  ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.302"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.</span>302 (msg, metadata)](#apidoc.element.elasticsearch.errors.302)
- description and source-code
```javascript
function StatusCodeError(msg, metadata) {
  this.status = status;
  this.displayName = className;

  var esErrObject = null;
  if (_.isPlainObject(msg)) {
    esErrObject = msg;
    msg = null;
  }

  if (!esErrObject) {
    // errors from es now come in two forms, an error string < 2.0 and
    // an object >= 2.0
    // TODO: remove after dropping support for < 2.0
    ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
    return this;
  }

  msg = [].concat(esErrObject.root_cause || []).reduce(function (memo, cause) {
    if (memo) memo += ' (and) ';

    memo += '[' + cause.type + '] ' + cause.reason;

    var extraData = _.omit(cause, ['type', 'reason']);
    if (_.size(extraData)) {
      memo += ', with ' + prettyPrint(extraData);
    }

    return memo;
  }, '');

  if (!msg) {
    if (esErrObject.type) msg += '[' + esErrObject.type + '] ';
    if (esErrObject.reason) msg += esErrObject.reason;
  }

  ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.303"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.</span>303 (msg, metadata)](#apidoc.element.elasticsearch.errors.303)
- description and source-code
```javascript
function StatusCodeError(msg, metadata) {
  this.status = status;
  this.displayName = className;

  var esErrObject = null;
  if (_.isPlainObject(msg)) {
    esErrObject = msg;
    msg = null;
  }

  if (!esErrObject) {
    // errors from es now come in two forms, an error string < 2.0 and
    // an object >= 2.0
    // TODO: remove after dropping support for < 2.0
    ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
    return this;
  }

  msg = [].concat(esErrObject.root_cause || []).reduce(function (memo, cause) {
    if (memo) memo += ' (and) ';

    memo += '[' + cause.type + '] ' + cause.reason;

    var extraData = _.omit(cause, ['type', 'reason']);
    if (_.size(extraData)) {
      memo += ', with ' + prettyPrint(extraData);
    }

    return memo;
  }, '');

  if (!msg) {
    if (esErrObject.type) msg += '[' + esErrObject.type + '] ';
    if (esErrObject.reason) msg += esErrObject.reason;
  }

  ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.304"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.</span>304 (msg, metadata)](#apidoc.element.elasticsearch.errors.304)
- description and source-code
```javascript
function StatusCodeError(msg, metadata) {
  this.status = status;
  this.displayName = className;

  var esErrObject = null;
  if (_.isPlainObject(msg)) {
    esErrObject = msg;
    msg = null;
  }

  if (!esErrObject) {
    // errors from es now come in two forms, an error string < 2.0 and
    // an object >= 2.0
    // TODO: remove after dropping support for < 2.0
    ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
    return this;
  }

  msg = [].concat(esErrObject.root_cause || []).reduce(function (memo, cause) {
    if (memo) memo += ' (and) ';

    memo += '[' + cause.type + '] ' + cause.reason;

    var extraData = _.omit(cause, ['type', 'reason']);
    if (_.size(extraData)) {
      memo += ', with ' + prettyPrint(extraData);
    }

    return memo;
  }, '');

  if (!msg) {
    if (esErrObject.type) msg += '[' + esErrObject.type + '] ';
    if (esErrObject.reason) msg += esErrObject.reason;
  }

  ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.305"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.</span>305 (msg, metadata)](#apidoc.element.elasticsearch.errors.305)
- description and source-code
```javascript
function StatusCodeError(msg, metadata) {
  this.status = status;
  this.displayName = className;

  var esErrObject = null;
  if (_.isPlainObject(msg)) {
    esErrObject = msg;
    msg = null;
  }

  if (!esErrObject) {
    // errors from es now come in two forms, an error string < 2.0 and
    // an object >= 2.0
    // TODO: remove after dropping support for < 2.0
    ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
    return this;
  }

  msg = [].concat(esErrObject.root_cause || []).reduce(function (memo, cause) {
    if (memo) memo += ' (and) ';

    memo += '[' + cause.type + '] ' + cause.reason;

    var extraData = _.omit(cause, ['type', 'reason']);
    if (_.size(extraData)) {
      memo += ', with ' + prettyPrint(extraData);
    }

    return memo;
  }, '');

  if (!msg) {
    if (esErrObject.type) msg += '[' + esErrObject.type + '] ';
    if (esErrObject.reason) msg += esErrObject.reason;
  }

  ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.307"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.</span>307 (msg, metadata)](#apidoc.element.elasticsearch.errors.307)
- description and source-code
```javascript
function StatusCodeError(msg, metadata) {
  this.status = status;
  this.displayName = className;

  var esErrObject = null;
  if (_.isPlainObject(msg)) {
    esErrObject = msg;
    msg = null;
  }

  if (!esErrObject) {
    // errors from es now come in two forms, an error string < 2.0 and
    // an object >= 2.0
    // TODO: remove after dropping support for < 2.0
    ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
    return this;
  }

  msg = [].concat(esErrObject.root_cause || []).reduce(function (memo, cause) {
    if (memo) memo += ' (and) ';

    memo += '[' + cause.type + '] ' + cause.reason;

    var extraData = _.omit(cause, ['type', 'reason']);
    if (_.size(extraData)) {
      memo += ', with ' + prettyPrint(extraData);
    }

    return memo;
  }, '');

  if (!msg) {
    if (esErrObject.type) msg += '[' + esErrObject.type + '] ';
    if (esErrObject.reason) msg += esErrObject.reason;
  }

  ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.308"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.</span>308 (msg, metadata)](#apidoc.element.elasticsearch.errors.308)
- description and source-code
```javascript
function StatusCodeError(msg, metadata) {
  this.status = status;
  this.displayName = className;

  var esErrObject = null;
  if (_.isPlainObject(msg)) {
    esErrObject = msg;
    msg = null;
  }

  if (!esErrObject) {
    // errors from es now come in two forms, an error string < 2.0 and
    // an object >= 2.0
    // TODO: remove after dropping support for < 2.0
    ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
    return this;
  }

  msg = [].concat(esErrObject.root_cause || []).reduce(function (memo, cause) {
    if (memo) memo += ' (and) ';

    memo += '[' + cause.type + '] ' + cause.reason;

    var extraData = _.omit(cause, ['type', 'reason']);
    if (_.size(extraData)) {
      memo += ', with ' + prettyPrint(extraData);
    }

    return memo;
  }, '');

  if (!msg) {
    if (esErrObject.type) msg += '[' + esErrObject.type + '] ';
    if (esErrObject.reason) msg += esErrObject.reason;
  }

  ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.400"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.</span>400 (msg, metadata)](#apidoc.element.elasticsearch.errors.400)
- description and source-code
```javascript
function StatusCodeError(msg, metadata) {
  this.status = status;
  this.displayName = className;

  var esErrObject = null;
  if (_.isPlainObject(msg)) {
    esErrObject = msg;
    msg = null;
  }

  if (!esErrObject) {
    // errors from es now come in two forms, an error string < 2.0 and
    // an object >= 2.0
    // TODO: remove after dropping support for < 2.0
    ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
    return this;
  }

  msg = [].concat(esErrObject.root_cause || []).reduce(function (memo, cause) {
    if (memo) memo += ' (and) ';

    memo += '[' + cause.type + '] ' + cause.reason;

    var extraData = _.omit(cause, ['type', 'reason']);
    if (_.size(extraData)) {
      memo += ', with ' + prettyPrint(extraData);
    }

    return memo;
  }, '');

  if (!msg) {
    if (esErrObject.type) msg += '[' + esErrObject.type + '] ';
    if (esErrObject.reason) msg += esErrObject.reason;
  }

  ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.401"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.</span>401 (msg, metadata)](#apidoc.element.elasticsearch.errors.401)
- description and source-code
```javascript
function StatusCodeError(msg, metadata) {
  this.status = status;
  this.displayName = className;

  var esErrObject = null;
  if (_.isPlainObject(msg)) {
    esErrObject = msg;
    msg = null;
  }

  if (!esErrObject) {
    // errors from es now come in two forms, an error string < 2.0 and
    // an object >= 2.0
    // TODO: remove after dropping support for < 2.0
    ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
    return this;
  }

  msg = [].concat(esErrObject.root_cause || []).reduce(function (memo, cause) {
    if (memo) memo += ' (and) ';

    memo += '[' + cause.type + '] ' + cause.reason;

    var extraData = _.omit(cause, ['type', 'reason']);
    if (_.size(extraData)) {
      memo += ', with ' + prettyPrint(extraData);
    }

    return memo;
  }, '');

  if (!msg) {
    if (esErrObject.type) msg += '[' + esErrObject.type + '] ';
    if (esErrObject.reason) msg += esErrObject.reason;
  }

  ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.402"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.</span>402 (msg, metadata)](#apidoc.element.elasticsearch.errors.402)
- description and source-code
```javascript
function StatusCodeError(msg, metadata) {
  this.status = status;
  this.displayName = className;

  var esErrObject = null;
  if (_.isPlainObject(msg)) {
    esErrObject = msg;
    msg = null;
  }

  if (!esErrObject) {
    // errors from es now come in two forms, an error string < 2.0 and
    // an object >= 2.0
    // TODO: remove after dropping support for < 2.0
    ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
    return this;
  }

  msg = [].concat(esErrObject.root_cause || []).reduce(function (memo, cause) {
    if (memo) memo += ' (and) ';

    memo += '[' + cause.type + '] ' + cause.reason;

    var extraData = _.omit(cause, ['type', 'reason']);
    if (_.size(extraData)) {
      memo += ', with ' + prettyPrint(extraData);
    }

    return memo;
  }, '');

  if (!msg) {
    if (esErrObject.type) msg += '[' + esErrObject.type + '] ';
    if (esErrObject.reason) msg += esErrObject.reason;
  }

  ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.403"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.</span>403 (msg, metadata)](#apidoc.element.elasticsearch.errors.403)
- description and source-code
```javascript
function StatusCodeError(msg, metadata) {
  this.status = status;
  this.displayName = className;

  var esErrObject = null;
  if (_.isPlainObject(msg)) {
    esErrObject = msg;
    msg = null;
  }

  if (!esErrObject) {
    // errors from es now come in two forms, an error string < 2.0 and
    // an object >= 2.0
    // TODO: remove after dropping support for < 2.0
    ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
    return this;
  }

  msg = [].concat(esErrObject.root_cause || []).reduce(function (memo, cause) {
    if (memo) memo += ' (and) ';

    memo += '[' + cause.type + '] ' + cause.reason;

    var extraData = _.omit(cause, ['type', 'reason']);
    if (_.size(extraData)) {
      memo += ', with ' + prettyPrint(extraData);
    }

    return memo;
  }, '');

  if (!msg) {
    if (esErrObject.type) msg += '[' + esErrObject.type + '] ';
    if (esErrObject.reason) msg += esErrObject.reason;
  }

  ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.404"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.</span>404 (msg, metadata)](#apidoc.element.elasticsearch.errors.404)
- description and source-code
```javascript
function StatusCodeError(msg, metadata) {
  this.status = status;
  this.displayName = className;

  var esErrObject = null;
  if (_.isPlainObject(msg)) {
    esErrObject = msg;
    msg = null;
  }

  if (!esErrObject) {
    // errors from es now come in two forms, an error string < 2.0 and
    // an object >= 2.0
    // TODO: remove after dropping support for < 2.0
    ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
    return this;
  }

  msg = [].concat(esErrObject.root_cause || []).reduce(function (memo, cause) {
    if (memo) memo += ' (and) ';

    memo += '[' + cause.type + '] ' + cause.reason;

    var extraData = _.omit(cause, ['type', 'reason']);
    if (_.size(extraData)) {
      memo += ', with ' + prettyPrint(extraData);
    }

    return memo;
  }, '');

  if (!msg) {
    if (esErrObject.type) msg += '[' + esErrObject.type + '] ';
    if (esErrObject.reason) msg += esErrObject.reason;
  }

  ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.405"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.</span>405 (msg, metadata)](#apidoc.element.elasticsearch.errors.405)
- description and source-code
```javascript
function StatusCodeError(msg, metadata) {
  this.status = status;
  this.displayName = className;

  var esErrObject = null;
  if (_.isPlainObject(msg)) {
    esErrObject = msg;
    msg = null;
  }

  if (!esErrObject) {
    // errors from es now come in two forms, an error string < 2.0 and
    // an object >= 2.0
    // TODO: remove after dropping support for < 2.0
    ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
    return this;
  }

  msg = [].concat(esErrObject.root_cause || []).reduce(function (memo, cause) {
    if (memo) memo += ' (and) ';

    memo += '[' + cause.type + '] ' + cause.reason;

    var extraData = _.omit(cause, ['type', 'reason']);
    if (_.size(extraData)) {
      memo += ', with ' + prettyPrint(extraData);
    }

    return memo;
  }, '');

  if (!msg) {
    if (esErrObject.type) msg += '[' + esErrObject.type + '] ';
    if (esErrObject.reason) msg += esErrObject.reason;
  }

  ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.406"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.</span>406 (msg, metadata)](#apidoc.element.elasticsearch.errors.406)
- description and source-code
```javascript
function StatusCodeError(msg, metadata) {
  this.status = status;
  this.displayName = className;

  var esErrObject = null;
  if (_.isPlainObject(msg)) {
    esErrObject = msg;
    msg = null;
  }

  if (!esErrObject) {
    // errors from es now come in two forms, an error string < 2.0 and
    // an object >= 2.0
    // TODO: remove after dropping support for < 2.0
    ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
    return this;
  }

  msg = [].concat(esErrObject.root_cause || []).reduce(function (memo, cause) {
    if (memo) memo += ' (and) ';

    memo += '[' + cause.type + '] ' + cause.reason;

    var extraData = _.omit(cause, ['type', 'reason']);
    if (_.size(extraData)) {
      memo += ', with ' + prettyPrint(extraData);
    }

    return memo;
  }, '');

  if (!msg) {
    if (esErrObject.type) msg += '[' + esErrObject.type + '] ';
    if (esErrObject.reason) msg += esErrObject.reason;
  }

  ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.407"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.</span>407 (msg, metadata)](#apidoc.element.elasticsearch.errors.407)
- description and source-code
```javascript
function StatusCodeError(msg, metadata) {
  this.status = status;
  this.displayName = className;

  var esErrObject = null;
  if (_.isPlainObject(msg)) {
    esErrObject = msg;
    msg = null;
  }

  if (!esErrObject) {
    // errors from es now come in two forms, an error string < 2.0 and
    // an object >= 2.0
    // TODO: remove after dropping support for < 2.0
    ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
    return this;
  }

  msg = [].concat(esErrObject.root_cause || []).reduce(function (memo, cause) {
    if (memo) memo += ' (and) ';

    memo += '[' + cause.type + '] ' + cause.reason;

    var extraData = _.omit(cause, ['type', 'reason']);
    if (_.size(extraData)) {
      memo += ', with ' + prettyPrint(extraData);
    }

    return memo;
  }, '');

  if (!msg) {
    if (esErrObject.type) msg += '[' + esErrObject.type + '] ';
    if (esErrObject.reason) msg += esErrObject.reason;
  }

  ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.408"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.</span>408 (msg, metadata)](#apidoc.element.elasticsearch.errors.408)
- description and source-code
```javascript
function StatusCodeError(msg, metadata) {
  this.status = status;
  this.displayName = className;

  var esErrObject = null;
  if (_.isPlainObject(msg)) {
    esErrObject = msg;
    msg = null;
  }

  if (!esErrObject) {
    // errors from es now come in two forms, an error string < 2.0 and
    // an object >= 2.0
    // TODO: remove after dropping support for < 2.0
    ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
    return this;
  }

  msg = [].concat(esErrObject.root_cause || []).reduce(function (memo, cause) {
    if (memo) memo += ' (and) ';

    memo += '[' + cause.type + '] ' + cause.reason;

    var extraData = _.omit(cause, ['type', 'reason']);
    if (_.size(extraData)) {
      memo += ', with ' + prettyPrint(extraData);
    }

    return memo;
  }, '');

  if (!msg) {
    if (esErrObject.type) msg += '[' + esErrObject.type + '] ';
    if (esErrObject.reason) msg += esErrObject.reason;
  }

  ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.409"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.</span>409 (msg, metadata)](#apidoc.element.elasticsearch.errors.409)
- description and source-code
```javascript
function StatusCodeError(msg, metadata) {
  this.status = status;
  this.displayName = className;

  var esErrObject = null;
  if (_.isPlainObject(msg)) {
    esErrObject = msg;
    msg = null;
  }

  if (!esErrObject) {
    // errors from es now come in two forms, an error string < 2.0 and
    // an object >= 2.0
    // TODO: remove after dropping support for < 2.0
    ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
    return this;
  }

  msg = [].concat(esErrObject.root_cause || []).reduce(function (memo, cause) {
    if (memo) memo += ' (and) ';

    memo += '[' + cause.type + '] ' + cause.reason;

    var extraData = _.omit(cause, ['type', 'reason']);
    if (_.size(extraData)) {
      memo += ', with ' + prettyPrint(extraData);
    }

    return memo;
  }, '');

  if (!msg) {
    if (esErrObject.type) msg += '[' + esErrObject.type + '] ';
    if (esErrObject.reason) msg += esErrObject.reason;
  }

  ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.410"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.</span>410 (msg, metadata)](#apidoc.element.elasticsearch.errors.410)
- description and source-code
```javascript
function StatusCodeError(msg, metadata) {
  this.status = status;
  this.displayName = className;

  var esErrObject = null;
  if (_.isPlainObject(msg)) {
    esErrObject = msg;
    msg = null;
  }

  if (!esErrObject) {
    // errors from es now come in two forms, an error string < 2.0 and
    // an object >= 2.0
    // TODO: remove after dropping support for < 2.0
    ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
    return this;
  }

  msg = [].concat(esErrObject.root_cause || []).reduce(function (memo, cause) {
    if (memo) memo += ' (and) ';

    memo += '[' + cause.type + '] ' + cause.reason;

    var extraData = _.omit(cause, ['type', 'reason']);
    if (_.size(extraData)) {
      memo += ', with ' + prettyPrint(extraData);
    }

    return memo;
  }, '');

  if (!msg) {
    if (esErrObject.type) msg += '[' + esErrObject.type + '] ';
    if (esErrObject.reason) msg += esErrObject.reason;
  }

  ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.411"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.</span>411 (msg, metadata)](#apidoc.element.elasticsearch.errors.411)
- description and source-code
```javascript
function StatusCodeError(msg, metadata) {
  this.status = status;
  this.displayName = className;

  var esErrObject = null;
  if (_.isPlainObject(msg)) {
    esErrObject = msg;
    msg = null;
  }

  if (!esErrObject) {
    // errors from es now come in two forms, an error string < 2.0 and
    // an object >= 2.0
    // TODO: remove after dropping support for < 2.0
    ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
    return this;
  }

  msg = [].concat(esErrObject.root_cause || []).reduce(function (memo, cause) {
    if (memo) memo += ' (and) ';

    memo += '[' + cause.type + '] ' + cause.reason;

    var extraData = _.omit(cause, ['type', 'reason']);
    if (_.size(extraData)) {
      memo += ', with ' + prettyPrint(extraData);
    }

    return memo;
  }, '');

  if (!msg) {
    if (esErrObject.type) msg += '[' + esErrObject.type + '] ';
    if (esErrObject.reason) msg += esErrObject.reason;
  }

  ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.412"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.</span>412 (msg, metadata)](#apidoc.element.elasticsearch.errors.412)
- description and source-code
```javascript
function StatusCodeError(msg, metadata) {
  this.status = status;
  this.displayName = className;

  var esErrObject = null;
  if (_.isPlainObject(msg)) {
    esErrObject = msg;
    msg = null;
  }

  if (!esErrObject) {
    // errors from es now come in two forms, an error string < 2.0 and
    // an object >= 2.0
    // TODO: remove after dropping support for < 2.0
    ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
    return this;
  }

  msg = [].concat(esErrObject.root_cause || []).reduce(function (memo, cause) {
    if (memo) memo += ' (and) ';

    memo += '[' + cause.type + '] ' + cause.reason;

    var extraData = _.omit(cause, ['type', 'reason']);
    if (_.size(extraData)) {
      memo += ', with ' + prettyPrint(extraData);
    }

    return memo;
  }, '');

  if (!msg) {
    if (esErrObject.type) msg += '[' + esErrObject.type + '] ';
    if (esErrObject.reason) msg += esErrObject.reason;
  }

  ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.413"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.</span>413 (msg, metadata)](#apidoc.element.elasticsearch.errors.413)
- description and source-code
```javascript
function StatusCodeError(msg, metadata) {
  this.status = status;
  this.displayName = className;

  var esErrObject = null;
  if (_.isPlainObject(msg)) {
    esErrObject = msg;
    msg = null;
  }

  if (!esErrObject) {
    // errors from es now come in two forms, an error string < 2.0 and
    // an object >= 2.0
    // TODO: remove after dropping support for < 2.0
    ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
    return this;
  }

  msg = [].concat(esErrObject.root_cause || []).reduce(function (memo, cause) {
    if (memo) memo += ' (and) ';

    memo += '[' + cause.type + '] ' + cause.reason;

    var extraData = _.omit(cause, ['type', 'reason']);
    if (_.size(extraData)) {
      memo += ', with ' + prettyPrint(extraData);
    }

    return memo;
  }, '');

  if (!msg) {
    if (esErrObject.type) msg += '[' + esErrObject.type + '] ';
    if (esErrObject.reason) msg += esErrObject.reason;
  }

  ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.414"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.</span>414 (msg, metadata)](#apidoc.element.elasticsearch.errors.414)
- description and source-code
```javascript
function StatusCodeError(msg, metadata) {
  this.status = status;
  this.displayName = className;

  var esErrObject = null;
  if (_.isPlainObject(msg)) {
    esErrObject = msg;
    msg = null;
  }

  if (!esErrObject) {
    // errors from es now come in two forms, an error string < 2.0 and
    // an object >= 2.0
    // TODO: remove after dropping support for < 2.0
    ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
    return this;
  }

  msg = [].concat(esErrObject.root_cause || []).reduce(function (memo, cause) {
    if (memo) memo += ' (and) ';

    memo += '[' + cause.type + '] ' + cause.reason;

    var extraData = _.omit(cause, ['type', 'reason']);
    if (_.size(extraData)) {
      memo += ', with ' + prettyPrint(extraData);
    }

    return memo;
  }, '');

  if (!msg) {
    if (esErrObject.type) msg += '[' + esErrObject.type + '] ';
    if (esErrObject.reason) msg += esErrObject.reason;
  }

  ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.415"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.</span>415 (msg, metadata)](#apidoc.element.elasticsearch.errors.415)
- description and source-code
```javascript
function StatusCodeError(msg, metadata) {
  this.status = status;
  this.displayName = className;

  var esErrObject = null;
  if (_.isPlainObject(msg)) {
    esErrObject = msg;
    msg = null;
  }

  if (!esErrObject) {
    // errors from es now come in two forms, an error string < 2.0 and
    // an object >= 2.0
    // TODO: remove after dropping support for < 2.0
    ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
    return this;
  }

  msg = [].concat(esErrObject.root_cause || []).reduce(function (memo, cause) {
    if (memo) memo += ' (and) ';

    memo += '[' + cause.type + '] ' + cause.reason;

    var extraData = _.omit(cause, ['type', 'reason']);
    if (_.size(extraData)) {
      memo += ', with ' + prettyPrint(extraData);
    }

    return memo;
  }, '');

  if (!msg) {
    if (esErrObject.type) msg += '[' + esErrObject.type + '] ';
    if (esErrObject.reason) msg += esErrObject.reason;
  }

  ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.416"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.</span>416 (msg, metadata)](#apidoc.element.elasticsearch.errors.416)
- description and source-code
```javascript
function StatusCodeError(msg, metadata) {
  this.status = status;
  this.displayName = className;

  var esErrObject = null;
  if (_.isPlainObject(msg)) {
    esErrObject = msg;
    msg = null;
  }

  if (!esErrObject) {
    // errors from es now come in two forms, an error string < 2.0 and
    // an object >= 2.0
    // TODO: remove after dropping support for < 2.0
    ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
    return this;
  }

  msg = [].concat(esErrObject.root_cause || []).reduce(function (memo, cause) {
    if (memo) memo += ' (and) ';

    memo += '[' + cause.type + '] ' + cause.reason;

    var extraData = _.omit(cause, ['type', 'reason']);
    if (_.size(extraData)) {
      memo += ', with ' + prettyPrint(extraData);
    }

    return memo;
  }, '');

  if (!msg) {
    if (esErrObject.type) msg += '[' + esErrObject.type + '] ';
    if (esErrObject.reason) msg += esErrObject.reason;
  }

  ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.417"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.</span>417 (msg, metadata)](#apidoc.element.elasticsearch.errors.417)
- description and source-code
```javascript
function StatusCodeError(msg, metadata) {
  this.status = status;
  this.displayName = className;

  var esErrObject = null;
  if (_.isPlainObject(msg)) {
    esErrObject = msg;
    msg = null;
  }

  if (!esErrObject) {
    // errors from es now come in two forms, an error string < 2.0 and
    // an object >= 2.0
    // TODO: remove after dropping support for < 2.0
    ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
    return this;
  }

  msg = [].concat(esErrObject.root_cause || []).reduce(function (memo, cause) {
    if (memo) memo += ' (and) ';

    memo += '[' + cause.type + '] ' + cause.reason;

    var extraData = _.omit(cause, ['type', 'reason']);
    if (_.size(extraData)) {
      memo += ', with ' + prettyPrint(extraData);
    }

    return memo;
  }, '');

  if (!msg) {
    if (esErrObject.type) msg += '[' + esErrObject.type + '] ';
    if (esErrObject.reason) msg += esErrObject.reason;
  }

  ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.418"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.</span>418 (msg, metadata)](#apidoc.element.elasticsearch.errors.418)
- description and source-code
```javascript
function StatusCodeError(msg, metadata) {
  this.status = status;
  this.displayName = className;

  var esErrObject = null;
  if (_.isPlainObject(msg)) {
    esErrObject = msg;
    msg = null;
  }

  if (!esErrObject) {
    // errors from es now come in two forms, an error string < 2.0 and
    // an object >= 2.0
    // TODO: remove after dropping support for < 2.0
    ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
    return this;
  }

  msg = [].concat(esErrObject.root_cause || []).reduce(function (memo, cause) {
    if (memo) memo += ' (and) ';

    memo += '[' + cause.type + '] ' + cause.reason;

    var extraData = _.omit(cause, ['type', 'reason']);
    if (_.size(extraData)) {
      memo += ', with ' + prettyPrint(extraData);
    }

    return memo;
  }, '');

  if (!msg) {
    if (esErrObject.type) msg += '[' + esErrObject.type + '] ';
    if (esErrObject.reason) msg += esErrObject.reason;
  }

  ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.421"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.</span>421 (msg, metadata)](#apidoc.element.elasticsearch.errors.421)
- description and source-code
```javascript
function StatusCodeError(msg, metadata) {
  this.status = status;
  this.displayName = className;

  var esErrObject = null;
  if (_.isPlainObject(msg)) {
    esErrObject = msg;
    msg = null;
  }

  if (!esErrObject) {
    // errors from es now come in two forms, an error string < 2.0 and
    // an object >= 2.0
    // TODO: remove after dropping support for < 2.0
    ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
    return this;
  }

  msg = [].concat(esErrObject.root_cause || []).reduce(function (memo, cause) {
    if (memo) memo += ' (and) ';

    memo += '[' + cause.type + '] ' + cause.reason;

    var extraData = _.omit(cause, ['type', 'reason']);
    if (_.size(extraData)) {
      memo += ', with ' + prettyPrint(extraData);
    }

    return memo;
  }, '');

  if (!msg) {
    if (esErrObject.type) msg += '[' + esErrObject.type + '] ';
    if (esErrObject.reason) msg += esErrObject.reason;
  }

  ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.426"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.</span>426 (msg, metadata)](#apidoc.element.elasticsearch.errors.426)
- description and source-code
```javascript
function StatusCodeError(msg, metadata) {
  this.status = status;
  this.displayName = className;

  var esErrObject = null;
  if (_.isPlainObject(msg)) {
    esErrObject = msg;
    msg = null;
  }

  if (!esErrObject) {
    // errors from es now come in two forms, an error string < 2.0 and
    // an object >= 2.0
    // TODO: remove after dropping support for < 2.0
    ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
    return this;
  }

  msg = [].concat(esErrObject.root_cause || []).reduce(function (memo, cause) {
    if (memo) memo += ' (and) ';

    memo += '[' + cause.type + '] ' + cause.reason;

    var extraData = _.omit(cause, ['type', 'reason']);
    if (_.size(extraData)) {
      memo += ', with ' + prettyPrint(extraData);
    }

    return memo;
  }, '');

  if (!msg) {
    if (esErrObject.type) msg += '[' + esErrObject.type + '] ';
    if (esErrObject.reason) msg += esErrObject.reason;
  }

  ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.429"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.</span>429 (msg, metadata)](#apidoc.element.elasticsearch.errors.429)
- description and source-code
```javascript
function StatusCodeError(msg, metadata) {
  this.status = status;
  this.displayName = className;

  var esErrObject = null;
  if (_.isPlainObject(msg)) {
    esErrObject = msg;
    msg = null;
  }

  if (!esErrObject) {
    // errors from es now come in two forms, an error string < 2.0 and
    // an object >= 2.0
    // TODO: remove after dropping support for < 2.0
    ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
    return this;
  }

  msg = [].concat(esErrObject.root_cause || []).reduce(function (memo, cause) {
    if (memo) memo += ' (and) ';

    memo += '[' + cause.type + '] ' + cause.reason;

    var extraData = _.omit(cause, ['type', 'reason']);
    if (_.size(extraData)) {
      memo += ', with ' + prettyPrint(extraData);
    }

    return memo;
  }, '');

  if (!msg) {
    if (esErrObject.type) msg += '[' + esErrObject.type + '] ';
    if (esErrObject.reason) msg += esErrObject.reason;
  }

  ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.450"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.</span>450 (msg, metadata)](#apidoc.element.elasticsearch.errors.450)
- description and source-code
```javascript
function StatusCodeError(msg, metadata) {
  this.status = status;
  this.displayName = className;

  var esErrObject = null;
  if (_.isPlainObject(msg)) {
    esErrObject = msg;
    msg = null;
  }

  if (!esErrObject) {
    // errors from es now come in two forms, an error string < 2.0 and
    // an object >= 2.0
    // TODO: remove after dropping support for < 2.0
    ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
    return this;
  }

  msg = [].concat(esErrObject.root_cause || []).reduce(function (memo, cause) {
    if (memo) memo += ' (and) ';

    memo += '[' + cause.type + '] ' + cause.reason;

    var extraData = _.omit(cause, ['type', 'reason']);
    if (_.size(extraData)) {
      memo += ', with ' + prettyPrint(extraData);
    }

    return memo;
  }, '');

  if (!msg) {
    if (esErrObject.type) msg += '[' + esErrObject.type + '] ';
    if (esErrObject.reason) msg += esErrObject.reason;
  }

  ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.494"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.</span>494 (msg, metadata)](#apidoc.element.elasticsearch.errors.494)
- description and source-code
```javascript
function StatusCodeError(msg, metadata) {
  this.status = status;
  this.displayName = className;

  var esErrObject = null;
  if (_.isPlainObject(msg)) {
    esErrObject = msg;
    msg = null;
  }

  if (!esErrObject) {
    // errors from es now come in two forms, an error string < 2.0 and
    // an object >= 2.0
    // TODO: remove after dropping support for < 2.0
    ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
    return this;
  }

  msg = [].concat(esErrObject.root_cause || []).reduce(function (memo, cause) {
    if (memo) memo += ' (and) ';

    memo += '[' + cause.type + '] ' + cause.reason;

    var extraData = _.omit(cause, ['type', 'reason']);
    if (_.size(extraData)) {
      memo += ', with ' + prettyPrint(extraData);
    }

    return memo;
  }, '');

  if (!msg) {
    if (esErrObject.type) msg += '[' + esErrObject.type + '] ';
    if (esErrObject.reason) msg += esErrObject.reason;
  }

  ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.497"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.</span>497 (msg, metadata)](#apidoc.element.elasticsearch.errors.497)
- description and source-code
```javascript
function StatusCodeError(msg, metadata) {
  this.status = status;
  this.displayName = className;

  var esErrObject = null;
  if (_.isPlainObject(msg)) {
    esErrObject = msg;
    msg = null;
  }

  if (!esErrObject) {
    // errors from es now come in two forms, an error string < 2.0 and
    // an object >= 2.0
    // TODO: remove after dropping support for < 2.0
    ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
    return this;
  }

  msg = [].concat(esErrObject.root_cause || []).reduce(function (memo, cause) {
    if (memo) memo += ' (and) ';

    memo += '[' + cause.type + '] ' + cause.reason;

    var extraData = _.omit(cause, ['type', 'reason']);
    if (_.size(extraData)) {
      memo += ', with ' + prettyPrint(extraData);
    }

    return memo;
  }, '');

  if (!msg) {
    if (esErrObject.type) msg += '[' + esErrObject.type + '] ';
    if (esErrObject.reason) msg += esErrObject.reason;
  }

  ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.499"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.</span>499 (msg, metadata)](#apidoc.element.elasticsearch.errors.499)
- description and source-code
```javascript
function StatusCodeError(msg, metadata) {
  this.status = status;
  this.displayName = className;

  var esErrObject = null;
  if (_.isPlainObject(msg)) {
    esErrObject = msg;
    msg = null;
  }

  if (!esErrObject) {
    // errors from es now come in two forms, an error string < 2.0 and
    // an object >= 2.0
    // TODO: remove after dropping support for < 2.0
    ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
    return this;
  }

  msg = [].concat(esErrObject.root_cause || []).reduce(function (memo, cause) {
    if (memo) memo += ' (and) ';

    memo += '[' + cause.type + '] ' + cause.reason;

    var extraData = _.omit(cause, ['type', 'reason']);
    if (_.size(extraData)) {
      memo += ', with ' + prettyPrint(extraData);
    }

    return memo;
  }, '');

  if (!msg) {
    if (esErrObject.type) msg += '[' + esErrObject.type + '] ';
    if (esErrObject.reason) msg += esErrObject.reason;
  }

  ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.500"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.</span>500 (msg, metadata)](#apidoc.element.elasticsearch.errors.500)
- description and source-code
```javascript
function StatusCodeError(msg, metadata) {
  this.status = status;
  this.displayName = className;

  var esErrObject = null;
  if (_.isPlainObject(msg)) {
    esErrObject = msg;
    msg = null;
  }

  if (!esErrObject) {
    // errors from es now come in two forms, an error string < 2.0 and
    // an object >= 2.0
    // TODO: remove after dropping support for < 2.0
    ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
    return this;
  }

  msg = [].concat(esErrObject.root_cause || []).reduce(function (memo, cause) {
    if (memo) memo += ' (and) ';

    memo += '[' + cause.type + '] ' + cause.reason;

    var extraData = _.omit(cause, ['type', 'reason']);
    if (_.size(extraData)) {
      memo += ', with ' + prettyPrint(extraData);
    }

    return memo;
  }, '');

  if (!msg) {
    if (esErrObject.type) msg += '[' + esErrObject.type + '] ';
    if (esErrObject.reason) msg += esErrObject.reason;
  }

  ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.501"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.</span>501 (msg, metadata)](#apidoc.element.elasticsearch.errors.501)
- description and source-code
```javascript
function StatusCodeError(msg, metadata) {
  this.status = status;
  this.displayName = className;

  var esErrObject = null;
  if (_.isPlainObject(msg)) {
    esErrObject = msg;
    msg = null;
  }

  if (!esErrObject) {
    // errors from es now come in two forms, an error string < 2.0 and
    // an object >= 2.0
    // TODO: remove after dropping support for < 2.0
    ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
    return this;
  }

  msg = [].concat(esErrObject.root_cause || []).reduce(function (memo, cause) {
    if (memo) memo += ' (and) ';

    memo += '[' + cause.type + '] ' + cause.reason;

    var extraData = _.omit(cause, ['type', 'reason']);
    if (_.size(extraData)) {
      memo += ', with ' + prettyPrint(extraData);
    }

    return memo;
  }, '');

  if (!msg) {
    if (esErrObject.type) msg += '[' + esErrObject.type + '] ';
    if (esErrObject.reason) msg += esErrObject.reason;
  }

  ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.502"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.</span>502 (msg, metadata)](#apidoc.element.elasticsearch.errors.502)
- description and source-code
```javascript
function StatusCodeError(msg, metadata) {
  this.status = status;
  this.displayName = className;

  var esErrObject = null;
  if (_.isPlainObject(msg)) {
    esErrObject = msg;
    msg = null;
  }

  if (!esErrObject) {
    // errors from es now come in two forms, an error string < 2.0 and
    // an object >= 2.0
    // TODO: remove after dropping support for < 2.0
    ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
    return this;
  }

  msg = [].concat(esErrObject.root_cause || []).reduce(function (memo, cause) {
    if (memo) memo += ' (and) ';

    memo += '[' + cause.type + '] ' + cause.reason;

    var extraData = _.omit(cause, ['type', 'reason']);
    if (_.size(extraData)) {
      memo += ', with ' + prettyPrint(extraData);
    }

    return memo;
  }, '');

  if (!msg) {
    if (esErrObject.type) msg += '[' + esErrObject.type + '] ';
    if (esErrObject.reason) msg += esErrObject.reason;
  }

  ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.503"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.</span>503 (msg, metadata)](#apidoc.element.elasticsearch.errors.503)
- description and source-code
```javascript
function StatusCodeError(msg, metadata) {
  this.status = status;
  this.displayName = className;

  var esErrObject = null;
  if (_.isPlainObject(msg)) {
    esErrObject = msg;
    msg = null;
  }

  if (!esErrObject) {
    // errors from es now come in two forms, an error string < 2.0 and
    // an object >= 2.0
    // TODO: remove after dropping support for < 2.0
    ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
    return this;
  }

  msg = [].concat(esErrObject.root_cause || []).reduce(function (memo, cause) {
    if (memo) memo += ' (and) ';

    memo += '[' + cause.type + '] ' + cause.reason;

    var extraData = _.omit(cause, ['type', 'reason']);
    if (_.size(extraData)) {
      memo += ', with ' + prettyPrint(extraData);
    }

    return memo;
  }, '');

  if (!msg) {
    if (esErrObject.type) msg += '[' + esErrObject.type + '] ';
    if (esErrObject.reason) msg += esErrObject.reason;
  }

  ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.504"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.</span>504 (msg, metadata)](#apidoc.element.elasticsearch.errors.504)
- description and source-code
```javascript
function StatusCodeError(msg, metadata) {
  this.status = status;
  this.displayName = className;

  var esErrObject = null;
  if (_.isPlainObject(msg)) {
    esErrObject = msg;
    msg = null;
  }

  if (!esErrObject) {
    // errors from es now come in two forms, an error string < 2.0 and
    // an object >= 2.0
    // TODO: remove after dropping support for < 2.0
    ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
    return this;
  }

  msg = [].concat(esErrObject.root_cause || []).reduce(function (memo, cause) {
    if (memo) memo += ' (and) ';

    memo += '[' + cause.type + '] ' + cause.reason;

    var extraData = _.omit(cause, ['type', 'reason']);
    if (_.size(extraData)) {
      memo += ', with ' + prettyPrint(extraData);
    }

    return memo;
  }, '');

  if (!msg) {
    if (esErrObject.type) msg += '[' + esErrObject.type + '] ';
    if (esErrObject.reason) msg += esErrObject.reason;
  }

  ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.505"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.</span>505 (msg, metadata)](#apidoc.element.elasticsearch.errors.505)
- description and source-code
```javascript
function StatusCodeError(msg, metadata) {
  this.status = status;
  this.displayName = className;

  var esErrObject = null;
  if (_.isPlainObject(msg)) {
    esErrObject = msg;
    msg = null;
  }

  if (!esErrObject) {
    // errors from es now come in two forms, an error string < 2.0 and
    // an object >= 2.0
    // TODO: remove after dropping support for < 2.0
    ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
    return this;
  }

  msg = [].concat(esErrObject.root_cause || []).reduce(function (memo, cause) {
    if (memo) memo += ' (and) ';

    memo += '[' + cause.type + '] ' + cause.reason;

    var extraData = _.omit(cause, ['type', 'reason']);
    if (_.size(extraData)) {
      memo += ', with ' + prettyPrint(extraData);
    }

    return memo;
  }, '');

  if (!msg) {
    if (esErrObject.type) msg += '[' + esErrObject.type + '] ';
    if (esErrObject.reason) msg += esErrObject.reason;
  }

  ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.506"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.</span>506 (msg, metadata)](#apidoc.element.elasticsearch.errors.506)
- description and source-code
```javascript
function StatusCodeError(msg, metadata) {
  this.status = status;
  this.displayName = className;

  var esErrObject = null;
  if (_.isPlainObject(msg)) {
    esErrObject = msg;
    msg = null;
  }

  if (!esErrObject) {
    // errors from es now come in two forms, an error string < 2.0 and
    // an object >= 2.0
    // TODO: remove after dropping support for < 2.0
    ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
    return this;
  }

  msg = [].concat(esErrObject.root_cause || []).reduce(function (memo, cause) {
    if (memo) memo += ' (and) ';

    memo += '[' + cause.type + '] ' + cause.reason;

    var extraData = _.omit(cause, ['type', 'reason']);
    if (_.size(extraData)) {
      memo += ', with ' + prettyPrint(extraData);
    }

    return memo;
  }, '');

  if (!msg) {
    if (esErrObject.type) msg += '[' + esErrObject.type + '] ';
    if (esErrObject.reason) msg += esErrObject.reason;
  }

  ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.510"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.</span>510 (msg, metadata)](#apidoc.element.elasticsearch.errors.510)
- description and source-code
```javascript
function StatusCodeError(msg, metadata) {
  this.status = status;
  this.displayName = className;

  var esErrObject = null;
  if (_.isPlainObject(msg)) {
    esErrObject = msg;
    msg = null;
  }

  if (!esErrObject) {
    // errors from es now come in two forms, an error string < 2.0 and
    // an object >= 2.0
    // TODO: remove after dropping support for < 2.0
    ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
    return this;
  }

  msg = [].concat(esErrObject.root_cause || []).reduce(function (memo, cause) {
    if (memo) memo += ' (and) ';

    memo += '[' + cause.type + '] ' + cause.reason;

    var extraData = _.omit(cause, ['type', 'reason']);
    if (_.size(extraData)) {
      memo += ', with ' + prettyPrint(extraData);
    }

    return memo;
  }, '');

  if (!msg) {
    if (esErrObject.type) msg += '[' + esErrObject.type + '] ';
    if (esErrObject.reason) msg += esErrObject.reason;
  }

  ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.AuthenticationException"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.</span>AuthenticationException (msg, metadata)](#apidoc.element.elasticsearch.errors.AuthenticationException)
- description and source-code
```javascript
function StatusCodeError(msg, metadata) {
  this.status = status;
  this.displayName = className;

  var esErrObject = null;
  if (_.isPlainObject(msg)) {
    esErrObject = msg;
    msg = null;
  }

  if (!esErrObject) {
    // errors from es now come in two forms, an error string < 2.0 and
    // an object >= 2.0
    // TODO: remove after dropping support for < 2.0
    ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
    return this;
  }

  msg = [].concat(esErrObject.root_cause || []).reduce(function (memo, cause) {
    if (memo) memo += ' (and) ';

    memo += '[' + cause.type + '] ' + cause.reason;

    var extraData = _.omit(cause, ['type', 'reason']);
    if (_.size(extraData)) {
      memo += ', with ' + prettyPrint(extraData);
    }

    return memo;
  }, '');

  if (!msg) {
    if (esErrObject.type) msg += '[' + esErrObject.type + '] ';
    if (esErrObject.reason) msg += esErrObject.reason;
  }

  ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.AuthorizationException"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.</span>AuthorizationException (msg, metadata)](#apidoc.element.elasticsearch.errors.AuthorizationException)
- description and source-code
```javascript
function StatusCodeError(msg, metadata) {
  this.status = status;
  this.displayName = className;

  var esErrObject = null;
  if (_.isPlainObject(msg)) {
    esErrObject = msg;
    msg = null;
  }

  if (!esErrObject) {
    // errors from es now come in two forms, an error string < 2.0 and
    // an object >= 2.0
    // TODO: remove after dropping support for < 2.0
    ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
    return this;
  }

  msg = [].concat(esErrObject.root_cause || []).reduce(function (memo, cause) {
    if (memo) memo += ' (and) ';

    memo += '[' + cause.type + '] ' + cause.reason;

    var extraData = _.omit(cause, ['type', 'reason']);
    if (_.size(extraData)) {
      memo += ', with ' + prettyPrint(extraData);
    }

    return memo;
  }, '');

  if (!msg) {
    if (esErrObject.type) msg += '[' + esErrObject.type + '] ';
    if (esErrObject.reason) msg += esErrObject.reason;
  }

  ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.BadGateway"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.</span>BadGateway (msg, metadata)](#apidoc.element.elasticsearch.errors.BadGateway)
- description and source-code
```javascript
function StatusCodeError(msg, metadata) {
  this.status = status;
  this.displayName = className;

  var esErrObject = null;
  if (_.isPlainObject(msg)) {
    esErrObject = msg;
    msg = null;
  }

  if (!esErrObject) {
    // errors from es now come in two forms, an error string < 2.0 and
    // an object >= 2.0
    // TODO: remove after dropping support for < 2.0
    ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
    return this;
  }

  msg = [].concat(esErrObject.root_cause || []).reduce(function (memo, cause) {
    if (memo) memo += ' (and) ';

    memo += '[' + cause.type + '] ' + cause.reason;

    var extraData = _.omit(cause, ['type', 'reason']);
    if (_.size(extraData)) {
      memo += ', with ' + prettyPrint(extraData);
    }

    return memo;
  }, '');

  if (!msg) {
    if (esErrObject.type) msg += '[' + esErrObject.type + '] ';
    if (esErrObject.reason) msg += esErrObject.reason;
  }

  ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.BadRequest"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.</span>BadRequest (msg, metadata)](#apidoc.element.elasticsearch.errors.BadRequest)
- description and source-code
```javascript
function StatusCodeError(msg, metadata) {
  this.status = status;
  this.displayName = className;

  var esErrObject = null;
  if (_.isPlainObject(msg)) {
    esErrObject = msg;
    msg = null;
  }

  if (!esErrObject) {
    // errors from es now come in two forms, an error string < 2.0 and
    // an object >= 2.0
    // TODO: remove after dropping support for < 2.0
    ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
    return this;
  }

  msg = [].concat(esErrObject.root_cause || []).reduce(function (memo, cause) {
    if (memo) memo += ' (and) ';

    memo += '[' + cause.type + '] ' + cause.reason;

    var extraData = _.omit(cause, ['type', 'reason']);
    if (_.size(extraData)) {
      memo += ', with ' + prettyPrint(extraData);
    }

    return memo;
  }, '');

  if (!msg) {
    if (esErrObject.type) msg += '[' + esErrObject.type + '] ';
    if (esErrObject.reason) msg += esErrObject.reason;
  }

  ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.BlockedByWindowsParentalControls"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.</span>BlockedByWindowsParentalControls (msg, metadata)](#apidoc.element.elasticsearch.errors.BlockedByWindowsParentalControls)
- description and source-code
```javascript
function StatusCodeError(msg, metadata) {
  this.status = status;
  this.displayName = className;

  var esErrObject = null;
  if (_.isPlainObject(msg)) {
    esErrObject = msg;
    msg = null;
  }

  if (!esErrObject) {
    // errors from es now come in two forms, an error string < 2.0 and
    // an object >= 2.0
    // TODO: remove after dropping support for < 2.0
    ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
    return this;
  }

  msg = [].concat(esErrObject.root_cause || []).reduce(function (memo, cause) {
    if (memo) memo += ' (and) ';

    memo += '[' + cause.type + '] ' + cause.reason;

    var extraData = _.omit(cause, ['type', 'reason']);
    if (_.size(extraData)) {
      memo += ', with ' + prettyPrint(extraData);
    }

    return memo;
  }, '');

  if (!msg) {
    if (esErrObject.type) msg += '[' + esErrObject.type + '] ';
    if (esErrObject.reason) msg += esErrObject.reason;
  }

  ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.ClientClosedRequest"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.</span>ClientClosedRequest (msg, metadata)](#apidoc.element.elasticsearch.errors.ClientClosedRequest)
- description and source-code
```javascript
function StatusCodeError(msg, metadata) {
  this.status = status;
  this.displayName = className;

  var esErrObject = null;
  if (_.isPlainObject(msg)) {
    esErrObject = msg;
    msg = null;
  }

  if (!esErrObject) {
    // errors from es now come in two forms, an error string < 2.0 and
    // an object >= 2.0
    // TODO: remove after dropping support for < 2.0
    ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
    return this;
  }

  msg = [].concat(esErrObject.root_cause || []).reduce(function (memo, cause) {
    if (memo) memo += ' (and) ';

    memo += '[' + cause.type + '] ' + cause.reason;

    var extraData = _.omit(cause, ['type', 'reason']);
    if (_.size(extraData)) {
      memo += ', with ' + prettyPrint(extraData);
    }

    return memo;
  }, '');

  if (!msg) {
    if (esErrObject.type) msg += '[' + esErrObject.type + '] ';
    if (esErrObject.reason) msg += esErrObject.reason;
  }

  ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.Conflict"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.</span>Conflict (msg, metadata)](#apidoc.element.elasticsearch.errors.Conflict)
- description and source-code
```javascript
function StatusCodeError(msg, metadata) {
  this.status = status;
  this.displayName = className;

  var esErrObject = null;
  if (_.isPlainObject(msg)) {
    esErrObject = msg;
    msg = null;
  }

  if (!esErrObject) {
    // errors from es now come in two forms, an error string < 2.0 and
    // an object >= 2.0
    // TODO: remove after dropping support for < 2.0
    ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
    return this;
  }

  msg = [].concat(esErrObject.root_cause || []).reduce(function (memo, cause) {
    if (memo) memo += ' (and) ';

    memo += '[' + cause.type + '] ' + cause.reason;

    var extraData = _.omit(cause, ['type', 'reason']);
    if (_.size(extraData)) {
      memo += ', with ' + prettyPrint(extraData);
    }

    return memo;
  }, '');

  if (!msg) {
    if (esErrObject.type) msg += '[' + esErrObject.type + '] ';
    if (esErrObject.reason) msg += esErrObject.reason;
  }

  ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.ConnectionFault"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.</span>ConnectionFault (msg)](#apidoc.element.elasticsearch.errors.ConnectionFault)
- description and source-code
```javascript
function ConnectionFault(msg) {
  ErrorAbstract.call(this, msg || 'Connection Failure', errors.ConnectionFault);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.ExpectationFailed"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.</span>ExpectationFailed (msg, metadata)](#apidoc.element.elasticsearch.errors.ExpectationFailed)
- description and source-code
```javascript
function StatusCodeError(msg, metadata) {
  this.status = status;
  this.displayName = className;

  var esErrObject = null;
  if (_.isPlainObject(msg)) {
    esErrObject = msg;
    msg = null;
  }

  if (!esErrObject) {
    // errors from es now come in two forms, an error string < 2.0 and
    // an object >= 2.0
    // TODO: remove after dropping support for < 2.0
    ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
    return this;
  }

  msg = [].concat(esErrObject.root_cause || []).reduce(function (memo, cause) {
    if (memo) memo += ' (and) ';

    memo += '[' + cause.type + '] ' + cause.reason;

    var extraData = _.omit(cause, ['type', 'reason']);
    if (_.size(extraData)) {
      memo += ', with ' + prettyPrint(extraData);
    }

    return memo;
  }, '');

  if (!msg) {
    if (esErrObject.type) msg += '[' + esErrObject.type + '] ';
    if (esErrObject.reason) msg += esErrObject.reason;
  }

  ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.Forbidden"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.</span>Forbidden (msg, metadata)](#apidoc.element.elasticsearch.errors.Forbidden)
- description and source-code
```javascript
function StatusCodeError(msg, metadata) {
  this.status = status;
  this.displayName = className;

  var esErrObject = null;
  if (_.isPlainObject(msg)) {
    esErrObject = msg;
    msg = null;
  }

  if (!esErrObject) {
    // errors from es now come in two forms, an error string < 2.0 and
    // an object >= 2.0
    // TODO: remove after dropping support for < 2.0
    ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
    return this;
  }

  msg = [].concat(esErrObject.root_cause || []).reduce(function (memo, cause) {
    if (memo) memo += ' (and) ';

    memo += '[' + cause.type + '] ' + cause.reason;

    var extraData = _.omit(cause, ['type', 'reason']);
    if (_.size(extraData)) {
      memo += ', with ' + prettyPrint(extraData);
    }

    return memo;
  }, '');

  if (!msg) {
    if (esErrObject.type) msg += '[' + esErrObject.type + '] ';
    if (esErrObject.reason) msg += esErrObject.reason;
  }

  ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.Found"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.</span>Found (msg, metadata)](#apidoc.element.elasticsearch.errors.Found)
- description and source-code
```javascript
function StatusCodeError(msg, metadata) {
  this.status = status;
  this.displayName = className;

  var esErrObject = null;
  if (_.isPlainObject(msg)) {
    esErrObject = msg;
    msg = null;
  }

  if (!esErrObject) {
    // errors from es now come in two forms, an error string < 2.0 and
    // an object >= 2.0
    // TODO: remove after dropping support for < 2.0
    ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
    return this;
  }

  msg = [].concat(esErrObject.root_cause || []).reduce(function (memo, cause) {
    if (memo) memo += ' (and) ';

    memo += '[' + cause.type + '] ' + cause.reason;

    var extraData = _.omit(cause, ['type', 'reason']);
    if (_.size(extraData)) {
      memo += ', with ' + prettyPrint(extraData);
    }

    return memo;
  }, '');

  if (!msg) {
    if (esErrObject.type) msg += '[' + esErrObject.type + '] ';
    if (esErrObject.reason) msg += esErrObject.reason;
  }

  ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.GatewayTimeout"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.</span>GatewayTimeout (msg, metadata)](#apidoc.element.elasticsearch.errors.GatewayTimeout)
- description and source-code
```javascript
function StatusCodeError(msg, metadata) {
  this.status = status;
  this.displayName = className;

  var esErrObject = null;
  if (_.isPlainObject(msg)) {
    esErrObject = msg;
    msg = null;
  }

  if (!esErrObject) {
    // errors from es now come in two forms, an error string < 2.0 and
    // an object >= 2.0
    // TODO: remove after dropping support for < 2.0
    ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
    return this;
  }

  msg = [].concat(esErrObject.root_cause || []).reduce(function (memo, cause) {
    if (memo) memo += ' (and) ';

    memo += '[' + cause.type + '] ' + cause.reason;

    var extraData = _.omit(cause, ['type', 'reason']);
    if (_.size(extraData)) {
      memo += ', with ' + prettyPrint(extraData);
    }

    return memo;
  }, '');

  if (!msg) {
    if (esErrObject.type) msg += '[' + esErrObject.type + '] ';
    if (esErrObject.reason) msg += esErrObject.reason;
  }

  ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.Generic"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.</span>Generic (msg, metadata)](#apidoc.element.elasticsearch.errors.Generic)
- description and source-code
```javascript
function Generic(msg, metadata) {
  ErrorAbstract.call(this, msg || 'Generic Error', errors.Generic, metadata);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.Gone"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.</span>Gone (msg, metadata)](#apidoc.element.elasticsearch.errors.Gone)
- description and source-code
```javascript
function StatusCodeError(msg, metadata) {
  this.status = status;
  this.displayName = className;

  var esErrObject = null;
  if (_.isPlainObject(msg)) {
    esErrObject = msg;
    msg = null;
  }

  if (!esErrObject) {
    // errors from es now come in two forms, an error string < 2.0 and
    // an object >= 2.0
    // TODO: remove after dropping support for < 2.0
    ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
    return this;
  }

  msg = [].concat(esErrObject.root_cause || []).reduce(function (memo, cause) {
    if (memo) memo += ' (and) ';

    memo += '[' + cause.type + '] ' + cause.reason;

    var extraData = _.omit(cause, ['type', 'reason']);
    if (_.size(extraData)) {
      memo += ', with ' + prettyPrint(extraData);
    }

    return memo;
  }, '');

  if (!msg) {
    if (esErrObject.type) msg += '[' + esErrObject.type + '] ';
    if (esErrObject.reason) msg += esErrObject.reason;
  }

  ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.HTTPToHTTPS"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.</span>HTTPToHTTPS (msg, metadata)](#apidoc.element.elasticsearch.errors.HTTPToHTTPS)
- description and source-code
```javascript
function StatusCodeError(msg, metadata) {
  this.status = status;
  this.displayName = className;

  var esErrObject = null;
  if (_.isPlainObject(msg)) {
    esErrObject = msg;
    msg = null;
  }

  if (!esErrObject) {
    // errors from es now come in two forms, an error string < 2.0 and
    // an object >= 2.0
    // TODO: remove after dropping support for < 2.0
    ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
    return this;
  }

  msg = [].concat(esErrObject.root_cause || []).reduce(function (memo, cause) {
    if (memo) memo += ' (and) ';

    memo += '[' + cause.type + '] ' + cause.reason;

    var extraData = _.omit(cause, ['type', 'reason']);
    if (_.size(extraData)) {
      memo += ', with ' + prettyPrint(extraData);
    }

    return memo;
  }, '');

  if (!msg) {
    if (esErrObject.type) msg += '[' + esErrObject.type + '] ';
    if (esErrObject.reason) msg += esErrObject.reason;
  }

  ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.HTTPVersionNotSupported"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.</span>HTTPVersionNotSupported (msg, metadata)](#apidoc.element.elasticsearch.errors.HTTPVersionNotSupported)
- description and source-code
```javascript
function StatusCodeError(msg, metadata) {
  this.status = status;
  this.displayName = className;

  var esErrObject = null;
  if (_.isPlainObject(msg)) {
    esErrObject = msg;
    msg = null;
  }

  if (!esErrObject) {
    // errors from es now come in two forms, an error string < 2.0 and
    // an object >= 2.0
    // TODO: remove after dropping support for < 2.0
    ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
    return this;
  }

  msg = [].concat(esErrObject.root_cause || []).reduce(function (memo, cause) {
    if (memo) memo += ' (and) ';

    memo += '[' + cause.type + '] ' + cause.reason;

    var extraData = _.omit(cause, ['type', 'reason']);
    if (_.size(extraData)) {
      memo += ', with ' + prettyPrint(extraData);
    }

    return memo;
  }, '');

  if (!msg) {
    if (esErrObject.type) msg += '[' + esErrObject.type + '] ';
    if (esErrObject.reason) msg += esErrObject.reason;
  }

  ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.ImATeapot"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.</span>ImATeapot (msg, metadata)](#apidoc.element.elasticsearch.errors.ImATeapot)
- description and source-code
```javascript
function StatusCodeError(msg, metadata) {
  this.status = status;
  this.displayName = className;

  var esErrObject = null;
  if (_.isPlainObject(msg)) {
    esErrObject = msg;
    msg = null;
  }

  if (!esErrObject) {
    // errors from es now come in two forms, an error string < 2.0 and
    // an object >= 2.0
    // TODO: remove after dropping support for < 2.0
    ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
    return this;
  }

  msg = [].concat(esErrObject.root_cause || []).reduce(function (memo, cause) {
    if (memo) memo += ' (and) ';

    memo += '[' + cause.type + '] ' + cause.reason;

    var extraData = _.omit(cause, ['type', 'reason']);
    if (_.size(extraData)) {
      memo += ', with ' + prettyPrint(extraData);
    }

    return memo;
  }, '');

  if (!msg) {
    if (esErrObject.type) msg += '[' + esErrObject.type + '] ';
    if (esErrObject.reason) msg += esErrObject.reason;
  }

  ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.InternalServerError"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.</span>InternalServerError (msg, metadata)](#apidoc.element.elasticsearch.errors.InternalServerError)
- description and source-code
```javascript
function StatusCodeError(msg, metadata) {
  this.status = status;
  this.displayName = className;

  var esErrObject = null;
  if (_.isPlainObject(msg)) {
    esErrObject = msg;
    msg = null;
  }

  if (!esErrObject) {
    // errors from es now come in two forms, an error string < 2.0 and
    // an object >= 2.0
    // TODO: remove after dropping support for < 2.0
    ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
    return this;
  }

  msg = [].concat(esErrObject.root_cause || []).reduce(function (memo, cause) {
    if (memo) memo += ' (and) ';

    memo += '[' + cause.type + '] ' + cause.reason;

    var extraData = _.omit(cause, ['type', 'reason']);
    if (_.size(extraData)) {
      memo += ', with ' + prettyPrint(extraData);
    }

    return memo;
  }, '');

  if (!msg) {
    if (esErrObject.type) msg += '[' + esErrObject.type + '] ';
    if (esErrObject.reason) msg += esErrObject.reason;
  }

  ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.LengthRequired"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.</span>LengthRequired (msg, metadata)](#apidoc.element.elasticsearch.errors.LengthRequired)
- description and source-code
```javascript
function StatusCodeError(msg, metadata) {
  this.status = status;
  this.displayName = className;

  var esErrObject = null;
  if (_.isPlainObject(msg)) {
    esErrObject = msg;
    msg = null;
  }

  if (!esErrObject) {
    // errors from es now come in two forms, an error string < 2.0 and
    // an object >= 2.0
    // TODO: remove after dropping support for < 2.0
    ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
    return this;
  }

  msg = [].concat(esErrObject.root_cause || []).reduce(function (memo, cause) {
    if (memo) memo += ' (and) ';

    memo += '[' + cause.type + '] ' + cause.reason;

    var extraData = _.omit(cause, ['type', 'reason']);
    if (_.size(extraData)) {
      memo += ', with ' + prettyPrint(extraData);
    }

    return memo;
  }, '');

  if (!msg) {
    if (esErrObject.type) msg += '[' + esErrObject.type + '] ';
    if (esErrObject.reason) msg += esErrObject.reason;
  }

  ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.MethodNotAllowed"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.</span>MethodNotAllowed (msg, metadata)](#apidoc.element.elasticsearch.errors.MethodNotAllowed)
- description and source-code
```javascript
function StatusCodeError(msg, metadata) {
  this.status = status;
  this.displayName = className;

  var esErrObject = null;
  if (_.isPlainObject(msg)) {
    esErrObject = msg;
    msg = null;
  }

  if (!esErrObject) {
    // errors from es now come in two forms, an error string < 2.0 and
    // an object >= 2.0
    // TODO: remove after dropping support for < 2.0
    ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
    return this;
  }

  msg = [].concat(esErrObject.root_cause || []).reduce(function (memo, cause) {
    if (memo) memo += ' (and) ';

    memo += '[' + cause.type + '] ' + cause.reason;

    var extraData = _.omit(cause, ['type', 'reason']);
    if (_.size(extraData)) {
      memo += ', with ' + prettyPrint(extraData);
    }

    return memo;
  }, '');

  if (!msg) {
    if (esErrObject.type) msg += '[' + esErrObject.type + '] ';
    if (esErrObject.reason) msg += esErrObject.reason;
  }

  ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.MovedPermanently"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.</span>MovedPermanently (msg, metadata)](#apidoc.element.elasticsearch.errors.MovedPermanently)
- description and source-code
```javascript
function StatusCodeError(msg, metadata) {
  this.status = status;
  this.displayName = className;

  var esErrObject = null;
  if (_.isPlainObject(msg)) {
    esErrObject = msg;
    msg = null;
  }

  if (!esErrObject) {
    // errors from es now come in two forms, an error string < 2.0 and
    // an object >= 2.0
    // TODO: remove after dropping support for < 2.0
    ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
    return this;
  }

  msg = [].concat(esErrObject.root_cause || []).reduce(function (memo, cause) {
    if (memo) memo += ' (and) ';

    memo += '[' + cause.type + '] ' + cause.reason;

    var extraData = _.omit(cause, ['type', 'reason']);
    if (_.size(extraData)) {
      memo += ', with ' + prettyPrint(extraData);
    }

    return memo;
  }, '');

  if (!msg) {
    if (esErrObject.type) msg += '[' + esErrObject.type + '] ';
    if (esErrObject.reason) msg += esErrObject.reason;
  }

  ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.MultipleChoices"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.</span>MultipleChoices (msg, metadata)](#apidoc.element.elasticsearch.errors.MultipleChoices)
- description and source-code
```javascript
function StatusCodeError(msg, metadata) {
  this.status = status;
  this.displayName = className;

  var esErrObject = null;
  if (_.isPlainObject(msg)) {
    esErrObject = msg;
    msg = null;
  }

  if (!esErrObject) {
    // errors from es now come in two forms, an error string < 2.0 and
    // an object >= 2.0
    // TODO: remove after dropping support for < 2.0
    ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
    return this;
  }

  msg = [].concat(esErrObject.root_cause || []).reduce(function (memo, cause) {
    if (memo) memo += ' (and) ';

    memo += '[' + cause.type + '] ' + cause.reason;

    var extraData = _.omit(cause, ['type', 'reason']);
    if (_.size(extraData)) {
      memo += ', with ' + prettyPrint(extraData);
    }

    return memo;
  }, '');

  if (!msg) {
    if (esErrObject.type) msg += '[' + esErrObject.type + '] ';
    if (esErrObject.reason) msg += esErrObject.reason;
  }

  ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.NoConnections"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.</span>NoConnections (msg)](#apidoc.element.elasticsearch.errors.NoConnections)
- description and source-code
```javascript
function NoConnections(msg) {
  ErrorAbstract.call(this, msg || 'No Living connections', errors.NoConnections);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.NotAcceptable"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.</span>NotAcceptable (msg, metadata)](#apidoc.element.elasticsearch.errors.NotAcceptable)
- description and source-code
```javascript
function StatusCodeError(msg, metadata) {
  this.status = status;
  this.displayName = className;

  var esErrObject = null;
  if (_.isPlainObject(msg)) {
    esErrObject = msg;
    msg = null;
  }

  if (!esErrObject) {
    // errors from es now come in two forms, an error string < 2.0 and
    // an object >= 2.0
    // TODO: remove after dropping support for < 2.0
    ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
    return this;
  }

  msg = [].concat(esErrObject.root_cause || []).reduce(function (memo, cause) {
    if (memo) memo += ' (and) ';

    memo += '[' + cause.type + '] ' + cause.reason;

    var extraData = _.omit(cause, ['type', 'reason']);
    if (_.size(extraData)) {
      memo += ', with ' + prettyPrint(extraData);
    }

    return memo;
  }, '');

  if (!msg) {
    if (esErrObject.type) msg += '[' + esErrObject.type + '] ';
    if (esErrObject.reason) msg += esErrObject.reason;
  }

  ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.NotExtended"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.</span>NotExtended (msg, metadata)](#apidoc.element.elasticsearch.errors.NotExtended)
- description and source-code
```javascript
function StatusCodeError(msg, metadata) {
  this.status = status;
  this.displayName = className;

  var esErrObject = null;
  if (_.isPlainObject(msg)) {
    esErrObject = msg;
    msg = null;
  }

  if (!esErrObject) {
    // errors from es now come in two forms, an error string < 2.0 and
    // an object >= 2.0
    // TODO: remove after dropping support for < 2.0
    ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
    return this;
  }

  msg = [].concat(esErrObject.root_cause || []).reduce(function (memo, cause) {
    if (memo) memo += ' (and) ';

    memo += '[' + cause.type + '] ' + cause.reason;

    var extraData = _.omit(cause, ['type', 'reason']);
    if (_.size(extraData)) {
      memo += ', with ' + prettyPrint(extraData);
    }

    return memo;
  }, '');

  if (!msg) {
    if (esErrObject.type) msg += '[' + esErrObject.type + '] ';
    if (esErrObject.reason) msg += esErrObject.reason;
  }

  ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.NotFound"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.</span>NotFound (msg, metadata)](#apidoc.element.elasticsearch.errors.NotFound)
- description and source-code
```javascript
function StatusCodeError(msg, metadata) {
  this.status = status;
  this.displayName = className;

  var esErrObject = null;
  if (_.isPlainObject(msg)) {
    esErrObject = msg;
    msg = null;
  }

  if (!esErrObject) {
    // errors from es now come in two forms, an error string < 2.0 and
    // an object >= 2.0
    // TODO: remove after dropping support for < 2.0
    ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
    return this;
  }

  msg = [].concat(esErrObject.root_cause || []).reduce(function (memo, cause) {
    if (memo) memo += ' (and) ';

    memo += '[' + cause.type + '] ' + cause.reason;

    var extraData = _.omit(cause, ['type', 'reason']);
    if (_.size(extraData)) {
      memo += ', with ' + prettyPrint(extraData);
    }

    return memo;
  }, '');

  if (!msg) {
    if (esErrObject.type) msg += '[' + esErrObject.type + '] ';
    if (esErrObject.reason) msg += esErrObject.reason;
  }

  ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.NotImplemented"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.</span>NotImplemented (msg, metadata)](#apidoc.element.elasticsearch.errors.NotImplemented)
- description and source-code
```javascript
function StatusCodeError(msg, metadata) {
  this.status = status;
  this.displayName = className;

  var esErrObject = null;
  if (_.isPlainObject(msg)) {
    esErrObject = msg;
    msg = null;
  }

  if (!esErrObject) {
    // errors from es now come in two forms, an error string < 2.0 and
    // an object >= 2.0
    // TODO: remove after dropping support for < 2.0
    ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
    return this;
  }

  msg = [].concat(esErrObject.root_cause || []).reduce(function (memo, cause) {
    if (memo) memo += ' (and) ';

    memo += '[' + cause.type + '] ' + cause.reason;

    var extraData = _.omit(cause, ['type', 'reason']);
    if (_.size(extraData)) {
      memo += ', with ' + prettyPrint(extraData);
    }

    return memo;
  }, '');

  if (!msg) {
    if (esErrObject.type) msg += '[' + esErrObject.type + '] ';
    if (esErrObject.reason) msg += esErrObject.reason;
  }

  ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.NotModified"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.</span>NotModified (msg, metadata)](#apidoc.element.elasticsearch.errors.NotModified)
- description and source-code
```javascript
function StatusCodeError(msg, metadata) {
  this.status = status;
  this.displayName = className;

  var esErrObject = null;
  if (_.isPlainObject(msg)) {
    esErrObject = msg;
    msg = null;
  }

  if (!esErrObject) {
    // errors from es now come in two forms, an error string < 2.0 and
    // an object >= 2.0
    // TODO: remove after dropping support for < 2.0
    ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
    return this;
  }

  msg = [].concat(esErrObject.root_cause || []).reduce(function (memo, cause) {
    if (memo) memo += ' (and) ';

    memo += '[' + cause.type + '] ' + cause.reason;

    var extraData = _.omit(cause, ['type', 'reason']);
    if (_.size(extraData)) {
      memo += ', with ' + prettyPrint(extraData);
    }

    return memo;
  }, '');

  if (!msg) {
    if (esErrObject.type) msg += '[' + esErrObject.type + '] ';
    if (esErrObject.reason) msg += esErrObject.reason;
  }

  ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.PaymentRequired"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.</span>PaymentRequired (msg, metadata)](#apidoc.element.elasticsearch.errors.PaymentRequired)
- description and source-code
```javascript
function StatusCodeError(msg, metadata) {
  this.status = status;
  this.displayName = className;

  var esErrObject = null;
  if (_.isPlainObject(msg)) {
    esErrObject = msg;
    msg = null;
  }

  if (!esErrObject) {
    // errors from es now come in two forms, an error string < 2.0 and
    // an object >= 2.0
    // TODO: remove after dropping support for < 2.0
    ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
    return this;
  }

  msg = [].concat(esErrObject.root_cause || []).reduce(function (memo, cause) {
    if (memo) memo += ' (and) ';

    memo += '[' + cause.type + '] ' + cause.reason;

    var extraData = _.omit(cause, ['type', 'reason']);
    if (_.size(extraData)) {
      memo += ', with ' + prettyPrint(extraData);
    }

    return memo;
  }, '');

  if (!msg) {
    if (esErrObject.type) msg += '[' + esErrObject.type + '] ';
    if (esErrObject.reason) msg += esErrObject.reason;
  }

  ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.PermanentRedirect"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.</span>PermanentRedirect (msg, metadata)](#apidoc.element.elasticsearch.errors.PermanentRedirect)
- description and source-code
```javascript
function StatusCodeError(msg, metadata) {
  this.status = status;
  this.displayName = className;

  var esErrObject = null;
  if (_.isPlainObject(msg)) {
    esErrObject = msg;
    msg = null;
  }

  if (!esErrObject) {
    // errors from es now come in two forms, an error string < 2.0 and
    // an object >= 2.0
    // TODO: remove after dropping support for < 2.0
    ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
    return this;
  }

  msg = [].concat(esErrObject.root_cause || []).reduce(function (memo, cause) {
    if (memo) memo += ' (and) ';

    memo += '[' + cause.type + '] ' + cause.reason;

    var extraData = _.omit(cause, ['type', 'reason']);
    if (_.size(extraData)) {
      memo += ', with ' + prettyPrint(extraData);
    }

    return memo;
  }, '');

  if (!msg) {
    if (esErrObject.type) msg += '[' + esErrObject.type + '] ';
    if (esErrObject.reason) msg += esErrObject.reason;
  }

  ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.PreconditionFailed"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.</span>PreconditionFailed (msg, metadata)](#apidoc.element.elasticsearch.errors.PreconditionFailed)
- description and source-code
```javascript
function StatusCodeError(msg, metadata) {
  this.status = status;
  this.displayName = className;

  var esErrObject = null;
  if (_.isPlainObject(msg)) {
    esErrObject = msg;
    msg = null;
  }

  if (!esErrObject) {
    // errors from es now come in two forms, an error string < 2.0 and
    // an object >= 2.0
    // TODO: remove after dropping support for < 2.0
    ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
    return this;
  }

  msg = [].concat(esErrObject.root_cause || []).reduce(function (memo, cause) {
    if (memo) memo += ' (and) ';

    memo += '[' + cause.type + '] ' + cause.reason;

    var extraData = _.omit(cause, ['type', 'reason']);
    if (_.size(extraData)) {
      memo += ', with ' + prettyPrint(extraData);
    }

    return memo;
  }, '');

  if (!msg) {
    if (esErrObject.type) msg += '[' + esErrObject.type + '] ';
    if (esErrObject.reason) msg += esErrObject.reason;
  }

  ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.ProxyAuthenticationRequired"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.</span>ProxyAuthenticationRequired (msg, metadata)](#apidoc.element.elasticsearch.errors.ProxyAuthenticationRequired)
- description and source-code
```javascript
function StatusCodeError(msg, metadata) {
  this.status = status;
  this.displayName = className;

  var esErrObject = null;
  if (_.isPlainObject(msg)) {
    esErrObject = msg;
    msg = null;
  }

  if (!esErrObject) {
    // errors from es now come in two forms, an error string < 2.0 and
    // an object >= 2.0
    // TODO: remove after dropping support for < 2.0
    ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
    return this;
  }

  msg = [].concat(esErrObject.root_cause || []).reduce(function (memo, cause) {
    if (memo) memo += ' (and) ';

    memo += '[' + cause.type + '] ' + cause.reason;

    var extraData = _.omit(cause, ['type', 'reason']);
    if (_.size(extraData)) {
      memo += ', with ' + prettyPrint(extraData);
    }

    return memo;
  }, '');

  if (!msg) {
    if (esErrObject.type) msg += '[' + esErrObject.type + '] ';
    if (esErrObject.reason) msg += esErrObject.reason;
  }

  ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.RequestEntityTooLarge"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.</span>RequestEntityTooLarge (msg, metadata)](#apidoc.element.elasticsearch.errors.RequestEntityTooLarge)
- description and source-code
```javascript
function StatusCodeError(msg, metadata) {
  this.status = status;
  this.displayName = className;

  var esErrObject = null;
  if (_.isPlainObject(msg)) {
    esErrObject = msg;
    msg = null;
  }

  if (!esErrObject) {
    // errors from es now come in two forms, an error string < 2.0 and
    // an object >= 2.0
    // TODO: remove after dropping support for < 2.0
    ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
    return this;
  }

  msg = [].concat(esErrObject.root_cause || []).reduce(function (memo, cause) {
    if (memo) memo += ' (and) ';

    memo += '[' + cause.type + '] ' + cause.reason;

    var extraData = _.omit(cause, ['type', 'reason']);
    if (_.size(extraData)) {
      memo += ', with ' + prettyPrint(extraData);
    }

    return memo;
  }, '');

  if (!msg) {
    if (esErrObject.type) msg += '[' + esErrObject.type + '] ';
    if (esErrObject.reason) msg += esErrObject.reason;
  }

  ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.RequestHeaderTooLarge"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.</span>RequestHeaderTooLarge (msg, metadata)](#apidoc.element.elasticsearch.errors.RequestHeaderTooLarge)
- description and source-code
```javascript
function StatusCodeError(msg, metadata) {
  this.status = status;
  this.displayName = className;

  var esErrObject = null;
  if (_.isPlainObject(msg)) {
    esErrObject = msg;
    msg = null;
  }

  if (!esErrObject) {
    // errors from es now come in two forms, an error string < 2.0 and
    // an object >= 2.0
    // TODO: remove after dropping support for < 2.0
    ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
    return this;
  }

  msg = [].concat(esErrObject.root_cause || []).reduce(function (memo, cause) {
    if (memo) memo += ' (and) ';

    memo += '[' + cause.type + '] ' + cause.reason;

    var extraData = _.omit(cause, ['type', 'reason']);
    if (_.size(extraData)) {
      memo += ', with ' + prettyPrint(extraData);
    }

    return memo;
  }, '');

  if (!msg) {
    if (esErrObject.type) msg += '[' + esErrObject.type + '] ';
    if (esErrObject.reason) msg += esErrObject.reason;
  }

  ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.RequestTimeout"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.</span>RequestTimeout (msg, metadata)](#apidoc.element.elasticsearch.errors.RequestTimeout)
- description and source-code
```javascript
function StatusCodeError(msg, metadata) {
  this.status = status;
  this.displayName = className;

  var esErrObject = null;
  if (_.isPlainObject(msg)) {
    esErrObject = msg;
    msg = null;
  }

  if (!esErrObject) {
    // errors from es now come in two forms, an error string < 2.0 and
    // an object >= 2.0
    // TODO: remove after dropping support for < 2.0
    ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
    return this;
  }

  msg = [].concat(esErrObject.root_cause || []).reduce(function (memo, cause) {
    if (memo) memo += ' (and) ';

    memo += '[' + cause.type + '] ' + cause.reason;

    var extraData = _.omit(cause, ['type', 'reason']);
    if (_.size(extraData)) {
      memo += ', with ' + prettyPrint(extraData);
    }

    return memo;
  }, '');

  if (!msg) {
    if (esErrObject.type) msg += '[' + esErrObject.type + '] ';
    if (esErrObject.reason) msg += esErrObject.reason;
  }

  ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.RequestTypeError"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.</span>RequestTypeError (feature)](#apidoc.element.elasticsearch.errors.RequestTypeError)
- description and source-code
```javascript
function RequestTypeError(feature) {
  ErrorAbstract.call(this, 'Cross-domain AJAX requests ' + feature + ' are not supported', errors.RequestTypeError);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.RequestURITooLong"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.</span>RequestURITooLong (msg, metadata)](#apidoc.element.elasticsearch.errors.RequestURITooLong)
- description and source-code
```javascript
function StatusCodeError(msg, metadata) {
  this.status = status;
  this.displayName = className;

  var esErrObject = null;
  if (_.isPlainObject(msg)) {
    esErrObject = msg;
    msg = null;
  }

  if (!esErrObject) {
    // errors from es now come in two forms, an error string < 2.0 and
    // an object >= 2.0
    // TODO: remove after dropping support for < 2.0
    ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
    return this;
  }

  msg = [].concat(esErrObject.root_cause || []).reduce(function (memo, cause) {
    if (memo) memo += ' (and) ';

    memo += '[' + cause.type + '] ' + cause.reason;

    var extraData = _.omit(cause, ['type', 'reason']);
    if (_.size(extraData)) {
      memo += ', with ' + prettyPrint(extraData);
    }

    return memo;
  }, '');

  if (!msg) {
    if (esErrObject.type) msg += '[' + esErrObject.type + '] ';
    if (esErrObject.reason) msg += esErrObject.reason;
  }

  ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.RequestedRangeNotSatisfiable"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.</span>RequestedRangeNotSatisfiable (msg, metadata)](#apidoc.element.elasticsearch.errors.RequestedRangeNotSatisfiable)
- description and source-code
```javascript
function StatusCodeError(msg, metadata) {
  this.status = status;
  this.displayName = className;

  var esErrObject = null;
  if (_.isPlainObject(msg)) {
    esErrObject = msg;
    msg = null;
  }

  if (!esErrObject) {
    // errors from es now come in two forms, an error string < 2.0 and
    // an object >= 2.0
    // TODO: remove after dropping support for < 2.0
    ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
    return this;
  }

  msg = [].concat(esErrObject.root_cause || []).reduce(function (memo, cause) {
    if (memo) memo += ' (and) ';

    memo += '[' + cause.type + '] ' + cause.reason;

    var extraData = _.omit(cause, ['type', 'reason']);
    if (_.size(extraData)) {
      memo += ', with ' + prettyPrint(extraData);
    }

    return memo;
  }, '');

  if (!msg) {
    if (esErrObject.type) msg += '[' + esErrObject.type + '] ';
    if (esErrObject.reason) msg += esErrObject.reason;
  }

  ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.SeeOther"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.</span>SeeOther (msg, metadata)](#apidoc.element.elasticsearch.errors.SeeOther)
- description and source-code
```javascript
function StatusCodeError(msg, metadata) {
  this.status = status;
  this.displayName = className;

  var esErrObject = null;
  if (_.isPlainObject(msg)) {
    esErrObject = msg;
    msg = null;
  }

  if (!esErrObject) {
    // errors from es now come in two forms, an error string < 2.0 and
    // an object >= 2.0
    // TODO: remove after dropping support for < 2.0
    ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
    return this;
  }

  msg = [].concat(esErrObject.root_cause || []).reduce(function (memo, cause) {
    if (memo) memo += ' (and) ';

    memo += '[' + cause.type + '] ' + cause.reason;

    var extraData = _.omit(cause, ['type', 'reason']);
    if (_.size(extraData)) {
      memo += ', with ' + prettyPrint(extraData);
    }

    return memo;
  }, '');

  if (!msg) {
    if (esErrObject.type) msg += '[' + esErrObject.type + '] ';
    if (esErrObject.reason) msg += esErrObject.reason;
  }

  ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.Serialization"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.</span>Serialization (msg)](#apidoc.element.elasticsearch.errors.Serialization)
- description and source-code
```javascript
function Serialization(msg) {
  ErrorAbstract.call(this, msg || 'Unable to parse/serialize body', errors.Serialization);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.ServiceUnavailable"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.</span>ServiceUnavailable (msg, metadata)](#apidoc.element.elasticsearch.errors.ServiceUnavailable)
- description and source-code
```javascript
function StatusCodeError(msg, metadata) {
  this.status = status;
  this.displayName = className;

  var esErrObject = null;
  if (_.isPlainObject(msg)) {
    esErrObject = msg;
    msg = null;
  }

  if (!esErrObject) {
    // errors from es now come in two forms, an error string < 2.0 and
    // an object >= 2.0
    // TODO: remove after dropping support for < 2.0
    ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
    return this;
  }

  msg = [].concat(esErrObject.root_cause || []).reduce(function (memo, cause) {
    if (memo) memo += ' (and) ';

    memo += '[' + cause.type + '] ' + cause.reason;

    var extraData = _.omit(cause, ['type', 'reason']);
    if (_.size(extraData)) {
      memo += ', with ' + prettyPrint(extraData);
    }

    return memo;
  }, '');

  if (!msg) {
    if (esErrObject.type) msg += '[' + esErrObject.type + '] ';
    if (esErrObject.reason) msg += esErrObject.reason;
  }

  ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.TemporaryRedirect"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.</span>TemporaryRedirect (msg, metadata)](#apidoc.element.elasticsearch.errors.TemporaryRedirect)
- description and source-code
```javascript
function StatusCodeError(msg, metadata) {
  this.status = status;
  this.displayName = className;

  var esErrObject = null;
  if (_.isPlainObject(msg)) {
    esErrObject = msg;
    msg = null;
  }

  if (!esErrObject) {
    // errors from es now come in two forms, an error string < 2.0 and
    // an object >= 2.0
    // TODO: remove after dropping support for < 2.0
    ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
    return this;
  }

  msg = [].concat(esErrObject.root_cause || []).reduce(function (memo, cause) {
    if (memo) memo += ' (and) ';

    memo += '[' + cause.type + '] ' + cause.reason;

    var extraData = _.omit(cause, ['type', 'reason']);
    if (_.size(extraData)) {
      memo += ', with ' + prettyPrint(extraData);
    }

    return memo;
  }, '');

  if (!msg) {
    if (esErrObject.type) msg += '[' + esErrObject.type + '] ';
    if (esErrObject.reason) msg += esErrObject.reason;
  }

  ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.TooManyConnectionsFromThisIP"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.</span>TooManyConnectionsFromThisIP (msg, metadata)](#apidoc.element.elasticsearch.errors.TooManyConnectionsFromThisIP)
- description and source-code
```javascript
function StatusCodeError(msg, metadata) {
  this.status = status;
  this.displayName = className;

  var esErrObject = null;
  if (_.isPlainObject(msg)) {
    esErrObject = msg;
    msg = null;
  }

  if (!esErrObject) {
    // errors from es now come in two forms, an error string < 2.0 and
    // an object >= 2.0
    // TODO: remove after dropping support for < 2.0
    ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
    return this;
  }

  msg = [].concat(esErrObject.root_cause || []).reduce(function (memo, cause) {
    if (memo) memo += ' (and) ';

    memo += '[' + cause.type + '] ' + cause.reason;

    var extraData = _.omit(cause, ['type', 'reason']);
    if (_.size(extraData)) {
      memo += ', with ' + prettyPrint(extraData);
    }

    return memo;
  }, '');

  if (!msg) {
    if (esErrObject.type) msg += '[' + esErrObject.type + '] ';
    if (esErrObject.reason) msg += esErrObject.reason;
  }

  ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.TooManyRequests"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.</span>TooManyRequests (msg, metadata)](#apidoc.element.elasticsearch.errors.TooManyRequests)
- description and source-code
```javascript
function StatusCodeError(msg, metadata) {
  this.status = status;
  this.displayName = className;

  var esErrObject = null;
  if (_.isPlainObject(msg)) {
    esErrObject = msg;
    msg = null;
  }

  if (!esErrObject) {
    // errors from es now come in two forms, an error string < 2.0 and
    // an object >= 2.0
    // TODO: remove after dropping support for < 2.0
    ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
    return this;
  }

  msg = [].concat(esErrObject.root_cause || []).reduce(function (memo, cause) {
    if (memo) memo += ' (and) ';

    memo += '[' + cause.type + '] ' + cause.reason;

    var extraData = _.omit(cause, ['type', 'reason']);
    if (_.size(extraData)) {
      memo += ', with ' + prettyPrint(extraData);
    }

    return memo;
  }, '');

  if (!msg) {
    if (esErrObject.type) msg += '[' + esErrObject.type + '] ';
    if (esErrObject.reason) msg += esErrObject.reason;
  }

  ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.UnsupportedMediaType"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.</span>UnsupportedMediaType (msg, metadata)](#apidoc.element.elasticsearch.errors.UnsupportedMediaType)
- description and source-code
```javascript
function StatusCodeError(msg, metadata) {
  this.status = status;
  this.displayName = className;

  var esErrObject = null;
  if (_.isPlainObject(msg)) {
    esErrObject = msg;
    msg = null;
  }

  if (!esErrObject) {
    // errors from es now come in two forms, an error string < 2.0 and
    // an object >= 2.0
    // TODO: remove after dropping support for < 2.0
    ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
    return this;
  }

  msg = [].concat(esErrObject.root_cause || []).reduce(function (memo, cause) {
    if (memo) memo += ' (and) ';

    memo += '[' + cause.type + '] ' + cause.reason;

    var extraData = _.omit(cause, ['type', 'reason']);
    if (_.size(extraData)) {
      memo += ', with ' + prettyPrint(extraData);
    }

    return memo;
  }, '');

  if (!msg) {
    if (esErrObject.type) msg += '[' + esErrObject.type + '] ';
    if (esErrObject.reason) msg += esErrObject.reason;
  }

  ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.UpgradeRequired"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.</span>UpgradeRequired (msg, metadata)](#apidoc.element.elasticsearch.errors.UpgradeRequired)
- description and source-code
```javascript
function StatusCodeError(msg, metadata) {
  this.status = status;
  this.displayName = className;

  var esErrObject = null;
  if (_.isPlainObject(msg)) {
    esErrObject = msg;
    msg = null;
  }

  if (!esErrObject) {
    // errors from es now come in two forms, an error string < 2.0 and
    // an object >= 2.0
    // TODO: remove after dropping support for < 2.0
    ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
    return this;
  }

  msg = [].concat(esErrObject.root_cause || []).reduce(function (memo, cause) {
    if (memo) memo += ' (and) ';

    memo += '[' + cause.type + '] ' + cause.reason;

    var extraData = _.omit(cause, ['type', 'reason']);
    if (_.size(extraData)) {
      memo += ', with ' + prettyPrint(extraData);
    }

    return memo;
  }, '');

  if (!msg) {
    if (esErrObject.type) msg += '[' + esErrObject.type + '] ';
    if (esErrObject.reason) msg += esErrObject.reason;
  }

  ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.UseProxy"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.</span>UseProxy (msg, metadata)](#apidoc.element.elasticsearch.errors.UseProxy)
- description and source-code
```javascript
function StatusCodeError(msg, metadata) {
  this.status = status;
  this.displayName = className;

  var esErrObject = null;
  if (_.isPlainObject(msg)) {
    esErrObject = msg;
    msg = null;
  }

  if (!esErrObject) {
    // errors from es now come in two forms, an error string < 2.0 and
    // an object >= 2.0
    // TODO: remove after dropping support for < 2.0
    ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
    return this;
  }

  msg = [].concat(esErrObject.root_cause || []).reduce(function (memo, cause) {
    if (memo) memo += ' (and) ';

    memo += '[' + cause.type + '] ' + cause.reason;

    var extraData = _.omit(cause, ['type', 'reason']);
    if (_.size(extraData)) {
      memo += ', with ' + prettyPrint(extraData);
    }

    return memo;
  }, '');

  if (!msg) {
    if (esErrObject.type) msg += '[' + esErrObject.type + '] ';
    if (esErrObject.reason) msg += esErrObject.reason;
  }

  ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.VariantAlsoNegotiates"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.</span>VariantAlsoNegotiates (msg, metadata)](#apidoc.element.elasticsearch.errors.VariantAlsoNegotiates)
- description and source-code
```javascript
function StatusCodeError(msg, metadata) {
  this.status = status;
  this.displayName = className;

  var esErrObject = null;
  if (_.isPlainObject(msg)) {
    esErrObject = msg;
    msg = null;
  }

  if (!esErrObject) {
    // errors from es now come in two forms, an error string < 2.0 and
    // an object >= 2.0
    // TODO: remove after dropping support for < 2.0
    ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
    return this;
  }

  msg = [].concat(esErrObject.root_cause || []).reduce(function (memo, cause) {
    if (memo) memo += ' (and) ';

    memo += '[' + cause.type + '] ' + cause.reason;

    var extraData = _.omit(cause, ['type', 'reason']);
    if (_.size(extraData)) {
      memo += ', with ' + prettyPrint(extraData);
    }

    return memo;
  }, '');

  if (!msg) {
    if (esErrObject.type) msg += '[' + esErrObject.type + '] ';
    if (esErrObject.reason) msg += esErrObject.reason;
  }

  ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors._Abstract"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.</span>_Abstract (msg, constructor, metadata)](#apidoc.element.elasticsearch.errors._Abstract)
- description and source-code
```javascript
function ErrorAbstract(msg, constructor, metadata) {
  this.message = msg;

  Error.call(this, this.message);

  if (canCapture) {
    Error.captureStackTrace(this, constructor);
  }
  else if (canStack) {
    this.stack = (new Error()).stack;
  }
  else {
    this.stack = '';
  }

  if (metadata) {
    _.assign(this, metadata);

    this.toString = function () {
      return msg + ' :: ' + JSON.stringify(metadata);
    };

    this.toJSON = function () {
      return _.assign({
        msg: msg
      }, metadata);
    };
  }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.elasticsearch.errors.300"></a>[module elasticsearch.errors.300](#apidoc.module.elasticsearch.errors.300)

#### <a name="apidoc.element.elasticsearch.errors.300.super_"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.300.</span>super_ (msg, constructor, metadata)](#apidoc.element.elasticsearch.errors.300.super_)
- description and source-code
```javascript
function ErrorAbstract(msg, constructor, metadata) {
  this.message = msg;

  Error.call(this, this.message);

  if (canCapture) {
    Error.captureStackTrace(this, constructor);
  }
  else if (canStack) {
    this.stack = (new Error()).stack;
  }
  else {
    this.stack = '';
  }

  if (metadata) {
    _.assign(this, metadata);

    this.toString = function () {
      return msg + ' :: ' + JSON.stringify(metadata);
    };

    this.toJSON = function () {
      return _.assign({
        msg: msg
      }, metadata);
    };
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.300.300"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.</span>300 (msg, metadata)](#apidoc.element.elasticsearch.errors.300.300)
- description and source-code
```javascript
function StatusCodeError(msg, metadata) {
  this.status = status;
  this.displayName = className;

  var esErrObject = null;
  if (_.isPlainObject(msg)) {
    esErrObject = msg;
    msg = null;
  }

  if (!esErrObject) {
    // errors from es now come in two forms, an error string < 2.0 and
    // an object >= 2.0
    // TODO: remove after dropping support for < 2.0
    ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
    return this;
  }

  msg = [].concat(esErrObject.root_cause || []).reduce(function (memo, cause) {
    if (memo) memo += ' (and) ';

    memo += '[' + cause.type + '] ' + cause.reason;

    var extraData = _.omit(cause, ['type', 'reason']);
    if (_.size(extraData)) {
      memo += ', with ' + prettyPrint(extraData);
    }

    return memo;
  }, '');

  if (!msg) {
    if (esErrObject.type) msg += '[' + esErrObject.type + '] ';
    if (esErrObject.reason) msg += esErrObject.reason;
  }

  ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
  return this;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.elasticsearch.errors.301"></a>[module elasticsearch.errors.301](#apidoc.module.elasticsearch.errors.301)

#### <a name="apidoc.element.elasticsearch.errors.301.super_"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.301.</span>super_ (msg, constructor, metadata)](#apidoc.element.elasticsearch.errors.301.super_)
- description and source-code
```javascript
function ErrorAbstract(msg, constructor, metadata) {
  this.message = msg;

  Error.call(this, this.message);

  if (canCapture) {
    Error.captureStackTrace(this, constructor);
  }
  else if (canStack) {
    this.stack = (new Error()).stack;
  }
  else {
    this.stack = '';
  }

  if (metadata) {
    _.assign(this, metadata);

    this.toString = function () {
      return msg + ' :: ' + JSON.stringify(metadata);
    };

    this.toJSON = function () {
      return _.assign({
        msg: msg
      }, metadata);
    };
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.301.301"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.</span>301 (msg, metadata)](#apidoc.element.elasticsearch.errors.301.301)
- description and source-code
```javascript
function StatusCodeError(msg, metadata) {
  this.status = status;
  this.displayName = className;

  var esErrObject = null;
  if (_.isPlainObject(msg)) {
    esErrObject = msg;
    msg = null;
  }

  if (!esErrObject) {
    // errors from es now come in two forms, an error string < 2.0 and
    // an object >= 2.0
    // TODO: remove after dropping support for < 2.0
    ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
    return this;
  }

  msg = [].concat(esErrObject.root_cause || []).reduce(function (memo, cause) {
    if (memo) memo += ' (and) ';

    memo += '[' + cause.type + '] ' + cause.reason;

    var extraData = _.omit(cause, ['type', 'reason']);
    if (_.size(extraData)) {
      memo += ', with ' + prettyPrint(extraData);
    }

    return memo;
  }, '');

  if (!msg) {
    if (esErrObject.type) msg += '[' + esErrObject.type + '] ';
    if (esErrObject.reason) msg += esErrObject.reason;
  }

  ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
  return this;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.elasticsearch.errors.302"></a>[module elasticsearch.errors.302](#apidoc.module.elasticsearch.errors.302)

#### <a name="apidoc.element.elasticsearch.errors.302.super_"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.302.</span>super_ (msg, constructor, metadata)](#apidoc.element.elasticsearch.errors.302.super_)
- description and source-code
```javascript
function ErrorAbstract(msg, constructor, metadata) {
  this.message = msg;

  Error.call(this, this.message);

  if (canCapture) {
    Error.captureStackTrace(this, constructor);
  }
  else if (canStack) {
    this.stack = (new Error()).stack;
  }
  else {
    this.stack = '';
  }

  if (metadata) {
    _.assign(this, metadata);

    this.toString = function () {
      return msg + ' :: ' + JSON.stringify(metadata);
    };

    this.toJSON = function () {
      return _.assign({
        msg: msg
      }, metadata);
    };
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.302.302"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.</span>302 (msg, metadata)](#apidoc.element.elasticsearch.errors.302.302)
- description and source-code
```javascript
function StatusCodeError(msg, metadata) {
  this.status = status;
  this.displayName = className;

  var esErrObject = null;
  if (_.isPlainObject(msg)) {
    esErrObject = msg;
    msg = null;
  }

  if (!esErrObject) {
    // errors from es now come in two forms, an error string < 2.0 and
    // an object >= 2.0
    // TODO: remove after dropping support for < 2.0
    ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
    return this;
  }

  msg = [].concat(esErrObject.root_cause || []).reduce(function (memo, cause) {
    if (memo) memo += ' (and) ';

    memo += '[' + cause.type + '] ' + cause.reason;

    var extraData = _.omit(cause, ['type', 'reason']);
    if (_.size(extraData)) {
      memo += ', with ' + prettyPrint(extraData);
    }

    return memo;
  }, '');

  if (!msg) {
    if (esErrObject.type) msg += '[' + esErrObject.type + '] ';
    if (esErrObject.reason) msg += esErrObject.reason;
  }

  ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
  return this;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.elasticsearch.errors.303"></a>[module elasticsearch.errors.303](#apidoc.module.elasticsearch.errors.303)

#### <a name="apidoc.element.elasticsearch.errors.303.super_"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.303.</span>super_ (msg, constructor, metadata)](#apidoc.element.elasticsearch.errors.303.super_)
- description and source-code
```javascript
function ErrorAbstract(msg, constructor, metadata) {
  this.message = msg;

  Error.call(this, this.message);

  if (canCapture) {
    Error.captureStackTrace(this, constructor);
  }
  else if (canStack) {
    this.stack = (new Error()).stack;
  }
  else {
    this.stack = '';
  }

  if (metadata) {
    _.assign(this, metadata);

    this.toString = function () {
      return msg + ' :: ' + JSON.stringify(metadata);
    };

    this.toJSON = function () {
      return _.assign({
        msg: msg
      }, metadata);
    };
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.303.303"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.</span>303 (msg, metadata)](#apidoc.element.elasticsearch.errors.303.303)
- description and source-code
```javascript
function StatusCodeError(msg, metadata) {
  this.status = status;
  this.displayName = className;

  var esErrObject = null;
  if (_.isPlainObject(msg)) {
    esErrObject = msg;
    msg = null;
  }

  if (!esErrObject) {
    // errors from es now come in two forms, an error string < 2.0 and
    // an object >= 2.0
    // TODO: remove after dropping support for < 2.0
    ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
    return this;
  }

  msg = [].concat(esErrObject.root_cause || []).reduce(function (memo, cause) {
    if (memo) memo += ' (and) ';

    memo += '[' + cause.type + '] ' + cause.reason;

    var extraData = _.omit(cause, ['type', 'reason']);
    if (_.size(extraData)) {
      memo += ', with ' + prettyPrint(extraData);
    }

    return memo;
  }, '');

  if (!msg) {
    if (esErrObject.type) msg += '[' + esErrObject.type + '] ';
    if (esErrObject.reason) msg += esErrObject.reason;
  }

  ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
  return this;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.elasticsearch.errors.304"></a>[module elasticsearch.errors.304](#apidoc.module.elasticsearch.errors.304)

#### <a name="apidoc.element.elasticsearch.errors.304.super_"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.304.</span>super_ (msg, constructor, metadata)](#apidoc.element.elasticsearch.errors.304.super_)
- description and source-code
```javascript
function ErrorAbstract(msg, constructor, metadata) {
  this.message = msg;

  Error.call(this, this.message);

  if (canCapture) {
    Error.captureStackTrace(this, constructor);
  }
  else if (canStack) {
    this.stack = (new Error()).stack;
  }
  else {
    this.stack = '';
  }

  if (metadata) {
    _.assign(this, metadata);

    this.toString = function () {
      return msg + ' :: ' + JSON.stringify(metadata);
    };

    this.toJSON = function () {
      return _.assign({
        msg: msg
      }, metadata);
    };
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.304.304"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.</span>304 (msg, metadata)](#apidoc.element.elasticsearch.errors.304.304)
- description and source-code
```javascript
function StatusCodeError(msg, metadata) {
  this.status = status;
  this.displayName = className;

  var esErrObject = null;
  if (_.isPlainObject(msg)) {
    esErrObject = msg;
    msg = null;
  }

  if (!esErrObject) {
    // errors from es now come in two forms, an error string < 2.0 and
    // an object >= 2.0
    // TODO: remove after dropping support for < 2.0
    ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
    return this;
  }

  msg = [].concat(esErrObject.root_cause || []).reduce(function (memo, cause) {
    if (memo) memo += ' (and) ';

    memo += '[' + cause.type + '] ' + cause.reason;

    var extraData = _.omit(cause, ['type', 'reason']);
    if (_.size(extraData)) {
      memo += ', with ' + prettyPrint(extraData);
    }

    return memo;
  }, '');

  if (!msg) {
    if (esErrObject.type) msg += '[' + esErrObject.type + '] ';
    if (esErrObject.reason) msg += esErrObject.reason;
  }

  ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
  return this;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.elasticsearch.errors.305"></a>[module elasticsearch.errors.305](#apidoc.module.elasticsearch.errors.305)

#### <a name="apidoc.element.elasticsearch.errors.305.super_"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.305.</span>super_ (msg, constructor, metadata)](#apidoc.element.elasticsearch.errors.305.super_)
- description and source-code
```javascript
function ErrorAbstract(msg, constructor, metadata) {
  this.message = msg;

  Error.call(this, this.message);

  if (canCapture) {
    Error.captureStackTrace(this, constructor);
  }
  else if (canStack) {
    this.stack = (new Error()).stack;
  }
  else {
    this.stack = '';
  }

  if (metadata) {
    _.assign(this, metadata);

    this.toString = function () {
      return msg + ' :: ' + JSON.stringify(metadata);
    };

    this.toJSON = function () {
      return _.assign({
        msg: msg
      }, metadata);
    };
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.305.305"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.</span>305 (msg, metadata)](#apidoc.element.elasticsearch.errors.305.305)
- description and source-code
```javascript
function StatusCodeError(msg, metadata) {
  this.status = status;
  this.displayName = className;

  var esErrObject = null;
  if (_.isPlainObject(msg)) {
    esErrObject = msg;
    msg = null;
  }

  if (!esErrObject) {
    // errors from es now come in two forms, an error string < 2.0 and
    // an object >= 2.0
    // TODO: remove after dropping support for < 2.0
    ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
    return this;
  }

  msg = [].concat(esErrObject.root_cause || []).reduce(function (memo, cause) {
    if (memo) memo += ' (and) ';

    memo += '[' + cause.type + '] ' + cause.reason;

    var extraData = _.omit(cause, ['type', 'reason']);
    if (_.size(extraData)) {
      memo += ', with ' + prettyPrint(extraData);
    }

    return memo;
  }, '');

  if (!msg) {
    if (esErrObject.type) msg += '[' + esErrObject.type + '] ';
    if (esErrObject.reason) msg += esErrObject.reason;
  }

  ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
  return this;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.elasticsearch.errors.307"></a>[module elasticsearch.errors.307](#apidoc.module.elasticsearch.errors.307)

#### <a name="apidoc.element.elasticsearch.errors.307.super_"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.307.</span>super_ (msg, constructor, metadata)](#apidoc.element.elasticsearch.errors.307.super_)
- description and source-code
```javascript
function ErrorAbstract(msg, constructor, metadata) {
  this.message = msg;

  Error.call(this, this.message);

  if (canCapture) {
    Error.captureStackTrace(this, constructor);
  }
  else if (canStack) {
    this.stack = (new Error()).stack;
  }
  else {
    this.stack = '';
  }

  if (metadata) {
    _.assign(this, metadata);

    this.toString = function () {
      return msg + ' :: ' + JSON.stringify(metadata);
    };

    this.toJSON = function () {
      return _.assign({
        msg: msg
      }, metadata);
    };
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.307.307"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.</span>307 (msg, metadata)](#apidoc.element.elasticsearch.errors.307.307)
- description and source-code
```javascript
function StatusCodeError(msg, metadata) {
  this.status = status;
  this.displayName = className;

  var esErrObject = null;
  if (_.isPlainObject(msg)) {
    esErrObject = msg;
    msg = null;
  }

  if (!esErrObject) {
    // errors from es now come in two forms, an error string < 2.0 and
    // an object >= 2.0
    // TODO: remove after dropping support for < 2.0
    ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
    return this;
  }

  msg = [].concat(esErrObject.root_cause || []).reduce(function (memo, cause) {
    if (memo) memo += ' (and) ';

    memo += '[' + cause.type + '] ' + cause.reason;

    var extraData = _.omit(cause, ['type', 'reason']);
    if (_.size(extraData)) {
      memo += ', with ' + prettyPrint(extraData);
    }

    return memo;
  }, '');

  if (!msg) {
    if (esErrObject.type) msg += '[' + esErrObject.type + '] ';
    if (esErrObject.reason) msg += esErrObject.reason;
  }

  ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
  return this;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.elasticsearch.errors.308"></a>[module elasticsearch.errors.308](#apidoc.module.elasticsearch.errors.308)

#### <a name="apidoc.element.elasticsearch.errors.308.super_"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.308.</span>super_ (msg, constructor, metadata)](#apidoc.element.elasticsearch.errors.308.super_)
- description and source-code
```javascript
function ErrorAbstract(msg, constructor, metadata) {
  this.message = msg;

  Error.call(this, this.message);

  if (canCapture) {
    Error.captureStackTrace(this, constructor);
  }
  else if (canStack) {
    this.stack = (new Error()).stack;
  }
  else {
    this.stack = '';
  }

  if (metadata) {
    _.assign(this, metadata);

    this.toString = function () {
      return msg + ' :: ' + JSON.stringify(metadata);
    };

    this.toJSON = function () {
      return _.assign({
        msg: msg
      }, metadata);
    };
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.308.308"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.</span>308 (msg, metadata)](#apidoc.element.elasticsearch.errors.308.308)
- description and source-code
```javascript
function StatusCodeError(msg, metadata) {
  this.status = status;
  this.displayName = className;

  var esErrObject = null;
  if (_.isPlainObject(msg)) {
    esErrObject = msg;
    msg = null;
  }

  if (!esErrObject) {
    // errors from es now come in two forms, an error string < 2.0 and
    // an object >= 2.0
    // TODO: remove after dropping support for < 2.0
    ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
    return this;
  }

  msg = [].concat(esErrObject.root_cause || []).reduce(function (memo, cause) {
    if (memo) memo += ' (and) ';

    memo += '[' + cause.type + '] ' + cause.reason;

    var extraData = _.omit(cause, ['type', 'reason']);
    if (_.size(extraData)) {
      memo += ', with ' + prettyPrint(extraData);
    }

    return memo;
  }, '');

  if (!msg) {
    if (esErrObject.type) msg += '[' + esErrObject.type + '] ';
    if (esErrObject.reason) msg += esErrObject.reason;
  }

  ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
  return this;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.elasticsearch.errors.400"></a>[module elasticsearch.errors.400](#apidoc.module.elasticsearch.errors.400)

#### <a name="apidoc.element.elasticsearch.errors.400.super_"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.400.</span>super_ (msg, constructor, metadata)](#apidoc.element.elasticsearch.errors.400.super_)
- description and source-code
```javascript
function ErrorAbstract(msg, constructor, metadata) {
  this.message = msg;

  Error.call(this, this.message);

  if (canCapture) {
    Error.captureStackTrace(this, constructor);
  }
  else if (canStack) {
    this.stack = (new Error()).stack;
  }
  else {
    this.stack = '';
  }

  if (metadata) {
    _.assign(this, metadata);

    this.toString = function () {
      return msg + ' :: ' + JSON.stringify(metadata);
    };

    this.toJSON = function () {
      return _.assign({
        msg: msg
      }, metadata);
    };
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.400.400"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.</span>400 (msg, metadata)](#apidoc.element.elasticsearch.errors.400.400)
- description and source-code
```javascript
function StatusCodeError(msg, metadata) {
  this.status = status;
  this.displayName = className;

  var esErrObject = null;
  if (_.isPlainObject(msg)) {
    esErrObject = msg;
    msg = null;
  }

  if (!esErrObject) {
    // errors from es now come in two forms, an error string < 2.0 and
    // an object >= 2.0
    // TODO: remove after dropping support for < 2.0
    ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
    return this;
  }

  msg = [].concat(esErrObject.root_cause || []).reduce(function (memo, cause) {
    if (memo) memo += ' (and) ';

    memo += '[' + cause.type + '] ' + cause.reason;

    var extraData = _.omit(cause, ['type', 'reason']);
    if (_.size(extraData)) {
      memo += ', with ' + prettyPrint(extraData);
    }

    return memo;
  }, '');

  if (!msg) {
    if (esErrObject.type) msg += '[' + esErrObject.type + '] ';
    if (esErrObject.reason) msg += esErrObject.reason;
  }

  ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
  return this;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.elasticsearch.errors.401"></a>[module elasticsearch.errors.401](#apidoc.module.elasticsearch.errors.401)

#### <a name="apidoc.element.elasticsearch.errors.401.super_"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.401.</span>super_ (msg, constructor, metadata)](#apidoc.element.elasticsearch.errors.401.super_)
- description and source-code
```javascript
function ErrorAbstract(msg, constructor, metadata) {
  this.message = msg;

  Error.call(this, this.message);

  if (canCapture) {
    Error.captureStackTrace(this, constructor);
  }
  else if (canStack) {
    this.stack = (new Error()).stack;
  }
  else {
    this.stack = '';
  }

  if (metadata) {
    _.assign(this, metadata);

    this.toString = function () {
      return msg + ' :: ' + JSON.stringify(metadata);
    };

    this.toJSON = function () {
      return _.assign({
        msg: msg
      }, metadata);
    };
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.401.401"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.</span>401 (msg, metadata)](#apidoc.element.elasticsearch.errors.401.401)
- description and source-code
```javascript
function StatusCodeError(msg, metadata) {
  this.status = status;
  this.displayName = className;

  var esErrObject = null;
  if (_.isPlainObject(msg)) {
    esErrObject = msg;
    msg = null;
  }

  if (!esErrObject) {
    // errors from es now come in two forms, an error string < 2.0 and
    // an object >= 2.0
    // TODO: remove after dropping support for < 2.0
    ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
    return this;
  }

  msg = [].concat(esErrObject.root_cause || []).reduce(function (memo, cause) {
    if (memo) memo += ' (and) ';

    memo += '[' + cause.type + '] ' + cause.reason;

    var extraData = _.omit(cause, ['type', 'reason']);
    if (_.size(extraData)) {
      memo += ', with ' + prettyPrint(extraData);
    }

    return memo;
  }, '');

  if (!msg) {
    if (esErrObject.type) msg += '[' + esErrObject.type + '] ';
    if (esErrObject.reason) msg += esErrObject.reason;
  }

  ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
  return this;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.elasticsearch.errors.402"></a>[module elasticsearch.errors.402](#apidoc.module.elasticsearch.errors.402)

#### <a name="apidoc.element.elasticsearch.errors.402.super_"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.402.</span>super_ (msg, constructor, metadata)](#apidoc.element.elasticsearch.errors.402.super_)
- description and source-code
```javascript
function ErrorAbstract(msg, constructor, metadata) {
  this.message = msg;

  Error.call(this, this.message);

  if (canCapture) {
    Error.captureStackTrace(this, constructor);
  }
  else if (canStack) {
    this.stack = (new Error()).stack;
  }
  else {
    this.stack = '';
  }

  if (metadata) {
    _.assign(this, metadata);

    this.toString = function () {
      return msg + ' :: ' + JSON.stringify(metadata);
    };

    this.toJSON = function () {
      return _.assign({
        msg: msg
      }, metadata);
    };
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.402.402"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.</span>402 (msg, metadata)](#apidoc.element.elasticsearch.errors.402.402)
- description and source-code
```javascript
function StatusCodeError(msg, metadata) {
  this.status = status;
  this.displayName = className;

  var esErrObject = null;
  if (_.isPlainObject(msg)) {
    esErrObject = msg;
    msg = null;
  }

  if (!esErrObject) {
    // errors from es now come in two forms, an error string < 2.0 and
    // an object >= 2.0
    // TODO: remove after dropping support for < 2.0
    ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
    return this;
  }

  msg = [].concat(esErrObject.root_cause || []).reduce(function (memo, cause) {
    if (memo) memo += ' (and) ';

    memo += '[' + cause.type + '] ' + cause.reason;

    var extraData = _.omit(cause, ['type', 'reason']);
    if (_.size(extraData)) {
      memo += ', with ' + prettyPrint(extraData);
    }

    return memo;
  }, '');

  if (!msg) {
    if (esErrObject.type) msg += '[' + esErrObject.type + '] ';
    if (esErrObject.reason) msg += esErrObject.reason;
  }

  ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
  return this;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.elasticsearch.errors.403"></a>[module elasticsearch.errors.403](#apidoc.module.elasticsearch.errors.403)

#### <a name="apidoc.element.elasticsearch.errors.403.super_"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.403.</span>super_ (msg, constructor, metadata)](#apidoc.element.elasticsearch.errors.403.super_)
- description and source-code
```javascript
function ErrorAbstract(msg, constructor, metadata) {
  this.message = msg;

  Error.call(this, this.message);

  if (canCapture) {
    Error.captureStackTrace(this, constructor);
  }
  else if (canStack) {
    this.stack = (new Error()).stack;
  }
  else {
    this.stack = '';
  }

  if (metadata) {
    _.assign(this, metadata);

    this.toString = function () {
      return msg + ' :: ' + JSON.stringify(metadata);
    };

    this.toJSON = function () {
      return _.assign({
        msg: msg
      }, metadata);
    };
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.403.403"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.</span>403 (msg, metadata)](#apidoc.element.elasticsearch.errors.403.403)
- description and source-code
```javascript
function StatusCodeError(msg, metadata) {
  this.status = status;
  this.displayName = className;

  var esErrObject = null;
  if (_.isPlainObject(msg)) {
    esErrObject = msg;
    msg = null;
  }

  if (!esErrObject) {
    // errors from es now come in two forms, an error string < 2.0 and
    // an object >= 2.0
    // TODO: remove after dropping support for < 2.0
    ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
    return this;
  }

  msg = [].concat(esErrObject.root_cause || []).reduce(function (memo, cause) {
    if (memo) memo += ' (and) ';

    memo += '[' + cause.type + '] ' + cause.reason;

    var extraData = _.omit(cause, ['type', 'reason']);
    if (_.size(extraData)) {
      memo += ', with ' + prettyPrint(extraData);
    }

    return memo;
  }, '');

  if (!msg) {
    if (esErrObject.type) msg += '[' + esErrObject.type + '] ';
    if (esErrObject.reason) msg += esErrObject.reason;
  }

  ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
  return this;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.elasticsearch.errors.404"></a>[module elasticsearch.errors.404](#apidoc.module.elasticsearch.errors.404)

#### <a name="apidoc.element.elasticsearch.errors.404.super_"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.404.</span>super_ (msg, constructor, metadata)](#apidoc.element.elasticsearch.errors.404.super_)
- description and source-code
```javascript
function ErrorAbstract(msg, constructor, metadata) {
  this.message = msg;

  Error.call(this, this.message);

  if (canCapture) {
    Error.captureStackTrace(this, constructor);
  }
  else if (canStack) {
    this.stack = (new Error()).stack;
  }
  else {
    this.stack = '';
  }

  if (metadata) {
    _.assign(this, metadata);

    this.toString = function () {
      return msg + ' :: ' + JSON.stringify(metadata);
    };

    this.toJSON = function () {
      return _.assign({
        msg: msg
      }, metadata);
    };
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.404.404"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.</span>404 (msg, metadata)](#apidoc.element.elasticsearch.errors.404.404)
- description and source-code
```javascript
function StatusCodeError(msg, metadata) {
  this.status = status;
  this.displayName = className;

  var esErrObject = null;
  if (_.isPlainObject(msg)) {
    esErrObject = msg;
    msg = null;
  }

  if (!esErrObject) {
    // errors from es now come in two forms, an error string < 2.0 and
    // an object >= 2.0
    // TODO: remove after dropping support for < 2.0
    ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
    return this;
  }

  msg = [].concat(esErrObject.root_cause || []).reduce(function (memo, cause) {
    if (memo) memo += ' (and) ';

    memo += '[' + cause.type + '] ' + cause.reason;

    var extraData = _.omit(cause, ['type', 'reason']);
    if (_.size(extraData)) {
      memo += ', with ' + prettyPrint(extraData);
    }

    return memo;
  }, '');

  if (!msg) {
    if (esErrObject.type) msg += '[' + esErrObject.type + '] ';
    if (esErrObject.reason) msg += esErrObject.reason;
  }

  ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
  return this;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.elasticsearch.errors.405"></a>[module elasticsearch.errors.405](#apidoc.module.elasticsearch.errors.405)

#### <a name="apidoc.element.elasticsearch.errors.405.super_"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.405.</span>super_ (msg, constructor, metadata)](#apidoc.element.elasticsearch.errors.405.super_)
- description and source-code
```javascript
function ErrorAbstract(msg, constructor, metadata) {
  this.message = msg;

  Error.call(this, this.message);

  if (canCapture) {
    Error.captureStackTrace(this, constructor);
  }
  else if (canStack) {
    this.stack = (new Error()).stack;
  }
  else {
    this.stack = '';
  }

  if (metadata) {
    _.assign(this, metadata);

    this.toString = function () {
      return msg + ' :: ' + JSON.stringify(metadata);
    };

    this.toJSON = function () {
      return _.assign({
        msg: msg
      }, metadata);
    };
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.405.405"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.</span>405 (msg, metadata)](#apidoc.element.elasticsearch.errors.405.405)
- description and source-code
```javascript
function StatusCodeError(msg, metadata) {
  this.status = status;
  this.displayName = className;

  var esErrObject = null;
  if (_.isPlainObject(msg)) {
    esErrObject = msg;
    msg = null;
  }

  if (!esErrObject) {
    // errors from es now come in two forms, an error string < 2.0 and
    // an object >= 2.0
    // TODO: remove after dropping support for < 2.0
    ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
    return this;
  }

  msg = [].concat(esErrObject.root_cause || []).reduce(function (memo, cause) {
    if (memo) memo += ' (and) ';

    memo += '[' + cause.type + '] ' + cause.reason;

    var extraData = _.omit(cause, ['type', 'reason']);
    if (_.size(extraData)) {
      memo += ', with ' + prettyPrint(extraData);
    }

    return memo;
  }, '');

  if (!msg) {
    if (esErrObject.type) msg += '[' + esErrObject.type + '] ';
    if (esErrObject.reason) msg += esErrObject.reason;
  }

  ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
  return this;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.elasticsearch.errors.406"></a>[module elasticsearch.errors.406](#apidoc.module.elasticsearch.errors.406)

#### <a name="apidoc.element.elasticsearch.errors.406.super_"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.406.</span>super_ (msg, constructor, metadata)](#apidoc.element.elasticsearch.errors.406.super_)
- description and source-code
```javascript
function ErrorAbstract(msg, constructor, metadata) {
  this.message = msg;

  Error.call(this, this.message);

  if (canCapture) {
    Error.captureStackTrace(this, constructor);
  }
  else if (canStack) {
    this.stack = (new Error()).stack;
  }
  else {
    this.stack = '';
  }

  if (metadata) {
    _.assign(this, metadata);

    this.toString = function () {
      return msg + ' :: ' + JSON.stringify(metadata);
    };

    this.toJSON = function () {
      return _.assign({
        msg: msg
      }, metadata);
    };
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.406.406"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.</span>406 (msg, metadata)](#apidoc.element.elasticsearch.errors.406.406)
- description and source-code
```javascript
function StatusCodeError(msg, metadata) {
  this.status = status;
  this.displayName = className;

  var esErrObject = null;
  if (_.isPlainObject(msg)) {
    esErrObject = msg;
    msg = null;
  }

  if (!esErrObject) {
    // errors from es now come in two forms, an error string < 2.0 and
    // an object >= 2.0
    // TODO: remove after dropping support for < 2.0
    ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
    return this;
  }

  msg = [].concat(esErrObject.root_cause || []).reduce(function (memo, cause) {
    if (memo) memo += ' (and) ';

    memo += '[' + cause.type + '] ' + cause.reason;

    var extraData = _.omit(cause, ['type', 'reason']);
    if (_.size(extraData)) {
      memo += ', with ' + prettyPrint(extraData);
    }

    return memo;
  }, '');

  if (!msg) {
    if (esErrObject.type) msg += '[' + esErrObject.type + '] ';
    if (esErrObject.reason) msg += esErrObject.reason;
  }

  ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
  return this;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.elasticsearch.errors.407"></a>[module elasticsearch.errors.407](#apidoc.module.elasticsearch.errors.407)

#### <a name="apidoc.element.elasticsearch.errors.407.super_"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.407.</span>super_ (msg, constructor, metadata)](#apidoc.element.elasticsearch.errors.407.super_)
- description and source-code
```javascript
function ErrorAbstract(msg, constructor, metadata) {
  this.message = msg;

  Error.call(this, this.message);

  if (canCapture) {
    Error.captureStackTrace(this, constructor);
  }
  else if (canStack) {
    this.stack = (new Error()).stack;
  }
  else {
    this.stack = '';
  }

  if (metadata) {
    _.assign(this, metadata);

    this.toString = function () {
      return msg + ' :: ' + JSON.stringify(metadata);
    };

    this.toJSON = function () {
      return _.assign({
        msg: msg
      }, metadata);
    };
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.407.407"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.</span>407 (msg, metadata)](#apidoc.element.elasticsearch.errors.407.407)
- description and source-code
```javascript
function StatusCodeError(msg, metadata) {
  this.status = status;
  this.displayName = className;

  var esErrObject = null;
  if (_.isPlainObject(msg)) {
    esErrObject = msg;
    msg = null;
  }

  if (!esErrObject) {
    // errors from es now come in two forms, an error string < 2.0 and
    // an object >= 2.0
    // TODO: remove after dropping support for < 2.0
    ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
    return this;
  }

  msg = [].concat(esErrObject.root_cause || []).reduce(function (memo, cause) {
    if (memo) memo += ' (and) ';

    memo += '[' + cause.type + '] ' + cause.reason;

    var extraData = _.omit(cause, ['type', 'reason']);
    if (_.size(extraData)) {
      memo += ', with ' + prettyPrint(extraData);
    }

    return memo;
  }, '');

  if (!msg) {
    if (esErrObject.type) msg += '[' + esErrObject.type + '] ';
    if (esErrObject.reason) msg += esErrObject.reason;
  }

  ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
  return this;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.elasticsearch.errors.408"></a>[module elasticsearch.errors.408](#apidoc.module.elasticsearch.errors.408)

#### <a name="apidoc.element.elasticsearch.errors.408.super_"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.408.</span>super_ (msg, constructor, metadata)](#apidoc.element.elasticsearch.errors.408.super_)
- description and source-code
```javascript
function ErrorAbstract(msg, constructor, metadata) {
  this.message = msg;

  Error.call(this, this.message);

  if (canCapture) {
    Error.captureStackTrace(this, constructor);
  }
  else if (canStack) {
    this.stack = (new Error()).stack;
  }
  else {
    this.stack = '';
  }

  if (metadata) {
    _.assign(this, metadata);

    this.toString = function () {
      return msg + ' :: ' + JSON.stringify(metadata);
    };

    this.toJSON = function () {
      return _.assign({
        msg: msg
      }, metadata);
    };
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.408.408"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.</span>408 (msg, metadata)](#apidoc.element.elasticsearch.errors.408.408)
- description and source-code
```javascript
function StatusCodeError(msg, metadata) {
  this.status = status;
  this.displayName = className;

  var esErrObject = null;
  if (_.isPlainObject(msg)) {
    esErrObject = msg;
    msg = null;
  }

  if (!esErrObject) {
    // errors from es now come in two forms, an error string < 2.0 and
    // an object >= 2.0
    // TODO: remove after dropping support for < 2.0
    ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
    return this;
  }

  msg = [].concat(esErrObject.root_cause || []).reduce(function (memo, cause) {
    if (memo) memo += ' (and) ';

    memo += '[' + cause.type + '] ' + cause.reason;

    var extraData = _.omit(cause, ['type', 'reason']);
    if (_.size(extraData)) {
      memo += ', with ' + prettyPrint(extraData);
    }

    return memo;
  }, '');

  if (!msg) {
    if (esErrObject.type) msg += '[' + esErrObject.type + '] ';
    if (esErrObject.reason) msg += esErrObject.reason;
  }

  ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
  return this;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.elasticsearch.errors.409"></a>[module elasticsearch.errors.409](#apidoc.module.elasticsearch.errors.409)

#### <a name="apidoc.element.elasticsearch.errors.409.super_"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.409.</span>super_ (msg, constructor, metadata)](#apidoc.element.elasticsearch.errors.409.super_)
- description and source-code
```javascript
function ErrorAbstract(msg, constructor, metadata) {
  this.message = msg;

  Error.call(this, this.message);

  if (canCapture) {
    Error.captureStackTrace(this, constructor);
  }
  else if (canStack) {
    this.stack = (new Error()).stack;
  }
  else {
    this.stack = '';
  }

  if (metadata) {
    _.assign(this, metadata);

    this.toString = function () {
      return msg + ' :: ' + JSON.stringify(metadata);
    };

    this.toJSON = function () {
      return _.assign({
        msg: msg
      }, metadata);
    };
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.409.409"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.</span>409 (msg, metadata)](#apidoc.element.elasticsearch.errors.409.409)
- description and source-code
```javascript
function StatusCodeError(msg, metadata) {
  this.status = status;
  this.displayName = className;

  var esErrObject = null;
  if (_.isPlainObject(msg)) {
    esErrObject = msg;
    msg = null;
  }

  if (!esErrObject) {
    // errors from es now come in two forms, an error string < 2.0 and
    // an object >= 2.0
    // TODO: remove after dropping support for < 2.0
    ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
    return this;
  }

  msg = [].concat(esErrObject.root_cause || []).reduce(function (memo, cause) {
    if (memo) memo += ' (and) ';

    memo += '[' + cause.type + '] ' + cause.reason;

    var extraData = _.omit(cause, ['type', 'reason']);
    if (_.size(extraData)) {
      memo += ', with ' + prettyPrint(extraData);
    }

    return memo;
  }, '');

  if (!msg) {
    if (esErrObject.type) msg += '[' + esErrObject.type + '] ';
    if (esErrObject.reason) msg += esErrObject.reason;
  }

  ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
  return this;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.elasticsearch.errors.410"></a>[module elasticsearch.errors.410](#apidoc.module.elasticsearch.errors.410)

#### <a name="apidoc.element.elasticsearch.errors.410.super_"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.410.</span>super_ (msg, constructor, metadata)](#apidoc.element.elasticsearch.errors.410.super_)
- description and source-code
```javascript
function ErrorAbstract(msg, constructor, metadata) {
  this.message = msg;

  Error.call(this, this.message);

  if (canCapture) {
    Error.captureStackTrace(this, constructor);
  }
  else if (canStack) {
    this.stack = (new Error()).stack;
  }
  else {
    this.stack = '';
  }

  if (metadata) {
    _.assign(this, metadata);

    this.toString = function () {
      return msg + ' :: ' + JSON.stringify(metadata);
    };

    this.toJSON = function () {
      return _.assign({
        msg: msg
      }, metadata);
    };
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.410.410"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.</span>410 (msg, metadata)](#apidoc.element.elasticsearch.errors.410.410)
- description and source-code
```javascript
function StatusCodeError(msg, metadata) {
  this.status = status;
  this.displayName = className;

  var esErrObject = null;
  if (_.isPlainObject(msg)) {
    esErrObject = msg;
    msg = null;
  }

  if (!esErrObject) {
    // errors from es now come in two forms, an error string < 2.0 and
    // an object >= 2.0
    // TODO: remove after dropping support for < 2.0
    ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
    return this;
  }

  msg = [].concat(esErrObject.root_cause || []).reduce(function (memo, cause) {
    if (memo) memo += ' (and) ';

    memo += '[' + cause.type + '] ' + cause.reason;

    var extraData = _.omit(cause, ['type', 'reason']);
    if (_.size(extraData)) {
      memo += ', with ' + prettyPrint(extraData);
    }

    return memo;
  }, '');

  if (!msg) {
    if (esErrObject.type) msg += '[' + esErrObject.type + '] ';
    if (esErrObject.reason) msg += esErrObject.reason;
  }

  ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
  return this;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.elasticsearch.errors.411"></a>[module elasticsearch.errors.411](#apidoc.module.elasticsearch.errors.411)

#### <a name="apidoc.element.elasticsearch.errors.411.super_"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.411.</span>super_ (msg, constructor, metadata)](#apidoc.element.elasticsearch.errors.411.super_)
- description and source-code
```javascript
function ErrorAbstract(msg, constructor, metadata) {
  this.message = msg;

  Error.call(this, this.message);

  if (canCapture) {
    Error.captureStackTrace(this, constructor);
  }
  else if (canStack) {
    this.stack = (new Error()).stack;
  }
  else {
    this.stack = '';
  }

  if (metadata) {
    _.assign(this, metadata);

    this.toString = function () {
      return msg + ' :: ' + JSON.stringify(metadata);
    };

    this.toJSON = function () {
      return _.assign({
        msg: msg
      }, metadata);
    };
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.411.411"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.</span>411 (msg, metadata)](#apidoc.element.elasticsearch.errors.411.411)
- description and source-code
```javascript
function StatusCodeError(msg, metadata) {
  this.status = status;
  this.displayName = className;

  var esErrObject = null;
  if (_.isPlainObject(msg)) {
    esErrObject = msg;
    msg = null;
  }

  if (!esErrObject) {
    // errors from es now come in two forms, an error string < 2.0 and
    // an object >= 2.0
    // TODO: remove after dropping support for < 2.0
    ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
    return this;
  }

  msg = [].concat(esErrObject.root_cause || []).reduce(function (memo, cause) {
    if (memo) memo += ' (and) ';

    memo += '[' + cause.type + '] ' + cause.reason;

    var extraData = _.omit(cause, ['type', 'reason']);
    if (_.size(extraData)) {
      memo += ', with ' + prettyPrint(extraData);
    }

    return memo;
  }, '');

  if (!msg) {
    if (esErrObject.type) msg += '[' + esErrObject.type + '] ';
    if (esErrObject.reason) msg += esErrObject.reason;
  }

  ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
  return this;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.elasticsearch.errors.412"></a>[module elasticsearch.errors.412](#apidoc.module.elasticsearch.errors.412)

#### <a name="apidoc.element.elasticsearch.errors.412.super_"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.412.</span>super_ (msg, constructor, metadata)](#apidoc.element.elasticsearch.errors.412.super_)
- description and source-code
```javascript
function ErrorAbstract(msg, constructor, metadata) {
  this.message = msg;

  Error.call(this, this.message);

  if (canCapture) {
    Error.captureStackTrace(this, constructor);
  }
  else if (canStack) {
    this.stack = (new Error()).stack;
  }
  else {
    this.stack = '';
  }

  if (metadata) {
    _.assign(this, metadata);

    this.toString = function () {
      return msg + ' :: ' + JSON.stringify(metadata);
    };

    this.toJSON = function () {
      return _.assign({
        msg: msg
      }, metadata);
    };
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.412.412"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.</span>412 (msg, metadata)](#apidoc.element.elasticsearch.errors.412.412)
- description and source-code
```javascript
function StatusCodeError(msg, metadata) {
  this.status = status;
  this.displayName = className;

  var esErrObject = null;
  if (_.isPlainObject(msg)) {
    esErrObject = msg;
    msg = null;
  }

  if (!esErrObject) {
    // errors from es now come in two forms, an error string < 2.0 and
    // an object >= 2.0
    // TODO: remove after dropping support for < 2.0
    ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
    return this;
  }

  msg = [].concat(esErrObject.root_cause || []).reduce(function (memo, cause) {
    if (memo) memo += ' (and) ';

    memo += '[' + cause.type + '] ' + cause.reason;

    var extraData = _.omit(cause, ['type', 'reason']);
    if (_.size(extraData)) {
      memo += ', with ' + prettyPrint(extraData);
    }

    return memo;
  }, '');

  if (!msg) {
    if (esErrObject.type) msg += '[' + esErrObject.type + '] ';
    if (esErrObject.reason) msg += esErrObject.reason;
  }

  ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
  return this;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.elasticsearch.errors.413"></a>[module elasticsearch.errors.413](#apidoc.module.elasticsearch.errors.413)

#### <a name="apidoc.element.elasticsearch.errors.413.super_"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.413.</span>super_ (msg, constructor, metadata)](#apidoc.element.elasticsearch.errors.413.super_)
- description and source-code
```javascript
function ErrorAbstract(msg, constructor, metadata) {
  this.message = msg;

  Error.call(this, this.message);

  if (canCapture) {
    Error.captureStackTrace(this, constructor);
  }
  else if (canStack) {
    this.stack = (new Error()).stack;
  }
  else {
    this.stack = '';
  }

  if (metadata) {
    _.assign(this, metadata);

    this.toString = function () {
      return msg + ' :: ' + JSON.stringify(metadata);
    };

    this.toJSON = function () {
      return _.assign({
        msg: msg
      }, metadata);
    };
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.413.413"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.</span>413 (msg, metadata)](#apidoc.element.elasticsearch.errors.413.413)
- description and source-code
```javascript
function StatusCodeError(msg, metadata) {
  this.status = status;
  this.displayName = className;

  var esErrObject = null;
  if (_.isPlainObject(msg)) {
    esErrObject = msg;
    msg = null;
  }

  if (!esErrObject) {
    // errors from es now come in two forms, an error string < 2.0 and
    // an object >= 2.0
    // TODO: remove after dropping support for < 2.0
    ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
    return this;
  }

  msg = [].concat(esErrObject.root_cause || []).reduce(function (memo, cause) {
    if (memo) memo += ' (and) ';

    memo += '[' + cause.type + '] ' + cause.reason;

    var extraData = _.omit(cause, ['type', 'reason']);
    if (_.size(extraData)) {
      memo += ', with ' + prettyPrint(extraData);
    }

    return memo;
  }, '');

  if (!msg) {
    if (esErrObject.type) msg += '[' + esErrObject.type + '] ';
    if (esErrObject.reason) msg += esErrObject.reason;
  }

  ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
  return this;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.elasticsearch.errors.414"></a>[module elasticsearch.errors.414](#apidoc.module.elasticsearch.errors.414)

#### <a name="apidoc.element.elasticsearch.errors.414.super_"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.414.</span>super_ (msg, constructor, metadata)](#apidoc.element.elasticsearch.errors.414.super_)
- description and source-code
```javascript
function ErrorAbstract(msg, constructor, metadata) {
  this.message = msg;

  Error.call(this, this.message);

  if (canCapture) {
    Error.captureStackTrace(this, constructor);
  }
  else if (canStack) {
    this.stack = (new Error()).stack;
  }
  else {
    this.stack = '';
  }

  if (metadata) {
    _.assign(this, metadata);

    this.toString = function () {
      return msg + ' :: ' + JSON.stringify(metadata);
    };

    this.toJSON = function () {
      return _.assign({
        msg: msg
      }, metadata);
    };
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.414.414"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.</span>414 (msg, metadata)](#apidoc.element.elasticsearch.errors.414.414)
- description and source-code
```javascript
function StatusCodeError(msg, metadata) {
  this.status = status;
  this.displayName = className;

  var esErrObject = null;
  if (_.isPlainObject(msg)) {
    esErrObject = msg;
    msg = null;
  }

  if (!esErrObject) {
    // errors from es now come in two forms, an error string < 2.0 and
    // an object >= 2.0
    // TODO: remove after dropping support for < 2.0
    ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
    return this;
  }

  msg = [].concat(esErrObject.root_cause || []).reduce(function (memo, cause) {
    if (memo) memo += ' (and) ';

    memo += '[' + cause.type + '] ' + cause.reason;

    var extraData = _.omit(cause, ['type', 'reason']);
    if (_.size(extraData)) {
      memo += ', with ' + prettyPrint(extraData);
    }

    return memo;
  }, '');

  if (!msg) {
    if (esErrObject.type) msg += '[' + esErrObject.type + '] ';
    if (esErrObject.reason) msg += esErrObject.reason;
  }

  ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
  return this;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.elasticsearch.errors.415"></a>[module elasticsearch.errors.415](#apidoc.module.elasticsearch.errors.415)

#### <a name="apidoc.element.elasticsearch.errors.415.super_"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.415.</span>super_ (msg, constructor, metadata)](#apidoc.element.elasticsearch.errors.415.super_)
- description and source-code
```javascript
function ErrorAbstract(msg, constructor, metadata) {
  this.message = msg;

  Error.call(this, this.message);

  if (canCapture) {
    Error.captureStackTrace(this, constructor);
  }
  else if (canStack) {
    this.stack = (new Error()).stack;
  }
  else {
    this.stack = '';
  }

  if (metadata) {
    _.assign(this, metadata);

    this.toString = function () {
      return msg + ' :: ' + JSON.stringify(metadata);
    };

    this.toJSON = function () {
      return _.assign({
        msg: msg
      }, metadata);
    };
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.415.415"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.</span>415 (msg, metadata)](#apidoc.element.elasticsearch.errors.415.415)
- description and source-code
```javascript
function StatusCodeError(msg, metadata) {
  this.status = status;
  this.displayName = className;

  var esErrObject = null;
  if (_.isPlainObject(msg)) {
    esErrObject = msg;
    msg = null;
  }

  if (!esErrObject) {
    // errors from es now come in two forms, an error string < 2.0 and
    // an object >= 2.0
    // TODO: remove after dropping support for < 2.0
    ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
    return this;
  }

  msg = [].concat(esErrObject.root_cause || []).reduce(function (memo, cause) {
    if (memo) memo += ' (and) ';

    memo += '[' + cause.type + '] ' + cause.reason;

    var extraData = _.omit(cause, ['type', 'reason']);
    if (_.size(extraData)) {
      memo += ', with ' + prettyPrint(extraData);
    }

    return memo;
  }, '');

  if (!msg) {
    if (esErrObject.type) msg += '[' + esErrObject.type + '] ';
    if (esErrObject.reason) msg += esErrObject.reason;
  }

  ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
  return this;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.elasticsearch.errors.416"></a>[module elasticsearch.errors.416](#apidoc.module.elasticsearch.errors.416)

#### <a name="apidoc.element.elasticsearch.errors.416.super_"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.416.</span>super_ (msg, constructor, metadata)](#apidoc.element.elasticsearch.errors.416.super_)
- description and source-code
```javascript
function ErrorAbstract(msg, constructor, metadata) {
  this.message = msg;

  Error.call(this, this.message);

  if (canCapture) {
    Error.captureStackTrace(this, constructor);
  }
  else if (canStack) {
    this.stack = (new Error()).stack;
  }
  else {
    this.stack = '';
  }

  if (metadata) {
    _.assign(this, metadata);

    this.toString = function () {
      return msg + ' :: ' + JSON.stringify(metadata);
    };

    this.toJSON = function () {
      return _.assign({
        msg: msg
      }, metadata);
    };
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.416.416"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.</span>416 (msg, metadata)](#apidoc.element.elasticsearch.errors.416.416)
- description and source-code
```javascript
function StatusCodeError(msg, metadata) {
  this.status = status;
  this.displayName = className;

  var esErrObject = null;
  if (_.isPlainObject(msg)) {
    esErrObject = msg;
    msg = null;
  }

  if (!esErrObject) {
    // errors from es now come in two forms, an error string < 2.0 and
    // an object >= 2.0
    // TODO: remove after dropping support for < 2.0
    ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
    return this;
  }

  msg = [].concat(esErrObject.root_cause || []).reduce(function (memo, cause) {
    if (memo) memo += ' (and) ';

    memo += '[' + cause.type + '] ' + cause.reason;

    var extraData = _.omit(cause, ['type', 'reason']);
    if (_.size(extraData)) {
      memo += ', with ' + prettyPrint(extraData);
    }

    return memo;
  }, '');

  if (!msg) {
    if (esErrObject.type) msg += '[' + esErrObject.type + '] ';
    if (esErrObject.reason) msg += esErrObject.reason;
  }

  ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
  return this;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.elasticsearch.errors.417"></a>[module elasticsearch.errors.417](#apidoc.module.elasticsearch.errors.417)

#### <a name="apidoc.element.elasticsearch.errors.417.super_"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.417.</span>super_ (msg, constructor, metadata)](#apidoc.element.elasticsearch.errors.417.super_)
- description and source-code
```javascript
function ErrorAbstract(msg, constructor, metadata) {
  this.message = msg;

  Error.call(this, this.message);

  if (canCapture) {
    Error.captureStackTrace(this, constructor);
  }
  else if (canStack) {
    this.stack = (new Error()).stack;
  }
  else {
    this.stack = '';
  }

  if (metadata) {
    _.assign(this, metadata);

    this.toString = function () {
      return msg + ' :: ' + JSON.stringify(metadata);
    };

    this.toJSON = function () {
      return _.assign({
        msg: msg
      }, metadata);
    };
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.417.417"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.</span>417 (msg, metadata)](#apidoc.element.elasticsearch.errors.417.417)
- description and source-code
```javascript
function StatusCodeError(msg, metadata) {
  this.status = status;
  this.displayName = className;

  var esErrObject = null;
  if (_.isPlainObject(msg)) {
    esErrObject = msg;
    msg = null;
  }

  if (!esErrObject) {
    // errors from es now come in two forms, an error string < 2.0 and
    // an object >= 2.0
    // TODO: remove after dropping support for < 2.0
    ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
    return this;
  }

  msg = [].concat(esErrObject.root_cause || []).reduce(function (memo, cause) {
    if (memo) memo += ' (and) ';

    memo += '[' + cause.type + '] ' + cause.reason;

    var extraData = _.omit(cause, ['type', 'reason']);
    if (_.size(extraData)) {
      memo += ', with ' + prettyPrint(extraData);
    }

    return memo;
  }, '');

  if (!msg) {
    if (esErrObject.type) msg += '[' + esErrObject.type + '] ';
    if (esErrObject.reason) msg += esErrObject.reason;
  }

  ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
  return this;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.elasticsearch.errors.418"></a>[module elasticsearch.errors.418](#apidoc.module.elasticsearch.errors.418)

#### <a name="apidoc.element.elasticsearch.errors.418.super_"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.418.</span>super_ (msg, constructor, metadata)](#apidoc.element.elasticsearch.errors.418.super_)
- description and source-code
```javascript
function ErrorAbstract(msg, constructor, metadata) {
  this.message = msg;

  Error.call(this, this.message);

  if (canCapture) {
    Error.captureStackTrace(this, constructor);
  }
  else if (canStack) {
    this.stack = (new Error()).stack;
  }
  else {
    this.stack = '';
  }

  if (metadata) {
    _.assign(this, metadata);

    this.toString = function () {
      return msg + ' :: ' + JSON.stringify(metadata);
    };

    this.toJSON = function () {
      return _.assign({
        msg: msg
      }, metadata);
    };
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.418.418"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.</span>418 (msg, metadata)](#apidoc.element.elasticsearch.errors.418.418)
- description and source-code
```javascript
function StatusCodeError(msg, metadata) {
  this.status = status;
  this.displayName = className;

  var esErrObject = null;
  if (_.isPlainObject(msg)) {
    esErrObject = msg;
    msg = null;
  }

  if (!esErrObject) {
    // errors from es now come in two forms, an error string < 2.0 and
    // an object >= 2.0
    // TODO: remove after dropping support for < 2.0
    ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
    return this;
  }

  msg = [].concat(esErrObject.root_cause || []).reduce(function (memo, cause) {
    if (memo) memo += ' (and) ';

    memo += '[' + cause.type + '] ' + cause.reason;

    var extraData = _.omit(cause, ['type', 'reason']);
    if (_.size(extraData)) {
      memo += ', with ' + prettyPrint(extraData);
    }

    return memo;
  }, '');

  if (!msg) {
    if (esErrObject.type) msg += '[' + esErrObject.type + '] ';
    if (esErrObject.reason) msg += esErrObject.reason;
  }

  ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
  return this;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.elasticsearch.errors.421"></a>[module elasticsearch.errors.421](#apidoc.module.elasticsearch.errors.421)

#### <a name="apidoc.element.elasticsearch.errors.421.super_"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.421.</span>super_ (msg, constructor, metadata)](#apidoc.element.elasticsearch.errors.421.super_)
- description and source-code
```javascript
function ErrorAbstract(msg, constructor, metadata) {
  this.message = msg;

  Error.call(this, this.message);

  if (canCapture) {
    Error.captureStackTrace(this, constructor);
  }
  else if (canStack) {
    this.stack = (new Error()).stack;
  }
  else {
    this.stack = '';
  }

  if (metadata) {
    _.assign(this, metadata);

    this.toString = function () {
      return msg + ' :: ' + JSON.stringify(metadata);
    };

    this.toJSON = function () {
      return _.assign({
        msg: msg
      }, metadata);
    };
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.421.421"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.</span>421 (msg, metadata)](#apidoc.element.elasticsearch.errors.421.421)
- description and source-code
```javascript
function StatusCodeError(msg, metadata) {
  this.status = status;
  this.displayName = className;

  var esErrObject = null;
  if (_.isPlainObject(msg)) {
    esErrObject = msg;
    msg = null;
  }

  if (!esErrObject) {
    // errors from es now come in two forms, an error string < 2.0 and
    // an object >= 2.0
    // TODO: remove after dropping support for < 2.0
    ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
    return this;
  }

  msg = [].concat(esErrObject.root_cause || []).reduce(function (memo, cause) {
    if (memo) memo += ' (and) ';

    memo += '[' + cause.type + '] ' + cause.reason;

    var extraData = _.omit(cause, ['type', 'reason']);
    if (_.size(extraData)) {
      memo += ', with ' + prettyPrint(extraData);
    }

    return memo;
  }, '');

  if (!msg) {
    if (esErrObject.type) msg += '[' + esErrObject.type + '] ';
    if (esErrObject.reason) msg += esErrObject.reason;
  }

  ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
  return this;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.elasticsearch.errors.426"></a>[module elasticsearch.errors.426](#apidoc.module.elasticsearch.errors.426)

#### <a name="apidoc.element.elasticsearch.errors.426.super_"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.426.</span>super_ (msg, constructor, metadata)](#apidoc.element.elasticsearch.errors.426.super_)
- description and source-code
```javascript
function ErrorAbstract(msg, constructor, metadata) {
  this.message = msg;

  Error.call(this, this.message);

  if (canCapture) {
    Error.captureStackTrace(this, constructor);
  }
  else if (canStack) {
    this.stack = (new Error()).stack;
  }
  else {
    this.stack = '';
  }

  if (metadata) {
    _.assign(this, metadata);

    this.toString = function () {
      return msg + ' :: ' + JSON.stringify(metadata);
    };

    this.toJSON = function () {
      return _.assign({
        msg: msg
      }, metadata);
    };
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.426.426"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.</span>426 (msg, metadata)](#apidoc.element.elasticsearch.errors.426.426)
- description and source-code
```javascript
function StatusCodeError(msg, metadata) {
  this.status = status;
  this.displayName = className;

  var esErrObject = null;
  if (_.isPlainObject(msg)) {
    esErrObject = msg;
    msg = null;
  }

  if (!esErrObject) {
    // errors from es now come in two forms, an error string < 2.0 and
    // an object >= 2.0
    // TODO: remove after dropping support for < 2.0
    ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
    return this;
  }

  msg = [].concat(esErrObject.root_cause || []).reduce(function (memo, cause) {
    if (memo) memo += ' (and) ';

    memo += '[' + cause.type + '] ' + cause.reason;

    var extraData = _.omit(cause, ['type', 'reason']);
    if (_.size(extraData)) {
      memo += ', with ' + prettyPrint(extraData);
    }

    return memo;
  }, '');

  if (!msg) {
    if (esErrObject.type) msg += '[' + esErrObject.type + '] ';
    if (esErrObject.reason) msg += esErrObject.reason;
  }

  ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
  return this;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.elasticsearch.errors.429"></a>[module elasticsearch.errors.429](#apidoc.module.elasticsearch.errors.429)

#### <a name="apidoc.element.elasticsearch.errors.429.super_"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.429.</span>super_ (msg, constructor, metadata)](#apidoc.element.elasticsearch.errors.429.super_)
- description and source-code
```javascript
function ErrorAbstract(msg, constructor, metadata) {
  this.message = msg;

  Error.call(this, this.message);

  if (canCapture) {
    Error.captureStackTrace(this, constructor);
  }
  else if (canStack) {
    this.stack = (new Error()).stack;
  }
  else {
    this.stack = '';
  }

  if (metadata) {
    _.assign(this, metadata);

    this.toString = function () {
      return msg + ' :: ' + JSON.stringify(metadata);
    };

    this.toJSON = function () {
      return _.assign({
        msg: msg
      }, metadata);
    };
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.429.429"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.</span>429 (msg, metadata)](#apidoc.element.elasticsearch.errors.429.429)
- description and source-code
```javascript
function StatusCodeError(msg, metadata) {
  this.status = status;
  this.displayName = className;

  var esErrObject = null;
  if (_.isPlainObject(msg)) {
    esErrObject = msg;
    msg = null;
  }

  if (!esErrObject) {
    // errors from es now come in two forms, an error string < 2.0 and
    // an object >= 2.0
    // TODO: remove after dropping support for < 2.0
    ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
    return this;
  }

  msg = [].concat(esErrObject.root_cause || []).reduce(function (memo, cause) {
    if (memo) memo += ' (and) ';

    memo += '[' + cause.type + '] ' + cause.reason;

    var extraData = _.omit(cause, ['type', 'reason']);
    if (_.size(extraData)) {
      memo += ', with ' + prettyPrint(extraData);
    }

    return memo;
  }, '');

  if (!msg) {
    if (esErrObject.type) msg += '[' + esErrObject.type + '] ';
    if (esErrObject.reason) msg += esErrObject.reason;
  }

  ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
  return this;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.elasticsearch.errors.450"></a>[module elasticsearch.errors.450](#apidoc.module.elasticsearch.errors.450)

#### <a name="apidoc.element.elasticsearch.errors.450.super_"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.450.</span>super_ (msg, constructor, metadata)](#apidoc.element.elasticsearch.errors.450.super_)
- description and source-code
```javascript
function ErrorAbstract(msg, constructor, metadata) {
  this.message = msg;

  Error.call(this, this.message);

  if (canCapture) {
    Error.captureStackTrace(this, constructor);
  }
  else if (canStack) {
    this.stack = (new Error()).stack;
  }
  else {
    this.stack = '';
  }

  if (metadata) {
    _.assign(this, metadata);

    this.toString = function () {
      return msg + ' :: ' + JSON.stringify(metadata);
    };

    this.toJSON = function () {
      return _.assign({
        msg: msg
      }, metadata);
    };
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.450.450"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.</span>450 (msg, metadata)](#apidoc.element.elasticsearch.errors.450.450)
- description and source-code
```javascript
function StatusCodeError(msg, metadata) {
  this.status = status;
  this.displayName = className;

  var esErrObject = null;
  if (_.isPlainObject(msg)) {
    esErrObject = msg;
    msg = null;
  }

  if (!esErrObject) {
    // errors from es now come in two forms, an error string < 2.0 and
    // an object >= 2.0
    // TODO: remove after dropping support for < 2.0
    ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
    return this;
  }

  msg = [].concat(esErrObject.root_cause || []).reduce(function (memo, cause) {
    if (memo) memo += ' (and) ';

    memo += '[' + cause.type + '] ' + cause.reason;

    var extraData = _.omit(cause, ['type', 'reason']);
    if (_.size(extraData)) {
      memo += ', with ' + prettyPrint(extraData);
    }

    return memo;
  }, '');

  if (!msg) {
    if (esErrObject.type) msg += '[' + esErrObject.type + '] ';
    if (esErrObject.reason) msg += esErrObject.reason;
  }

  ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
  return this;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.elasticsearch.errors.494"></a>[module elasticsearch.errors.494](#apidoc.module.elasticsearch.errors.494)

#### <a name="apidoc.element.elasticsearch.errors.494.super_"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.494.</span>super_ (msg, constructor, metadata)](#apidoc.element.elasticsearch.errors.494.super_)
- description and source-code
```javascript
function ErrorAbstract(msg, constructor, metadata) {
  this.message = msg;

  Error.call(this, this.message);

  if (canCapture) {
    Error.captureStackTrace(this, constructor);
  }
  else if (canStack) {
    this.stack = (new Error()).stack;
  }
  else {
    this.stack = '';
  }

  if (metadata) {
    _.assign(this, metadata);

    this.toString = function () {
      return msg + ' :: ' + JSON.stringify(metadata);
    };

    this.toJSON = function () {
      return _.assign({
        msg: msg
      }, metadata);
    };
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.494.494"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.</span>494 (msg, metadata)](#apidoc.element.elasticsearch.errors.494.494)
- description and source-code
```javascript
function StatusCodeError(msg, metadata) {
  this.status = status;
  this.displayName = className;

  var esErrObject = null;
  if (_.isPlainObject(msg)) {
    esErrObject = msg;
    msg = null;
  }

  if (!esErrObject) {
    // errors from es now come in two forms, an error string < 2.0 and
    // an object >= 2.0
    // TODO: remove after dropping support for < 2.0
    ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
    return this;
  }

  msg = [].concat(esErrObject.root_cause || []).reduce(function (memo, cause) {
    if (memo) memo += ' (and) ';

    memo += '[' + cause.type + '] ' + cause.reason;

    var extraData = _.omit(cause, ['type', 'reason']);
    if (_.size(extraData)) {
      memo += ', with ' + prettyPrint(extraData);
    }

    return memo;
  }, '');

  if (!msg) {
    if (esErrObject.type) msg += '[' + esErrObject.type + '] ';
    if (esErrObject.reason) msg += esErrObject.reason;
  }

  ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
  return this;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.elasticsearch.errors.497"></a>[module elasticsearch.errors.497](#apidoc.module.elasticsearch.errors.497)

#### <a name="apidoc.element.elasticsearch.errors.497.super_"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.497.</span>super_ (msg, constructor, metadata)](#apidoc.element.elasticsearch.errors.497.super_)
- description and source-code
```javascript
function ErrorAbstract(msg, constructor, metadata) {
  this.message = msg;

  Error.call(this, this.message);

  if (canCapture) {
    Error.captureStackTrace(this, constructor);
  }
  else if (canStack) {
    this.stack = (new Error()).stack;
  }
  else {
    this.stack = '';
  }

  if (metadata) {
    _.assign(this, metadata);

    this.toString = function () {
      return msg + ' :: ' + JSON.stringify(metadata);
    };

    this.toJSON = function () {
      return _.assign({
        msg: msg
      }, metadata);
    };
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.497.497"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.</span>497 (msg, metadata)](#apidoc.element.elasticsearch.errors.497.497)
- description and source-code
```javascript
function StatusCodeError(msg, metadata) {
  this.status = status;
  this.displayName = className;

  var esErrObject = null;
  if (_.isPlainObject(msg)) {
    esErrObject = msg;
    msg = null;
  }

  if (!esErrObject) {
    // errors from es now come in two forms, an error string < 2.0 and
    // an object >= 2.0
    // TODO: remove after dropping support for < 2.0
    ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
    return this;
  }

  msg = [].concat(esErrObject.root_cause || []).reduce(function (memo, cause) {
    if (memo) memo += ' (and) ';

    memo += '[' + cause.type + '] ' + cause.reason;

    var extraData = _.omit(cause, ['type', 'reason']);
    if (_.size(extraData)) {
      memo += ', with ' + prettyPrint(extraData);
    }

    return memo;
  }, '');

  if (!msg) {
    if (esErrObject.type) msg += '[' + esErrObject.type + '] ';
    if (esErrObject.reason) msg += esErrObject.reason;
  }

  ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
  return this;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.elasticsearch.errors.499"></a>[module elasticsearch.errors.499](#apidoc.module.elasticsearch.errors.499)

#### <a name="apidoc.element.elasticsearch.errors.499.super_"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.499.</span>super_ (msg, constructor, metadata)](#apidoc.element.elasticsearch.errors.499.super_)
- description and source-code
```javascript
function ErrorAbstract(msg, constructor, metadata) {
  this.message = msg;

  Error.call(this, this.message);

  if (canCapture) {
    Error.captureStackTrace(this, constructor);
  }
  else if (canStack) {
    this.stack = (new Error()).stack;
  }
  else {
    this.stack = '';
  }

  if (metadata) {
    _.assign(this, metadata);

    this.toString = function () {
      return msg + ' :: ' + JSON.stringify(metadata);
    };

    this.toJSON = function () {
      return _.assign({
        msg: msg
      }, metadata);
    };
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.499.499"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.</span>499 (msg, metadata)](#apidoc.element.elasticsearch.errors.499.499)
- description and source-code
```javascript
function StatusCodeError(msg, metadata) {
  this.status = status;
  this.displayName = className;

  var esErrObject = null;
  if (_.isPlainObject(msg)) {
    esErrObject = msg;
    msg = null;
  }

  if (!esErrObject) {
    // errors from es now come in two forms, an error string < 2.0 and
    // an object >= 2.0
    // TODO: remove after dropping support for < 2.0
    ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
    return this;
  }

  msg = [].concat(esErrObject.root_cause || []).reduce(function (memo, cause) {
    if (memo) memo += ' (and) ';

    memo += '[' + cause.type + '] ' + cause.reason;

    var extraData = _.omit(cause, ['type', 'reason']);
    if (_.size(extraData)) {
      memo += ', with ' + prettyPrint(extraData);
    }

    return memo;
  }, '');

  if (!msg) {
    if (esErrObject.type) msg += '[' + esErrObject.type + '] ';
    if (esErrObject.reason) msg += esErrObject.reason;
  }

  ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
  return this;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.elasticsearch.errors.500"></a>[module elasticsearch.errors.500](#apidoc.module.elasticsearch.errors.500)

#### <a name="apidoc.element.elasticsearch.errors.500.super_"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.500.</span>super_ (msg, constructor, metadata)](#apidoc.element.elasticsearch.errors.500.super_)
- description and source-code
```javascript
function ErrorAbstract(msg, constructor, metadata) {
  this.message = msg;

  Error.call(this, this.message);

  if (canCapture) {
    Error.captureStackTrace(this, constructor);
  }
  else if (canStack) {
    this.stack = (new Error()).stack;
  }
  else {
    this.stack = '';
  }

  if (metadata) {
    _.assign(this, metadata);

    this.toString = function () {
      return msg + ' :: ' + JSON.stringify(metadata);
    };

    this.toJSON = function () {
      return _.assign({
        msg: msg
      }, metadata);
    };
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.500.500"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.</span>500 (msg, metadata)](#apidoc.element.elasticsearch.errors.500.500)
- description and source-code
```javascript
function StatusCodeError(msg, metadata) {
  this.status = status;
  this.displayName = className;

  var esErrObject = null;
  if (_.isPlainObject(msg)) {
    esErrObject = msg;
    msg = null;
  }

  if (!esErrObject) {
    // errors from es now come in two forms, an error string < 2.0 and
    // an object >= 2.0
    // TODO: remove after dropping support for < 2.0
    ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
    return this;
  }

  msg = [].concat(esErrObject.root_cause || []).reduce(function (memo, cause) {
    if (memo) memo += ' (and) ';

    memo += '[' + cause.type + '] ' + cause.reason;

    var extraData = _.omit(cause, ['type', 'reason']);
    if (_.size(extraData)) {
      memo += ', with ' + prettyPrint(extraData);
    }

    return memo;
  }, '');

  if (!msg) {
    if (esErrObject.type) msg += '[' + esErrObject.type + '] ';
    if (esErrObject.reason) msg += esErrObject.reason;
  }

  ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
  return this;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.elasticsearch.errors.501"></a>[module elasticsearch.errors.501](#apidoc.module.elasticsearch.errors.501)

#### <a name="apidoc.element.elasticsearch.errors.501.super_"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.501.</span>super_ (msg, constructor, metadata)](#apidoc.element.elasticsearch.errors.501.super_)
- description and source-code
```javascript
function ErrorAbstract(msg, constructor, metadata) {
  this.message = msg;

  Error.call(this, this.message);

  if (canCapture) {
    Error.captureStackTrace(this, constructor);
  }
  else if (canStack) {
    this.stack = (new Error()).stack;
  }
  else {
    this.stack = '';
  }

  if (metadata) {
    _.assign(this, metadata);

    this.toString = function () {
      return msg + ' :: ' + JSON.stringify(metadata);
    };

    this.toJSON = function () {
      return _.assign({
        msg: msg
      }, metadata);
    };
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.501.501"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.</span>501 (msg, metadata)](#apidoc.element.elasticsearch.errors.501.501)
- description and source-code
```javascript
function StatusCodeError(msg, metadata) {
  this.status = status;
  this.displayName = className;

  var esErrObject = null;
  if (_.isPlainObject(msg)) {
    esErrObject = msg;
    msg = null;
  }

  if (!esErrObject) {
    // errors from es now come in two forms, an error string < 2.0 and
    // an object >= 2.0
    // TODO: remove after dropping support for < 2.0
    ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
    return this;
  }

  msg = [].concat(esErrObject.root_cause || []).reduce(function (memo, cause) {
    if (memo) memo += ' (and) ';

    memo += '[' + cause.type + '] ' + cause.reason;

    var extraData = _.omit(cause, ['type', 'reason']);
    if (_.size(extraData)) {
      memo += ', with ' + prettyPrint(extraData);
    }

    return memo;
  }, '');

  if (!msg) {
    if (esErrObject.type) msg += '[' + esErrObject.type + '] ';
    if (esErrObject.reason) msg += esErrObject.reason;
  }

  ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
  return this;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.elasticsearch.errors.502"></a>[module elasticsearch.errors.502](#apidoc.module.elasticsearch.errors.502)

#### <a name="apidoc.element.elasticsearch.errors.502.super_"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.502.</span>super_ (msg, constructor, metadata)](#apidoc.element.elasticsearch.errors.502.super_)
- description and source-code
```javascript
function ErrorAbstract(msg, constructor, metadata) {
  this.message = msg;

  Error.call(this, this.message);

  if (canCapture) {
    Error.captureStackTrace(this, constructor);
  }
  else if (canStack) {
    this.stack = (new Error()).stack;
  }
  else {
    this.stack = '';
  }

  if (metadata) {
    _.assign(this, metadata);

    this.toString = function () {
      return msg + ' :: ' + JSON.stringify(metadata);
    };

    this.toJSON = function () {
      return _.assign({
        msg: msg
      }, metadata);
    };
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.502.502"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.</span>502 (msg, metadata)](#apidoc.element.elasticsearch.errors.502.502)
- description and source-code
```javascript
function StatusCodeError(msg, metadata) {
  this.status = status;
  this.displayName = className;

  var esErrObject = null;
  if (_.isPlainObject(msg)) {
    esErrObject = msg;
    msg = null;
  }

  if (!esErrObject) {
    // errors from es now come in two forms, an error string < 2.0 and
    // an object >= 2.0
    // TODO: remove after dropping support for < 2.0
    ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
    return this;
  }

  msg = [].concat(esErrObject.root_cause || []).reduce(function (memo, cause) {
    if (memo) memo += ' (and) ';

    memo += '[' + cause.type + '] ' + cause.reason;

    var extraData = _.omit(cause, ['type', 'reason']);
    if (_.size(extraData)) {
      memo += ', with ' + prettyPrint(extraData);
    }

    return memo;
  }, '');

  if (!msg) {
    if (esErrObject.type) msg += '[' + esErrObject.type + '] ';
    if (esErrObject.reason) msg += esErrObject.reason;
  }

  ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
  return this;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.elasticsearch.errors.503"></a>[module elasticsearch.errors.503](#apidoc.module.elasticsearch.errors.503)

#### <a name="apidoc.element.elasticsearch.errors.503.super_"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.503.</span>super_ (msg, constructor, metadata)](#apidoc.element.elasticsearch.errors.503.super_)
- description and source-code
```javascript
function ErrorAbstract(msg, constructor, metadata) {
  this.message = msg;

  Error.call(this, this.message);

  if (canCapture) {
    Error.captureStackTrace(this, constructor);
  }
  else if (canStack) {
    this.stack = (new Error()).stack;
  }
  else {
    this.stack = '';
  }

  if (metadata) {
    _.assign(this, metadata);

    this.toString = function () {
      return msg + ' :: ' + JSON.stringify(metadata);
    };

    this.toJSON = function () {
      return _.assign({
        msg: msg
      }, metadata);
    };
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.503.503"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.</span>503 (msg, metadata)](#apidoc.element.elasticsearch.errors.503.503)
- description and source-code
```javascript
function StatusCodeError(msg, metadata) {
  this.status = status;
  this.displayName = className;

  var esErrObject = null;
  if (_.isPlainObject(msg)) {
    esErrObject = msg;
    msg = null;
  }

  if (!esErrObject) {
    // errors from es now come in two forms, an error string < 2.0 and
    // an object >= 2.0
    // TODO: remove after dropping support for < 2.0
    ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
    return this;
  }

  msg = [].concat(esErrObject.root_cause || []).reduce(function (memo, cause) {
    if (memo) memo += ' (and) ';

    memo += '[' + cause.type + '] ' + cause.reason;

    var extraData = _.omit(cause, ['type', 'reason']);
    if (_.size(extraData)) {
      memo += ', with ' + prettyPrint(extraData);
    }

    return memo;
  }, '');

  if (!msg) {
    if (esErrObject.type) msg += '[' + esErrObject.type + '] ';
    if (esErrObject.reason) msg += esErrObject.reason;
  }

  ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
  return this;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.elasticsearch.errors.504"></a>[module elasticsearch.errors.504](#apidoc.module.elasticsearch.errors.504)

#### <a name="apidoc.element.elasticsearch.errors.504.super_"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.504.</span>super_ (msg, constructor, metadata)](#apidoc.element.elasticsearch.errors.504.super_)
- description and source-code
```javascript
function ErrorAbstract(msg, constructor, metadata) {
  this.message = msg;

  Error.call(this, this.message);

  if (canCapture) {
    Error.captureStackTrace(this, constructor);
  }
  else if (canStack) {
    this.stack = (new Error()).stack;
  }
  else {
    this.stack = '';
  }

  if (metadata) {
    _.assign(this, metadata);

    this.toString = function () {
      return msg + ' :: ' + JSON.stringify(metadata);
    };

    this.toJSON = function () {
      return _.assign({
        msg: msg
      }, metadata);
    };
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.504.504"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.</span>504 (msg, metadata)](#apidoc.element.elasticsearch.errors.504.504)
- description and source-code
```javascript
function StatusCodeError(msg, metadata) {
  this.status = status;
  this.displayName = className;

  var esErrObject = null;
  if (_.isPlainObject(msg)) {
    esErrObject = msg;
    msg = null;
  }

  if (!esErrObject) {
    // errors from es now come in two forms, an error string < 2.0 and
    // an object >= 2.0
    // TODO: remove after dropping support for < 2.0
    ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
    return this;
  }

  msg = [].concat(esErrObject.root_cause || []).reduce(function (memo, cause) {
    if (memo) memo += ' (and) ';

    memo += '[' + cause.type + '] ' + cause.reason;

    var extraData = _.omit(cause, ['type', 'reason']);
    if (_.size(extraData)) {
      memo += ', with ' + prettyPrint(extraData);
    }

    return memo;
  }, '');

  if (!msg) {
    if (esErrObject.type) msg += '[' + esErrObject.type + '] ';
    if (esErrObject.reason) msg += esErrObject.reason;
  }

  ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
  return this;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.elasticsearch.errors.505"></a>[module elasticsearch.errors.505](#apidoc.module.elasticsearch.errors.505)

#### <a name="apidoc.element.elasticsearch.errors.505.super_"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.505.</span>super_ (msg, constructor, metadata)](#apidoc.element.elasticsearch.errors.505.super_)
- description and source-code
```javascript
function ErrorAbstract(msg, constructor, metadata) {
  this.message = msg;

  Error.call(this, this.message);

  if (canCapture) {
    Error.captureStackTrace(this, constructor);
  }
  else if (canStack) {
    this.stack = (new Error()).stack;
  }
  else {
    this.stack = '';
  }

  if (metadata) {
    _.assign(this, metadata);

    this.toString = function () {
      return msg + ' :: ' + JSON.stringify(metadata);
    };

    this.toJSON = function () {
      return _.assign({
        msg: msg
      }, metadata);
    };
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.505.505"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.</span>505 (msg, metadata)](#apidoc.element.elasticsearch.errors.505.505)
- description and source-code
```javascript
function StatusCodeError(msg, metadata) {
  this.status = status;
  this.displayName = className;

  var esErrObject = null;
  if (_.isPlainObject(msg)) {
    esErrObject = msg;
    msg = null;
  }

  if (!esErrObject) {
    // errors from es now come in two forms, an error string < 2.0 and
    // an object >= 2.0
    // TODO: remove after dropping support for < 2.0
    ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
    return this;
  }

  msg = [].concat(esErrObject.root_cause || []).reduce(function (memo, cause) {
    if (memo) memo += ' (and) ';

    memo += '[' + cause.type + '] ' + cause.reason;

    var extraData = _.omit(cause, ['type', 'reason']);
    if (_.size(extraData)) {
      memo += ', with ' + prettyPrint(extraData);
    }

    return memo;
  }, '');

  if (!msg) {
    if (esErrObject.type) msg += '[' + esErrObject.type + '] ';
    if (esErrObject.reason) msg += esErrObject.reason;
  }

  ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
  return this;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.elasticsearch.errors.506"></a>[module elasticsearch.errors.506](#apidoc.module.elasticsearch.errors.506)

#### <a name="apidoc.element.elasticsearch.errors.506.super_"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.506.</span>super_ (msg, constructor, metadata)](#apidoc.element.elasticsearch.errors.506.super_)
- description and source-code
```javascript
function ErrorAbstract(msg, constructor, metadata) {
  this.message = msg;

  Error.call(this, this.message);

  if (canCapture) {
    Error.captureStackTrace(this, constructor);
  }
  else if (canStack) {
    this.stack = (new Error()).stack;
  }
  else {
    this.stack = '';
  }

  if (metadata) {
    _.assign(this, metadata);

    this.toString = function () {
      return msg + ' :: ' + JSON.stringify(metadata);
    };

    this.toJSON = function () {
      return _.assign({
        msg: msg
      }, metadata);
    };
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.506.506"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.</span>506 (msg, metadata)](#apidoc.element.elasticsearch.errors.506.506)
- description and source-code
```javascript
function StatusCodeError(msg, metadata) {
  this.status = status;
  this.displayName = className;

  var esErrObject = null;
  if (_.isPlainObject(msg)) {
    esErrObject = msg;
    msg = null;
  }

  if (!esErrObject) {
    // errors from es now come in two forms, an error string < 2.0 and
    // an object >= 2.0
    // TODO: remove after dropping support for < 2.0
    ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
    return this;
  }

  msg = [].concat(esErrObject.root_cause || []).reduce(function (memo, cause) {
    if (memo) memo += ' (and) ';

    memo += '[' + cause.type + '] ' + cause.reason;

    var extraData = _.omit(cause, ['type', 'reason']);
    if (_.size(extraData)) {
      memo += ', with ' + prettyPrint(extraData);
    }

    return memo;
  }, '');

  if (!msg) {
    if (esErrObject.type) msg += '[' + esErrObject.type + '] ';
    if (esErrObject.reason) msg += esErrObject.reason;
  }

  ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
  return this;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.elasticsearch.errors.510"></a>[module elasticsearch.errors.510](#apidoc.module.elasticsearch.errors.510)

#### <a name="apidoc.element.elasticsearch.errors.510.super_"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.510.</span>super_ (msg, constructor, metadata)](#apidoc.element.elasticsearch.errors.510.super_)
- description and source-code
```javascript
function ErrorAbstract(msg, constructor, metadata) {
  this.message = msg;

  Error.call(this, this.message);

  if (canCapture) {
    Error.captureStackTrace(this, constructor);
  }
  else if (canStack) {
    this.stack = (new Error()).stack;
  }
  else {
    this.stack = '';
  }

  if (metadata) {
    _.assign(this, metadata);

    this.toString = function () {
      return msg + ' :: ' + JSON.stringify(metadata);
    };

    this.toJSON = function () {
      return _.assign({
        msg: msg
      }, metadata);
    };
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.510.510"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.</span>510 (msg, metadata)](#apidoc.element.elasticsearch.errors.510.510)
- description and source-code
```javascript
function StatusCodeError(msg, metadata) {
  this.status = status;
  this.displayName = className;

  var esErrObject = null;
  if (_.isPlainObject(msg)) {
    esErrObject = msg;
    msg = null;
  }

  if (!esErrObject) {
    // errors from es now come in two forms, an error string < 2.0 and
    // an object >= 2.0
    // TODO: remove after dropping support for < 2.0
    ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
    return this;
  }

  msg = [].concat(esErrObject.root_cause || []).reduce(function (memo, cause) {
    if (memo) memo += ' (and) ';

    memo += '[' + cause.type + '] ' + cause.reason;

    var extraData = _.omit(cause, ['type', 'reason']);
    if (_.size(extraData)) {
      memo += ', with ' + prettyPrint(extraData);
    }

    return memo;
  }, '');

  if (!msg) {
    if (esErrObject.type) msg += '[' + esErrObject.type + '] ';
    if (esErrObject.reason) msg += esErrObject.reason;
  }

  ErrorAbstract.call(this, msg || primaryName, StatusCodeError, metadata);
  return this;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.elasticsearch.errors.ConnectionFault"></a>[module elasticsearch.errors.ConnectionFault](#apidoc.module.elasticsearch.errors.ConnectionFault)

#### <a name="apidoc.element.elasticsearch.errors.ConnectionFault.ConnectionFault"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.</span>ConnectionFault (msg)](#apidoc.element.elasticsearch.errors.ConnectionFault.ConnectionFault)
- description and source-code
```javascript
function ConnectionFault(msg) {
  ErrorAbstract.call(this, msg || 'Connection Failure', errors.ConnectionFault);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.ConnectionFault.super_"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.ConnectionFault.</span>super_ (msg, constructor, metadata)](#apidoc.element.elasticsearch.errors.ConnectionFault.super_)
- description and source-code
```javascript
function ErrorAbstract(msg, constructor, metadata) {
  this.message = msg;

  Error.call(this, this.message);

  if (canCapture) {
    Error.captureStackTrace(this, constructor);
  }
  else if (canStack) {
    this.stack = (new Error()).stack;
  }
  else {
    this.stack = '';
  }

  if (metadata) {
    _.assign(this, metadata);

    this.toString = function () {
      return msg + ' :: ' + JSON.stringify(metadata);
    };

    this.toJSON = function () {
      return _.assign({
        msg: msg
      }, metadata);
    };
  }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.elasticsearch.errors.Generic"></a>[module elasticsearch.errors.Generic](#apidoc.module.elasticsearch.errors.Generic)

#### <a name="apidoc.element.elasticsearch.errors.Generic.Generic"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.</span>Generic (msg, metadata)](#apidoc.element.elasticsearch.errors.Generic.Generic)
- description and source-code
```javascript
function Generic(msg, metadata) {
  ErrorAbstract.call(this, msg || 'Generic Error', errors.Generic, metadata);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.Generic.super_"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.Generic.</span>super_ (msg, constructor, metadata)](#apidoc.element.elasticsearch.errors.Generic.super_)
- description and source-code
```javascript
function ErrorAbstract(msg, constructor, metadata) {
  this.message = msg;

  Error.call(this, this.message);

  if (canCapture) {
    Error.captureStackTrace(this, constructor);
  }
  else if (canStack) {
    this.stack = (new Error()).stack;
  }
  else {
    this.stack = '';
  }

  if (metadata) {
    _.assign(this, metadata);

    this.toString = function () {
      return msg + ' :: ' + JSON.stringify(metadata);
    };

    this.toJSON = function () {
      return _.assign({
        msg: msg
      }, metadata);
    };
  }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.elasticsearch.errors.NoConnections"></a>[module elasticsearch.errors.NoConnections](#apidoc.module.elasticsearch.errors.NoConnections)

#### <a name="apidoc.element.elasticsearch.errors.NoConnections.NoConnections"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.</span>NoConnections (msg)](#apidoc.element.elasticsearch.errors.NoConnections.NoConnections)
- description and source-code
```javascript
function NoConnections(msg) {
  ErrorAbstract.call(this, msg || 'No Living connections', errors.NoConnections);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.NoConnections.super_"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.NoConnections.</span>super_ (msg, constructor, metadata)](#apidoc.element.elasticsearch.errors.NoConnections.super_)
- description and source-code
```javascript
function ErrorAbstract(msg, constructor, metadata) {
  this.message = msg;

  Error.call(this, this.message);

  if (canCapture) {
    Error.captureStackTrace(this, constructor);
  }
  else if (canStack) {
    this.stack = (new Error()).stack;
  }
  else {
    this.stack = '';
  }

  if (metadata) {
    _.assign(this, metadata);

    this.toString = function () {
      return msg + ' :: ' + JSON.stringify(metadata);
    };

    this.toJSON = function () {
      return _.assign({
        msg: msg
      }, metadata);
    };
  }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.elasticsearch.errors.RequestTypeError"></a>[module elasticsearch.errors.RequestTypeError](#apidoc.module.elasticsearch.errors.RequestTypeError)

#### <a name="apidoc.element.elasticsearch.errors.RequestTypeError.RequestTypeError"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.</span>RequestTypeError (feature)](#apidoc.element.elasticsearch.errors.RequestTypeError.RequestTypeError)
- description and source-code
```javascript
function RequestTypeError(feature) {
  ErrorAbstract.call(this, 'Cross-domain AJAX requests ' + feature + ' are not supported', errors.RequestTypeError);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.RequestTypeError.super_"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.RequestTypeError.</span>super_ (msg, constructor, metadata)](#apidoc.element.elasticsearch.errors.RequestTypeError.super_)
- description and source-code
```javascript
function ErrorAbstract(msg, constructor, metadata) {
  this.message = msg;

  Error.call(this, this.message);

  if (canCapture) {
    Error.captureStackTrace(this, constructor);
  }
  else if (canStack) {
    this.stack = (new Error()).stack;
  }
  else {
    this.stack = '';
  }

  if (metadata) {
    _.assign(this, metadata);

    this.toString = function () {
      return msg + ' :: ' + JSON.stringify(metadata);
    };

    this.toJSON = function () {
      return _.assign({
        msg: msg
      }, metadata);
    };
  }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.elasticsearch.errors.Serialization"></a>[module elasticsearch.errors.Serialization](#apidoc.module.elasticsearch.errors.Serialization)

#### <a name="apidoc.element.elasticsearch.errors.Serialization.Serialization"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.</span>Serialization (msg)](#apidoc.element.elasticsearch.errors.Serialization.Serialization)
- description and source-code
```javascript
function Serialization(msg) {
  ErrorAbstract.call(this, msg || 'Unable to parse/serialize body', errors.Serialization);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors.Serialization.super_"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.Serialization.</span>super_ (msg, constructor, metadata)](#apidoc.element.elasticsearch.errors.Serialization.super_)
- description and source-code
```javascript
function ErrorAbstract(msg, constructor, metadata) {
  this.message = msg;

  Error.call(this, this.message);

  if (canCapture) {
    Error.captureStackTrace(this, constructor);
  }
  else if (canStack) {
    this.stack = (new Error()).stack;
  }
  else {
    this.stack = '';
  }

  if (metadata) {
    _.assign(this, metadata);

    this.toString = function () {
      return msg + ' :: ' + JSON.stringify(metadata);
    };

    this.toJSON = function () {
      return _.assign({
        msg: msg
      }, metadata);
    };
  }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.elasticsearch.errors._Abstract"></a>[module elasticsearch.errors._Abstract](#apidoc.module.elasticsearch.errors._Abstract)

#### <a name="apidoc.element.elasticsearch.errors._Abstract._Abstract"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors.</span>_Abstract (msg, constructor, metadata)](#apidoc.element.elasticsearch.errors._Abstract._Abstract)
- description and source-code
```javascript
function ErrorAbstract(msg, constructor, metadata) {
  this.message = msg;

  Error.call(this, this.message);

  if (canCapture) {
    Error.captureStackTrace(this, constructor);
  }
  else if (canStack) {
    this.stack = (new Error()).stack;
  }
  else {
    this.stack = '';
  }

  if (metadata) {
    _.assign(this, metadata);

    this.toString = function () {
      return msg + ' :: ' + JSON.stringify(metadata);
    };

    this.toJSON = function () {
      return _.assign({
        msg: msg
      }, metadata);
    };
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.elasticsearch.errors._Abstract.super_"></a>[function <span class="apidocSignatureSpan">elasticsearch.errors._Abstract.</span>super_ ()](#apidoc.element.elasticsearch.errors._Abstract.super_)
- description and source-code
```javascript
function Error() { [native code] }
```
- example usage
```shell
n/a
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
