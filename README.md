# api documentation for  [googleapis (v18.0.0)](https://github.com/google/google-api-nodejs-client#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-googleapis.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-googleapis) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-googleapis.svg)](https://travis-ci.org/npmdoc/node-npmdoc-googleapis)
#### Google APIs Client Library for Node.js

[![NPM](https://nodei.co/npm/googleapis.png?downloads=true)](https://www.npmjs.com/package/googleapis)

[![apidoc](https://npmdoc.github.io/node-npmdoc-googleapis/build/screenCapture.buildNpmdoc.browser.%2Fhome%2Ftravis%2Fbuild%2Fnpmdoc%2Fnode-npmdoc-googleapis%2Ftmp%2Fbuild%2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-googleapis/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-googleapis/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-googleapis/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Google Inc."
    },
    "bugs": {
        "url": "https://github.com/google/google-api-nodejs-client/issues"
    },
    "contributors": [
        {
            "name": "Burcu Dogan",
            "email": "jbd@google.com"
        },
        {
            "name": "Jason Allor",
            "email": "jasonall@google.com"
        },
        {
            "name": "Jason Dobry",
            "email": "jason.dobry@gmail.com"
        },
        {
            "name": "Ryan Seys",
            "email": "ryanseys@google.com"
        },
        {
            "name": "Tim Emiola",
            "email": "tbetbetbe@google.com"
        },
        {
            "name": "Justin Beckwith",
            "email": "beckwith@google.com"
        }
    ],
    "dependencies": {
        "async": "~2.1.4",
        "google-auth-library": "~0.10.0",
        "string-template": "~1.0.0"
    },
    "description": "Google APIs Client Library for Node.js",
    "devDependencies": {
        "ink-docstrap": "1.3.0",
        "intelli-espower-loader": "1.0.1",
        "js-beautify": "1.6.11",
        "jsdoc": "3.4.3",
        "minimist": "1.2.0",
        "mkdirp": "0.5.1",
        "mocha": "3.2.0",
        "nock": "9.0.9",
        "nyc": "10.1.2",
        "power-assert": "1.4.2",
        "rimraf": "2.6.1",
        "semistandard": "10.0.0",
        "swig": "1.4.2"
    },
    "directories": {},
    "dist": {
        "shasum": "76c7c8b7e3fadb61eac44389a9beaee9240ddf01",
        "tarball": "https://registry.npmjs.org/googleapis/-/googleapis-18.0.0.tgz"
    },
    "engines": {
        "node": ">=0.10"
    },
    "gitHead": "8493e2f60343f570574af6d2404e9bb2f0997406",
    "homepage": "https://github.com/google/google-api-nodejs-client#readme",
    "keywords": [
        "google",
        "api",
        "google apis",
        "client",
        "client library"
    ],
    "license": "Apache-2.0",
    "main": "./lib/googleapis.js",
    "maintainers": [
        {
            "name": "googleapis-packages",
            "email": "googleapis-packages@google.com"
        },
        {
            "name": "jdobry",
            "email": "jason.dobry@gmail.com"
        },
        {
            "name": "ryanseys",
            "email": "ryan@ryanseys.com"
        },
        {
            "name": "tbetbetbe",
            "email": "temiola@google.com"
        },
        {
            "name": "thejbf",
            "email": "burcujdogan@gmail.com"
        }
    ],
    "name": "googleapis",
    "nyc": {
        "exclude": [
            "apis"
        ]
    },
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/google/google-api-nodejs-client.git"
    },
    "scripts": {
        "cover": "nyc --cache mocha test/ --recursive -t 10000 -S -R spec --require intelli-espower-loader && nyc report --reporter=html",
        "doc": "jsdoc -c jsdoc-conf.json",
        "generate-apis": "node scripts/generate",
        "lint": "semistandard \"**/*.js\"",
        "mocha": "mocha test/ --recursive -t 10000 -S -R spec --require intelli-espower-loader",
        "prepare": "npm run generate-apis && npm test",
        "test": "npm run lint && npm run cover"
    },
    "semistandard": {
        "globals": [
            "after",
            "afterEach",
            "before",
            "beforeEach",
            "describe",
            "it"
        ],
        "ignore": [
            "apis",
            "templates/*"
        ]
    },
    "version": "18.0.0"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module googleapis](#apidoc.module.googleapis)
1.  [function <span class="apidocSignatureSpan">googleapis.</span>GoogleApis (options)](#apidoc.element.googleapis.GoogleApis)
1.  [function <span class="apidocSignatureSpan">googleapis.</span>acceleratedmobilepageurl ()](#apidoc.element.googleapis.acceleratedmobilepageurl)
1.  [function <span class="apidocSignatureSpan">googleapis.</span>adexchangebuyer ()](#apidoc.element.googleapis.adexchangebuyer)
1.  [function <span class="apidocSignatureSpan">googleapis.</span>adexchangebuyer2 ()](#apidoc.element.googleapis.adexchangebuyer2)
1.  [function <span class="apidocSignatureSpan">googleapis.</span>adexchangeseller ()](#apidoc.element.googleapis.adexchangeseller)
1.  [function <span class="apidocSignatureSpan">googleapis.</span>admin ()](#apidoc.element.googleapis.admin)
1.  [function <span class="apidocSignatureSpan">googleapis.</span>adsense ()](#apidoc.element.googleapis.adsense)
1.  [function <span class="apidocSignatureSpan">googleapis.</span>adsensehost ()](#apidoc.element.googleapis.adsensehost)
1.  [function <span class="apidocSignatureSpan">googleapis.</span>analytics ()](#apidoc.element.googleapis.analytics)
1.  [function <span class="apidocSignatureSpan">googleapis.</span>analyticsreporting ()](#apidoc.element.googleapis.analyticsreporting)
1.  [function <span class="apidocSignatureSpan">googleapis.</span>androidenterprise ()](#apidoc.element.googleapis.androidenterprise)
1.  [function <span class="apidocSignatureSpan">googleapis.</span>androidpublisher ()](#apidoc.element.googleapis.androidpublisher)
1.  [function <span class="apidocSignatureSpan">googleapis.</span>appengine ()](#apidoc.element.googleapis.appengine)
1.  [function <span class="apidocSignatureSpan">googleapis.</span>appsactivity ()](#apidoc.element.googleapis.appsactivity)
1.  [function <span class="apidocSignatureSpan">googleapis.</span>appstate ()](#apidoc.element.googleapis.appstate)
1.  [function <span class="apidocSignatureSpan">googleapis.</span>auth.ComputeClient ()](#apidoc.element.googleapis.auth.ComputeClient)
1.  [function <span class="apidocSignatureSpan">googleapis.</span>auth.JWTClient (email, keyFile, key, scopes, subject)](#apidoc.element.googleapis.auth.JWTClient)
1.  [function <span class="apidocSignatureSpan">googleapis.</span>bigquery ()](#apidoc.element.googleapis.bigquery)
1.  [function <span class="apidocSignatureSpan">googleapis.</span>blogger ()](#apidoc.element.googleapis.blogger)
1.  [function <span class="apidocSignatureSpan">googleapis.</span>books ()](#apidoc.element.googleapis.books)
1.  [function <span class="apidocSignatureSpan">googleapis.</span>calendar ()](#apidoc.element.googleapis.calendar)
1.  [function <span class="apidocSignatureSpan">googleapis.</span>civicinfo ()](#apidoc.element.googleapis.civicinfo)
1.  [function <span class="apidocSignatureSpan">googleapis.</span>classroom ()](#apidoc.element.googleapis.classroom)
1.  [function <span class="apidocSignatureSpan">googleapis.</span>cloudbilling ()](#apidoc.element.googleapis.cloudbilling)
1.  [function <span class="apidocSignatureSpan">googleapis.</span>cloudbuild ()](#apidoc.element.googleapis.cloudbuild)
1.  [function <span class="apidocSignatureSpan">googleapis.</span>clouddebugger ()](#apidoc.element.googleapis.clouddebugger)
1.  [function <span class="apidocSignatureSpan">googleapis.</span>clouderrorreporting ()](#apidoc.element.googleapis.clouderrorreporting)
1.  [function <span class="apidocSignatureSpan">googleapis.</span>cloudfunctions ()](#apidoc.element.googleapis.cloudfunctions)
1.  [function <span class="apidocSignatureSpan">googleapis.</span>cloudkms ()](#apidoc.element.googleapis.cloudkms)
1.  [function <span class="apidocSignatureSpan">googleapis.</span>cloudmonitoring ()](#apidoc.element.googleapis.cloudmonitoring)
1.  [function <span class="apidocSignatureSpan">googleapis.</span>cloudresourcemanager ()](#apidoc.element.googleapis.cloudresourcemanager)
1.  [function <span class="apidocSignatureSpan">googleapis.</span>cloudtrace ()](#apidoc.element.googleapis.cloudtrace)
1.  [function <span class="apidocSignatureSpan">googleapis.</span>clouduseraccounts ()](#apidoc.element.googleapis.clouduseraccounts)
1.  [function <span class="apidocSignatureSpan">googleapis.</span>compute ()](#apidoc.element.googleapis.compute)
1.  [function <span class="apidocSignatureSpan">googleapis.</span>consumersurveys ()](#apidoc.element.googleapis.consumersurveys)
1.  [function <span class="apidocSignatureSpan">googleapis.</span>container ()](#apidoc.element.googleapis.container)
1.  [function <span class="apidocSignatureSpan">googleapis.</span>content ()](#apidoc.element.googleapis.content)
1.  [function <span class="apidocSignatureSpan">googleapis.</span>customsearch ()](#apidoc.element.googleapis.customsearch)
1.  [function <span class="apidocSignatureSpan">googleapis.</span>dataflow ()](#apidoc.element.googleapis.dataflow)
1.  [function <span class="apidocSignatureSpan">googleapis.</span>dataproc ()](#apidoc.element.googleapis.dataproc)
1.  [function <span class="apidocSignatureSpan">googleapis.</span>datastore ()](#apidoc.element.googleapis.datastore)
1.  [function <span class="apidocSignatureSpan">googleapis.</span>deploymentmanager ()](#apidoc.element.googleapis.deploymentmanager)
1.  [function <span class="apidocSignatureSpan">googleapis.</span>dfareporting ()](#apidoc.element.googleapis.dfareporting)
1.  [function <span class="apidocSignatureSpan">googleapis.</span>discovery ()](#apidoc.element.googleapis.discovery)
1.  [function <span class="apidocSignatureSpan">googleapis.</span>dns ()](#apidoc.element.googleapis.dns)
1.  [function <span class="apidocSignatureSpan">googleapis.</span>doubleclickbidmanager ()](#apidoc.element.googleapis.doubleclickbidmanager)
1.  [function <span class="apidocSignatureSpan">googleapis.</span>doubleclicksearch ()](#apidoc.element.googleapis.doubleclicksearch)
1.  [function <span class="apidocSignatureSpan">googleapis.</span>drive ()](#apidoc.element.googleapis.drive)
1.  [function <span class="apidocSignatureSpan">googleapis.</span>firebasedynamiclinks ()](#apidoc.element.googleapis.firebasedynamiclinks)
1.  [function <span class="apidocSignatureSpan">googleapis.</span>firebaserules ()](#apidoc.element.googleapis.firebaserules)
1.  [function <span class="apidocSignatureSpan">googleapis.</span>fitness ()](#apidoc.element.googleapis.fitness)
1.  [function <span class="apidocSignatureSpan">googleapis.</span>fusiontables ()](#apidoc.element.googleapis.fusiontables)
1.  [function <span class="apidocSignatureSpan">googleapis.</span>games ()](#apidoc.element.googleapis.games)
1.  [function <span class="apidocSignatureSpan">googleapis.</span>gamesConfiguration ()](#apidoc.element.googleapis.gamesConfiguration)
1.  [function <span class="apidocSignatureSpan">googleapis.</span>gamesManagement ()](#apidoc.element.googleapis.gamesManagement)
1.  [function <span class="apidocSignatureSpan">googleapis.</span>genomics ()](#apidoc.element.googleapis.genomics)
1.  [function <span class="apidocSignatureSpan">googleapis.</span>gmail ()](#apidoc.element.googleapis.gmail)
1.  [function <span class="apidocSignatureSpan">googleapis.</span>groupsmigration ()](#apidoc.element.googleapis.groupsmigration)
1.  [function <span class="apidocSignatureSpan">googleapis.</span>groupssettings ()](#apidoc.element.googleapis.groupssettings)
1.  [function <span class="apidocSignatureSpan">googleapis.</span>iam ()](#apidoc.element.googleapis.iam)
1.  [function <span class="apidocSignatureSpan">googleapis.</span>identitytoolkit ()](#apidoc.element.googleapis.identitytoolkit)
1.  [function <span class="apidocSignatureSpan">googleapis.</span>kgsearch ()](#apidoc.element.googleapis.kgsearch)
1.  [function <span class="apidocSignatureSpan">googleapis.</span>language ()](#apidoc.element.googleapis.language)
1.  [function <span class="apidocSignatureSpan">googleapis.</span>licensing ()](#apidoc.element.googleapis.licensing)
1.  [function <span class="apidocSignatureSpan">googleapis.</span>logging ()](#apidoc.element.googleapis.logging)
1.  [function <span class="apidocSignatureSpan">googleapis.</span>manufacturers ()](#apidoc.element.googleapis.manufacturers)
1.  [function <span class="apidocSignatureSpan">googleapis.</span>mirror ()](#apidoc.element.googleapis.mirror)
1.  [function <span class="apidocSignatureSpan">googleapis.</span>ml ()](#apidoc.element.googleapis.ml)
1.  [function <span class="apidocSignatureSpan">googleapis.</span>monitoring ()](#apidoc.element.googleapis.monitoring)
1.  [function <span class="apidocSignatureSpan">googleapis.</span>oauth2 ()](#apidoc.element.googleapis.oauth2)
1.  [function <span class="apidocSignatureSpan">googleapis.</span>pagespeedonline ()](#apidoc.element.googleapis.pagespeedonline)
1.  [function <span class="apidocSignatureSpan">googleapis.</span>partners ()](#apidoc.element.googleapis.partners)
1.  [function <span class="apidocSignatureSpan">googleapis.</span>people ()](#apidoc.element.googleapis.people)
1.  [function <span class="apidocSignatureSpan">googleapis.</span>playmoviespartner ()](#apidoc.element.googleapis.playmoviespartner)
1.  [function <span class="apidocSignatureSpan">googleapis.</span>plus ()](#apidoc.element.googleapis.plus)
1.  [function <span class="apidocSignatureSpan">googleapis.</span>plusDomains ()](#apidoc.element.googleapis.plusDomains)
1.  [function <span class="apidocSignatureSpan">googleapis.</span>prediction ()](#apidoc.element.googleapis.prediction)
1.  [function <span class="apidocSignatureSpan">googleapis.</span>proximitybeacon ()](#apidoc.element.googleapis.proximitybeacon)
1.  [function <span class="apidocSignatureSpan">googleapis.</span>pubsub ()](#apidoc.element.googleapis.pubsub)
1.  [function <span class="apidocSignatureSpan">googleapis.</span>qpxExpress ()](#apidoc.element.googleapis.qpxExpress)
1.  [function <span class="apidocSignatureSpan">googleapis.</span>replicapool ()](#apidoc.element.googleapis.replicapool)
1.  [function <span class="apidocSignatureSpan">googleapis.</span>replicapoolupdater ()](#apidoc.element.googleapis.replicapoolupdater)
1.  [function <span class="apidocSignatureSpan">googleapis.</span>reseller ()](#apidoc.element.googleapis.reseller)
1.  [function <span class="apidocSignatureSpan">googleapis.</span>resourceviews ()](#apidoc.element.googleapis.resourceviews)
1.  [function <span class="apidocSignatureSpan">googleapis.</span>runtimeconfig ()](#apidoc.element.googleapis.runtimeconfig)
1.  [function <span class="apidocSignatureSpan">googleapis.</span>safebrowsing ()](#apidoc.element.googleapis.safebrowsing)
1.  [function <span class="apidocSignatureSpan">googleapis.</span>script ()](#apidoc.element.googleapis.script)
1.  [function <span class="apidocSignatureSpan">googleapis.</span>searchconsole ()](#apidoc.element.googleapis.searchconsole)
1.  [function <span class="apidocSignatureSpan">googleapis.</span>servicecontrol ()](#apidoc.element.googleapis.servicecontrol)
1.  [function <span class="apidocSignatureSpan">googleapis.</span>servicemanagement ()](#apidoc.element.googleapis.servicemanagement)
1.  [function <span class="apidocSignatureSpan">googleapis.</span>serviceuser ()](#apidoc.element.googleapis.serviceuser)
1.  [function <span class="apidocSignatureSpan">googleapis.</span>sheets ()](#apidoc.element.googleapis.sheets)
1.  [function <span class="apidocSignatureSpan">googleapis.</span>siteVerification ()](#apidoc.element.googleapis.siteVerification)
1.  [function <span class="apidocSignatureSpan">googleapis.</span>slides ()](#apidoc.element.googleapis.slides)
1.  [function <span class="apidocSignatureSpan">googleapis.</span>sourcerepo ()](#apidoc.element.googleapis.sourcerepo)
1.  [function <span class="apidocSignatureSpan">googleapis.</span>spanner ()](#apidoc.element.googleapis.spanner)
1.  [function <span class="apidocSignatureSpan">googleapis.</span>spectrum ()](#apidoc.element.googleapis.spectrum)
1.  [function <span class="apidocSignatureSpan">googleapis.</span>speech ()](#apidoc.element.googleapis.speech)
1.  [function <span class="apidocSignatureSpan">googleapis.</span>sqladmin ()](#apidoc.element.googleapis.sqladmin)
1.  [function <span class="apidocSignatureSpan">googleapis.</span>storage ()](#apidoc.element.googleapis.storage)
1.  [function <span class="apidocSignatureSpan">googleapis.</span>storagetransfer ()](#apidoc.element.googleapis.storagetransfer)
1.  [function <span class="apidocSignatureSpan">googleapis.</span>surveys ()](#apidoc.element.googleapis.surveys)
1.  [function <span class="apidocSignatureSpan">googleapis.</span>tagmanager ()](#apidoc.element.googleapis.tagmanager)
1.  [function <span class="apidocSignatureSpan">googleapis.</span>taskqueue ()](#apidoc.element.googleapis.taskqueue)
1.  [function <span class="apidocSignatureSpan">googleapis.</span>tasks ()](#apidoc.element.googleapis.tasks)
1.  [function <span class="apidocSignatureSpan">googleapis.</span>toolresults ()](#apidoc.element.googleapis.toolresults)
1.  [function <span class="apidocSignatureSpan">googleapis.</span>tracing ()](#apidoc.element.googleapis.tracing)
1.  [function <span class="apidocSignatureSpan">googleapis.</span>translate ()](#apidoc.element.googleapis.translate)
1.  [function <span class="apidocSignatureSpan">googleapis.</span>transporters ()](#apidoc.element.googleapis.transporters)
1.  [function <span class="apidocSignatureSpan">googleapis.</span>urlshortener ()](#apidoc.element.googleapis.urlshortener)
1.  [function <span class="apidocSignatureSpan">googleapis.</span>vision ()](#apidoc.element.googleapis.vision)
1.  [function <span class="apidocSignatureSpan">googleapis.</span>webfonts ()](#apidoc.element.googleapis.webfonts)
1.  [function <span class="apidocSignatureSpan">googleapis.</span>webmasters ()](#apidoc.element.googleapis.webmasters)
1.  [function <span class="apidocSignatureSpan">googleapis.</span>youtube ()](#apidoc.element.googleapis.youtube)
1.  [function <span class="apidocSignatureSpan">googleapis.</span>youtubeAnalytics ()](#apidoc.element.googleapis.youtubeAnalytics)
1.  [function <span class="apidocSignatureSpan">googleapis.</span>youtubereporting ()](#apidoc.element.googleapis.youtubereporting)
1.  object <span class="apidocSignatureSpan">googleapis.</span>GoogleApis.prototype
1.  object <span class="apidocSignatureSpan">googleapis.</span>_options
1.  object <span class="apidocSignatureSpan">googleapis.</span>auth
1.  object <span class="apidocSignatureSpan">googleapis.</span>auth.ComputeClient.prototype
1.  object <span class="apidocSignatureSpan">googleapis.</span>auth.ComputeClient.super_.prototype
1.  object <span class="apidocSignatureSpan">googleapis.</span>auth.JWTClient.prototype
1.  object <span class="apidocSignatureSpan">googleapis.</span>discovery.prototype
1.  object <span class="apidocSignatureSpan">googleapis.</span>generator_utils
1.  object <span class="apidocSignatureSpan">googleapis.</span>transporters.prototype
1.  object <span class="apidocSignatureSpan">googleapis.</span>utils

#### [module googleapis.GoogleApis](#apidoc.module.googleapis.GoogleApis)
1.  [function <span class="apidocSignatureSpan">googleapis.</span>GoogleApis (options)](#apidoc.element.googleapis.GoogleApis.GoogleApis)

#### [module googleapis.GoogleApis.prototype](#apidoc.module.googleapis.GoogleApis.prototype)
1.  [function <span class="apidocSignatureSpan">googleapis.GoogleApis.prototype.</span>addAPIs (apis)](#apidoc.element.googleapis.GoogleApis.prototype.addAPIs)
1.  [function <span class="apidocSignatureSpan">googleapis.GoogleApis.prototype.</span>discover (url, callback)](#apidoc.element.googleapis.GoogleApis.prototype.discover)
1.  [function <span class="apidocSignatureSpan">googleapis.GoogleApis.prototype.</span>discoverAPI (path, options, callback)](#apidoc.element.googleapis.GoogleApis.prototype.discoverAPI)
1.  [function <span class="apidocSignatureSpan">googleapis.GoogleApis.prototype.</span>options (options)](#apidoc.element.googleapis.GoogleApis.prototype.options)

#### [module googleapis.auth](#apidoc.module.googleapis.auth)
1.  [function <span class="apidocSignatureSpan">googleapis.auth.</span>ComputeClient ()](#apidoc.element.googleapis.auth.ComputeClient)
1.  [function <span class="apidocSignatureSpan">googleapis.auth.</span>JWTClient (email, keyFile, key, scopes, subject)](#apidoc.element.googleapis.auth.JWTClient)
1.  object <span class="apidocSignatureSpan">googleapis.auth.</span>_cachedCredential

#### [module googleapis.auth.ComputeClient](#apidoc.module.googleapis.auth.ComputeClient)
1.  [function <span class="apidocSignatureSpan">googleapis.auth.</span>ComputeClient ()](#apidoc.element.googleapis.auth.ComputeClient.ComputeClient)
1.  [function <span class="apidocSignatureSpan">googleapis.auth.ComputeClient.</span>super_ (clientId, clientSecret, redirectUri, opt_opts)](#apidoc.element.googleapis.auth.ComputeClient.super_)
1.  string <span class="apidocSignatureSpan">googleapis.auth.ComputeClient.</span>GOOGLE_OAUTH2_TOKEN_URL_

#### [module googleapis.auth.ComputeClient.prototype](#apidoc.module.googleapis.auth.ComputeClient.prototype)
1.  [function <span class="apidocSignatureSpan">googleapis.auth.ComputeClient.prototype.</span>_injectErrorMessage (err, result, response, callback)](#apidoc.element.googleapis.auth.ComputeClient.prototype._injectErrorMessage)
1.  [function <span class="apidocSignatureSpan">googleapis.auth.ComputeClient.prototype.</span>createScopedRequired ()](#apidoc.element.googleapis.auth.ComputeClient.prototype.createScopedRequired)
1.  [function <span class="apidocSignatureSpan">googleapis.auth.ComputeClient.prototype.</span>refreshToken_ (ignored_, opt_callback)](#apidoc.element.googleapis.auth.ComputeClient.prototype.refreshToken_)

#### [module googleapis.auth.ComputeClient.super_.prototype](#apidoc.module.googleapis.auth.ComputeClient.super_.prototype)
1.  [function <span class="apidocSignatureSpan">googleapis.auth.ComputeClient.super_.prototype.</span>_makeRequest (opts, callback)](#apidoc.element.googleapis.auth.ComputeClient.super_.prototype._makeRequest)
1.  [function <span class="apidocSignatureSpan">googleapis.auth.ComputeClient.super_.prototype.</span>_postRequest (err, result, response, callback)](#apidoc.element.googleapis.auth.ComputeClient.super_.prototype._postRequest)
1.  [function <span class="apidocSignatureSpan">googleapis.auth.ComputeClient.super_.prototype.</span>decodeBase64 (b64String)](#apidoc.element.googleapis.auth.ComputeClient.super_.prototype.decodeBase64)
1.  [function <span class="apidocSignatureSpan">googleapis.auth.ComputeClient.super_.prototype.</span>generateAuthUrl (opt_opts)](#apidoc.element.googleapis.auth.ComputeClient.super_.prototype.generateAuthUrl)
1.  [function <span class="apidocSignatureSpan">googleapis.auth.ComputeClient.super_.prototype.</span>getAccessToken (callback)](#apidoc.element.googleapis.auth.ComputeClient.super_.prototype.getAccessToken)
1.  [function <span class="apidocSignatureSpan">googleapis.auth.ComputeClient.super_.prototype.</span>getFederatedSignonCerts (callback)](#apidoc.element.googleapis.auth.ComputeClient.super_.prototype.getFederatedSignonCerts)
1.  [function <span class="apidocSignatureSpan">googleapis.auth.ComputeClient.super_.prototype.</span>getRequestMetadata (opt_uri, metadataCb)](#apidoc.element.googleapis.auth.ComputeClient.super_.prototype.getRequestMetadata)
1.  [function <span class="apidocSignatureSpan">googleapis.auth.ComputeClient.super_.prototype.</span>getToken (code, opt_callback)](#apidoc.element.googleapis.auth.ComputeClient.super_.prototype.getToken)
1.  [function <span class="apidocSignatureSpan">googleapis.auth.ComputeClient.super_.prototype.</span>refreshAccessToken (callback)](#apidoc.element.googleapis.auth.ComputeClient.super_.prototype.refreshAccessToken)
1.  [function <span class="apidocSignatureSpan">googleapis.auth.ComputeClient.super_.prototype.</span>refreshToken_ (refresh_token, opt_callback)](#apidoc.element.googleapis.auth.ComputeClient.super_.prototype.refreshToken_)
1.  [function <span class="apidocSignatureSpan">googleapis.auth.ComputeClient.super_.prototype.</span>request (opts, callback)](#apidoc.element.googleapis.auth.ComputeClient.super_.prototype.request)
1.  [function <span class="apidocSignatureSpan">googleapis.auth.ComputeClient.super_.prototype.</span>revokeCredentials (callback)](#apidoc.element.googleapis.auth.ComputeClient.super_.prototype.revokeCredentials)
1.  [function <span class="apidocSignatureSpan">googleapis.auth.ComputeClient.super_.prototype.</span>revokeToken (token, opt_callback)](#apidoc.element.googleapis.auth.ComputeClient.super_.prototype.revokeToken)
1.  [function <span class="apidocSignatureSpan">googleapis.auth.ComputeClient.super_.prototype.</span>verifyIdToken (idToken, audience, callback)](#apidoc.element.googleapis.auth.ComputeClient.super_.prototype.verifyIdToken)
1.  [function <span class="apidocSignatureSpan">googleapis.auth.ComputeClient.super_.prototype.</span>verifySignedJwtWithCerts (jwt, certs, requiredAudience, issuers, maxExpiry)](#apidoc.element.googleapis.auth.ComputeClient.super_.prototype.verifySignedJwtWithCerts)

#### [module googleapis.auth.JWTClient](#apidoc.module.googleapis.auth.JWTClient)
1.  [function <span class="apidocSignatureSpan">googleapis.auth.</span>JWTClient (email, keyFile, key, scopes, subject)](#apidoc.element.googleapis.auth.JWTClient.JWTClient)
1.  [function <span class="apidocSignatureSpan">googleapis.auth.JWTClient.</span>super_ (clientId, clientSecret, redirectUri, opt_opts)](#apidoc.element.googleapis.auth.JWTClient.super_)

#### [module googleapis.auth.JWTClient.prototype](#apidoc.module.googleapis.auth.JWTClient.prototype)
1.  [function <span class="apidocSignatureSpan">googleapis.auth.JWTClient.prototype.</span>_createGToken (callback)](#apidoc.element.googleapis.auth.JWTClient.prototype._createGToken)
1.  [function <span class="apidocSignatureSpan">googleapis.auth.JWTClient.prototype.</span>authorize (opt_callback)](#apidoc.element.googleapis.auth.JWTClient.prototype.authorize)
1.  [function <span class="apidocSignatureSpan">googleapis.auth.JWTClient.prototype.</span>createScoped (scopes)](#apidoc.element.googleapis.auth.JWTClient.prototype.createScoped)
1.  [function <span class="apidocSignatureSpan">googleapis.auth.JWTClient.prototype.</span>createScopedRequired ()](#apidoc.element.googleapis.auth.JWTClient.prototype.createScopedRequired)
1.  [function <span class="apidocSignatureSpan">googleapis.auth.JWTClient.prototype.</span>fromJSON (json, opt_callback)](#apidoc.element.googleapis.auth.JWTClient.prototype.fromJSON)
1.  [function <span class="apidocSignatureSpan">googleapis.auth.JWTClient.prototype.</span>fromStream (stream, opt_callback)](#apidoc.element.googleapis.auth.JWTClient.prototype.fromStream)
1.  [function <span class="apidocSignatureSpan">googleapis.auth.JWTClient.prototype.</span>getRequestMetadata (opt_uri, metadataCb)](#apidoc.element.googleapis.auth.JWTClient.prototype.getRequestMetadata)
1.  [function <span class="apidocSignatureSpan">googleapis.auth.JWTClient.prototype.</span>refreshToken_ (ignored_, opt_callback)](#apidoc.element.googleapis.auth.JWTClient.prototype.refreshToken_)

#### [module googleapis.discovery](#apidoc.module.googleapis.discovery)
1.  [function <span class="apidocSignatureSpan">googleapis.</span>discovery (options)](#apidoc.element.googleapis.discovery.discovery)

#### [module googleapis.discovery.prototype](#apidoc.module.googleapis.discovery.prototype)
1.  [function <span class="apidocSignatureSpan">googleapis.discovery.prototype.</span>discoverAPI (apiDiscoveryUrl, callback)](#apidoc.element.googleapis.discovery.prototype.discoverAPI)
1.  [function <span class="apidocSignatureSpan">googleapis.discovery.prototype.</span>discoverAllAPIs (discoveryUrl, callback)](#apidoc.element.googleapis.discovery.prototype.discoverAllAPIs)
1.  [function <span class="apidocSignatureSpan">googleapis.discovery.prototype.</span>log ()](#apidoc.element.googleapis.discovery.prototype.log)

#### [module googleapis.generator_utils](#apidoc.module.googleapis.generator_utils)
1.  [function <span class="apidocSignatureSpan">googleapis.generator_utils.</span>DefaultTransporter ()](#apidoc.element.googleapis.generator_utils.DefaultTransporter)
1.  [function <span class="apidocSignatureSpan">googleapis.generator_utils.</span>buildurl (input)](#apidoc.element.googleapis.generator_utils.buildurl)
1.  [function <span class="apidocSignatureSpan">googleapis.generator_utils.</span>handleError (err, callback)](#apidoc.element.googleapis.generator_utils.handleError)

#### [module googleapis.transporters](#apidoc.module.googleapis.transporters)
1.  [function <span class="apidocSignatureSpan">googleapis.</span>transporters ()](#apidoc.element.googleapis.transporters.transporters)

#### [module googleapis.transporters.prototype](#apidoc.module.googleapis.transporters.prototype)
1.  [function <span class="apidocSignatureSpan">googleapis.transporters.prototype.</span>configure (opts)](#apidoc.element.googleapis.transporters.prototype.configure)
1.  [function <span class="apidocSignatureSpan">googleapis.transporters.prototype.</span>request (opts, opt_callback)](#apidoc.element.googleapis.transporters.prototype.request)
1.  [function <span class="apidocSignatureSpan">googleapis.transporters.prototype.</span>wrapCallback_ (opt_callback)](#apidoc.element.googleapis.transporters.prototype.wrapCallback_)
1.  string <span class="apidocSignatureSpan">googleapis.transporters.prototype.</span>USER_AGENT

#### [module googleapis.utils](#apidoc.module.googleapis.utils)
1.  [function <span class="apidocSignatureSpan">googleapis.utils.</span>extend (obj)](#apidoc.element.googleapis.utils.extend)



# <a name="apidoc.module.googleapis"></a>[module googleapis](#apidoc.module.googleapis)

#### <a name="apidoc.element.googleapis.GoogleApis"></a>[function <span class="apidocSignatureSpan">googleapis.</span>GoogleApis (options)](#apidoc.element.googleapis.GoogleApis)
- description and source-code
```javascript
function GoogleApis(options) {
  this.options(options);
  this.addAPIs(apis);

<span class="apidocCodeCommentSpan">  /**
   * A reference to an instance of GoogleAuth.
   *
   * @name GoogleApis#auth
   * @type {GoogleAuth}
   */
</span>  this.auth = new GoogleAuth();

  /**
   * A reference to the {@link GoogleApis} constructor function.
   *
   * @name GoogleApis#GoogleApis
   * @see GoogleApis
   * @type {Function}
   */
  this.GoogleApis = GoogleApis;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.googleapis.acceleratedmobilepageurl"></a>[function <span class="apidocSignatureSpan">googleapis.</span>acceleratedmobilepageurl ()](#apidoc.element.googleapis.acceleratedmobilepageurl)
- description and source-code
```javascript
acceleratedmobilepageurl = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.googleapis.adexchangebuyer"></a>[function <span class="apidocSignatureSpan">googleapis.</span>adexchangebuyer ()](#apidoc.element.googleapis.adexchangebuyer)
- description and source-code
```javascript
adexchangebuyer = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.googleapis.adexchangebuyer2"></a>[function <span class="apidocSignatureSpan">googleapis.</span>adexchangebuyer2 ()](#apidoc.element.googleapis.adexchangebuyer2)
- description and source-code
```javascript
adexchangebuyer2 = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.googleapis.adexchangeseller"></a>[function <span class="apidocSignatureSpan">googleapis.</span>adexchangeseller ()](#apidoc.element.googleapis.adexchangeseller)
- description and source-code
```javascript
adexchangeseller = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.googleapis.admin"></a>[function <span class="apidocSignatureSpan">googleapis.</span>admin ()](#apidoc.element.googleapis.admin)
- description and source-code
```javascript
admin = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.googleapis.adsense"></a>[function <span class="apidocSignatureSpan">googleapis.</span>adsense ()](#apidoc.element.googleapis.adsense)
- description and source-code
```javascript
adsense = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.googleapis.adsensehost"></a>[function <span class="apidocSignatureSpan">googleapis.</span>adsensehost ()](#apidoc.element.googleapis.adsensehost)
- description and source-code
```javascript
adsensehost = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.googleapis.analytics"></a>[function <span class="apidocSignatureSpan">googleapis.</span>analytics ()](#apidoc.element.googleapis.analytics)
- description and source-code
```javascript
analytics = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.googleapis.analyticsreporting"></a>[function <span class="apidocSignatureSpan">googleapis.</span>analyticsreporting ()](#apidoc.element.googleapis.analyticsreporting)
- description and source-code
```javascript
analyticsreporting = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.googleapis.androidenterprise"></a>[function <span class="apidocSignatureSpan">googleapis.</span>androidenterprise ()](#apidoc.element.googleapis.androidenterprise)
- description and source-code
```javascript
androidenterprise = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.googleapis.androidpublisher"></a>[function <span class="apidocSignatureSpan">googleapis.</span>androidpublisher ()](#apidoc.element.googleapis.androidpublisher)
- description and source-code
```javascript
androidpublisher = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.googleapis.appengine"></a>[function <span class="apidocSignatureSpan">googleapis.</span>appengine ()](#apidoc.element.googleapis.appengine)
- description and source-code
```javascript
appengine = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.googleapis.appsactivity"></a>[function <span class="apidocSignatureSpan">googleapis.</span>appsactivity ()](#apidoc.element.googleapis.appsactivity)
- description and source-code
```javascript
appsactivity = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.googleapis.appstate"></a>[function <span class="apidocSignatureSpan">googleapis.</span>appstate ()](#apidoc.element.googleapis.appstate)
- description and source-code
```javascript
appstate = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.googleapis.auth.ComputeClient"></a>[function <span class="apidocSignatureSpan">googleapis.</span>auth.ComputeClient ()](#apidoc.element.googleapis.auth.ComputeClient)
- description and source-code
```javascript
function Compute() {
  Compute.super_.call(this);
  // Start with an expired refresh token, which will automatically be refreshed
  // before the first API call is made.
  this.credentials = {
    refresh_token: 'compute-placeholder',
    expiry_date: 1
  };

  // Hook the post request method so we can provide better error messages.
  this._postRequest = this._injectErrorMessage;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.googleapis.auth.JWTClient"></a>[function <span class="apidocSignatureSpan">googleapis.</span>auth.JWTClient (email, keyFile, key, scopes, subject)](#apidoc.element.googleapis.auth.JWTClient)
- description and source-code
```javascript
function JWT(email, keyFile, key, scopes, subject) {
  JWT.super_.call(this);
  this.email = email;
  this.keyFile = keyFile;
  this.key = key;
  this.scopes = scopes;
  this.subject = subject;
  this.gToken = gToken;

  this.credentials = {
    refresh_token: 'jwt-placeholder',
    expiry_date: 1
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.googleapis.bigquery"></a>[function <span class="apidocSignatureSpan">googleapis.</span>bigquery ()](#apidoc.element.googleapis.bigquery)
- description and source-code
```javascript
bigquery = function () { [native code] }
```
- example usage
```shell
...
You can specify an 'auth' object to be used per request. Each request also
inherits the options specified at the service level and global level.

For example:

'''js
var google = require('googleapis');
var bigquery = google.bigquery('v2');

// This method looks for the GCLOUD_PROJECT and GOOGLE_APPLICATION_CREDENTIALS
// environment variables.
google.auth.getApplicationDefault(function (err, authClient, projectId) {
if (err) {
  console.log('Authentication failed because of ', err);
  return;
...
```

#### <a name="apidoc.element.googleapis.blogger"></a>[function <span class="apidocSignatureSpan">googleapis.</span>blogger ()](#apidoc.element.googleapis.blogger)
- description and source-code
```javascript
blogger = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.googleapis.books"></a>[function <span class="apidocSignatureSpan">googleapis.</span>books ()](#apidoc.element.googleapis.books)
- description and source-code
```javascript
books = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.googleapis.calendar"></a>[function <span class="apidocSignatureSpan">googleapis.</span>calendar ()](#apidoc.element.googleapis.calendar)
- description and source-code
```javascript
calendar = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.googleapis.civicinfo"></a>[function <span class="apidocSignatureSpan">googleapis.</span>civicinfo ()](#apidoc.element.googleapis.civicinfo)
- description and source-code
```javascript
civicinfo = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.googleapis.classroom"></a>[function <span class="apidocSignatureSpan">googleapis.</span>classroom ()](#apidoc.element.googleapis.classroom)
- description and source-code
```javascript
classroom = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.googleapis.cloudbilling"></a>[function <span class="apidocSignatureSpan">googleapis.</span>cloudbilling ()](#apidoc.element.googleapis.cloudbilling)
- description and source-code
```javascript
cloudbilling = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.googleapis.cloudbuild"></a>[function <span class="apidocSignatureSpan">googleapis.</span>cloudbuild ()](#apidoc.element.googleapis.cloudbuild)
- description and source-code
```javascript
cloudbuild = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.googleapis.clouddebugger"></a>[function <span class="apidocSignatureSpan">googleapis.</span>clouddebugger ()](#apidoc.element.googleapis.clouddebugger)
- description and source-code
```javascript
clouddebugger = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.googleapis.clouderrorreporting"></a>[function <span class="apidocSignatureSpan">googleapis.</span>clouderrorreporting ()](#apidoc.element.googleapis.clouderrorreporting)
- description and source-code
```javascript
clouderrorreporting = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.googleapis.cloudfunctions"></a>[function <span class="apidocSignatureSpan">googleapis.</span>cloudfunctions ()](#apidoc.element.googleapis.cloudfunctions)
- description and source-code
```javascript
cloudfunctions = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.googleapis.cloudkms"></a>[function <span class="apidocSignatureSpan">googleapis.</span>cloudkms ()](#apidoc.element.googleapis.cloudkms)
- description and source-code
```javascript
cloudkms = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.googleapis.cloudmonitoring"></a>[function <span class="apidocSignatureSpan">googleapis.</span>cloudmonitoring ()](#apidoc.element.googleapis.cloudmonitoring)
- description and source-code
```javascript
cloudmonitoring = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.googleapis.cloudresourcemanager"></a>[function <span class="apidocSignatureSpan">googleapis.</span>cloudresourcemanager ()](#apidoc.element.googleapis.cloudresourcemanager)
- description and source-code
```javascript
cloudresourcemanager = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.googleapis.cloudtrace"></a>[function <span class="apidocSignatureSpan">googleapis.</span>cloudtrace ()](#apidoc.element.googleapis.cloudtrace)
- description and source-code
```javascript
cloudtrace = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.googleapis.clouduseraccounts"></a>[function <span class="apidocSignatureSpan">googleapis.</span>clouduseraccounts ()](#apidoc.element.googleapis.clouduseraccounts)
- description and source-code
```javascript
clouduseraccounts = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.googleapis.compute"></a>[function <span class="apidocSignatureSpan">googleapis.</span>compute ()](#apidoc.element.googleapis.compute)
- description and source-code
```javascript
compute = function () { [native code] }
```
- example usage
```shell
...
  authClient = authClient.createScoped([
    'https://www.googleapis.com/auth/compute'
  ]);
}

// Fetch the list of GCE zones within a project.
// NOTE: You must fill in your valid project ID before running this sample!
var compute = google.compute({
  version: 'v1',
  auth: authClient
});
var projectId = 'YOUR_PROJECT_ID';

compute.zones.list({
  project: projectId,
...
```

#### <a name="apidoc.element.googleapis.consumersurveys"></a>[function <span class="apidocSignatureSpan">googleapis.</span>consumersurveys ()](#apidoc.element.googleapis.consumersurveys)
- description and source-code
```javascript
consumersurveys = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.googleapis.container"></a>[function <span class="apidocSignatureSpan">googleapis.</span>container ()](#apidoc.element.googleapis.container)
- description and source-code
```javascript
container = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.googleapis.content"></a>[function <span class="apidocSignatureSpan">googleapis.</span>content ()](#apidoc.element.googleapis.content)
- description and source-code
```javascript
content = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.googleapis.customsearch"></a>[function <span class="apidocSignatureSpan">googleapis.</span>customsearch ()](#apidoc.element.googleapis.customsearch)
- description and source-code
```javascript
customsearch = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.googleapis.dataflow"></a>[function <span class="apidocSignatureSpan">googleapis.</span>dataflow ()](#apidoc.element.googleapis.dataflow)
- description and source-code
```javascript
dataflow = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.googleapis.dataproc"></a>[function <span class="apidocSignatureSpan">googleapis.</span>dataproc ()](#apidoc.element.googleapis.dataproc)
- description and source-code
```javascript
dataproc = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.googleapis.datastore"></a>[function <span class="apidocSignatureSpan">googleapis.</span>datastore ()](#apidoc.element.googleapis.datastore)
- description and source-code
```javascript
datastore = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.googleapis.deploymentmanager"></a>[function <span class="apidocSignatureSpan">googleapis.</span>deploymentmanager ()](#apidoc.element.googleapis.deploymentmanager)
- description and source-code
```javascript
deploymentmanager = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.googleapis.dfareporting"></a>[function <span class="apidocSignatureSpan">googleapis.</span>dfareporting ()](#apidoc.element.googleapis.dfareporting)
- description and source-code
```javascript
dfareporting = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.googleapis.discovery"></a>[function <span class="apidocSignatureSpan">googleapis.</span>discovery ()](#apidoc.element.googleapis.discovery)
- description and source-code
```javascript
discovery = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.googleapis.dns"></a>[function <span class="apidocSignatureSpan">googleapis.</span>dns ()](#apidoc.element.googleapis.dns)
- description and source-code
```javascript
dns = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.googleapis.doubleclickbidmanager"></a>[function <span class="apidocSignatureSpan">googleapis.</span>doubleclickbidmanager ()](#apidoc.element.googleapis.doubleclickbidmanager)
- description and source-code
```javascript
doubleclickbidmanager = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.googleapis.doubleclicksearch"></a>[function <span class="apidocSignatureSpan">googleapis.</span>doubleclicksearch ()](#apidoc.element.googleapis.doubleclicksearch)
- description and source-code
```javascript
doubleclicksearch = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.googleapis.drive"></a>[function <span class="apidocSignatureSpan">googleapis.</span>drive ()](#apidoc.element.googleapis.drive)
- description and source-code
```javascript
drive = function () { [native code] }
```
- example usage
```shell
...
var OAuth2 = google.auth.OAuth2;
var oauth2Client = new OAuth2(
  YOUR_CLIENT_ID,
  YOUR_CLIENT_SECRET,
  YOUR_REDIRECT_URL
);

var drive = google.drive({
  version: 'v2',
  auth: oauth2Client
});
'''

See the [Options section][options] for more information.
...
```

#### <a name="apidoc.element.googleapis.firebasedynamiclinks"></a>[function <span class="apidocSignatureSpan">googleapis.</span>firebasedynamiclinks ()](#apidoc.element.googleapis.firebasedynamiclinks)
- description and source-code
```javascript
firebasedynamiclinks = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.googleapis.firebaserules"></a>[function <span class="apidocSignatureSpan">googleapis.</span>firebaserules ()](#apidoc.element.googleapis.firebaserules)
- description and source-code
```javascript
firebaserules = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.googleapis.fitness"></a>[function <span class="apidocSignatureSpan">googleapis.</span>fitness ()](#apidoc.element.googleapis.fitness)
- description and source-code
```javascript
fitness = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.googleapis.fusiontables"></a>[function <span class="apidocSignatureSpan">googleapis.</span>fusiontables ()](#apidoc.element.googleapis.fusiontables)
- description and source-code
```javascript
fusiontables = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.googleapis.games"></a>[function <span class="apidocSignatureSpan">googleapis.</span>games ()](#apidoc.element.googleapis.games)
- description and source-code
```javascript
games = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.googleapis.gamesConfiguration"></a>[function <span class="apidocSignatureSpan">googleapis.</span>gamesConfiguration ()](#apidoc.element.googleapis.gamesConfiguration)
- description and source-code
```javascript
gamesConfiguration = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.googleapis.gamesManagement"></a>[function <span class="apidocSignatureSpan">googleapis.</span>gamesManagement ()](#apidoc.element.googleapis.gamesManagement)
- description and source-code
```javascript
gamesManagement = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.googleapis.genomics"></a>[function <span class="apidocSignatureSpan">googleapis.</span>genomics ()](#apidoc.element.googleapis.genomics)
- description and source-code
```javascript
genomics = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.googleapis.gmail"></a>[function <span class="apidocSignatureSpan">googleapis.</span>gmail ()](#apidoc.element.googleapis.gmail)
- description and source-code
```javascript
gmail = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.googleapis.groupsmigration"></a>[function <span class="apidocSignatureSpan">googleapis.</span>groupsmigration ()](#apidoc.element.googleapis.groupsmigration)
- description and source-code
```javascript
groupsmigration = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.googleapis.groupssettings"></a>[function <span class="apidocSignatureSpan">googleapis.</span>groupssettings ()](#apidoc.element.googleapis.groupssettings)
- description and source-code
```javascript
groupssettings = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.googleapis.iam"></a>[function <span class="apidocSignatureSpan">googleapis.</span>iam ()](#apidoc.element.googleapis.iam)
- description and source-code
```javascript
iam = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.googleapis.identitytoolkit"></a>[function <span class="apidocSignatureSpan">googleapis.</span>identitytoolkit ()](#apidoc.element.googleapis.identitytoolkit)
- description and source-code
```javascript
identitytoolkit = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.googleapis.kgsearch"></a>[function <span class="apidocSignatureSpan">googleapis.</span>kgsearch ()](#apidoc.element.googleapis.kgsearch)
- description and source-code
```javascript
kgsearch = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.googleapis.language"></a>[function <span class="apidocSignatureSpan">googleapis.</span>language ()](#apidoc.element.googleapis.language)
- description and source-code
```javascript
language = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.googleapis.licensing"></a>[function <span class="apidocSignatureSpan">googleapis.</span>licensing ()](#apidoc.element.googleapis.licensing)
- description and source-code
```javascript
licensing = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.googleapis.logging"></a>[function <span class="apidocSignatureSpan">googleapis.</span>logging ()](#apidoc.element.googleapis.logging)
- description and source-code
```javascript
logging = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.googleapis.manufacturers"></a>[function <span class="apidocSignatureSpan">googleapis.</span>manufacturers ()](#apidoc.element.googleapis.manufacturers)
- description and source-code
```javascript
manufacturers = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.googleapis.mirror"></a>[function <span class="apidocSignatureSpan">googleapis.</span>mirror ()](#apidoc.element.googleapis.mirror)
- description and source-code
```javascript
mirror = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.googleapis.ml"></a>[function <span class="apidocSignatureSpan">googleapis.</span>ml ()](#apidoc.element.googleapis.ml)
- description and source-code
```javascript
ml = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.googleapis.monitoring"></a>[function <span class="apidocSignatureSpan">googleapis.</span>monitoring ()](#apidoc.element.googleapis.monitoring)
- description and source-code
```javascript
monitoring = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.googleapis.oauth2"></a>[function <span class="apidocSignatureSpan">googleapis.</span>oauth2 ()](#apidoc.element.googleapis.oauth2)
- description and source-code
```javascript
oauth2 = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.googleapis.pagespeedonline"></a>[function <span class="apidocSignatureSpan">googleapis.</span>pagespeedonline ()](#apidoc.element.googleapis.pagespeedonline)
- description and source-code
```javascript
pagespeedonline = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.googleapis.partners"></a>[function <span class="apidocSignatureSpan">googleapis.</span>partners ()](#apidoc.element.googleapis.partners)
- description and source-code
```javascript
partners = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.googleapis.people"></a>[function <span class="apidocSignatureSpan">googleapis.</span>people ()](#apidoc.element.googleapis.people)
- description and source-code
```javascript
people = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.googleapis.playmoviespartner"></a>[function <span class="apidocSignatureSpan">googleapis.</span>playmoviespartner ()](#apidoc.element.googleapis.playmoviespartner)
- description and source-code
```javascript
playmoviespartner = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.googleapis.plus"></a>[function <span class="apidocSignatureSpan">googleapis.</span>plus ()](#apidoc.element.googleapis.plus)
- description and source-code
```javascript
plus = function () { [native code] }
```
- example usage
```shell
...
we cannot reliably restart your media stream). Set 'expiry_date' to 'true' to
force a refresh.

The following sample retrieves Google+ profile of the authenticated user.

''' js
var google = require('googleapis');
var plus = google.plus('v1');
var OAuth2 = google.auth.OAuth2;
var oauth2Client = new OAuth2(
  YOUR_CLIENT_ID,
  YOUR_CLIENT_SECRET,
  YOUR_REDIRECT_URL
);
...
```

#### <a name="apidoc.element.googleapis.plusDomains"></a>[function <span class="apidocSignatureSpan">googleapis.</span>plusDomains ()](#apidoc.element.googleapis.plusDomains)
- description and source-code
```javascript
plusDomains = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.googleapis.prediction"></a>[function <span class="apidocSignatureSpan">googleapis.</span>prediction ()](#apidoc.element.googleapis.prediction)
- description and source-code
```javascript
prediction = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.googleapis.proximitybeacon"></a>[function <span class="apidocSignatureSpan">googleapis.</span>proximitybeacon ()](#apidoc.element.googleapis.proximitybeacon)
- description and source-code
```javascript
proximitybeacon = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.googleapis.pubsub"></a>[function <span class="apidocSignatureSpan">googleapis.</span>pubsub ()](#apidoc.element.googleapis.pubsub)
- description and source-code
```javascript
pubsub = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.googleapis.qpxExpress"></a>[function <span class="apidocSignatureSpan">googleapis.</span>qpxExpress ()](#apidoc.element.googleapis.qpxExpress)
- description and source-code
```javascript
qpxExpress = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.googleapis.replicapool"></a>[function <span class="apidocSignatureSpan">googleapis.</span>replicapool ()](#apidoc.element.googleapis.replicapool)
- description and source-code
```javascript
replicapool = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.googleapis.replicapoolupdater"></a>[function <span class="apidocSignatureSpan">googleapis.</span>replicapoolupdater ()](#apidoc.element.googleapis.replicapoolupdater)
- description and source-code
```javascript
replicapoolupdater = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.googleapis.reseller"></a>[function <span class="apidocSignatureSpan">googleapis.</span>reseller ()](#apidoc.element.googleapis.reseller)
- description and source-code
```javascript
reseller = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.googleapis.resourceviews"></a>[function <span class="apidocSignatureSpan">googleapis.</span>resourceviews ()](#apidoc.element.googleapis.resourceviews)
- description and source-code
```javascript
resourceviews = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.googleapis.runtimeconfig"></a>[function <span class="apidocSignatureSpan">googleapis.</span>runtimeconfig ()](#apidoc.element.googleapis.runtimeconfig)
- description and source-code
```javascript
runtimeconfig = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.googleapis.safebrowsing"></a>[function <span class="apidocSignatureSpan">googleapis.</span>safebrowsing ()](#apidoc.element.googleapis.safebrowsing)
- description and source-code
```javascript
safebrowsing = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.googleapis.script"></a>[function <span class="apidocSignatureSpan">googleapis.</span>script ()](#apidoc.element.googleapis.script)
- description and source-code
```javascript
script = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.googleapis.searchconsole"></a>[function <span class="apidocSignatureSpan">googleapis.</span>searchconsole ()](#apidoc.element.googleapis.searchconsole)
- description and source-code
```javascript
searchconsole = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.googleapis.servicecontrol"></a>[function <span class="apidocSignatureSpan">googleapis.</span>servicecontrol ()](#apidoc.element.googleapis.servicecontrol)
- description and source-code
```javascript
servicecontrol = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.googleapis.servicemanagement"></a>[function <span class="apidocSignatureSpan">googleapis.</span>servicemanagement ()](#apidoc.element.googleapis.servicemanagement)
- description and source-code
```javascript
servicemanagement = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.googleapis.serviceuser"></a>[function <span class="apidocSignatureSpan">googleapis.</span>serviceuser ()](#apidoc.element.googleapis.serviceuser)
- description and source-code
```javascript
serviceuser = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.googleapis.sheets"></a>[function <span class="apidocSignatureSpan">googleapis.</span>sheets ()](#apidoc.element.googleapis.sheets)
- description and source-code
```javascript
sheets = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.googleapis.siteVerification"></a>[function <span class="apidocSignatureSpan">googleapis.</span>siteVerification ()](#apidoc.element.googleapis.siteVerification)
- description and source-code
```javascript
siteVerification = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.googleapis.slides"></a>[function <span class="apidocSignatureSpan">googleapis.</span>slides ()](#apidoc.element.googleapis.slides)
- description and source-code
```javascript
slides = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.googleapis.sourcerepo"></a>[function <span class="apidocSignatureSpan">googleapis.</span>sourcerepo ()](#apidoc.element.googleapis.sourcerepo)
- description and source-code
```javascript
sourcerepo = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.googleapis.spanner"></a>[function <span class="apidocSignatureSpan">googleapis.</span>spanner ()](#apidoc.element.googleapis.spanner)
- description and source-code
```javascript
spanner = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.googleapis.spectrum"></a>[function <span class="apidocSignatureSpan">googleapis.</span>spectrum ()](#apidoc.element.googleapis.spectrum)
- description and source-code
```javascript
spectrum = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.googleapis.speech"></a>[function <span class="apidocSignatureSpan">googleapis.</span>speech ()](#apidoc.element.googleapis.speech)
- description and source-code
```javascript
speech = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.googleapis.sqladmin"></a>[function <span class="apidocSignatureSpan">googleapis.</span>sqladmin ()](#apidoc.element.googleapis.sqladmin)
- description and source-code
```javascript
sqladmin = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.googleapis.storage"></a>[function <span class="apidocSignatureSpan">googleapis.</span>storage ()](#apidoc.element.googleapis.storage)
- description and source-code
```javascript
storage = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.googleapis.storagetransfer"></a>[function <span class="apidocSignatureSpan">googleapis.</span>storagetransfer ()](#apidoc.element.googleapis.storagetransfer)
- description and source-code
```javascript
storagetransfer = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.googleapis.surveys"></a>[function <span class="apidocSignatureSpan">googleapis.</span>surveys ()](#apidoc.element.googleapis.surveys)
- description and source-code
```javascript
surveys = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.googleapis.tagmanager"></a>[function <span class="apidocSignatureSpan">googleapis.</span>tagmanager ()](#apidoc.element.googleapis.tagmanager)
- description and source-code
```javascript
tagmanager = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.googleapis.taskqueue"></a>[function <span class="apidocSignatureSpan">googleapis.</span>taskqueue ()](#apidoc.element.googleapis.taskqueue)
- description and source-code
```javascript
taskqueue = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.googleapis.tasks"></a>[function <span class="apidocSignatureSpan">googleapis.</span>tasks ()](#apidoc.element.googleapis.tasks)
- description and source-code
```javascript
tasks = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.googleapis.toolresults"></a>[function <span class="apidocSignatureSpan">googleapis.</span>toolresults ()](#apidoc.element.googleapis.toolresults)
- description and source-code
```javascript
toolresults = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.googleapis.tracing"></a>[function <span class="apidocSignatureSpan">googleapis.</span>tracing ()](#apidoc.element.googleapis.tracing)
- description and source-code
```javascript
tracing = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.googleapis.translate"></a>[function <span class="apidocSignatureSpan">googleapis.</span>translate ()](#apidoc.element.googleapis.translate)
- description and source-code
```javascript
translate = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.googleapis.transporters"></a>[function <span class="apidocSignatureSpan">googleapis.</span>transporters ()](#apidoc.element.googleapis.transporters)
- description and source-code
```javascript
function DefaultTransporter() {}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.googleapis.urlshortener"></a>[function <span class="apidocSignatureSpan">googleapis.</span>urlshortener ()](#apidoc.element.googleapis.urlshortener)
- description and source-code
```javascript
urlshortener = function () { [native code] }
```
- example usage
```shell
...
## Usage

Example: Creates a URL Shortener client and retrieves the long url of the
given short url:

''' js
var google = require('googleapis');
var urlshortener = google.urlshortener('v1');

var params = {
  shortUrl: 'http://goo.gl/xKbRu3'
};

// get the long url of a shortened url
urlshortener.url.get(params, function (err, response) {
...
```

#### <a name="apidoc.element.googleapis.vision"></a>[function <span class="apidocSignatureSpan">googleapis.</span>vision ()](#apidoc.element.googleapis.vision)
- description and source-code
```javascript
vision = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.googleapis.webfonts"></a>[function <span class="apidocSignatureSpan">googleapis.</span>webfonts ()](#apidoc.element.googleapis.webfonts)
- description and source-code
```javascript
webfonts = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.googleapis.webmasters"></a>[function <span class="apidocSignatureSpan">googleapis.</span>webmasters ()](#apidoc.element.googleapis.webmasters)
- description and source-code
```javascript
webmasters = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.googleapis.youtube"></a>[function <span class="apidocSignatureSpan">googleapis.</span>youtube ()](#apidoc.element.googleapis.youtube)
- description and source-code
```javascript
youtube = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.googleapis.youtubeAnalytics"></a>[function <span class="apidocSignatureSpan">googleapis.</span>youtubeAnalytics ()](#apidoc.element.googleapis.youtubeAnalytics)
- description and source-code
```javascript
youtubeAnalytics = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.googleapis.youtubereporting"></a>[function <span class="apidocSignatureSpan">googleapis.</span>youtubereporting ()](#apidoc.element.googleapis.youtubereporting)
- description and source-code
```javascript
youtubereporting = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.googleapis.GoogleApis"></a>[module googleapis.GoogleApis](#apidoc.module.googleapis.GoogleApis)

#### <a name="apidoc.element.googleapis.GoogleApis.GoogleApis"></a>[function <span class="apidocSignatureSpan">googleapis.</span>GoogleApis (options)](#apidoc.element.googleapis.GoogleApis.GoogleApis)
- description and source-code
```javascript
function GoogleApis(options) {
  this.options(options);
  this.addAPIs(apis);

<span class="apidocCodeCommentSpan">  /**
   * A reference to an instance of GoogleAuth.
   *
   * @name GoogleApis#auth
   * @type {GoogleAuth}
   */
</span>  this.auth = new GoogleAuth();

  /**
   * A reference to the {@link GoogleApis} constructor function.
   *
   * @name GoogleApis#GoogleApis
   * @see GoogleApis
   * @type {Function}
   */
  this.GoogleApis = GoogleApis;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.googleapis.GoogleApis.prototype"></a>[module googleapis.GoogleApis.prototype](#apidoc.module.googleapis.GoogleApis.prototype)

#### <a name="apidoc.element.googleapis.GoogleApis.prototype.addAPIs"></a>[function <span class="apidocSignatureSpan">googleapis.GoogleApis.prototype.</span>addAPIs (apis)](#apidoc.element.googleapis.GoogleApis.prototype.addAPIs)
- description and source-code
```javascript
addAPIs = function (apis) {
  for (var apiName in apis) {
    this[apiName] = apis[apiName].bind(this);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.googleapis.GoogleApis.prototype.discover"></a>[function <span class="apidocSignatureSpan">googleapis.GoogleApis.prototype.</span>discover (url, callback)](#apidoc.element.googleapis.GoogleApis.prototype.discover)
- description and source-code
```javascript
discover = function (url, callback) {
  var self = this;

  discovery.discoverAllAPIs(url, function (err, apis) {
    if (err) {
      return callback(err);
    }
    self.addAPIs(apis);
    callback();
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.googleapis.GoogleApis.prototype.discoverAPI"></a>[function <span class="apidocSignatureSpan">googleapis.GoogleApis.prototype.</span>discoverAPI (path, options, callback)](#apidoc.element.googleapis.GoogleApis.prototype.discoverAPI)
- description and source-code
```javascript
discoverAPI = function (path, options, callback) {
  var self = this;
  if (typeof options === 'function') {
    callback = options;
    options = {};
  }
  if (!options) {
    options = {};
  }
  discovery.discoverAPI(path, function (err, Endpoint) {
    if (err) {
      return callback(err);
    }
    var ep = new Endpoint(options);
    ep.google = self; // for drive.google.transporter
    return callback(null, Object.freeze(ep)); // create new & freeze
  });
}
```
- example usage
```shell
...
  }, function (err, resp) {
if (err) {
  return handleError(err, callback);
}

async.parallel(resp.items.map(function (api) {
  return function (cb) {
    self.discoverAPI(api.discoveryRestUrl, function (err, _api) {
      if (err) {
        return cb(err);
      }
      api.api = _api;
      cb(null, api);
    });
  };
...
```

#### <a name="apidoc.element.googleapis.GoogleApis.prototype.options"></a>[function <span class="apidocSignatureSpan">googleapis.GoogleApis.prototype.</span>options (options)](#apidoc.element.googleapis.GoogleApis.prototype.options)
- description and source-code
```javascript
options = function (options) {
  this._options = options || {};
}
```
- example usage
```shell
...
var oauth2Client = new OAuth2(
  YOUR_CLIENT_ID,
  YOUR_CLIENT_SECRET,
  YOUR_REDIRECT_URL
);

// set auth as a global default
google.options({
  auth: oauth2Client
});
'''

Example: Setting a service-level 'auth' option.

''' js
...
```



# <a name="apidoc.module.googleapis.auth"></a>[module googleapis.auth](#apidoc.module.googleapis.auth)

#### <a name="apidoc.element.googleapis.auth.ComputeClient"></a>[function <span class="apidocSignatureSpan">googleapis.auth.</span>ComputeClient ()](#apidoc.element.googleapis.auth.ComputeClient)
- description and source-code
```javascript
function Compute() {
  Compute.super_.call(this);
  // Start with an expired refresh token, which will automatically be refreshed
  // before the first API call is made.
  this.credentials = {
    refresh_token: 'compute-placeholder',
    expiry_date: 1
  };

  // Hook the post request method so we can provide better error messages.
  this._postRequest = this._injectErrorMessage;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.googleapis.auth.JWTClient"></a>[function <span class="apidocSignatureSpan">googleapis.auth.</span>JWTClient (email, keyFile, key, scopes, subject)](#apidoc.element.googleapis.auth.JWTClient)
- description and source-code
```javascript
function JWT(email, keyFile, key, scopes, subject) {
  JWT.super_.call(this);
  this.email = email;
  this.keyFile = keyFile;
  this.key = key;
  this.scopes = scopes;
  this.subject = subject;
  this.gToken = gToken;

  this.credentials = {
    refresh_token: 'jwt-placeholder',
    expiry_date: 1
  };
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.googleapis.auth.ComputeClient"></a>[module googleapis.auth.ComputeClient](#apidoc.module.googleapis.auth.ComputeClient)

#### <a name="apidoc.element.googleapis.auth.ComputeClient.ComputeClient"></a>[function <span class="apidocSignatureSpan">googleapis.auth.</span>ComputeClient ()](#apidoc.element.googleapis.auth.ComputeClient.ComputeClient)
- description and source-code
```javascript
function Compute() {
  Compute.super_.call(this);
  // Start with an expired refresh token, which will automatically be refreshed
  // before the first API call is made.
  this.credentials = {
    refresh_token: 'compute-placeholder',
    expiry_date: 1
  };

  // Hook the post request method so we can provide better error messages.
  this._postRequest = this._injectErrorMessage;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.googleapis.auth.ComputeClient.super_"></a>[function <span class="apidocSignatureSpan">googleapis.auth.ComputeClient.</span>super_ (clientId, clientSecret, redirectUri, opt_opts)](#apidoc.element.googleapis.auth.ComputeClient.super_)
- description and source-code
```javascript
function OAuth2Client(clientId, clientSecret, redirectUri, opt_opts) {
  OAuth2Client.super_.call(this);

  this.clientId_ = clientId;
  this.clientSecret_ = clientSecret;
  this.redirectUri_ = redirectUri;
  this.opts = opt_opts || {};
  this.credentials = {};
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.googleapis.auth.ComputeClient.prototype"></a>[module googleapis.auth.ComputeClient.prototype](#apidoc.module.googleapis.auth.ComputeClient.prototype)

#### <a name="apidoc.element.googleapis.auth.ComputeClient.prototype._injectErrorMessage"></a>[function <span class="apidocSignatureSpan">googleapis.auth.ComputeClient.prototype.</span>_injectErrorMessage (err, result, response, callback)](#apidoc.element.googleapis.auth.ComputeClient.prototype._injectErrorMessage)
- description and source-code
```javascript
_injectErrorMessage = function (err, result, response, callback) {
  if (response && response.statusCode) {
    var helpfulMessage = null;
    if (response.statusCode === 403) {
      helpfulMessage = 'A Forbidden error was returned while attempting to retrieve an access ' +
        'token for the Compute Engine built-in service account. This may be because the Compute ' +
        'Engine instance does not have the correct permission scopes specified.';
    } else if (response.statusCode === 404) {
      helpfulMessage = 'A Not Found error was returned while attempting to retrieve an access' +
        'token for the Compute Engine built-in service account. This may be because the Compute ' +
        'Engine instance does not have any permission scopes specified.';
    }
    if (helpfulMessage) {
      if (err && err.message) {
        helpfulMessage += ' ' + err.message;
      }

      if (err) {
        err.message = helpfulMessage;
      } else {
        err = new Error(helpfulMessage);
        err.code = response.statusCode;
      }
    }
  }
  callback(err, result, response);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.googleapis.auth.ComputeClient.prototype.createScopedRequired"></a>[function <span class="apidocSignatureSpan">googleapis.auth.ComputeClient.prototype.</span>createScopedRequired ()](#apidoc.element.googleapis.auth.ComputeClient.prototype.createScopedRequired)
- description and source-code
```javascript
createScopedRequired = function () {
  // On compute engine, scopes are specified at the compute instance's creation time,
  // and cannot be changed. For this reason, always return false.
  return false;
}
```
- example usage
```shell
...
  throw err;
}

// The createScopedRequired method returns true when running on GAE or a local developer
// machine. In that case, the desired scopes must be passed in manually. When the code is
// running in GCE or a Managed VM, the scopes are pulled from the GCE metadata server.
// See https://cloud.google.com/compute/docs/authentication for more information.
if (authClient.createScopedRequired && authClient.createScopedRequired()) {
  // Scopes can be specified either as an array or as a single, space-delimited string.
  authClient = authClient.createScoped([
    'https://www.googleapis.com/auth/compute'
  ]);
}

// Fetch the list of GCE zones within a project.
...
```

#### <a name="apidoc.element.googleapis.auth.ComputeClient.prototype.refreshToken_"></a>[function <span class="apidocSignatureSpan">googleapis.auth.ComputeClient.prototype.</span>refreshToken_ (ignored_, opt_callback)](#apidoc.element.googleapis.auth.ComputeClient.prototype.refreshToken_)
- description and source-code
```javascript
refreshToken_ = function (ignored_, opt_callback) {
  var uri = this.opts.tokenUrl || Compute.GOOGLE_OAUTH2_TOKEN_URL_;
  // request for new token
  this.transporter.request({
    method: 'GET',
    uri: uri,
    json: true
  }, function(err, tokens, response) {
    if (!err && tokens && tokens.expires_in) {
      tokens.expiry_date = ((new Date()).getTime() + (tokens.expires_in * 1000));
      delete tokens.expires_in;
    }

    if (opt_callback) {
      opt_callback(err, tokens, response);
    }
  });
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.googleapis.auth.ComputeClient.super_.prototype"></a>[module googleapis.auth.ComputeClient.super_.prototype](#apidoc.module.googleapis.auth.ComputeClient.super_.prototype)

#### <a name="apidoc.element.googleapis.auth.ComputeClient.super_.prototype._makeRequest"></a>[function <span class="apidocSignatureSpan">googleapis.auth.ComputeClient.super_.prototype.</span>_makeRequest (opts, callback)](#apidoc.element.googleapis.auth.ComputeClient.super_.prototype._makeRequest)
- description and source-code
```javascript
_makeRequest = function (opts, callback) {
  return this.transporter.request(opts, callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.googleapis.auth.ComputeClient.super_.prototype._postRequest"></a>[function <span class="apidocSignatureSpan">googleapis.auth.ComputeClient.super_.prototype.</span>_postRequest (err, result, response, callback)](#apidoc.element.googleapis.auth.ComputeClient.super_.prototype._postRequest)
- description and source-code
```javascript
_postRequest = function (err, result, response, callback) {
  callback(err, result, response);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.googleapis.auth.ComputeClient.super_.prototype.decodeBase64"></a>[function <span class="apidocSignatureSpan">googleapis.auth.ComputeClient.super_.prototype.</span>decodeBase64 (b64String)](#apidoc.element.googleapis.auth.ComputeClient.super_.prototype.decodeBase64)
- description and source-code
```javascript
decodeBase64 = function (b64String) {
  var buffer = new Buffer(b64String, 'base64');
  return buffer.toString('utf8');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.googleapis.auth.ComputeClient.super_.prototype.generateAuthUrl"></a>[function <span class="apidocSignatureSpan">googleapis.auth.ComputeClient.super_.prototype.</span>generateAuthUrl (opt_opts)](#apidoc.element.googleapis.auth.ComputeClient.super_.prototype.generateAuthUrl)
- description and source-code
```javascript
generateAuthUrl = function (opt_opts) {
  var opts = opt_opts || {};
  opts.response_type = opts.response_type || 'code';
  opts.client_id = opts.client_id || this.clientId_;
  opts.redirect_uri = opts.redirect_uri || this.redirectUri_;

  // Allow scopes to be passed either as array or a string
  if (opts.scope instanceof Array) {
    opts.scope = opts.scope.join(' ');
  }

  var rootUrl = this.opts.authBaseUrl ||
    OAuth2Client.GOOGLE_OAUTH2_AUTH_BASE_URL_;

  return rootUrl + '?' + querystring.stringify(opts);
}
```
- example usage
```shell
...

// generate a url that asks permissions for Google+ and Google Calendar scopes
var scopes = [
'https://www.googleapis.com/auth/plus.me',
'https://www.googleapis.com/auth/calendar'
];

var url = oauth2Client.generateAuthUrl({
// 'online' (default) or 'offline' (gets refresh_token)
access_type: 'offline',

// If you only need one scope you can pass it as a string
scope: scopes,

// Optional property that passes state parameters to redirect URI
...
```

#### <a name="apidoc.element.googleapis.auth.ComputeClient.super_.prototype.getAccessToken"></a>[function <span class="apidocSignatureSpan">googleapis.auth.ComputeClient.super_.prototype.</span>getAccessToken (callback)](#apidoc.element.googleapis.auth.ComputeClient.super_.prototype.getAccessToken)
- description and source-code
```javascript
getAccessToken = function (callback) {
  var credentials = this.credentials;
  var expiryDate = credentials.expiry_date;

  // if no expiry time, assume it's not expired
  var isTokenExpired = expiryDate ? expiryDate <= (new Date()).getTime() : false;

  if (!credentials.access_token && !credentials.refresh_token) {
    return callback(new Error('No access or refresh token is set.'), null);
  }

  var shouldRefresh = !credentials.access_token || isTokenExpired;
  if (shouldRefresh && credentials.refresh_token) {
    if (!this.credentials.refresh_token) {
      return callback(new Error('No refresh token is set.'), null);
    }

    this.refreshAccessToken(function(err, tokens, response) {
      if (err) {
        return callback(err, null, response);
      }
      if (!tokens || (tokens && !tokens.access_token)) {
        return callback(new Error('Could not refresh access token.'), null, response);
      }
      return callback(null, tokens.access_token, response);
    });
  } else {
    return callback(null, credentials.access_token, null);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.googleapis.auth.ComputeClient.super_.prototype.getFederatedSignonCerts"></a>[function <span class="apidocSignatureSpan">googleapis.auth.ComputeClient.super_.prototype.</span>getFederatedSignonCerts (callback)](#apidoc.element.googleapis.auth.ComputeClient.super_.prototype.getFederatedSignonCerts)
- description and source-code
```javascript
getFederatedSignonCerts = function (callback) {
  var nowTime = (new Date()).getTime();
  if (certificateExpiry && (nowTime < certificateExpiry.getTime())) {
    callback(null, certificateCache);
    return;
  }

  this.transporter.request({
    method: 'GET',
    uri: OAuth2Client.GOOGLE_OAUTH2_FEDERATED_SIGNON_CERTS_URL_,
    json: true
  }, function(err, body, response) {
    if (err) {
      callback('Failed to retrieve verification certificates: ' + err, null, response);
      return;
    }

    var cacheControl = response.headers['cache-control'];
    var cacheAge = -1;
    if (cacheControl) {
      var pattern = new RegExp('max-age=([0-9]*)');
      var regexResult = pattern.exec(cacheControl);
      if (regexResult.length === 2) {
        // Cache results with max-age (in seconds)
        cacheAge = regexResult[1] * 1000; // milliseconds
      }
    }

    var now = new Date();
    certificateExpiry = cacheAge === -1 ? null : new Date(now.getTime() + cacheAge);
    certificateCache = body;
    callback(null, body, response);
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.googleapis.auth.ComputeClient.super_.prototype.getRequestMetadata"></a>[function <span class="apidocSignatureSpan">googleapis.auth.ComputeClient.super_.prototype.</span>getRequestMetadata (opt_uri, metadataCb)](#apidoc.element.googleapis.auth.ComputeClient.super_.prototype.getRequestMetadata)
- description and source-code
```javascript
getRequestMetadata = function (opt_uri, metadataCb) {
  var that = this;
  var thisCreds = this.credentials;

  if (!thisCreds.access_token && !thisCreds.refresh_token) {
    return metadataCb(new Error('No access or refresh token is set.'), null);
  }

  // if no expiry time, assume it's not expired
  var expiryDate = thisCreds.expiry_date;
  var isTokenExpired = expiryDate ? expiryDate <= (new Date()).getTime() : false;

  if (thisCreds.access_token && !isTokenExpired) {
    thisCreds.token_type = thisCreds.token_type || 'Bearer';
    var headers = {'Authorization': thisCreds.token_type + ' ' + thisCreds.access_token };
    return metadataCb(null, headers , null);
  }

  return this.refreshToken_(thisCreds.refresh_token, function(err, tokens, response) {
    if (err) {
      return metadataCb(err, null, response);
    } else {
      if (!tokens || (tokens && !tokens.access_token)) {
        return metadataCb(new Error('Could not refresh access token.'), null, response);
      }

      var credentials = that.credentials;
      credentials.token_type = credentials.token_type || 'Bearer';
      tokens.refresh_token = credentials.refresh_token;
      that.credentials = tokens;
      var headers = {'Authorization': credentials.token_type + ' ' + tokens.access_token };
      return metadataCb(err, headers , response);
    }
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.googleapis.auth.ComputeClient.super_.prototype.getToken"></a>[function <span class="apidocSignatureSpan">googleapis.auth.ComputeClient.super_.prototype.</span>getToken (code, opt_callback)](#apidoc.element.googleapis.auth.ComputeClient.super_.prototype.getToken)
- description and source-code
```javascript
getToken = function (code, opt_callback) {
  var uri = this.opts.tokenUrl || OAuth2Client.GOOGLE_OAUTH2_TOKEN_URL_;
  var values = {
    code: code,
    client_id: this.clientId_,
    client_secret: this.clientSecret_,
    redirect_uri: this.redirectUri_,
    grant_type: 'authorization_code'
  };

  this.transporter.request({
    method: 'POST',
    uri: uri,
    form: values,
    json: true
  }, function(err, tokens, response) {
    if (!err && tokens && tokens.expires_in) {
      tokens.expiry_date = ((new Date()).getTime() + (tokens.expires_in * 1000));
      delete tokens.expires_in;
    }
    var done = opt_callback || noop;
    done(err, tokens, response);
  });
}
```
- example usage
```shell
...
    GET /oauthcallback?code={authorizationCode}

##### Retrieve access token

With the code returned, you can ask for an access token as shown below:

''' js
oauth2Client.getToken(code, function (err, tokens) {
  // Now tokens contains an access_token and an optional refresh_token. Save them.
  if (!err) {
    oauth2Client.setCredentials(tokens);
  }
});
'''
...
```

#### <a name="apidoc.element.googleapis.auth.ComputeClient.super_.prototype.refreshAccessToken"></a>[function <span class="apidocSignatureSpan">googleapis.auth.ComputeClient.super_.prototype.</span>refreshAccessToken (callback)](#apidoc.element.googleapis.auth.ComputeClient.super_.prototype.refreshAccessToken)
- description and source-code
```javascript
refreshAccessToken = function (callback) {
  var that = this;

  if (!this.credentials.refresh_token) {
    callback(new Error('No refresh token is set.'), null);
    return;
  }

  this.refreshToken_(this.credentials.refresh_token, function(err, result, response) {
    if (err) {
      callback(err, null, response);
    } else {
      var tokens = result;
      tokens.refresh_token = that.credentials.refresh_token;
      that.credentials = tokens;
      callback(null, that.credentials, response);
    }
  });
}
```
- example usage
```shell
...
##### Manually refreshing access token

If you need to manually refresh the 'access_token' associated with your OAuth2
client, make sure you have a 'refresh_token' set in your credentials first and
then call:

''' js
oauth2Client.refreshAccessToken(function(err, tokens) {
  // your access_token is now refreshed and stored in oauth2Client
  // store these new tokens in a safe place (e.g. database)
});
'''

#### Using API keys
...
```

#### <a name="apidoc.element.googleapis.auth.ComputeClient.super_.prototype.refreshToken_"></a>[function <span class="apidocSignatureSpan">googleapis.auth.ComputeClient.super_.prototype.</span>refreshToken_ (refresh_token, opt_callback)](#apidoc.element.googleapis.auth.ComputeClient.super_.prototype.refreshToken_)
- description and source-code
```javascript
refreshToken_ = function (refresh_token, opt_callback) {
  var uri = this.opts.tokenUrl || OAuth2Client.GOOGLE_OAUTH2_TOKEN_URL_;
  var values = {
    refresh_token: refresh_token,
    client_id: this.clientId_,
    client_secret: this.clientSecret_,
    grant_type: 'refresh_token'
  };

  // request for new token
  return this.transporter.request({
    method: 'POST',
    uri: uri,
    form: values,
    json: true
  }, function(err, tokens, response) {
    if (!err && tokens && tokens.expires_in) {
      tokens.expiry_date = ((new Date()).getTime() + (tokens.expires_in * 1000));
      delete tokens.expires_in;
    }
    var done = opt_callback || noop;
    done(err, tokens, response);
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.googleapis.auth.ComputeClient.super_.prototype.request"></a>[function <span class="apidocSignatureSpan">googleapis.auth.ComputeClient.super_.prototype.</span>request (opts, callback)](#apidoc.element.googleapis.auth.ComputeClient.super_.prototype.request)
- description and source-code
```javascript
request = function (opts, callback) {
<span class="apidocCodeCommentSpan">  /* jshint latedef:false */
</span>  var that = this;

  // Callbacks will close over this to ensure that we only retry once
  var retry = true;

  // Hook the callback routine to call the _postRequest method.
  var postRequestCb = function(err, body, resp) {
    var statusCode = resp && resp.statusCode;
    // Automatically retry 401 and 403 responses
    // if err is set and is unrelated to response
    // then getting credentials failed, and retrying won't help
    if (retry && (statusCode === 401 || statusCode === 403) &&
        (!err || err.code === statusCode)) {
      /* It only makes sense to retry once, because the retry is intended to
       * handle expiration-related failures. If refreshing the token does not
       * fix the failure, then refreshing again probably won't help */
      retry = false;
      // Force token refresh
      that.refreshAccessToken(function() {
        that.getRequestMetadata(unusedUri, authCb);
      });
    } else {
      that._postRequest(err, body, resp, callback);
    }
  };

  var authCb = function(err, headers, response) {
    if (err) {
      postRequestCb(err, null, response);
    } else {
      if (headers) {
        opts.headers = opts.headers || {};
        opts.headers.Authorization = headers.Authorization;
      }
      return that._makeRequest(opts, postRequestCb);
    }
  };

  var unusedUri = null;
  return this.getRequestMetadata(unusedUri, authCb);
}
```
- example usage
```shell
...
  options
);
delete options.auth; // is overridden by our auth code
delete options.params; // We handle params ourselves and Request does not recognise 'params'

// create request (using authClient or otherwise and return request obj)
if (authClient) {
  req = authClient.request(options, callback);
} else {
  req = new DefaultTransporter().request(options, callback);
}

if (body) {
  body.pipe(req);
}
...
```

#### <a name="apidoc.element.googleapis.auth.ComputeClient.super_.prototype.revokeCredentials"></a>[function <span class="apidocSignatureSpan">googleapis.auth.ComputeClient.super_.prototype.</span>revokeCredentials (callback)](#apidoc.element.googleapis.auth.ComputeClient.super_.prototype.revokeCredentials)
- description and source-code
```javascript
revokeCredentials = function (callback) {
  var token = this.credentials.access_token;
  this.credentials = {};
  if (token) {
    this.revokeToken(token, callback);
  } else {
    callback(new Error('No access token to revoke.'), null);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.googleapis.auth.ComputeClient.super_.prototype.revokeToken"></a>[function <span class="apidocSignatureSpan">googleapis.auth.ComputeClient.super_.prototype.</span>revokeToken (token, opt_callback)](#apidoc.element.googleapis.auth.ComputeClient.super_.prototype.revokeToken)
- description and source-code
```javascript
revokeToken = function (token, opt_callback) {
  this.transporter.request({
    uri: OAuth2Client.GOOGLE_OAUTH2_REVOKE_URL_ +
      '?' + querystring.stringify({ token: token }),
    json: true
  }, opt_callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.googleapis.auth.ComputeClient.super_.prototype.verifyIdToken"></a>[function <span class="apidocSignatureSpan">googleapis.auth.ComputeClient.super_.prototype.</span>verifyIdToken (idToken, audience, callback)](#apidoc.element.googleapis.auth.ComputeClient.super_.prototype.verifyIdToken)
- description and source-code
```javascript
verifyIdToken = function (idToken, audience, callback) {
  if (!idToken || !callback) {
    throw new Error('The verifyIdToken method requires both ' +
      'an ID Token and a callback method');
  }

  this.getFederatedSignonCerts(function(err, certs) {
    if (err) {
      callback(err, null);
    }
    var login;
    try {
      login = this.verifySignedJwtWithCerts(idToken, certs, audience,
        OAuth2Client.ISSUERS_);
    } catch (err) {
      callback(err);
      return;
    }

    callback(null, login);
  }.bind(this));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.googleapis.auth.ComputeClient.super_.prototype.verifySignedJwtWithCerts"></a>[function <span class="apidocSignatureSpan">googleapis.auth.ComputeClient.super_.prototype.</span>verifySignedJwtWithCerts (jwt, certs, requiredAudience, issuers, maxExpiry)](#apidoc.element.googleapis.auth.ComputeClient.super_.prototype.verifySignedJwtWithCerts)
- description and source-code
```javascript
verifySignedJwtWithCerts = function (jwt, certs, requiredAudience, issuers, maxExpiry) {

  if (!maxExpiry) {
    maxExpiry = OAuth2Client.MAX_TOKEN_LIFETIME_SECS_;
  }

  var segments = jwt.split('.');
  if (segments.length !== 3) {
    throw new Error('Wrong number of segments in token: ' + jwt);
  }
  var signed = segments[0] + '.' + segments[1];

  var signature = segments[2];

  var envelope, payload;
  try {
    envelope = JSON.parse(this.decodeBase64(segments[0]));
  } catch (err) { }

  if (!envelope) {
    throw new Error('Can\'t parse token envelope: ' + segments[0]);
  }

  try {
    payload = JSON.parse(this.decodeBase64(segments[1]));
  } catch (err) { }
  if (!payload) {
    throw new Error('Can\'t parse token payload: ' + segments[1]);
  }

  if (!certs.hasOwnProperty(envelope.kid)) {
    // If this is not present, then there's no reason to attempt verification
    throw new Error('No pem found for envelope: ' + JSON.stringify(envelope));
  }
  var pem = certs[envelope.kid];
  var pemVerifier = new PemVerifier();
  var verified = pemVerifier.verify(pem, signed, signature, 'base64');

  if (!verified) {
    throw new Error('Invalid token signature: ' + jwt);
  }

  if (!payload.iat) {
    throw new Error('No issue time in token: ' + JSON.stringify(payload));
  }

  if (!payload.exp) {
    throw new Error('No expiration time in token: ' + JSON.stringify(payload));
  }

  var iat = parseInt(payload.iat, 10);
  var exp = parseInt(payload.exp, 10);
  var now = new Date().getTime() / 1000;

  if (exp >= now + maxExpiry) {
    throw new Error('Expiration time too far in future: ' +
      JSON.stringify(payload));
  }

  var earliest = iat - OAuth2Client.CLOCK_SKEW_SECS_;
  var latest = exp + OAuth2Client.CLOCK_SKEW_SECS_;

  if (now < earliest) {
    throw new Error('Token used too early, ' + now + ' < ' + earliest + ': ' +
      JSON.stringify(payload));
  }

  if (now > latest) {
    throw new Error('Token used too late, ' + now + ' > ' + latest + ': ' +
      JSON.stringify(payload));
  }

  if (issuers && issuers.indexOf(payload.iss) < 0) {
    throw new Error('Invalid issuer, expected one of [' + issuers +
        '], but got ' + payload.iss);
  }

  // Check the audience matches if we have one
  if (typeof requiredAudience !== 'undefined' && requiredAudience !== null) {
    var aud = payload.aud;
    var audVerified = false;
    //If the requiredAudience is an array, check if it contains token audience
    if(requiredAudience.constructor === Array)
    {
        audVerified = (requiredAudience.indexOf(aud) > -1);
    }
    else{
        audVerified = (aud === requiredAudience);
    }
    if (!audVerified) {
       throw new Error('Wrong recipient, payload audience != requiredAudience');
    }
  }

  return new LoginTicket(envelope, payload);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.googleapis.auth.JWTClient"></a>[module googleapis.auth.JWTClient](#apidoc.module.googleapis.auth.JWTClient)

#### <a name="apidoc.element.googleapis.auth.JWTClient.JWTClient"></a>[function <span class="apidocSignatureSpan">googleapis.auth.</span>JWTClient (email, keyFile, key, scopes, subject)](#apidoc.element.googleapis.auth.JWTClient.JWTClient)
- description and source-code
```javascript
function JWT(email, keyFile, key, scopes, subject) {
  JWT.super_.call(this);
  this.email = email;
  this.keyFile = keyFile;
  this.key = key;
  this.scopes = scopes;
  this.subject = subject;
  this.gToken = gToken;

  this.credentials = {
    refresh_token: 'jwt-placeholder',
    expiry_date: 1
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.googleapis.auth.JWTClient.super_"></a>[function <span class="apidocSignatureSpan">googleapis.auth.JWTClient.</span>super_ (clientId, clientSecret, redirectUri, opt_opts)](#apidoc.element.googleapis.auth.JWTClient.super_)
- description and source-code
```javascript
function OAuth2Client(clientId, clientSecret, redirectUri, opt_opts) {
  OAuth2Client.super_.call(this);

  this.clientId_ = clientId;
  this.clientSecret_ = clientSecret;
  this.redirectUri_ = redirectUri;
  this.opts = opt_opts || {};
  this.credentials = {};
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.googleapis.auth.JWTClient.prototype"></a>[module googleapis.auth.JWTClient.prototype](#apidoc.module.googleapis.auth.JWTClient.prototype)

#### <a name="apidoc.element.googleapis.auth.JWTClient.prototype._createGToken"></a>[function <span class="apidocSignatureSpan">googleapis.auth.JWTClient.prototype.</span>_createGToken (callback)](#apidoc.element.googleapis.auth.JWTClient.prototype._createGToken)
- description and source-code
```javascript
_createGToken = function (callback) {
  if (this.gtoken) {
    return callback(null, this.gtoken);
  } else {
    this.gtoken = this.gToken({
      iss: this.email,
      sub: this.subject,
      scope: this.scopes,
      keyFile: this.keyFile,
      key: this.key
    });
    return callback(null, this.gtoken);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.googleapis.auth.JWTClient.prototype.authorize"></a>[function <span class="apidocSignatureSpan">googleapis.auth.JWTClient.prototype.</span>authorize (opt_callback)](#apidoc.element.googleapis.auth.JWTClient.prototype.authorize)
- description and source-code
```javascript
authorize = function (opt_callback) {
  var that = this;
  var done = opt_callback || noop;

  that.refreshToken_(null, function(err, result) {
    if (!err) {
      that.credentials = result;
      that.credentials.refresh_token = 'jwt-placeholder';
      that.key = that.gtoken.key;
      that.email = that.gtoken.iss;
    }
    done(err, result);
  });
}
```
- example usage
```shell
...
key.client_email,
null,
key.private_key,
[scope1, scope2],
null
);

jwtClient.authorize(function (err, tokens) {
if (err) {
  console.log(err);
  return;
}

// Make an authorized request to list Drive files.
drive.files.list({
...
```

#### <a name="apidoc.element.googleapis.auth.JWTClient.prototype.createScoped"></a>[function <span class="apidocSignatureSpan">googleapis.auth.JWTClient.prototype.</span>createScoped (scopes)](#apidoc.element.googleapis.auth.JWTClient.prototype.createScoped)
- description and source-code
```javascript
createScoped = function (scopes) {
  return new JWT(this.email, this.keyFile, this.key, scopes, this.subject);
}
```
- example usage
```shell
...

// The createScopedRequired method returns true when running on GAE or a local developer
// machine. In that case, the desired scopes must be passed in manually. When the code is
// running in GCE or a Managed VM, the scopes are pulled from the GCE metadata server.
// See https://cloud.google.com/compute/docs/authentication for more information.
if (authClient.createScopedRequired && authClient.createScopedRequired()) {
  // Scopes can be specified either as an array or as a single, space-delimited string.
  authClient = authClient.createScoped([
    'https://www.googleapis.com/auth/compute'
  ]);
}

// Fetch the list of GCE zones within a project.
// NOTE: You must fill in your valid project ID before running this sample!
var compute = google.compute({
...
```

#### <a name="apidoc.element.googleapis.auth.JWTClient.prototype.createScopedRequired"></a>[function <span class="apidocSignatureSpan">googleapis.auth.JWTClient.prototype.</span>createScopedRequired ()](#apidoc.element.googleapis.auth.JWTClient.prototype.createScopedRequired)
- description and source-code
```javascript
createScopedRequired = function () {
  // If scopes is null, always return true.
  if (this.scopes) {
    // For arrays, check the array length.
    if (this.scopes instanceof Array) {
      return this.scopes.length === 0;
    }

    // For others, convert to a string and check the length.
    return String(this.scopes).length === 0;
  }

  return true;
}
```
- example usage
```shell
...
  throw err;
}

// The createScopedRequired method returns true when running on GAE or a local developer
// machine. In that case, the desired scopes must be passed in manually. When the code is
// running in GCE or a Managed VM, the scopes are pulled from the GCE metadata server.
// See https://cloud.google.com/compute/docs/authentication for more information.
if (authClient.createScopedRequired && authClient.createScopedRequired()) {
  // Scopes can be specified either as an array or as a single, space-delimited string.
  authClient = authClient.createScoped([
    'https://www.googleapis.com/auth/compute'
  ]);
}

// Fetch the list of GCE zones within a project.
...
```

#### <a name="apidoc.element.googleapis.auth.JWTClient.prototype.fromJSON"></a>[function <span class="apidocSignatureSpan">googleapis.auth.JWTClient.prototype.</span>fromJSON (json, opt_callback)](#apidoc.element.googleapis.auth.JWTClient.prototype.fromJSON)
- description and source-code
```javascript
fromJSON = function (json, opt_callback) {
  var that = this;
  var done = opt_callback || noop;
  if (!json) {
    done(new Error(
      'Must pass in a JSON object containing the service account auth settings.'));
    return;
  }
  if (!json.client_email) {
    done(new Error(
      'The incoming JSON object does not contain a client_email field'));
    return;
  }
  if (!json.private_key) {
    done(new Error(
      'The incoming JSON object does not contain a private_key field'));
    return;
  }
  // Extract the relevant information from the json key file.
  that.email = json.client_email;
  that.key = json.private_key;
  that.projectId = json.project_id;
  done();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.googleapis.auth.JWTClient.prototype.fromStream"></a>[function <span class="apidocSignatureSpan">googleapis.auth.JWTClient.prototype.</span>fromStream (stream, opt_callback)](#apidoc.element.googleapis.auth.JWTClient.prototype.fromStream)
- description and source-code
```javascript
fromStream = function (stream, opt_callback) {
  var that = this;
  var done = opt_callback || noop;

  if (!stream) {
    process.nextTick(function() {
      done(
        new Error('Must pass in a stream containing the service account auth settings.'));
    });
    return;
  }
  var s = '';
  stream.setEncoding('utf8');
  stream.on('data', function (chunk) {
    s += chunk;
  });
  stream.on('end', function () {
    try {
      var data = JSON.parse(s);
      that.fromJSON(data, opt_callback);
    } catch (err) {
      done(err);
    }
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.googleapis.auth.JWTClient.prototype.getRequestMetadata"></a>[function <span class="apidocSignatureSpan">googleapis.auth.JWTClient.prototype.</span>getRequestMetadata (opt_uri, metadataCb)](#apidoc.element.googleapis.auth.JWTClient.prototype.getRequestMetadata)
- description and source-code
```javascript
getRequestMetadata = function (opt_uri, metadataCb) {
  if (this.createScopedRequired() && opt_uri) {
    // no scopes have been set, but a uri has been provided.  Use JWTAccess credentials.
    var alt = new JWTAccess(this.email, this.key);
    return alt.getRequestMetadata(opt_uri, metadataCb);
  } else {
    return JWT.super_.prototype.getRequestMetadata.call(
        this, opt_uri, metadataCb);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.googleapis.auth.JWTClient.prototype.refreshToken_"></a>[function <span class="apidocSignatureSpan">googleapis.auth.JWTClient.prototype.</span>refreshToken_ (ignored_, opt_callback)](#apidoc.element.googleapis.auth.JWTClient.prototype.refreshToken_)
- description and source-code
```javascript
refreshToken_ = function (ignored_, opt_callback) {
  var done = opt_callback || noop;

  return this._createGToken(function(err, gToken) {
    if (err) {
      return done(err);
    } else {
      return gToken.getToken(function (err, token) {
        return done(err, {
          access_token: token,
          token_type: 'Bearer',
          expiry_date: gToken.expires_at
        });
      });
    }
  });
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.googleapis.discovery"></a>[module googleapis.discovery](#apidoc.module.googleapis.discovery)

#### <a name="apidoc.element.googleapis.discovery.discovery"></a>[function <span class="apidocSignatureSpan">googleapis.</span>discovery (options)](#apidoc.element.googleapis.discovery.discovery)
- description and source-code
```javascript
function Discovery(options) {
  this.options = options || {};
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.googleapis.discovery.prototype"></a>[module googleapis.discovery.prototype](#apidoc.module.googleapis.discovery.prototype)

#### <a name="apidoc.element.googleapis.discovery.prototype.discoverAPI"></a>[function <span class="apidocSignatureSpan">googleapis.discovery.prototype.</span>discoverAPI (apiDiscoveryUrl, callback)](#apidoc.element.googleapis.discovery.prototype.discoverAPI)
- description and source-code
```javascript
discoverAPI = function (apiDiscoveryUrl, callback) {
  function _generate (err, resp) {
    if (err) {
      return handleError(err, callback);
    }
    return callback(null, makeEndpoint(resp));
  }

  if (typeof apiDiscoveryUrl === 'string') {
    var parts = url.parse(apiDiscoveryUrl);

    if (apiDiscoveryUrl && !parts.protocol) {
      this.log('Reading from file ' + apiDiscoveryUrl);
      try {
        return fs.readFile(apiDiscoveryUrl, {
          encoding: 'utf8'
        }, function (err, file) {
          _generate(err, JSON.parse(file));
        });
      } catch (err) {
        return handleError(err, callback);
      }
    } else {
      this.log('Requesting ' + apiDiscoveryUrl);
      transporter.request({
        uri: apiDiscoveryUrl
      }, _generate);
    }
  } else {
    var options = apiDiscoveryUrl;
    this.log('Requesting ' + options.url);
    var parameters = {
      options: {
        url: options.url,
        method: 'GET'
      },
      requiredParams: [],
      pathParams: [],
      context: {
        google: {
          _options: {}
        },
        _options: {}
      }
    };
    delete options.url;
    parameters.params = options;
    createAPIRequest(parameters, _generate);
  }
}
```
- example usage
```shell
...
  }, function (err, resp) {
if (err) {
  return handleError(err, callback);
}

async.parallel(resp.items.map(function (api) {
  return function (cb) {
    self.discoverAPI(api.discoveryRestUrl, function (err, _api) {
      if (err) {
        return cb(err);
      }
      api.api = _api;
      cb(null, api);
    });
  };
...
```

#### <a name="apidoc.element.googleapis.discovery.prototype.discoverAllAPIs"></a>[function <span class="apidocSignatureSpan">googleapis.discovery.prototype.</span>discoverAllAPIs (discoveryUrl, callback)](#apidoc.element.googleapis.discovery.prototype.discoverAllAPIs)
- description and source-code
```javascript
discoverAllAPIs = function (discoveryUrl, callback) {
  var self = this;
  var headers = this.options.includePrivate ? {} : { 'X-User-Ip': '0.0.0.0' };
  transporter.request({
    uri: discoveryUrl,
    headers: headers
  }, function (err, resp) {
    if (err) {
      return handleError(err, callback);
    }

    async.parallel(resp.items.map(function (api) {
      return function (cb) {
        self.discoverAPI(api.discoveryRestUrl, function (err, _api) {
          if (err) {
            return cb(err);
          }
          api.api = _api;
          cb(null, api);
        });
      };
    }), function (err, apis) {
      if (err) {
        return callback(err);
      }

      var versionIndex = {};
      var apisIndex = {};

      apis.forEach(function (api) {
        if (!apisIndex[api.name]) {
          versionIndex[api.name] = {};
          apisIndex[api.name] = function (options) {
            var type = typeof options;
            var version;
            if (type === 'string') {
              version = options;
              options = {};
            } else if (type === 'object') {
              version = options.version;
              delete options.version;
            } else {
              throw new Error('Argument error: Accepts only string or object');
            }
            try {
              var Endpoint = versionIndex[api.name][version];
              var ep = new Endpoint(options);
              ep.google = this; // for drive.google.transporter
              return Object.freeze(ep); // create new & freeze
            } catch (e) {
              throw new Error(util.format('Unable to load endpoint %s("%s"): %s',
                api.name, version, e.message));
            }
          };
        }
        versionIndex[api.name][api.version] = api.api;
      });

      return callback(null, apisIndex);
    });
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.googleapis.discovery.prototype.log"></a>[function <span class="apidocSignatureSpan">googleapis.discovery.prototype.</span>log ()](#apidoc.element.googleapis.discovery.prototype.log)
- description and source-code
```javascript
log = function () {
  if (this.options && this.options.debug) {
    console.log.apply(this, arguments);
  }
}
```
- example usage
```shell
...
var params = {
  shortUrl: 'http://goo.gl/xKbRu3'
};

// get the long url of a shortened url
urlshortener.url.get(params, function (err, response) {
  if (err) {
    console.log('Encountered error', err);
  } else {
    console.log('Long url is', response.longUrl);
  }
});
'''

### Create a service client
...
```



# <a name="apidoc.module.googleapis.generator_utils"></a>[module googleapis.generator_utils](#apidoc.module.googleapis.generator_utils)

#### <a name="apidoc.element.googleapis.generator_utils.DefaultTransporter"></a>[function <span class="apidocSignatureSpan">googleapis.generator_utils.</span>DefaultTransporter ()](#apidoc.element.googleapis.generator_utils.DefaultTransporter)
- description and source-code
```javascript
function DefaultTransporter() {}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.googleapis.generator_utils.buildurl"></a>[function <span class="apidocSignatureSpan">googleapis.generator_utils.</span>buildurl (input)](#apidoc.element.googleapis.generator_utils.buildurl)
- description and source-code
```javascript
function buildurl(input) {
  return ('\'' + input + '\'')
    // No * symbols
    .replace(/\*/g, '')
    // No + symbols
    .replace(/\+/g, '')
    // replace double slashes with single slash (except in https://)
    .replace(/([^:]\/)\/+/g, '$1')
    // No {/ symbols
    .replace(/\{\//g, '/{');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.googleapis.generator_utils.handleError"></a>[function <span class="apidocSignatureSpan">googleapis.generator_utils.</span>handleError (err, callback)](#apidoc.element.googleapis.generator_utils.handleError)
- description and source-code
```javascript
function handleError(err, callback) {
  if (callback && typeof callback === 'function') {
    callback(err, null);
  }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.googleapis.transporters"></a>[module googleapis.transporters](#apidoc.module.googleapis.transporters)

#### <a name="apidoc.element.googleapis.transporters.transporters"></a>[function <span class="apidocSignatureSpan">googleapis.</span>transporters ()](#apidoc.element.googleapis.transporters.transporters)
- description and source-code
```javascript
function DefaultTransporter() {}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.googleapis.transporters.prototype"></a>[module googleapis.transporters.prototype](#apidoc.module.googleapis.transporters.prototype)

#### <a name="apidoc.element.googleapis.transporters.prototype.configure"></a>[function <span class="apidocSignatureSpan">googleapis.transporters.prototype.</span>configure (opts)](#apidoc.element.googleapis.transporters.prototype.configure)
- description and source-code
```javascript
configure = function (opts) {
  // set transporter user agent
  opts.headers = opts.headers || {};
  if (!opts.headers['User-Agent']) {
    opts.headers['User-Agent'] = this.USER_AGENT;
  } else if (opts.headers['User-Agent'].indexOf(this.USER_AGENT) === -1) {
    opts.headers['User-Agent'] = opts.headers['User-Agent'] + ' ' + this.USER_AGENT;
  }
  return opts;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.googleapis.transporters.prototype.request"></a>[function <span class="apidocSignatureSpan">googleapis.transporters.prototype.</span>request (opts, opt_callback)](#apidoc.element.googleapis.transporters.prototype.request)
- description and source-code
```javascript
request = function (opts, opt_callback) {
  opts = this.configure(opts);
  return request(opts.uri || opts.url, opts, this.wrapCallback_(opt_callback));
}
```
- example usage
```shell
...
  options
);
delete options.auth; // is overridden by our auth code
delete options.params; // We handle params ourselves and Request does not recognise 'params'

// create request (using authClient or otherwise and return request obj)
if (authClient) {
  req = authClient.request(options, callback);
} else {
  req = new DefaultTransporter().request(options, callback);
}

if (body) {
  body.pipe(req);
}
...
```

#### <a name="apidoc.element.googleapis.transporters.prototype.wrapCallback_"></a>[function <span class="apidocSignatureSpan">googleapis.transporters.prototype.</span>wrapCallback_ (opt_callback)](#apidoc.element.googleapis.transporters.prototype.wrapCallback_)
- description and source-code
```javascript
wrapCallback_ = function (opt_callback) {
  return function(err, res, body) {
    if (err || !body) {
      return opt_callback && opt_callback(err, body, res);
    }
    // Only and only application/json responses should
    // be decoded back to JSON, but there are cases API back-ends
    // responds without proper content-type.
    try {
      body = JSON.parse(body);
    } catch (err) { /* no op */ }

    if (body && body.error && res.statusCode !== 200) {
      if (typeof body.error === 'string') {
        err = new Error(body.error);
        err.code = res.statusCode;

      } else if (Array.isArray(body.error.errors)) {
        err = new Error(body.error.errors.map(
                         function(err) { return err.message; }
                       ).join('\n'));
        err.code = body.error.code;
        err.errors = body.error.errors;

      } else {
        err = new Error(body.error.message);
        err.code = body.error.code || res.statusCode;
      }

      body = null;

    } else if (res.statusCode >= 500) {
      // Consider all '500 responses' errors.
      err = new Error(body);
      err.code = res.statusCode;
      body = null;
    }

    if (opt_callback) {
      opt_callback(err, body, res);
    }
  };
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.googleapis.utils"></a>[module googleapis.utils](#apidoc.module.googleapis.utils)

#### <a name="apidoc.element.googleapis.utils.extend"></a>[function <span class="apidocSignatureSpan">googleapis.utils.</span>extend (obj)](#apidoc.element.googleapis.utils.extend)
- description and source-code
```javascript
extend = function (obj) {
  var source, prop;
  for (var i = 1, length = arguments.length; i < length; i++) {
    source = arguments[i];
    for (prop in source) {
      if (source.hasOwnProperty(prop)) {
        obj[prop] = source[prop];
      }
    }
  }
  return obj;
}
```
- example usage
```shell
...
 * @param  {object}   parameters Parameters used to form request
 * @param  {Function} callback   Callback when request finished or error found
 * @return {Request}             Returns Request object or null
 */
function createAPIRequest (parameters, callback) {
var req, body, missingParams;
var params = parameters.params;
var options = utils.extend({}, parameters.options);

// If the params are not present, and callback was passed instead,
// use params as the callback and create empty params.
if (typeof params === 'function') {
  callback = params;
  params = {};
}
...
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
