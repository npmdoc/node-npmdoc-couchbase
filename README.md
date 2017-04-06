# api documentation for  [couchbase (v2.3.2)](http://www.couchbase.com/communities/nodejs)  [![npm package](https://img.shields.io/npm/v/npmdoc-couchbase.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-couchbase) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-couchbase.svg)](https://travis-ci.org/npmdoc/node-npmdoc-couchbase)
#### The official Couchbase Node.js Client Library.

[![NPM](https://nodei.co/npm/couchbase.png?downloads=true)](https://www.npmjs.com/package/couchbase)

[![apidoc](https://npmdoc.github.io/node-npmdoc-couchbase/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-couchbase_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-couchbase/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-couchbase/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-couchbase/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "bugs": {
        "url": "http://www.couchbase.com/issues/browse/JSCBC",
        "email": "support@couchbase.com"
    },
    "config": {
        "native": false
    },
    "contributors": [
        {
            "name": "Alex McFadyen",
            "email": "alexmcfadyen@gmail.com"
        },
        {
            "name": "Brett Lawson",
            "email": "brett19@gmail.com"
        },
        {
            "name": "Bryan Donovan",
            "email": "bdondo@gmail.com"
        },
        {
            "name": "Chris Anderson",
            "email": "jchris@apache.org"
        },
        {
            "name": "Christoph Vitz",
            "email": "c.vitz@itsonix.eu"
        },
        {
            "name": "Fatih Cetinkaya",
            "email": "cmuratfatih@gmail.com"
        },
        {
            "name": "John",
            "email": "robodude2k@yahoo.com"
        },
        {
            "name": "Jonathan Giroux",
            "email": "bloutiouf@gmail.com"
        },
        {
            "name": "Kenan Sulayman",
            "email": "kenan@sly.mn"
        },
        {
            "name": "Kevin Reilly",
            "email": "kevin.reilly@touchfactor.com"
        },
        {
            "name": "Marcus Mennemeier",
            "email": "m.mennemeier@global-communication.de"
        },
        {
            "name": "Mark Everitt",
            "email": "meveritt@wizcorp.jp"
        },
        {
            "name": "Mark Nunberg",
            "email": "mnunberg@haskalah.org"
        },
        {
            "name": "Mark Nunberg",
            "email": "munberg@haskalah.org"
        },
        {
            "name": "Mark S. Everitt",
            "email": "mark.s.everitt@gmail.com"
        },
        {
            "name": "Patrick Heneise",
            "email": "patrick.heneise@gmail.com"
        },
        {
            "name": "Philipp Fehre",
            "email": "philipp.fehre@googlemail.com"
        },
        {
            "name": "Rod Vagg",
            "email": "rod@vagg.org"
        },
        {
            "name": "Sergey Avseyev",
            "email": "sergey.avseyev@gmail.com"
        },
        {
            "name": "Shimon Schwartz",
            "email": "shimonenator@gmail.com"
        },
        {
            "name": "Trond Norbye",
            "email": "trond.norbye@gmail.com"
        },
        {
            "name": "Tugdual Grall",
            "email": "tugdual@gmail.com"
        },
        {
            "name": "Tyler Waters",
            "email": "tyler.waters@gmail.com"
        },
        {
            "name": "kevireilly",
            "email": "kevin.reilly@touchfactor.com"
        },
        {
            "name": "markgetz",
            "email": "mark.getz@kellpro.com"
        },
        {
            "name": "pbihler",
            "email": "pbihler@users.noreply.github.com"
        },
        {
            "name": "prataprc",
            "email": "prataprc@gmail.com"
        },
        {
            "name": "subalakr",
            "email": "b.subhashni@gmail.com"
        }
    ],
    "dependencies": {
        "bindings": "~1.2.1",
        "mocha": "~3.2.0",
        "nan": "~2.5.1",
        "prebuild": "~6.1.0",
        "request": "~2.80.0"
    },
    "description": "The official Couchbase Node.js Client Library.",
    "devDependencies": {
        "ink-docstrap": "git+https://github.com/brett19/docstrap.git#master",
        "istanbul": "~0.4.3",
        "jsdoc": "~3.4.0",
        "jsdoc-stability-tag": "~1.0.0",
        "jshint": "~2.9.2",
        "mocha": "~3.2.0"
    },
    "directories": {},
    "dist": {
        "shasum": "5192180460dca378623bbecf64340cc87c3d82da",
        "tarball": "https://registry.npmjs.org/couchbase/-/couchbase-2.3.2.tgz"
    },
    "engines": {
        "node": ">=0.8.8"
    },
    "homepage": "http://www.couchbase.com/communities/nodejs",
    "keywords": [
        "couchbase",
        "libcouchbase",
        "memcached",
        "nosql",
        "json",
        "document"
    ],
    "license": "Apache-2.0",
    "main": "./lib/couchbase",
    "maintainers": [
        {
            "name": "couchbase",
            "email": "support@couchbase.com"
        },
        {
            "name": "brett19",
            "email": "brett19@gmail.com"
        }
    ],
    "name": "couchbase",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/couchbase/couchnode.git"
    },
    "scripts": {
        "install": "prebuild --install",
        "prebuild": "prebuild --verbose --strip",
        "rebuild": "prebuild --compile",
        "test": "mocha"
    },
    "version": "2.3.2"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module couchbase](#apidoc.module.couchbase)
1.  [function <span class="apidocSignatureSpan">couchbase.</span>BucketImpl (options)](#apidoc.element.couchbase.BucketImpl)
1.  [function <span class="apidocSignatureSpan">couchbase.</span>BucketImpl.FtsQueryResponse ()](#apidoc.element.couchbase.BucketImpl.FtsQueryResponse)
1.  [function <span class="apidocSignatureSpan">couchbase.</span>BucketImpl.N1qlQueryResponse ()](#apidoc.element.couchbase.BucketImpl.N1qlQueryResponse)
1.  [function <span class="apidocSignatureSpan">couchbase.</span>CbasQuery ()](#apidoc.element.couchbase.CbasQuery)
1.  [function <span class="apidocSignatureSpan">couchbase.</span>CbasQuery.Direct (str)](#apidoc.element.couchbase.CbasQuery.Direct)
1.  [function <span class="apidocSignatureSpan">couchbase.</span>ClassicAuthenticator (buckets, username, password)](#apidoc.element.couchbase.ClassicAuthenticator)
1.  [function <span class="apidocSignatureSpan">couchbase.</span>Cluster (cnstr, options)](#apidoc.element.couchbase.Cluster)
1.  [function <span class="apidocSignatureSpan">couchbase.</span>Cluster.CbasQueryResponse ()](#apidoc.element.couchbase.Cluster.CbasQueryResponse)
1.  [function <span class="apidocSignatureSpan">couchbase.</span>Error (message)](#apidoc.element.couchbase.Error)
1.  [function <span class="apidocSignatureSpan">couchbase.</span>Error.super_ ()](#apidoc.element.couchbase.Error.super_)
1.  [function <span class="apidocSignatureSpan">couchbase.</span>Mock.Cluster (cnstr)](#apidoc.element.couchbase.Mock.Cluster)
1.  [function <span class="apidocSignatureSpan">couchbase.</span>MutationState ()](#apidoc.element.couchbase.MutationState)
1.  [function <span class="apidocSignatureSpan">couchbase.</span>N1qlQuery ()](#apidoc.element.couchbase.N1qlQuery)
1.  [function <span class="apidocSignatureSpan">couchbase.</span>N1qlQuery.Direct (str)](#apidoc.element.couchbase.N1qlQuery.Direct)
1.  [function <span class="apidocSignatureSpan">couchbase.</span>SearchFacet.DateFacet (field, size)](#apidoc.element.couchbase.SearchFacet.DateFacet)
1.  [function <span class="apidocSignatureSpan">couchbase.</span>SearchFacet.NumericFacet (field, size)](#apidoc.element.couchbase.SearchFacet.NumericFacet)
1.  [function <span class="apidocSignatureSpan">couchbase.</span>SearchQuery (indexName, query)](#apidoc.element.couchbase.SearchQuery)
1.  [function <span class="apidocSignatureSpan">couchbase.</span>SearchQuery.BooleanQuery ()](#apidoc.element.couchbase.SearchQuery.BooleanQuery)
1.  [function <span class="apidocSignatureSpan">couchbase.</span>SearchQuery.ConjunctionQuery (queries)](#apidoc.element.couchbase.SearchQuery.ConjunctionQuery)
1.  [function <span class="apidocSignatureSpan">couchbase.</span>SearchQuery.DateRangeQuery ()](#apidoc.element.couchbase.SearchQuery.DateRangeQuery)
1.  [function <span class="apidocSignatureSpan">couchbase.</span>SearchQuery.DisjunctionQuery (queries)](#apidoc.element.couchbase.SearchQuery.DisjunctionQuery)
1.  [function <span class="apidocSignatureSpan">couchbase.</span>SearchQuery.DocIdQuery (ids)](#apidoc.element.couchbase.SearchQuery.DocIdQuery)
1.  [function <span class="apidocSignatureSpan">couchbase.</span>SearchQuery.MatchAllQuery ()](#apidoc.element.couchbase.SearchQuery.MatchAllQuery)
1.  [function <span class="apidocSignatureSpan">couchbase.</span>SearchQuery.MatchNoneQuery ()](#apidoc.element.couchbase.SearchQuery.MatchNoneQuery)
1.  [function <span class="apidocSignatureSpan">couchbase.</span>SearchQuery.MatchPhraseQuery (phrase)](#apidoc.element.couchbase.SearchQuery.MatchPhraseQuery)
1.  [function <span class="apidocSignatureSpan">couchbase.</span>SearchQuery.MatchQuery (match)](#apidoc.element.couchbase.SearchQuery.MatchQuery)
1.  [function <span class="apidocSignatureSpan">couchbase.</span>SearchQuery.NumericRangeQuery ()](#apidoc.element.couchbase.SearchQuery.NumericRangeQuery)
1.  [function <span class="apidocSignatureSpan">couchbase.</span>SearchQuery.PhraseQuery (terms)](#apidoc.element.couchbase.SearchQuery.PhraseQuery)
1.  [function <span class="apidocSignatureSpan">couchbase.</span>SearchQuery.PrefixQuery (prefix)](#apidoc.element.couchbase.SearchQuery.PrefixQuery)
1.  [function <span class="apidocSignatureSpan">couchbase.</span>SearchQuery.QueryStringQuery (query)](#apidoc.element.couchbase.SearchQuery.QueryStringQuery)
1.  [function <span class="apidocSignatureSpan">couchbase.</span>SearchQuery.RegexpQuery (regexp)](#apidoc.element.couchbase.SearchQuery.RegexpQuery)
1.  [function <span class="apidocSignatureSpan">couchbase.</span>SearchQuery.TermQuery (term)](#apidoc.element.couchbase.SearchQuery.TermQuery)
1.  [function <span class="apidocSignatureSpan">couchbase.</span>SearchQuery.WildcardQuery (wildcard)](#apidoc.element.couchbase.SearchQuery.WildcardQuery)
1.  [function <span class="apidocSignatureSpan">couchbase.</span>SpatialQuery ()](#apidoc.element.couchbase.SpatialQuery)
1.  [function <span class="apidocSignatureSpan">couchbase.</span>ViewQuery ()](#apidoc.element.couchbase.ViewQuery)
1.  [function <span class="apidocSignatureSpan">couchbase.</span>bucketmgr (bucket)](#apidoc.element.couchbase.bucketmgr)
1.  [function <span class="apidocSignatureSpan">couchbase.</span>clustermgr (cluster, username, password)](#apidoc.element.couchbase.clustermgr)
1.  object <span class="apidocSignatureSpan">couchbase.</span>BucketImpl.prototype
1.  object <span class="apidocSignatureSpan">couchbase.</span>CbasQuery.Direct.prototype
1.  object <span class="apidocSignatureSpan">couchbase.</span>CbasQuery.prototype
1.  object <span class="apidocSignatureSpan">couchbase.</span>Cluster.prototype
1.  object <span class="apidocSignatureSpan">couchbase.</span>Mock
1.  object <span class="apidocSignatureSpan">couchbase.</span>Mock.Cluster.prototype
1.  object <span class="apidocSignatureSpan">couchbase.</span>MutationState.prototype
1.  object <span class="apidocSignatureSpan">couchbase.</span>N1qlQuery.Direct.prototype
1.  object <span class="apidocSignatureSpan">couchbase.</span>N1qlQuery.prototype
1.  object <span class="apidocSignatureSpan">couchbase.</span>SearchFacet
1.  object <span class="apidocSignatureSpan">couchbase.</span>SearchFacet.DateFacet.prototype
1.  object <span class="apidocSignatureSpan">couchbase.</span>SearchFacet.NumericFacet.prototype
1.  object <span class="apidocSignatureSpan">couchbase.</span>SearchQuery.BooleanQuery.prototype
1.  object <span class="apidocSignatureSpan">couchbase.</span>SearchQuery.ConjunctionQuery.prototype
1.  object <span class="apidocSignatureSpan">couchbase.</span>SearchQuery.DateRangeQuery.prototype
1.  object <span class="apidocSignatureSpan">couchbase.</span>SearchQuery.DisjunctionQuery.prototype
1.  object <span class="apidocSignatureSpan">couchbase.</span>SearchQuery.DocIdQuery.prototype
1.  object <span class="apidocSignatureSpan">couchbase.</span>SearchQuery.MatchAllQuery.prototype
1.  object <span class="apidocSignatureSpan">couchbase.</span>SearchQuery.MatchNoneQuery.prototype
1.  object <span class="apidocSignatureSpan">couchbase.</span>SearchQuery.MatchPhraseQuery.prototype
1.  object <span class="apidocSignatureSpan">couchbase.</span>SearchQuery.MatchQuery.prototype
1.  object <span class="apidocSignatureSpan">couchbase.</span>SearchQuery.NumericRangeQuery.prototype
1.  object <span class="apidocSignatureSpan">couchbase.</span>SearchQuery.PhraseQuery.prototype
1.  object <span class="apidocSignatureSpan">couchbase.</span>SearchQuery.PrefixQuery.prototype
1.  object <span class="apidocSignatureSpan">couchbase.</span>SearchQuery.QueryStringQuery.prototype
1.  object <span class="apidocSignatureSpan">couchbase.</span>SearchQuery.RegexpQuery.prototype
1.  object <span class="apidocSignatureSpan">couchbase.</span>SearchQuery.TermQuery.prototype
1.  object <span class="apidocSignatureSpan">couchbase.</span>SearchQuery.WildcardQuery.prototype
1.  object <span class="apidocSignatureSpan">couchbase.</span>SearchQuery.prototype
1.  object <span class="apidocSignatureSpan">couchbase.</span>SpatialQuery.prototype
1.  object <span class="apidocSignatureSpan">couchbase.</span>ViewQuery.prototype
1.  object <span class="apidocSignatureSpan">couchbase.</span>auth
1.  object <span class="apidocSignatureSpan">couchbase.</span>binding
1.  object <span class="apidocSignatureSpan">couchbase.</span>bucketmgr.prototype
1.  object <span class="apidocSignatureSpan">couchbase.</span>clustermgr.prototype
1.  object <span class="apidocSignatureSpan">couchbase.</span>errors
1.  object <span class="apidocSignatureSpan">couchbase.</span>searchquery_queries
1.  object <span class="apidocSignatureSpan">couchbase.</span>utils

#### [module couchbase.BucketImpl](#apidoc.module.couchbase.BucketImpl)
1.  [function <span class="apidocSignatureSpan">couchbase.</span>BucketImpl (options)](#apidoc.element.couchbase.BucketImpl.BucketImpl)
1.  [function <span class="apidocSignatureSpan">couchbase.BucketImpl.</span>FtsQueryResponse ()](#apidoc.element.couchbase.BucketImpl.FtsQueryResponse)
1.  [function <span class="apidocSignatureSpan">couchbase.BucketImpl.</span>N1qlQueryResponse ()](#apidoc.element.couchbase.BucketImpl.N1qlQueryResponse)
1.  [function <span class="apidocSignatureSpan">couchbase.BucketImpl.</span>super_ ()](#apidoc.element.couchbase.BucketImpl.super_)

#### [module couchbase.BucketImpl.FtsQueryResponse](#apidoc.module.couchbase.BucketImpl.FtsQueryResponse)
1.  [function <span class="apidocSignatureSpan">couchbase.BucketImpl.</span>FtsQueryResponse ()](#apidoc.element.couchbase.BucketImpl.FtsQueryResponse.FtsQueryResponse)
1.  [function <span class="apidocSignatureSpan">couchbase.BucketImpl.FtsQueryResponse.</span>super_ ()](#apidoc.element.couchbase.BucketImpl.FtsQueryResponse.super_)

#### [module couchbase.BucketImpl.N1qlQueryResponse](#apidoc.module.couchbase.BucketImpl.N1qlQueryResponse)
1.  [function <span class="apidocSignatureSpan">couchbase.BucketImpl.</span>N1qlQueryResponse ()](#apidoc.element.couchbase.BucketImpl.N1qlQueryResponse.N1qlQueryResponse)
1.  [function <span class="apidocSignatureSpan">couchbase.BucketImpl.N1qlQueryResponse.</span>super_ ()](#apidoc.element.couchbase.BucketImpl.N1qlQueryResponse.super_)

#### [module couchbase.BucketImpl.prototype](#apidoc.module.couchbase.BucketImpl.prototype)
1.  [function <span class="apidocSignatureSpan">couchbase.BucketImpl.prototype.</span>_capiRequest (path, method, callback)](#apidoc.element.couchbase.BucketImpl.prototype._capiRequest)
1.  [function <span class="apidocSignatureSpan">couchbase.BucketImpl.prototype.</span>_checkCasOption (options)](#apidoc.element.couchbase.BucketImpl.prototype._checkCasOption)
1.  [function <span class="apidocSignatureSpan">couchbase.BucketImpl.prototype.</span>_checkDuraOptions (options)](#apidoc.element.couchbase.BucketImpl.prototype._checkDuraOptions)
1.  [function <span class="apidocSignatureSpan">couchbase.BucketImpl.prototype.</span>_checkExpiryOption (options)](#apidoc.element.couchbase.BucketImpl.prototype._checkExpiryOption)
1.  [function <span class="apidocSignatureSpan">couchbase.BucketImpl.prototype.</span>_checkHashkeyOption (options)](#apidoc.element.couchbase.BucketImpl.prototype._checkHashkeyOption)
1.  [function <span class="apidocSignatureSpan">couchbase.BucketImpl.prototype.</span>_ctl (cc, value)](#apidoc.element.couchbase.BucketImpl.prototype._ctl)
1.  [function <span class="apidocSignatureSpan">couchbase.BucketImpl.prototype.</span>_execAndUriParse (fn)](#apidoc.element.couchbase.BucketImpl.prototype._execAndUriParse)
1.  [function <span class="apidocSignatureSpan">couchbase.BucketImpl.prototype.</span>_fts (query, callback)](#apidoc.element.couchbase.BucketImpl.prototype._fts)
1.  [function <span class="apidocSignatureSpan">couchbase.BucketImpl.prototype.</span>_ftsReq (q, emitter)](#apidoc.element.couchbase.BucketImpl.prototype._ftsReq)
1.  [function <span class="apidocSignatureSpan">couchbase.BucketImpl.prototype.</span>_interceptEndure (key, options, is_delete, callback)](#apidoc.element.couchbase.BucketImpl.prototype._interceptEndure)
1.  [function <span class="apidocSignatureSpan">couchbase.BucketImpl.prototype.</span>_invoke (fn, args)](#apidoc.element.couchbase.BucketImpl.prototype._invoke)
1.  [function <span class="apidocSignatureSpan">couchbase.BucketImpl.prototype.</span>_isValidKey (key)](#apidoc.element.couchbase.BucketImpl.prototype._isValidKey)
1.  [function <span class="apidocSignatureSpan">couchbase.BucketImpl.prototype.</span>_isValidPath (path)](#apidoc.element.couchbase.BucketImpl.prototype._isValidPath)
1.  [function <span class="apidocSignatureSpan">couchbase.BucketImpl.prototype.</span>_lookupIn (builder, callback)](#apidoc.element.couchbase.BucketImpl.prototype._lookupIn)
1.  [function <span class="apidocSignatureSpan">couchbase.BucketImpl.prototype.</span>_maybeInvoke (fn, args)](#apidoc.element.couchbase.BucketImpl.prototype._maybeInvoke)
1.  [function <span class="apidocSignatureSpan">couchbase.BucketImpl.prototype.</span>_mgmtRequest (path, method, callback)](#apidoc.element.couchbase.BucketImpl.prototype._mgmtRequest)
1.  [function <span class="apidocSignatureSpan">couchbase.BucketImpl.prototype.</span>_mutateIn (builder, callback)](#apidoc.element.couchbase.BucketImpl.prototype._mutateIn)
1.  [function <span class="apidocSignatureSpan">couchbase.BucketImpl.prototype.</span>_n1ql (query, params, callback)](#apidoc.element.couchbase.BucketImpl.prototype._n1ql)
1.  [function <span class="apidocSignatureSpan">couchbase.BucketImpl.prototype.</span>_n1qlReq (host, q, adhoc, emitter)](#apidoc.element.couchbase.BucketImpl.prototype._n1qlReq)
1.  [function <span class="apidocSignatureSpan">couchbase.BucketImpl.prototype.</span>_store (key, value, options, callback, opType)](#apidoc.element.couchbase.BucketImpl.prototype._store)
1.  [function <span class="apidocSignatureSpan">couchbase.BucketImpl.prototype.</span>_view (viewtype, ddoc, name, q, callback)](#apidoc.element.couchbase.BucketImpl.prototype._view)
1.  [function <span class="apidocSignatureSpan">couchbase.BucketImpl.prototype.</span>_viewReq (viewtype, ddoc, name, q, emitter)](#apidoc.element.couchbase.BucketImpl.prototype._viewReq)
1.  [function <span class="apidocSignatureSpan">couchbase.BucketImpl.prototype.</span>append (key, fragment, options, callback)](#apidoc.element.couchbase.BucketImpl.prototype.append)
1.  [function <span class="apidocSignatureSpan">couchbase.BucketImpl.prototype.</span>counter (key, delta, options, callback)](#apidoc.element.couchbase.BucketImpl.prototype.counter)
1.  [function <span class="apidocSignatureSpan">couchbase.BucketImpl.prototype.</span>disconnect ()](#apidoc.element.couchbase.BucketImpl.prototype.disconnect)
1.  [function <span class="apidocSignatureSpan">couchbase.BucketImpl.prototype.</span>enableN1ql (hosts)](#apidoc.element.couchbase.BucketImpl.prototype.enableN1ql)
1.  [function <span class="apidocSignatureSpan">couchbase.BucketImpl.prototype.</span>get (key, options, callback)](#apidoc.element.couchbase.BucketImpl.prototype.get)
1.  [function <span class="apidocSignatureSpan">couchbase.BucketImpl.prototype.</span>getAndLock (key, options, callback)](#apidoc.element.couchbase.BucketImpl.prototype.getAndLock)
1.  [function <span class="apidocSignatureSpan">couchbase.BucketImpl.prototype.</span>getAndTouch (key, expiry, options, callback)](#apidoc.element.couchbase.BucketImpl.prototype.getAndTouch)
1.  [function <span class="apidocSignatureSpan">couchbase.BucketImpl.prototype.</span>getMulti (keys, options, callback)](#apidoc.element.couchbase.BucketImpl.prototype.getMulti)
1.  [function <span class="apidocSignatureSpan">couchbase.BucketImpl.prototype.</span>getReplica (key, options, callback)](#apidoc.element.couchbase.BucketImpl.prototype.getReplica)
1.  [function <span class="apidocSignatureSpan">couchbase.BucketImpl.prototype.</span>insert (key, value, options, callback)](#apidoc.element.couchbase.BucketImpl.prototype.insert)
1.  [function <span class="apidocSignatureSpan">couchbase.BucketImpl.prototype.</span>listAppend (key, value, options, callback)](#apidoc.element.couchbase.BucketImpl.prototype.listAppend)
1.  [function <span class="apidocSignatureSpan">couchbase.BucketImpl.prototype.</span>listGet (key, index, options, callback)](#apidoc.element.couchbase.BucketImpl.prototype.listGet)
1.  [function <span class="apidocSignatureSpan">couchbase.BucketImpl.prototype.</span>listPrepend (key, value, options, callback)](#apidoc.element.couchbase.BucketImpl.prototype.listPrepend)
1.  [function <span class="apidocSignatureSpan">couchbase.BucketImpl.prototype.</span>listPush (key, value, options, callback)](#apidoc.element.couchbase.BucketImpl.prototype.listPush)
1.  [function <span class="apidocSignatureSpan">couchbase.BucketImpl.prototype.</span>listRemove (key, index, options, callback)](#apidoc.element.couchbase.BucketImpl.prototype.listRemove)
1.  [function <span class="apidocSignatureSpan">couchbase.BucketImpl.prototype.</span>listSet (key, index, value, options, callback)](#apidoc.element.couchbase.BucketImpl.prototype.listSet)
1.  [function <span class="apidocSignatureSpan">couchbase.BucketImpl.prototype.</span>listShift (key, value, options, callback)](#apidoc.element.couchbase.BucketImpl.prototype.listShift)
1.  [function <span class="apidocSignatureSpan">couchbase.BucketImpl.prototype.</span>listSize (key, options, callback)](#apidoc.element.couchbase.BucketImpl.prototype.listSize)
1.  [function <span class="apidocSignatureSpan">couchbase.BucketImpl.prototype.</span>lookupIn (key, options)](#apidoc.element.couchbase.BucketImpl.prototype.lookupIn)
1.  [function <span class="apidocSignatureSpan">couchbase.BucketImpl.prototype.</span>manager ()](#apidoc.element.couchbase.BucketImpl.prototype.manager)
1.  [function <span class="apidocSignatureSpan">couchbase.BucketImpl.prototype.</span>mapAdd (key, path, value, options, callback)](#apidoc.element.couchbase.BucketImpl.prototype.mapAdd)
1.  [function <span class="apidocSignatureSpan">couchbase.BucketImpl.prototype.</span>mapGet (key, path, options, callback)](#apidoc.element.couchbase.BucketImpl.prototype.mapGet)
1.  [function <span class="apidocSignatureSpan">couchbase.BucketImpl.prototype.</span>mapRemove (key, path, options, callback)](#apidoc.element.couchbase.BucketImpl.prototype.mapRemove)
1.  [function <span class="apidocSignatureSpan">couchbase.BucketImpl.prototype.</span>mapSize (key, options, callback)](#apidoc.element.couchbase.BucketImpl.prototype.mapSize)
1.  [function <span class="apidocSignatureSpan">couchbase.BucketImpl.prototype.</span>mutateIn (key, options)](#apidoc.element.couchbase.BucketImpl.prototype.mutateIn)
1.  [function <span class="apidocSignatureSpan">couchbase.BucketImpl.prototype.</span>prepend (key, fragment, options, callback)](#apidoc.element.couchbase.BucketImpl.prototype.prepend)
1.  [function <span class="apidocSignatureSpan">couchbase.BucketImpl.prototype.</span>query (query, params, callback)](#apidoc.element.couchbase.BucketImpl.prototype.query)
1.  [function <span class="apidocSignatureSpan">couchbase.BucketImpl.prototype.</span>queuePop (key, options, callback)](#apidoc.element.couchbase.BucketImpl.prototype.queuePop)
1.  [function <span class="apidocSignatureSpan">couchbase.BucketImpl.prototype.</span>queuePush (key, value, options, callback)](#apidoc.element.couchbase.BucketImpl.prototype.queuePush)
1.  [function <span class="apidocSignatureSpan">couchbase.BucketImpl.prototype.</span>queueSize (key, options, callback)](#apidoc.element.couchbase.BucketImpl.prototype.queueSize)
1.  [function <span class="apidocSignatureSpan">couchbase.BucketImpl.prototype.</span>remove (key, options, callback)](#apidoc.element.couchbase.BucketImpl.prototype.remove)
1.  [function <span class="apidocSignatureSpan">couchbase.BucketImpl.prototype.</span>replace (key, value, options, callback)](#apidoc.element.couchbase.BucketImpl.prototype.replace)
1.  [function <span class="apidocSignatureSpan">couchbase.BucketImpl.prototype.</span>setAdd (key, value, options, callback)](#apidoc.element.couchbase.BucketImpl.prototype.setAdd)
1.  [function <span class="apidocSignatureSpan">couchbase.BucketImpl.prototype.</span>setExists (key, value, options, callback)](#apidoc.element.couchbase.BucketImpl.prototype.setExists)
1.  [function <span class="apidocSignatureSpan">couchbase.BucketImpl.prototype.</span>setRemove (key, value, options, callback)](#apidoc.element.couchbase.BucketImpl.prototype.setRemove)
1.  [function <span class="apidocSignatureSpan">couchbase.BucketImpl.prototype.</span>setSize (key, options, callback)](#apidoc.element.couchbase.BucketImpl.prototype.setSize)
1.  [function <span class="apidocSignatureSpan">couchbase.BucketImpl.prototype.</span>setTranscoder (encoder, decoder)](#apidoc.element.couchbase.BucketImpl.prototype.setTranscoder)
1.  [function <span class="apidocSignatureSpan">couchbase.BucketImpl.prototype.</span>touch (key, expiry, options, callback)](#apidoc.element.couchbase.BucketImpl.prototype.touch)
1.  [function <span class="apidocSignatureSpan">couchbase.BucketImpl.prototype.</span>unlock (key, cas, options, callback)](#apidoc.element.couchbase.BucketImpl.prototype.unlock)
1.  [function <span class="apidocSignatureSpan">couchbase.BucketImpl.prototype.</span>upsert (key, value, options, callback)](#apidoc.element.couchbase.BucketImpl.prototype.upsert)

#### [module couchbase.CbasQuery](#apidoc.module.couchbase.CbasQuery)
1.  [function <span class="apidocSignatureSpan">couchbase.</span>CbasQuery ()](#apidoc.element.couchbase.CbasQuery.CbasQuery)
1.  [function <span class="apidocSignatureSpan">couchbase.CbasQuery.</span>Direct (str)](#apidoc.element.couchbase.CbasQuery.Direct)
1.  [function <span class="apidocSignatureSpan">couchbase.CbasQuery.</span>fromString (str)](#apidoc.element.couchbase.CbasQuery.fromString)

#### [module couchbase.CbasQuery.Direct](#apidoc.module.couchbase.CbasQuery.Direct)
1.  [function <span class="apidocSignatureSpan">couchbase.CbasQuery.</span>Direct (str)](#apidoc.element.couchbase.CbasQuery.Direct.Direct)
1.  [function <span class="apidocSignatureSpan">couchbase.CbasQuery.Direct.</span>super_ ()](#apidoc.element.couchbase.CbasQuery.Direct.super_)

#### [module couchbase.CbasQuery.Direct.prototype](#apidoc.module.couchbase.CbasQuery.Direct.prototype)
1.  [function <span class="apidocSignatureSpan">couchbase.CbasQuery.Direct.prototype.</span>toObject (args)](#apidoc.element.couchbase.CbasQuery.Direct.prototype.toObject)
1.  [function <span class="apidocSignatureSpan">couchbase.CbasQuery.Direct.prototype.</span>toString (args)](#apidoc.element.couchbase.CbasQuery.Direct.prototype.toString)

#### [module couchbase.CbasQuery.prototype](#apidoc.module.couchbase.CbasQuery.prototype)
1.  [function <span class="apidocSignatureSpan">couchbase.CbasQuery.prototype.</span>toString ()](#apidoc.element.couchbase.CbasQuery.prototype.toString)

#### [module couchbase.Cluster](#apidoc.module.couchbase.Cluster)
1.  [function <span class="apidocSignatureSpan">couchbase.</span>Cluster (cnstr, options)](#apidoc.element.couchbase.Cluster.Cluster)
1.  [function <span class="apidocSignatureSpan">couchbase.Cluster.</span>CbasQueryResponse ()](#apidoc.element.couchbase.Cluster.CbasQueryResponse)

#### [module couchbase.Cluster.CbasQueryResponse](#apidoc.module.couchbase.Cluster.CbasQueryResponse)
1.  [function <span class="apidocSignatureSpan">couchbase.Cluster.</span>CbasQueryResponse ()](#apidoc.element.couchbase.Cluster.CbasQueryResponse.CbasQueryResponse)
1.  [function <span class="apidocSignatureSpan">couchbase.Cluster.CbasQueryResponse.</span>super_ ()](#apidoc.element.couchbase.Cluster.CbasQueryResponse.super_)

#### [module couchbase.Cluster.prototype](#apidoc.module.couchbase.Cluster.prototype)
1.  [function <span class="apidocSignatureSpan">couchbase.Cluster.prototype.</span>_cbas (query, params, callback)](#apidoc.element.couchbase.Cluster.prototype._cbas)
1.  [function <span class="apidocSignatureSpan">couchbase.Cluster.prototype.</span>_cbasReq (host, q, emitter)](#apidoc.element.couchbase.Cluster.prototype._cbasReq)
1.  [function <span class="apidocSignatureSpan">couchbase.Cluster.prototype.</span>_fts (query, callback)](#apidoc.element.couchbase.Cluster.prototype._fts)
1.  [function <span class="apidocSignatureSpan">couchbase.Cluster.prototype.</span>_ftsReq (q, emitter)](#apidoc.element.couchbase.Cluster.prototype._ftsReq)
1.  [function <span class="apidocSignatureSpan">couchbase.Cluster.prototype.</span>_invoke (fn, args)](#apidoc.element.couchbase.Cluster.prototype._invoke)
1.  [function <span class="apidocSignatureSpan">couchbase.Cluster.prototype.</span>_maybeInvoke (fn, args)](#apidoc.element.couchbase.Cluster.prototype._maybeInvoke)
1.  [function <span class="apidocSignatureSpan">couchbase.Cluster.prototype.</span>_n1ql (query, params, callback)](#apidoc.element.couchbase.Cluster.prototype._n1ql)
1.  [function <span class="apidocSignatureSpan">couchbase.Cluster.prototype.</span>_n1qlReq (host, q, adhoc, emitter)](#apidoc.element.couchbase.Cluster.prototype._n1qlReq)
1.  [function <span class="apidocSignatureSpan">couchbase.Cluster.prototype.</span>authenticate (auther)](#apidoc.element.couchbase.Cluster.prototype.authenticate)
1.  [function <span class="apidocSignatureSpan">couchbase.Cluster.prototype.</span>enableCbas (hosts)](#apidoc.element.couchbase.Cluster.prototype.enableCbas)
1.  [function <span class="apidocSignatureSpan">couchbase.Cluster.prototype.</span>manager (username, password)](#apidoc.element.couchbase.Cluster.prototype.manager)
1.  [function <span class="apidocSignatureSpan">couchbase.Cluster.prototype.</span>openBucket (name, password, callback)](#apidoc.element.couchbase.Cluster.prototype.openBucket)
1.  [function <span class="apidocSignatureSpan">couchbase.Cluster.prototype.</span>query (query, params, callback)](#apidoc.element.couchbase.Cluster.prototype.query)

#### [module couchbase.Error](#apidoc.module.couchbase.Error)
1.  [function <span class="apidocSignatureSpan">couchbase.</span>Error (message)](#apidoc.element.couchbase.Error.Error)
1.  [function <span class="apidocSignatureSpan">couchbase.Error.</span>super_ ()](#apidoc.element.couchbase.Error.super_)

#### [module couchbase.Error.super_](#apidoc.module.couchbase.Error.super_)
1.  [function <span class="apidocSignatureSpan">couchbase.Error.</span>super_ ()](#apidoc.element.couchbase.Error.super_.super_)
1.  [function <span class="apidocSignatureSpan">couchbase.Error.super_.</span>captureStackTrace ()](#apidoc.element.couchbase.Error.super_.captureStackTrace)
1.  number <span class="apidocSignatureSpan">couchbase.Error.super_.</span>stackTraceLimit

#### [module couchbase.Mock](#apidoc.module.couchbase.Mock)
1.  [function <span class="apidocSignatureSpan">couchbase.Mock.</span>Cluster (cnstr)](#apidoc.element.couchbase.Mock.Cluster)
1.  [function <span class="apidocSignatureSpan">couchbase.Mock.</span>Error (message, code)](#apidoc.element.couchbase.Mock.Error)
1.  [function <span class="apidocSignatureSpan">couchbase.Mock.</span>N1qlQuery ()](#apidoc.element.couchbase.Mock.N1qlQuery)
1.  [function <span class="apidocSignatureSpan">couchbase.Mock.</span>SpatialQuery ()](#apidoc.element.couchbase.Mock.SpatialQuery)
1.  [function <span class="apidocSignatureSpan">couchbase.Mock.</span>ViewQuery ()](#apidoc.element.couchbase.Mock.ViewQuery)
1.  object <span class="apidocSignatureSpan">couchbase.</span>Mock
1.  object <span class="apidocSignatureSpan">couchbase.Mock.</span>errors

#### [module couchbase.Mock.Cluster](#apidoc.module.couchbase.Mock.Cluster)
1.  [function <span class="apidocSignatureSpan">couchbase.Mock.</span>Cluster (cnstr)](#apidoc.element.couchbase.Mock.Cluster.Cluster)

#### [module couchbase.Mock.Cluster.prototype](#apidoc.module.couchbase.Mock.Cluster.prototype)
1.  [function <span class="apidocSignatureSpan">couchbase.Mock.Cluster.prototype.</span>manager (username, password)](#apidoc.element.couchbase.Mock.Cluster.prototype.manager)
1.  [function <span class="apidocSignatureSpan">couchbase.Mock.Cluster.prototype.</span>openBucket (name, password, callback)](#apidoc.element.couchbase.Mock.Cluster.prototype.openBucket)

#### [module couchbase.MutationState](#apidoc.module.couchbase.MutationState)
1.  [function <span class="apidocSignatureSpan">couchbase.</span>MutationState ()](#apidoc.element.couchbase.MutationState.MutationState)

#### [module couchbase.MutationState.prototype](#apidoc.module.couchbase.MutationState.prototype)
1.  [function <span class="apidocSignatureSpan">couchbase.MutationState.prototype.</span>_addSingle (token)](#apidoc.element.couchbase.MutationState.prototype._addSingle)
1.  [function <span class="apidocSignatureSpan">couchbase.MutationState.prototype.</span>add ()](#apidoc.element.couchbase.MutationState.prototype.add)
1.  [function <span class="apidocSignatureSpan">couchbase.MutationState.prototype.</span>inspect ()](#apidoc.element.couchbase.MutationState.prototype.inspect)
1.  [function <span class="apidocSignatureSpan">couchbase.MutationState.prototype.</span>toJSON ()](#apidoc.element.couchbase.MutationState.prototype.toJSON)

#### [module couchbase.N1qlQuery](#apidoc.module.couchbase.N1qlQuery)
1.  [function <span class="apidocSignatureSpan">couchbase.</span>N1qlQuery ()](#apidoc.element.couchbase.N1qlQuery.N1qlQuery)
1.  [function <span class="apidocSignatureSpan">couchbase.N1qlQuery.</span>Direct (str)](#apidoc.element.couchbase.N1qlQuery.Direct)
1.  [function <span class="apidocSignatureSpan">couchbase.N1qlQuery.</span>fromString (str)](#apidoc.element.couchbase.N1qlQuery.fromString)
1.  object <span class="apidocSignatureSpan">couchbase.N1qlQuery.</span>Consistency

#### [module couchbase.N1qlQuery.Direct](#apidoc.module.couchbase.N1qlQuery.Direct)
1.  [function <span class="apidocSignatureSpan">couchbase.N1qlQuery.</span>Direct (str)](#apidoc.element.couchbase.N1qlQuery.Direct.Direct)
1.  [function <span class="apidocSignatureSpan">couchbase.N1qlQuery.Direct.</span>super_ ()](#apidoc.element.couchbase.N1qlQuery.Direct.super_)

#### [module couchbase.N1qlQuery.Direct.prototype](#apidoc.module.couchbase.N1qlQuery.Direct.prototype)
1.  [function <span class="apidocSignatureSpan">couchbase.N1qlQuery.Direct.prototype.</span>adhoc (adhoc)](#apidoc.element.couchbase.N1qlQuery.Direct.prototype.adhoc)
1.  [function <span class="apidocSignatureSpan">couchbase.N1qlQuery.Direct.prototype.</span>consistency (val)](#apidoc.element.couchbase.N1qlQuery.Direct.prototype.consistency)
1.  [function <span class="apidocSignatureSpan">couchbase.N1qlQuery.Direct.prototype.</span>consistentWith (state)](#apidoc.element.couchbase.N1qlQuery.Direct.prototype.consistentWith)
1.  [function <span class="apidocSignatureSpan">couchbase.N1qlQuery.Direct.prototype.</span>pretty (pretty)](#apidoc.element.couchbase.N1qlQuery.Direct.prototype.pretty)
1.  [function <span class="apidocSignatureSpan">couchbase.N1qlQuery.Direct.prototype.</span>toObject (args)](#apidoc.element.couchbase.N1qlQuery.Direct.prototype.toObject)
1.  [function <span class="apidocSignatureSpan">couchbase.N1qlQuery.Direct.prototype.</span>toString (args)](#apidoc.element.couchbase.N1qlQuery.Direct.prototype.toString)

#### [module couchbase.N1qlQuery.prototype](#apidoc.module.couchbase.N1qlQuery.prototype)
1.  [function <span class="apidocSignatureSpan">couchbase.N1qlQuery.prototype.</span>toString ()](#apidoc.element.couchbase.N1qlQuery.prototype.toString)

#### [module couchbase.SearchFacet](#apidoc.module.couchbase.SearchFacet)
1.  [function <span class="apidocSignatureSpan">couchbase.SearchFacet.</span>DateFacet (field, size)](#apidoc.element.couchbase.SearchFacet.DateFacet)
1.  [function <span class="apidocSignatureSpan">couchbase.SearchFacet.</span>NumericFacet (field, size)](#apidoc.element.couchbase.SearchFacet.NumericFacet)
1.  [function <span class="apidocSignatureSpan">couchbase.SearchFacet.</span>TermFacet (field, size)](#apidoc.element.couchbase.SearchFacet.TermFacet)
1.  [function <span class="apidocSignatureSpan">couchbase.SearchFacet.</span>date (field, size)](#apidoc.element.couchbase.SearchFacet.date)
1.  [function <span class="apidocSignatureSpan">couchbase.SearchFacet.</span>numeric (field, size)](#apidoc.element.couchbase.SearchFacet.numeric)
1.  [function <span class="apidocSignatureSpan">couchbase.SearchFacet.</span>term (field, size)](#apidoc.element.couchbase.SearchFacet.term)

#### [module couchbase.SearchFacet.DateFacet](#apidoc.module.couchbase.SearchFacet.DateFacet)
1.  [function <span class="apidocSignatureSpan">couchbase.SearchFacet.</span>DateFacet (field, size)](#apidoc.element.couchbase.SearchFacet.DateFacet.DateFacet)

#### [module couchbase.SearchFacet.DateFacet.prototype](#apidoc.module.couchbase.SearchFacet.DateFacet.prototype)
1.  [function <span class="apidocSignatureSpan">couchbase.SearchFacet.DateFacet.prototype.</span>addRange (name, start, end)](#apidoc.element.couchbase.SearchFacet.DateFacet.prototype.addRange)

#### [module couchbase.SearchFacet.NumericFacet](#apidoc.module.couchbase.SearchFacet.NumericFacet)
1.  [function <span class="apidocSignatureSpan">couchbase.SearchFacet.</span>NumericFacet (field, size)](#apidoc.element.couchbase.SearchFacet.NumericFacet.NumericFacet)

#### [module couchbase.SearchFacet.NumericFacet.prototype](#apidoc.module.couchbase.SearchFacet.NumericFacet.prototype)
1.  [function <span class="apidocSignatureSpan">couchbase.SearchFacet.NumericFacet.prototype.</span>addRange (name, start, end)](#apidoc.element.couchbase.SearchFacet.NumericFacet.prototype.addRange)

#### [module couchbase.SearchQuery](#apidoc.module.couchbase.SearchQuery)
1.  [function <span class="apidocSignatureSpan">couchbase.</span>SearchQuery (indexName, query)](#apidoc.element.couchbase.SearchQuery.SearchQuery)
1.  [function <span class="apidocSignatureSpan">couchbase.SearchQuery.</span>BooleanFieldQuery (val)](#apidoc.element.couchbase.SearchQuery.BooleanFieldQuery)
1.  [function <span class="apidocSignatureSpan">couchbase.SearchQuery.</span>BooleanQuery ()](#apidoc.element.couchbase.SearchQuery.BooleanQuery)
1.  [function <span class="apidocSignatureSpan">couchbase.SearchQuery.</span>ConjunctionQuery (queries)](#apidoc.element.couchbase.SearchQuery.ConjunctionQuery)
1.  [function <span class="apidocSignatureSpan">couchbase.SearchQuery.</span>DateRangeQuery ()](#apidoc.element.couchbase.SearchQuery.DateRangeQuery)
1.  [function <span class="apidocSignatureSpan">couchbase.SearchQuery.</span>DisjunctionQuery (queries)](#apidoc.element.couchbase.SearchQuery.DisjunctionQuery)
1.  [function <span class="apidocSignatureSpan">couchbase.SearchQuery.</span>DocIdQuery (ids)](#apidoc.element.couchbase.SearchQuery.DocIdQuery)
1.  [function <span class="apidocSignatureSpan">couchbase.SearchQuery.</span>MatchAllQuery ()](#apidoc.element.couchbase.SearchQuery.MatchAllQuery)
1.  [function <span class="apidocSignatureSpan">couchbase.SearchQuery.</span>MatchNoneQuery ()](#apidoc.element.couchbase.SearchQuery.MatchNoneQuery)
1.  [function <span class="apidocSignatureSpan">couchbase.SearchQuery.</span>MatchPhraseQuery (phrase)](#apidoc.element.couchbase.SearchQuery.MatchPhraseQuery)
1.  [function <span class="apidocSignatureSpan">couchbase.SearchQuery.</span>MatchQuery (match)](#apidoc.element.couchbase.SearchQuery.MatchQuery)
1.  [function <span class="apidocSignatureSpan">couchbase.SearchQuery.</span>NumericRangeQuery ()](#apidoc.element.couchbase.SearchQuery.NumericRangeQuery)
1.  [function <span class="apidocSignatureSpan">couchbase.SearchQuery.</span>PhraseQuery (terms)](#apidoc.element.couchbase.SearchQuery.PhraseQuery)
1.  [function <span class="apidocSignatureSpan">couchbase.SearchQuery.</span>PrefixQuery (prefix)](#apidoc.element.couchbase.SearchQuery.PrefixQuery)
1.  [function <span class="apidocSignatureSpan">couchbase.SearchQuery.</span>QueryStringQuery (query)](#apidoc.element.couchbase.SearchQuery.QueryStringQuery)
1.  [function <span class="apidocSignatureSpan">couchbase.SearchQuery.</span>RegexpQuery (regexp)](#apidoc.element.couchbase.SearchQuery.RegexpQuery)
1.  [function <span class="apidocSignatureSpan">couchbase.SearchQuery.</span>TermQuery (term)](#apidoc.element.couchbase.SearchQuery.TermQuery)
1.  [function <span class="apidocSignatureSpan">couchbase.SearchQuery.</span>WildcardQuery (wildcard)](#apidoc.element.couchbase.SearchQuery.WildcardQuery)
1.  [function <span class="apidocSignatureSpan">couchbase.SearchQuery.</span>boolean ()](#apidoc.element.couchbase.SearchQuery.boolean)
1.  [function <span class="apidocSignatureSpan">couchbase.SearchQuery.</span>booleanField (val)](#apidoc.element.couchbase.SearchQuery.booleanField)
1.  [function <span class="apidocSignatureSpan">couchbase.SearchQuery.</span>conjuncts (queries)](#apidoc.element.couchbase.SearchQuery.conjuncts)
1.  [function <span class="apidocSignatureSpan">couchbase.SearchQuery.</span>dateRange ()](#apidoc.element.couchbase.SearchQuery.dateRange)
1.  [function <span class="apidocSignatureSpan">couchbase.SearchQuery.</span>disjuncts (queries)](#apidoc.element.couchbase.SearchQuery.disjuncts)
1.  [function <span class="apidocSignatureSpan">couchbase.SearchQuery.</span>docIds (ids)](#apidoc.element.couchbase.SearchQuery.docIds)
1.  [function <span class="apidocSignatureSpan">couchbase.SearchQuery.</span>match (match)](#apidoc.element.couchbase.SearchQuery.match)
1.  [function <span class="apidocSignatureSpan">couchbase.SearchQuery.</span>matchAll ()](#apidoc.element.couchbase.SearchQuery.matchAll)
1.  [function <span class="apidocSignatureSpan">couchbase.SearchQuery.</span>matchNone ()](#apidoc.element.couchbase.SearchQuery.matchNone)
1.  [function <span class="apidocSignatureSpan">couchbase.SearchQuery.</span>matchPhrase (phrase)](#apidoc.element.couchbase.SearchQuery.matchPhrase)
1.  [function <span class="apidocSignatureSpan">couchbase.SearchQuery.</span>new (indexName, query)](#apidoc.element.couchbase.SearchQuery.new)
1.  [function <span class="apidocSignatureSpan">couchbase.SearchQuery.</span>numericRange ()](#apidoc.element.couchbase.SearchQuery.numericRange)
1.  [function <span class="apidocSignatureSpan">couchbase.SearchQuery.</span>phrase (terms)](#apidoc.element.couchbase.SearchQuery.phrase)
1.  [function <span class="apidocSignatureSpan">couchbase.SearchQuery.</span>prefix (prefix)](#apidoc.element.couchbase.SearchQuery.prefix)
1.  [function <span class="apidocSignatureSpan">couchbase.SearchQuery.</span>queryString (query)](#apidoc.element.couchbase.SearchQuery.queryString)
1.  [function <span class="apidocSignatureSpan">couchbase.SearchQuery.</span>regexp (regexp)](#apidoc.element.couchbase.SearchQuery.regexp)
1.  [function <span class="apidocSignatureSpan">couchbase.SearchQuery.</span>term (term)](#apidoc.element.couchbase.SearchQuery.term)
1.  [function <span class="apidocSignatureSpan">couchbase.SearchQuery.</span>wildcard (wildcard)](#apidoc.element.couchbase.SearchQuery.wildcard)
1.  object <span class="apidocSignatureSpan">couchbase.SearchQuery.</span>Consistency
1.  object <span class="apidocSignatureSpan">couchbase.SearchQuery.</span>HighlightStyle

#### [module couchbase.SearchQuery.BooleanQuery](#apidoc.module.couchbase.SearchQuery.BooleanQuery)
1.  [function <span class="apidocSignatureSpan">couchbase.SearchQuery.</span>BooleanQuery ()](#apidoc.element.couchbase.SearchQuery.BooleanQuery.BooleanQuery)

#### [module couchbase.SearchQuery.BooleanQuery.prototype](#apidoc.module.couchbase.SearchQuery.BooleanQuery.prototype)
1.  [function <span class="apidocSignatureSpan">couchbase.SearchQuery.BooleanQuery.prototype.</span>boost (boost)](#apidoc.element.couchbase.SearchQuery.BooleanQuery.prototype.boost)
1.  [function <span class="apidocSignatureSpan">couchbase.SearchQuery.BooleanQuery.prototype.</span>must (query)](#apidoc.element.couchbase.SearchQuery.BooleanQuery.prototype.must)
1.  [function <span class="apidocSignatureSpan">couchbase.SearchQuery.BooleanQuery.prototype.</span>mustNot (query)](#apidoc.element.couchbase.SearchQuery.BooleanQuery.prototype.mustNot)
1.  [function <span class="apidocSignatureSpan">couchbase.SearchQuery.BooleanQuery.prototype.</span>should (query)](#apidoc.element.couchbase.SearchQuery.BooleanQuery.prototype.should)
1.  [function <span class="apidocSignatureSpan">couchbase.SearchQuery.BooleanQuery.prototype.</span>shouldMin (shouldMin)](#apidoc.element.couchbase.SearchQuery.BooleanQuery.prototype.shouldMin)
1.  [function <span class="apidocSignatureSpan">couchbase.SearchQuery.BooleanQuery.prototype.</span>toJSON ()](#apidoc.element.couchbase.SearchQuery.BooleanQuery.prototype.toJSON)

#### [module couchbase.SearchQuery.ConjunctionQuery](#apidoc.module.couchbase.SearchQuery.ConjunctionQuery)
1.  [function <span class="apidocSignatureSpan">couchbase.SearchQuery.</span>ConjunctionQuery (queries)](#apidoc.element.couchbase.SearchQuery.ConjunctionQuery.ConjunctionQuery)

#### [module couchbase.SearchQuery.ConjunctionQuery.prototype](#apidoc.module.couchbase.SearchQuery.ConjunctionQuery.prototype)
1.  [function <span class="apidocSignatureSpan">couchbase.SearchQuery.ConjunctionQuery.prototype.</span>and (queries)](#apidoc.element.couchbase.SearchQuery.ConjunctionQuery.prototype.and)
1.  [function <span class="apidocSignatureSpan">couchbase.SearchQuery.ConjunctionQuery.prototype.</span>boost (boost)](#apidoc.element.couchbase.SearchQuery.ConjunctionQuery.prototype.boost)
1.  [function <span class="apidocSignatureSpan">couchbase.SearchQuery.ConjunctionQuery.prototype.</span>toJSON ()](#apidoc.element.couchbase.SearchQuery.ConjunctionQuery.prototype.toJSON)

#### [module couchbase.SearchQuery.DateRangeQuery](#apidoc.module.couchbase.SearchQuery.DateRangeQuery)
1.  [function <span class="apidocSignatureSpan">couchbase.SearchQuery.</span>DateRangeQuery ()](#apidoc.element.couchbase.SearchQuery.DateRangeQuery.DateRangeQuery)

#### [module couchbase.SearchQuery.DateRangeQuery.prototype](#apidoc.module.couchbase.SearchQuery.DateRangeQuery.prototype)
1.  [function <span class="apidocSignatureSpan">couchbase.SearchQuery.DateRangeQuery.prototype.</span>boost (boost)](#apidoc.element.couchbase.SearchQuery.DateRangeQuery.prototype.boost)
1.  [function <span class="apidocSignatureSpan">couchbase.SearchQuery.DateRangeQuery.prototype.</span>dateTimeParser (dateTimeParser)](#apidoc.element.couchbase.SearchQuery.DateRangeQuery.prototype.dateTimeParser)
1.  [function <span class="apidocSignatureSpan">couchbase.SearchQuery.DateRangeQuery.prototype.</span>toJSON ()](#apidoc.element.couchbase.SearchQuery.DateRangeQuery.prototype.toJSON)

#### [module couchbase.SearchQuery.DisjunctionQuery](#apidoc.module.couchbase.SearchQuery.DisjunctionQuery)
1.  [function <span class="apidocSignatureSpan">couchbase.SearchQuery.</span>DisjunctionQuery (queries)](#apidoc.element.couchbase.SearchQuery.DisjunctionQuery.DisjunctionQuery)

#### [module couchbase.SearchQuery.DisjunctionQuery.prototype](#apidoc.module.couchbase.SearchQuery.DisjunctionQuery.prototype)
1.  [function <span class="apidocSignatureSpan">couchbase.SearchQuery.DisjunctionQuery.prototype.</span>boost (boost)](#apidoc.element.couchbase.SearchQuery.DisjunctionQuery.prototype.boost)
1.  [function <span class="apidocSignatureSpan">couchbase.SearchQuery.DisjunctionQuery.prototype.</span>or (queries)](#apidoc.element.couchbase.SearchQuery.DisjunctionQuery.prototype.or)
1.  [function <span class="apidocSignatureSpan">couchbase.SearchQuery.DisjunctionQuery.prototype.</span>toJSON ()](#apidoc.element.couchbase.SearchQuery.DisjunctionQuery.prototype.toJSON)

#### [module couchbase.SearchQuery.DocIdQuery](#apidoc.module.couchbase.SearchQuery.DocIdQuery)
1.  [function <span class="apidocSignatureSpan">couchbase.SearchQuery.</span>DocIdQuery (ids)](#apidoc.element.couchbase.SearchQuery.DocIdQuery.DocIdQuery)

#### [module couchbase.SearchQuery.DocIdQuery.prototype](#apidoc.module.couchbase.SearchQuery.DocIdQuery.prototype)
1.  [function <span class="apidocSignatureSpan">couchbase.SearchQuery.DocIdQuery.prototype.</span>addDocIds (ids)](#apidoc.element.couchbase.SearchQuery.DocIdQuery.prototype.addDocIds)
1.  [function <span class="apidocSignatureSpan">couchbase.SearchQuery.DocIdQuery.prototype.</span>boost (boost)](#apidoc.element.couchbase.SearchQuery.DocIdQuery.prototype.boost)
1.  [function <span class="apidocSignatureSpan">couchbase.SearchQuery.DocIdQuery.prototype.</span>field (field)](#apidoc.element.couchbase.SearchQuery.DocIdQuery.prototype.field)
1.  [function <span class="apidocSignatureSpan">couchbase.SearchQuery.DocIdQuery.prototype.</span>toJSON ()](#apidoc.element.couchbase.SearchQuery.DocIdQuery.prototype.toJSON)

#### [module couchbase.SearchQuery.MatchAllQuery](#apidoc.module.couchbase.SearchQuery.MatchAllQuery)
1.  [function <span class="apidocSignatureSpan">couchbase.SearchQuery.</span>MatchAllQuery ()](#apidoc.element.couchbase.SearchQuery.MatchAllQuery.MatchAllQuery)

#### [module couchbase.SearchQuery.MatchAllQuery.prototype](#apidoc.module.couchbase.SearchQuery.MatchAllQuery.prototype)
1.  [function <span class="apidocSignatureSpan">couchbase.SearchQuery.MatchAllQuery.prototype.</span>toJSON ()](#apidoc.element.couchbase.SearchQuery.MatchAllQuery.prototype.toJSON)

#### [module couchbase.SearchQuery.MatchNoneQuery](#apidoc.module.couchbase.SearchQuery.MatchNoneQuery)
1.  [function <span class="apidocSignatureSpan">couchbase.SearchQuery.</span>MatchNoneQuery ()](#apidoc.element.couchbase.SearchQuery.MatchNoneQuery.MatchNoneQuery)

#### [module couchbase.SearchQuery.MatchNoneQuery.prototype](#apidoc.module.couchbase.SearchQuery.MatchNoneQuery.prototype)
1.  [function <span class="apidocSignatureSpan">couchbase.SearchQuery.MatchNoneQuery.prototype.</span>toJSON ()](#apidoc.element.couchbase.SearchQuery.MatchNoneQuery.prototype.toJSON)

#### [module couchbase.SearchQuery.MatchPhraseQuery](#apidoc.module.couchbase.SearchQuery.MatchPhraseQuery)
1.  [function <span class="apidocSignatureSpan">couchbase.SearchQuery.</span>MatchPhraseQuery (phrase)](#apidoc.element.couchbase.SearchQuery.MatchPhraseQuery.MatchPhraseQuery)

#### [module couchbase.SearchQuery.MatchPhraseQuery.prototype](#apidoc.module.couchbase.SearchQuery.MatchPhraseQuery.prototype)
1.  [function <span class="apidocSignatureSpan">couchbase.SearchQuery.MatchPhraseQuery.prototype.</span>analyzer (analyzer)](#apidoc.element.couchbase.SearchQuery.MatchPhraseQuery.prototype.analyzer)
1.  [function <span class="apidocSignatureSpan">couchbase.SearchQuery.MatchPhraseQuery.prototype.</span>boost (boost)](#apidoc.element.couchbase.SearchQuery.MatchPhraseQuery.prototype.boost)
1.  [function <span class="apidocSignatureSpan">couchbase.SearchQuery.MatchPhraseQuery.prototype.</span>field (field)](#apidoc.element.couchbase.SearchQuery.MatchPhraseQuery.prototype.field)
1.  [function <span class="apidocSignatureSpan">couchbase.SearchQuery.MatchPhraseQuery.prototype.</span>toJSON ()](#apidoc.element.couchbase.SearchQuery.MatchPhraseQuery.prototype.toJSON)

#### [module couchbase.SearchQuery.MatchQuery](#apidoc.module.couchbase.SearchQuery.MatchQuery)
1.  [function <span class="apidocSignatureSpan">couchbase.SearchQuery.</span>MatchQuery (match)](#apidoc.element.couchbase.SearchQuery.MatchQuery.MatchQuery)

#### [module couchbase.SearchQuery.MatchQuery.prototype](#apidoc.module.couchbase.SearchQuery.MatchQuery.prototype)
1.  [function <span class="apidocSignatureSpan">couchbase.SearchQuery.MatchQuery.prototype.</span>analyzer (analyzer)](#apidoc.element.couchbase.SearchQuery.MatchQuery.prototype.analyzer)
1.  [function <span class="apidocSignatureSpan">couchbase.SearchQuery.MatchQuery.prototype.</span>boost (boost)](#apidoc.element.couchbase.SearchQuery.MatchQuery.prototype.boost)
1.  [function <span class="apidocSignatureSpan">couchbase.SearchQuery.MatchQuery.prototype.</span>field (field)](#apidoc.element.couchbase.SearchQuery.MatchQuery.prototype.field)
1.  [function <span class="apidocSignatureSpan">couchbase.SearchQuery.MatchQuery.prototype.</span>fuzziness (fuzziness)](#apidoc.element.couchbase.SearchQuery.MatchQuery.prototype.fuzziness)
1.  [function <span class="apidocSignatureSpan">couchbase.SearchQuery.MatchQuery.prototype.</span>prefixLength (prefixLength)](#apidoc.element.couchbase.SearchQuery.MatchQuery.prototype.prefixLength)
1.  [function <span class="apidocSignatureSpan">couchbase.SearchQuery.MatchQuery.prototype.</span>toJSON ()](#apidoc.element.couchbase.SearchQuery.MatchQuery.prototype.toJSON)

#### [module couchbase.SearchQuery.NumericRangeQuery](#apidoc.module.couchbase.SearchQuery.NumericRangeQuery)
1.  [function <span class="apidocSignatureSpan">couchbase.SearchQuery.</span>NumericRangeQuery ()](#apidoc.element.couchbase.SearchQuery.NumericRangeQuery.NumericRangeQuery)

#### [module couchbase.SearchQuery.NumericRangeQuery.prototype](#apidoc.module.couchbase.SearchQuery.NumericRangeQuery.prototype)
1.  [function <span class="apidocSignatureSpan">couchbase.SearchQuery.NumericRangeQuery.prototype.</span>boost (boost)](#apidoc.element.couchbase.SearchQuery.NumericRangeQuery.prototype.boost)
1.  [function <span class="apidocSignatureSpan">couchbase.SearchQuery.NumericRangeQuery.prototype.</span>toJSON ()](#apidoc.element.couchbase.SearchQuery.NumericRangeQuery.prototype.toJSON)

#### [module couchbase.SearchQuery.PhraseQuery](#apidoc.module.couchbase.SearchQuery.PhraseQuery)
1.  [function <span class="apidocSignatureSpan">couchbase.SearchQuery.</span>PhraseQuery (terms)](#apidoc.element.couchbase.SearchQuery.PhraseQuery.PhraseQuery)

#### [module couchbase.SearchQuery.PhraseQuery.prototype](#apidoc.module.couchbase.SearchQuery.PhraseQuery.prototype)
1.  [function <span class="apidocSignatureSpan">couchbase.SearchQuery.PhraseQuery.prototype.</span>boost (boost)](#apidoc.element.couchbase.SearchQuery.PhraseQuery.prototype.boost)
1.  [function <span class="apidocSignatureSpan">couchbase.SearchQuery.PhraseQuery.prototype.</span>field (field)](#apidoc.element.couchbase.SearchQuery.PhraseQuery.prototype.field)
1.  [function <span class="apidocSignatureSpan">couchbase.SearchQuery.PhraseQuery.prototype.</span>toJSON ()](#apidoc.element.couchbase.SearchQuery.PhraseQuery.prototype.toJSON)

#### [module couchbase.SearchQuery.PrefixQuery](#apidoc.module.couchbase.SearchQuery.PrefixQuery)
1.  [function <span class="apidocSignatureSpan">couchbase.SearchQuery.</span>PrefixQuery (prefix)](#apidoc.element.couchbase.SearchQuery.PrefixQuery.PrefixQuery)

#### [module couchbase.SearchQuery.PrefixQuery.prototype](#apidoc.module.couchbase.SearchQuery.PrefixQuery.prototype)
1.  [function <span class="apidocSignatureSpan">couchbase.SearchQuery.PrefixQuery.prototype.</span>boost (boost)](#apidoc.element.couchbase.SearchQuery.PrefixQuery.prototype.boost)
1.  [function <span class="apidocSignatureSpan">couchbase.SearchQuery.PrefixQuery.prototype.</span>field (field)](#apidoc.element.couchbase.SearchQuery.PrefixQuery.prototype.field)
1.  [function <span class="apidocSignatureSpan">couchbase.SearchQuery.PrefixQuery.prototype.</span>toJSON ()](#apidoc.element.couchbase.SearchQuery.PrefixQuery.prototype.toJSON)

#### [module couchbase.SearchQuery.QueryStringQuery](#apidoc.module.couchbase.SearchQuery.QueryStringQuery)
1.  [function <span class="apidocSignatureSpan">couchbase.SearchQuery.</span>QueryStringQuery (query)](#apidoc.element.couchbase.SearchQuery.QueryStringQuery.QueryStringQuery)

#### [module couchbase.SearchQuery.QueryStringQuery.prototype](#apidoc.module.couchbase.SearchQuery.QueryStringQuery.prototype)
1.  [function <span class="apidocSignatureSpan">couchbase.SearchQuery.QueryStringQuery.prototype.</span>boost (boost)](#apidoc.element.couchbase.SearchQuery.QueryStringQuery.prototype.boost)
1.  [function <span class="apidocSignatureSpan">couchbase.SearchQuery.QueryStringQuery.prototype.</span>toJSON ()](#apidoc.element.couchbase.SearchQuery.QueryStringQuery.prototype.toJSON)

#### [module couchbase.SearchQuery.RegexpQuery](#apidoc.module.couchbase.SearchQuery.RegexpQuery)
1.  [function <span class="apidocSignatureSpan">couchbase.SearchQuery.</span>RegexpQuery (regexp)](#apidoc.element.couchbase.SearchQuery.RegexpQuery.RegexpQuery)

#### [module couchbase.SearchQuery.RegexpQuery.prototype](#apidoc.module.couchbase.SearchQuery.RegexpQuery.prototype)
1.  [function <span class="apidocSignatureSpan">couchbase.SearchQuery.RegexpQuery.prototype.</span>boost (boost)](#apidoc.element.couchbase.SearchQuery.RegexpQuery.prototype.boost)
1.  [function <span class="apidocSignatureSpan">couchbase.SearchQuery.RegexpQuery.prototype.</span>field (field)](#apidoc.element.couchbase.SearchQuery.RegexpQuery.prototype.field)
1.  [function <span class="apidocSignatureSpan">couchbase.SearchQuery.RegexpQuery.prototype.</span>toJSON ()](#apidoc.element.couchbase.SearchQuery.RegexpQuery.prototype.toJSON)

#### [module couchbase.SearchQuery.TermQuery](#apidoc.module.couchbase.SearchQuery.TermQuery)
1.  [function <span class="apidocSignatureSpan">couchbase.SearchQuery.</span>TermQuery (term)](#apidoc.element.couchbase.SearchQuery.TermQuery.TermQuery)

#### [module couchbase.SearchQuery.TermQuery.prototype](#apidoc.module.couchbase.SearchQuery.TermQuery.prototype)
1.  [function <span class="apidocSignatureSpan">couchbase.SearchQuery.TermQuery.prototype.</span>boost (boost)](#apidoc.element.couchbase.SearchQuery.TermQuery.prototype.boost)
1.  [function <span class="apidocSignatureSpan">couchbase.SearchQuery.TermQuery.prototype.</span>field (field)](#apidoc.element.couchbase.SearchQuery.TermQuery.prototype.field)
1.  [function <span class="apidocSignatureSpan">couchbase.SearchQuery.TermQuery.prototype.</span>fuzziness (fuzziness)](#apidoc.element.couchbase.SearchQuery.TermQuery.prototype.fuzziness)
1.  [function <span class="apidocSignatureSpan">couchbase.SearchQuery.TermQuery.prototype.</span>prefixLength (prefixLength)](#apidoc.element.couchbase.SearchQuery.TermQuery.prototype.prefixLength)
1.  [function <span class="apidocSignatureSpan">couchbase.SearchQuery.TermQuery.prototype.</span>toJSON ()](#apidoc.element.couchbase.SearchQuery.TermQuery.prototype.toJSON)

#### [module couchbase.SearchQuery.WildcardQuery](#apidoc.module.couchbase.SearchQuery.WildcardQuery)
1.  [function <span class="apidocSignatureSpan">couchbase.SearchQuery.</span>WildcardQuery (wildcard)](#apidoc.element.couchbase.SearchQuery.WildcardQuery.WildcardQuery)

#### [module couchbase.SearchQuery.WildcardQuery.prototype](#apidoc.module.couchbase.SearchQuery.WildcardQuery.prototype)
1.  [function <span class="apidocSignatureSpan">couchbase.SearchQuery.WildcardQuery.prototype.</span>boost (boost)](#apidoc.element.couchbase.SearchQuery.WildcardQuery.prototype.boost)
1.  [function <span class="apidocSignatureSpan">couchbase.SearchQuery.WildcardQuery.prototype.</span>field (field)](#apidoc.element.couchbase.SearchQuery.WildcardQuery.prototype.field)
1.  [function <span class="apidocSignatureSpan">couchbase.SearchQuery.WildcardQuery.prototype.</span>toJSON ()](#apidoc.element.couchbase.SearchQuery.WildcardQuery.prototype.toJSON)

#### [module couchbase.SearchQuery.prototype](#apidoc.module.couchbase.SearchQuery.prototype)
1.  [function <span class="apidocSignatureSpan">couchbase.SearchQuery.prototype.</span>addFacet (name, facet)](#apidoc.element.couchbase.SearchQuery.prototype.addFacet)
1.  [function <span class="apidocSignatureSpan">couchbase.SearchQuery.prototype.</span>consistency (val)](#apidoc.element.couchbase.SearchQuery.prototype.consistency)
1.  [function <span class="apidocSignatureSpan">couchbase.SearchQuery.prototype.</span>consistentWith (state)](#apidoc.element.couchbase.SearchQuery.prototype.consistentWith)
1.  [function <span class="apidocSignatureSpan">couchbase.SearchQuery.prototype.</span>explain (explain)](#apidoc.element.couchbase.SearchQuery.prototype.explain)
1.  [function <span class="apidocSignatureSpan">couchbase.SearchQuery.prototype.</span>fields (fields)](#apidoc.element.couchbase.SearchQuery.prototype.fields)
1.  [function <span class="apidocSignatureSpan">couchbase.SearchQuery.prototype.</span>highlight (style, fields)](#apidoc.element.couchbase.SearchQuery.prototype.highlight)
1.  [function <span class="apidocSignatureSpan">couchbase.SearchQuery.prototype.</span>limit (limit)](#apidoc.element.couchbase.SearchQuery.prototype.limit)
1.  [function <span class="apidocSignatureSpan">couchbase.SearchQuery.prototype.</span>skip (skip)](#apidoc.element.couchbase.SearchQuery.prototype.skip)
1.  [function <span class="apidocSignatureSpan">couchbase.SearchQuery.prototype.</span>sort (fields)](#apidoc.element.couchbase.SearchQuery.prototype.sort)
1.  [function <span class="apidocSignatureSpan">couchbase.SearchQuery.prototype.</span>timeout (timeout)](#apidoc.element.couchbase.SearchQuery.prototype.timeout)
1.  [function <span class="apidocSignatureSpan">couchbase.SearchQuery.prototype.</span>toJSON ()](#apidoc.element.couchbase.SearchQuery.prototype.toJSON)

#### [module couchbase.SpatialQuery](#apidoc.module.couchbase.SpatialQuery)
1.  [function <span class="apidocSignatureSpan">couchbase.</span>SpatialQuery ()](#apidoc.element.couchbase.SpatialQuery.SpatialQuery)
1.  [function <span class="apidocSignatureSpan">couchbase.SpatialQuery.</span>from (ddoc, name)](#apidoc.element.couchbase.SpatialQuery.from)
1.  object <span class="apidocSignatureSpan">couchbase.SpatialQuery.</span>Update

#### [module couchbase.SpatialQuery.prototype](#apidoc.module.couchbase.SpatialQuery.prototype)
1.  [function <span class="apidocSignatureSpan">couchbase.SpatialQuery.prototype.</span>bbox (bbox)](#apidoc.element.couchbase.SpatialQuery.prototype.bbox)
1.  [function <span class="apidocSignatureSpan">couchbase.SpatialQuery.prototype.</span>custom (opts)](#apidoc.element.couchbase.SpatialQuery.prototype.custom)
1.  [function <span class="apidocSignatureSpan">couchbase.SpatialQuery.prototype.</span>from (ddoc, name)](#apidoc.element.couchbase.SpatialQuery.prototype.from)
1.  [function <span class="apidocSignatureSpan">couchbase.SpatialQuery.prototype.</span>limit (limit)](#apidoc.element.couchbase.SpatialQuery.prototype.limit)
1.  [function <span class="apidocSignatureSpan">couchbase.SpatialQuery.prototype.</span>skip (skip)](#apidoc.element.couchbase.SpatialQuery.prototype.skip)
1.  [function <span class="apidocSignatureSpan">couchbase.SpatialQuery.prototype.</span>stale (stale)](#apidoc.element.couchbase.SpatialQuery.prototype.stale)

#### [module couchbase.ViewQuery](#apidoc.module.couchbase.ViewQuery)
1.  [function <span class="apidocSignatureSpan">couchbase.</span>ViewQuery ()](#apidoc.element.couchbase.ViewQuery.ViewQuery)
1.  [function <span class="apidocSignatureSpan">couchbase.ViewQuery.</span>Default ()](#apidoc.element.couchbase.ViewQuery.Default)
1.  [function <span class="apidocSignatureSpan">couchbase.ViewQuery.</span>Spatial ()](#apidoc.element.couchbase.ViewQuery.Spatial)
1.  [function <span class="apidocSignatureSpan">couchbase.ViewQuery.</span>from (ddoc, name)](#apidoc.element.couchbase.ViewQuery.from)
1.  [function <span class="apidocSignatureSpan">couchbase.ViewQuery.</span>fromSpatial (ddoc, name)](#apidoc.element.couchbase.ViewQuery.fromSpatial)
1.  object <span class="apidocSignatureSpan">couchbase.ViewQuery.</span>ErrorMode
1.  object <span class="apidocSignatureSpan">couchbase.ViewQuery.</span>Order
1.  object <span class="apidocSignatureSpan">couchbase.ViewQuery.</span>Update

#### [module couchbase.ViewQuery.prototype](#apidoc.module.couchbase.ViewQuery.prototype)
1.  [function <span class="apidocSignatureSpan">couchbase.ViewQuery.prototype.</span>custom (opts)](#apidoc.element.couchbase.ViewQuery.prototype.custom)
1.  [function <span class="apidocSignatureSpan">couchbase.ViewQuery.prototype.</span>from (ddoc, name)](#apidoc.element.couchbase.ViewQuery.prototype.from)
1.  [function <span class="apidocSignatureSpan">couchbase.ViewQuery.prototype.</span>full_set (full_set)](#apidoc.element.couchbase.ViewQuery.prototype.full_set)
1.  [function <span class="apidocSignatureSpan">couchbase.ViewQuery.prototype.</span>group (group)](#apidoc.element.couchbase.ViewQuery.prototype.group)
1.  [function <span class="apidocSignatureSpan">couchbase.ViewQuery.prototype.</span>group_level (group_level)](#apidoc.element.couchbase.ViewQuery.prototype.group_level)
1.  [function <span class="apidocSignatureSpan">couchbase.ViewQuery.prototype.</span>id_range (start, end)](#apidoc.element.couchbase.ViewQuery.prototype.id_range)
1.  [function <span class="apidocSignatureSpan">couchbase.ViewQuery.prototype.</span>include_docs (include_docs)](#apidoc.element.couchbase.ViewQuery.prototype.include_docs)
1.  [function <span class="apidocSignatureSpan">couchbase.ViewQuery.prototype.</span>key (key)](#apidoc.element.couchbase.ViewQuery.prototype.key)
1.  [function <span class="apidocSignatureSpan">couchbase.ViewQuery.prototype.</span>keys (keys)](#apidoc.element.couchbase.ViewQuery.prototype.keys)
1.  [function <span class="apidocSignatureSpan">couchbase.ViewQuery.prototype.</span>limit (limit)](#apidoc.element.couchbase.ViewQuery.prototype.limit)
1.  [function <span class="apidocSignatureSpan">couchbase.ViewQuery.prototype.</span>on_error (mode)](#apidoc.element.couchbase.ViewQuery.prototype.on_error)
1.  [function <span class="apidocSignatureSpan">couchbase.ViewQuery.prototype.</span>order (order)](#apidoc.element.couchbase.ViewQuery.prototype.order)
1.  [function <span class="apidocSignatureSpan">couchbase.ViewQuery.prototype.</span>range (start, end, inclusive_end)](#apidoc.element.couchbase.ViewQuery.prototype.range)
1.  [function <span class="apidocSignatureSpan">couchbase.ViewQuery.prototype.</span>reduce (reduce)](#apidoc.element.couchbase.ViewQuery.prototype.reduce)
1.  [function <span class="apidocSignatureSpan">couchbase.ViewQuery.prototype.</span>skip (skip)](#apidoc.element.couchbase.ViewQuery.prototype.skip)
1.  [function <span class="apidocSignatureSpan">couchbase.ViewQuery.prototype.</span>stale (stale)](#apidoc.element.couchbase.ViewQuery.prototype.stale)

#### [module couchbase.auth](#apidoc.module.couchbase.auth)
1.  [function <span class="apidocSignatureSpan">couchbase.auth.</span>ClassicAuthenticator (buckets, username, password)](#apidoc.element.couchbase.auth.ClassicAuthenticator)

#### [module couchbase.binding](#apidoc.module.couchbase.binding)
1.  [function <span class="apidocSignatureSpan">couchbase.binding.</span>CouchbaseImpl ()](#apidoc.element.couchbase.binding.CouchbaseImpl)
1.  [function <span class="apidocSignatureSpan">couchbase.binding.</span>Error (message)](#apidoc.element.couchbase.binding.Error)
1.  [function <span class="apidocSignatureSpan">couchbase.binding.</span>_setErrorClass ()](#apidoc.element.couchbase.binding._setErrorClass)
1.  object <span class="apidocSignatureSpan">couchbase.binding.</span>Constants
1.  string <span class="apidocSignatureSpan">couchbase.binding.</span>path

#### [module couchbase.bucketmgr](#apidoc.module.couchbase.bucketmgr)
1.  [function <span class="apidocSignatureSpan">couchbase.</span>bucketmgr (bucket)](#apidoc.element.couchbase.bucketmgr.bucketmgr)

#### [module couchbase.bucketmgr.prototype](#apidoc.module.couchbase.bucketmgr.prototype)
1.  [function <span class="apidocSignatureSpan">couchbase.bucketmgr.prototype.</span>_capiRequest (path, method, callback)](#apidoc.element.couchbase.bucketmgr.prototype._capiRequest)
1.  [function <span class="apidocSignatureSpan">couchbase.bucketmgr.prototype.</span>_checkIndexesActive (checkList, callback)](#apidoc.element.couchbase.bucketmgr.prototype._checkIndexesActive)
1.  [function <span class="apidocSignatureSpan">couchbase.bucketmgr.prototype.</span>_createIndex (options, callback)](#apidoc.element.couchbase.bucketmgr.prototype._createIndex)
1.  [function <span class="apidocSignatureSpan">couchbase.bucketmgr.prototype.</span>_dropIndex (options, callback)](#apidoc.element.couchbase.bucketmgr.prototype._dropIndex)
1.  [function <span class="apidocSignatureSpan">couchbase.bucketmgr.prototype.</span>_mgmtRequest (path, method, callback)](#apidoc.element.couchbase.bucketmgr.prototype._mgmtRequest)
1.  [function <span class="apidocSignatureSpan">couchbase.bucketmgr.prototype.</span>buildDeferredIndexes (callback)](#apidoc.element.couchbase.bucketmgr.prototype.buildDeferredIndexes)
1.  [function <span class="apidocSignatureSpan">couchbase.bucketmgr.prototype.</span>createIndex (indexName, fields, options, callback)](#apidoc.element.couchbase.bucketmgr.prototype.createIndex)
1.  [function <span class="apidocSignatureSpan">couchbase.bucketmgr.prototype.</span>createPrimaryIndex (options, callback)](#apidoc.element.couchbase.bucketmgr.prototype.createPrimaryIndex)
1.  [function <span class="apidocSignatureSpan">couchbase.bucketmgr.prototype.</span>dropIndex (indexName, options, callback)](#apidoc.element.couchbase.bucketmgr.prototype.dropIndex)
1.  [function <span class="apidocSignatureSpan">couchbase.bucketmgr.prototype.</span>dropPrimaryIndex (options, callback)](#apidoc.element.couchbase.bucketmgr.prototype.dropPrimaryIndex)
1.  [function <span class="apidocSignatureSpan">couchbase.bucketmgr.prototype.</span>flush (callback)](#apidoc.element.couchbase.bucketmgr.prototype.flush)
1.  [function <span class="apidocSignatureSpan">couchbase.bucketmgr.prototype.</span>getDesignDocument (name, callback)](#apidoc.element.couchbase.bucketmgr.prototype.getDesignDocument)
1.  [function <span class="apidocSignatureSpan">couchbase.bucketmgr.prototype.</span>getDesignDocuments (callback)](#apidoc.element.couchbase.bucketmgr.prototype.getDesignDocuments)
1.  [function <span class="apidocSignatureSpan">couchbase.bucketmgr.prototype.</span>getIndexes (callback)](#apidoc.element.couchbase.bucketmgr.prototype.getIndexes)
1.  [function <span class="apidocSignatureSpan">couchbase.bucketmgr.prototype.</span>insertDesignDocument (name, data, callback)](#apidoc.element.couchbase.bucketmgr.prototype.insertDesignDocument)
1.  [function <span class="apidocSignatureSpan">couchbase.bucketmgr.prototype.</span>removeDesignDocument (name, callback)](#apidoc.element.couchbase.bucketmgr.prototype.removeDesignDocument)
1.  [function <span class="apidocSignatureSpan">couchbase.bucketmgr.prototype.</span>upsertDesignDocument (name, data, callback)](#apidoc.element.couchbase.bucketmgr.prototype.upsertDesignDocument)
1.  [function <span class="apidocSignatureSpan">couchbase.bucketmgr.prototype.</span>watchIndexes (watchList, options, callback)](#apidoc.element.couchbase.bucketmgr.prototype.watchIndexes)

#### [module couchbase.clustermgr](#apidoc.module.couchbase.clustermgr)
1.  [function <span class="apidocSignatureSpan">couchbase.</span>clustermgr (cluster, username, password)](#apidoc.element.couchbase.clustermgr.clustermgr)

#### [module couchbase.clustermgr.prototype](#apidoc.module.couchbase.clustermgr.prototype)
1.  [function <span class="apidocSignatureSpan">couchbase.clustermgr.prototype.</span>_mgmtRequest (path, method, uses_qs)](#apidoc.element.couchbase.clustermgr.prototype._mgmtRequest)
1.  [function <span class="apidocSignatureSpan">couchbase.clustermgr.prototype.</span>createBucket (name, opts, callback)](#apidoc.element.couchbase.clustermgr.prototype.createBucket)
1.  [function <span class="apidocSignatureSpan">couchbase.clustermgr.prototype.</span>getUsers (callback)](#apidoc.element.couchbase.clustermgr.prototype.getUsers)
1.  [function <span class="apidocSignatureSpan">couchbase.clustermgr.prototype.</span>listBuckets (callback)](#apidoc.element.couchbase.clustermgr.prototype.listBuckets)
1.  [function <span class="apidocSignatureSpan">couchbase.clustermgr.prototype.</span>removeBucket (name, callback)](#apidoc.element.couchbase.clustermgr.prototype.removeBucket)
1.  [function <span class="apidocSignatureSpan">couchbase.clustermgr.prototype.</span>removeUser (userid, callback)](#apidoc.element.couchbase.clustermgr.prototype.removeUser)
1.  [function <span class="apidocSignatureSpan">couchbase.clustermgr.prototype.</span>upsertUser (userid, settings, callback)](#apidoc.element.couchbase.clustermgr.prototype.upsertUser)

#### [module couchbase.searchquery_queries](#apidoc.module.couchbase.searchquery_queries)
1.  [function <span class="apidocSignatureSpan">couchbase.searchquery_queries.</span>BooleanFieldQuery (val)](#apidoc.element.couchbase.searchquery_queries.BooleanFieldQuery)
1.  [function <span class="apidocSignatureSpan">couchbase.searchquery_queries.</span>BooleanQuery ()](#apidoc.element.couchbase.searchquery_queries.BooleanQuery)
1.  [function <span class="apidocSignatureSpan">couchbase.searchquery_queries.</span>ConjunctionQuery (queries)](#apidoc.element.couchbase.searchquery_queries.ConjunctionQuery)
1.  [function <span class="apidocSignatureSpan">couchbase.searchquery_queries.</span>DateRangeQuery ()](#apidoc.element.couchbase.searchquery_queries.DateRangeQuery)
1.  [function <span class="apidocSignatureSpan">couchbase.searchquery_queries.</span>DisjunctionQuery (queries)](#apidoc.element.couchbase.searchquery_queries.DisjunctionQuery)
1.  [function <span class="apidocSignatureSpan">couchbase.searchquery_queries.</span>DocIdQuery (ids)](#apidoc.element.couchbase.searchquery_queries.DocIdQuery)
1.  [function <span class="apidocSignatureSpan">couchbase.searchquery_queries.</span>MatchAllQuery ()](#apidoc.element.couchbase.searchquery_queries.MatchAllQuery)
1.  [function <span class="apidocSignatureSpan">couchbase.searchquery_queries.</span>MatchNoneQuery ()](#apidoc.element.couchbase.searchquery_queries.MatchNoneQuery)
1.  [function <span class="apidocSignatureSpan">couchbase.searchquery_queries.</span>MatchPhraseQuery (phrase)](#apidoc.element.couchbase.searchquery_queries.MatchPhraseQuery)
1.  [function <span class="apidocSignatureSpan">couchbase.searchquery_queries.</span>MatchQuery (match)](#apidoc.element.couchbase.searchquery_queries.MatchQuery)
1.  [function <span class="apidocSignatureSpan">couchbase.searchquery_queries.</span>NumericRangeQuery ()](#apidoc.element.couchbase.searchquery_queries.NumericRangeQuery)
1.  [function <span class="apidocSignatureSpan">couchbase.searchquery_queries.</span>PhraseQuery (terms)](#apidoc.element.couchbase.searchquery_queries.PhraseQuery)
1.  [function <span class="apidocSignatureSpan">couchbase.searchquery_queries.</span>PrefixQuery (prefix)](#apidoc.element.couchbase.searchquery_queries.PrefixQuery)
1.  [function <span class="apidocSignatureSpan">couchbase.searchquery_queries.</span>QueryStringQuery (query)](#apidoc.element.couchbase.searchquery_queries.QueryStringQuery)
1.  [function <span class="apidocSignatureSpan">couchbase.searchquery_queries.</span>RegexpQuery (regexp)](#apidoc.element.couchbase.searchquery_queries.RegexpQuery)
1.  [function <span class="apidocSignatureSpan">couchbase.searchquery_queries.</span>TermQuery (term)](#apidoc.element.couchbase.searchquery_queries.TermQuery)
1.  [function <span class="apidocSignatureSpan">couchbase.searchquery_queries.</span>WildcardQuery (wildcard)](#apidoc.element.couchbase.searchquery_queries.WildcardQuery)
1.  [function <span class="apidocSignatureSpan">couchbase.searchquery_queries.</span>boolean ()](#apidoc.element.couchbase.searchquery_queries.boolean)
1.  [function <span class="apidocSignatureSpan">couchbase.searchquery_queries.</span>booleanField (val)](#apidoc.element.couchbase.searchquery_queries.booleanField)
1.  [function <span class="apidocSignatureSpan">couchbase.searchquery_queries.</span>conjuncts (queries)](#apidoc.element.couchbase.searchquery_queries.conjuncts)
1.  [function <span class="apidocSignatureSpan">couchbase.searchquery_queries.</span>dateRange ()](#apidoc.element.couchbase.searchquery_queries.dateRange)
1.  [function <span class="apidocSignatureSpan">couchbase.searchquery_queries.</span>disjuncts (queries)](#apidoc.element.couchbase.searchquery_queries.disjuncts)
1.  [function <span class="apidocSignatureSpan">couchbase.searchquery_queries.</span>docIds (ids)](#apidoc.element.couchbase.searchquery_queries.docIds)
1.  [function <span class="apidocSignatureSpan">couchbase.searchquery_queries.</span>match (match)](#apidoc.element.couchbase.searchquery_queries.match)
1.  [function <span class="apidocSignatureSpan">couchbase.searchquery_queries.</span>matchAll ()](#apidoc.element.couchbase.searchquery_queries.matchAll)
1.  [function <span class="apidocSignatureSpan">couchbase.searchquery_queries.</span>matchNone ()](#apidoc.element.couchbase.searchquery_queries.matchNone)
1.  [function <span class="apidocSignatureSpan">couchbase.searchquery_queries.</span>matchPhrase (phrase)](#apidoc.element.couchbase.searchquery_queries.matchPhrase)
1.  [function <span class="apidocSignatureSpan">couchbase.searchquery_queries.</span>numericRange ()](#apidoc.element.couchbase.searchquery_queries.numericRange)
1.  [function <span class="apidocSignatureSpan">couchbase.searchquery_queries.</span>phrase (terms)](#apidoc.element.couchbase.searchquery_queries.phrase)
1.  [function <span class="apidocSignatureSpan">couchbase.searchquery_queries.</span>prefix (prefix)](#apidoc.element.couchbase.searchquery_queries.prefix)
1.  [function <span class="apidocSignatureSpan">couchbase.searchquery_queries.</span>queryString (query)](#apidoc.element.couchbase.searchquery_queries.queryString)
1.  [function <span class="apidocSignatureSpan">couchbase.searchquery_queries.</span>regexp (regexp)](#apidoc.element.couchbase.searchquery_queries.regexp)
1.  [function <span class="apidocSignatureSpan">couchbase.searchquery_queries.</span>term (term)](#apidoc.element.couchbase.searchquery_queries.term)
1.  [function <span class="apidocSignatureSpan">couchbase.searchquery_queries.</span>wildcard (wildcard)](#apidoc.element.couchbase.searchquery_queries.wildcard)

#### [module couchbase.utils](#apidoc.module.couchbase.utils)
1.  [function <span class="apidocSignatureSpan">couchbase.utils.</span>unpackArgs (first, args, first_index)](#apidoc.element.couchbase.utils.unpackArgs)



# <a name="apidoc.module.couchbase"></a>[module couchbase](#apidoc.module.couchbase)

#### <a name="apidoc.element.couchbase.BucketImpl"></a>[function <span class="apidocSignatureSpan">couchbase.</span>BucketImpl (options)](#apidoc.element.couchbase.BucketImpl)
- description and source-code
```javascript
function Bucket(options) {
  // We normalize both for consistency as well as to
  //  create a duplicate object to use
  options.dsnObj = connStr.normalize(options.dsnObj);

  var bucketDsn = connStr.stringify(options.dsnObj);
  var bucketUser = options.username;
  var bucketPass = options.password;

  this._name = options.dsnObj.bucket;
  this._username = options.username;
  this._password = options.password;

  this._cb = new CBpp(bucketDsn, bucketUser, bucketPass);

  this.connected = null;
  this._cb.setConnectCallback(function(err) {
    if (err) {
      this.connected = false;
      return this.emit('error', err);
    }
    this.connected = true;
    this.emit('connect');
  }.bind(this));

  this.waitQueue = [];
  this.on('connect', function() {
    for (var i = 0; i < this.waitQueue.length; ++i) {
      var itm = this.waitQueue[i];
      this._invoke(itm[0], itm[1]);
    }
    this.waitQueue = [];
  });
  this.on('error', function(err) {
    for (var i = 0; i < this.waitQueue.length; ++i) {
      var itm = this.waitQueue[i];
      itm[1][itm[1].length-1](err, null);
    }
    this.waitQueue = [];
  });

  this.httpAgent = new http.Agent();
  this.httpAgent.maxSockets = 250;

<span class="apidocCodeCommentSpan">  /* istanbul ignore else  */
</span>  if (options.dsnObj.hosts.length !== 1 ||
      options.dsnObj.hosts[0][1] ||
      (options.dsnObj.scheme !== 'couchbase' &&
        options.dsnObj.scheme !== 'couchbases')) {
    // We perform the connect on the next tick to ensure
    //   consistent behaviour between SRV and non-SRV.
    process.nextTick(function() {
      this._cb.connect();
    }.bind(this));
  } else {
    var srvHost = options.dsnObj.hosts[0][0];
    var srvPrefix = '_' + options.dsnObj.scheme;

    dns.resolveSrv(srvPrefix + '.' + srvHost, function(err, addrs) {
      if (!err) {
        options.dsnObj.hosts = [];
        for (var i = 0; i < addrs.length; ++i) {
          options.dsnObj.hosts.push([addrs[i].name, addrs[i].port]);
        }
        var srvDsn = connStr.stringify(options.dsnObj);
        this._cb.control(CONST.CNTL_REINIT_DSN, CONST.CNTL_SET, srvDsn);
      }

      this._cb.connect();
    }.bind(this));
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.BucketImpl.FtsQueryResponse"></a>[function <span class="apidocSignatureSpan">couchbase.</span>BucketImpl.FtsQueryResponse ()](#apidoc.element.couchbase.BucketImpl.FtsQueryResponse)
- description and source-code
```javascript
function FtsQueryResponse() {
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.BucketImpl.N1qlQueryResponse"></a>[function <span class="apidocSignatureSpan">couchbase.</span>BucketImpl.N1qlQueryResponse ()](#apidoc.element.couchbase.BucketImpl.N1qlQueryResponse)
- description and source-code
```javascript
function N1qlQueryResponse() {
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.CbasQuery"></a>[function <span class="apidocSignatureSpan">couchbase.</span>CbasQuery ()](#apidoc.element.couchbase.CbasQuery)
- description and source-code
```javascript
function CbasQuery() {
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.CbasQuery.Direct"></a>[function <span class="apidocSignatureSpan">couchbase.</span>CbasQuery.Direct (str)](#apidoc.element.couchbase.CbasQuery.Direct)
- description and source-code
```javascript
function CbasStringQuery(str) {
  this.options = {
    statement: str
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.ClassicAuthenticator"></a>[function <span class="apidocSignatureSpan">couchbase.</span>ClassicAuthenticator (buckets, username, password)](#apidoc.element.couchbase.ClassicAuthenticator)
- description and source-code
```javascript
function ClassicAuthenticator(buckets, username, password) {
  this.buckets = buckets;
  this.username = username;
  this.password = password;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.Cluster"></a>[function <span class="apidocSignatureSpan">couchbase.</span>Cluster (cnstr, options)](#apidoc.element.couchbase.Cluster)
- description and source-code
```javascript
function Cluster(cnstr, options) {
  this.dsnObj = connstr.parse(cnstr);
  this.auther = null;
  this.connectingBuckets = [];
  this.connectedBuckets = [];
  this.waitQueue = [];

  this.cbasHosts = null;

  // Copy passed options into the connection string
  if (options instanceof Object) {
    for (var i in options) {
      if (options.hasOwnProperty(i)) {
        this.dsnObj.options[i] = encodeURIComponent(options[i]);
      }
    }
  }
}
```
- example usage
```shell
...
until the connection is successfully established.

Here is a simple example of instantiating a connection, adding a new document
into the bucket and then retrieving its contents:

'''javascript
var couchbase = require('couchbase');
var cluster = new couchbase.Cluster('couchbase://127.0.0.1');
var bucket = cluster.openBucket('default');

bucket.upsert('testdoc', {name:'Frank'}, function(err, result) {
if (err) throw err;

bucket.get('testdoc', function(err, result) {
  if (err) throw err;
...
```

#### <a name="apidoc.element.couchbase.Cluster.CbasQueryResponse"></a>[function <span class="apidocSignatureSpan">couchbase.</span>Cluster.CbasQueryResponse ()](#apidoc.element.couchbase.Cluster.CbasQueryResponse)
- description and source-code
```javascript
function CbasQueryResponse() {
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.Error"></a>[function <span class="apidocSignatureSpan">couchbase.</span>Error (message)](#apidoc.element.couchbase.Error)
- description and source-code
```javascript
function CouchbaseError(message) {
  Error.call(this);
  Error.captureStackTrace(this, CouchbaseError);
  this.message = message;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.Error.super_"></a>[function <span class="apidocSignatureSpan">couchbase.</span>Error.super_ ()](#apidoc.element.couchbase.Error.super_)
- description and source-code
```javascript
function Error() { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.Mock.Cluster"></a>[function <span class="apidocSignatureSpan">couchbase.</span>Mock.Cluster (cnstr)](#apidoc.element.couchbase.Mock.Cluster)
- description and source-code
```javascript
function MockCluster(cnstr) {
  this.dsnObj = connstr.parse(cnstr);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.MutationState"></a>[function <span class="apidocSignatureSpan">couchbase.</span>MutationState ()](#apidoc.element.couchbase.MutationState)
- description and source-code
```javascript
function MutationState() {
  this._data = {};
  for (var i = 0; i < arguments.length; ++i) {
    this._addSingle(arguments[i]);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.N1qlQuery"></a>[function <span class="apidocSignatureSpan">couchbase.</span>N1qlQuery ()](#apidoc.element.couchbase.N1qlQuery)
- description and source-code
```javascript
function N1qlQuery() {
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.N1qlQuery.Direct"></a>[function <span class="apidocSignatureSpan">couchbase.</span>N1qlQuery.Direct (str)](#apidoc.element.couchbase.N1qlQuery.Direct)
- description and source-code
```javascript
function N1qlStringQuery(str) {
  this.options = {
    statement: str
  };
  this.isAdhoc = true;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.SearchFacet.DateFacet"></a>[function <span class="apidocSignatureSpan">couchbase.</span>SearchFacet.DateFacet (field, size)](#apidoc.element.couchbase.SearchFacet.DateFacet)
- description and source-code
```javascript
function DateFacet(field, size) {
  this.field = field;
  this.size = size;
  this.date_ranges = [];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.SearchFacet.NumericFacet"></a>[function <span class="apidocSignatureSpan">couchbase.</span>SearchFacet.NumericFacet (field, size)](#apidoc.element.couchbase.SearchFacet.NumericFacet)
- description and source-code
```javascript
function NumericFacet(field, size) {
  this.field = field;
  this.size = size;
  this.numeric_ranges = [];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.SearchQuery"></a>[function <span class="apidocSignatureSpan">couchbase.</span>SearchQuery (indexName, query)](#apidoc.element.couchbase.SearchQuery)
- description and source-code
```javascript
function SearchQuery(indexName, query) {
  this.data = {
    indexName: indexName,
    query: query
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.SearchQuery.BooleanQuery"></a>[function <span class="apidocSignatureSpan">couchbase.</span>SearchQuery.BooleanQuery ()](#apidoc.element.couchbase.SearchQuery.BooleanQuery)
- description and source-code
```javascript
function BooleanQuery() {
  this.data = {};
  this.shouldMin = undefined;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.SearchQuery.ConjunctionQuery"></a>[function <span class="apidocSignatureSpan">couchbase.</span>SearchQuery.ConjunctionQuery (queries)](#apidoc.element.couchbase.SearchQuery.ConjunctionQuery)
- description and source-code
```javascript
function ConjunctionQuery(queries) {
  queries = cbutils.unpackArgs(queries, arguments);
  this.data = {
    conjuncts: []
  };
  this.and(queries);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.SearchQuery.DateRangeQuery"></a>[function <span class="apidocSignatureSpan">couchbase.</span>SearchQuery.DateRangeQuery ()](#apidoc.element.couchbase.SearchQuery.DateRangeQuery)
- description and source-code
```javascript
function DateRangeQuery() {
  this.data = {};
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.SearchQuery.DisjunctionQuery"></a>[function <span class="apidocSignatureSpan">couchbase.</span>SearchQuery.DisjunctionQuery (queries)](#apidoc.element.couchbase.SearchQuery.DisjunctionQuery)
- description and source-code
```javascript
function DisjunctionQuery(queries) {
  queries = cbutils.unpackArgs(queries);
  this.data = {
    disjuncts: []
  };
  this.or(queries);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.SearchQuery.DocIdQuery"></a>[function <span class="apidocSignatureSpan">couchbase.</span>SearchQuery.DocIdQuery (ids)](#apidoc.element.couchbase.SearchQuery.DocIdQuery)
- description and source-code
```javascript
function DocIdQuery(ids) {
  ids = cbutils.unpackArgs(ids, arguments);
  this.data = {
    ids: []
  };
  this.addDocIds(ids);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.SearchQuery.MatchAllQuery"></a>[function <span class="apidocSignatureSpan">couchbase.</span>SearchQuery.MatchAllQuery ()](#apidoc.element.couchbase.SearchQuery.MatchAllQuery)
- description and source-code
```javascript
function MatchAllQuery() {
  this.data = {
    match_all: null
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.SearchQuery.MatchNoneQuery"></a>[function <span class="apidocSignatureSpan">couchbase.</span>SearchQuery.MatchNoneQuery ()](#apidoc.element.couchbase.SearchQuery.MatchNoneQuery)
- description and source-code
```javascript
function MatchNoneQuery() {
  this.data = {
    match_none: null
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.SearchQuery.MatchPhraseQuery"></a>[function <span class="apidocSignatureSpan">couchbase.</span>SearchQuery.MatchPhraseQuery (phrase)](#apidoc.element.couchbase.SearchQuery.MatchPhraseQuery)
- description and source-code
```javascript
function MatchPhraseQuery(phrase) {
  this.data = {
    match_phrase: phrase
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.SearchQuery.MatchQuery"></a>[function <span class="apidocSignatureSpan">couchbase.</span>SearchQuery.MatchQuery (match)](#apidoc.element.couchbase.SearchQuery.MatchQuery)
- description and source-code
```javascript
function MatchQuery(match) {
  this.data = {
    match: match
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.SearchQuery.NumericRangeQuery"></a>[function <span class="apidocSignatureSpan">couchbase.</span>SearchQuery.NumericRangeQuery ()](#apidoc.element.couchbase.SearchQuery.NumericRangeQuery)
- description and source-code
```javascript
function NumericRangeQuery() {
  this.data = {};
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.SearchQuery.PhraseQuery"></a>[function <span class="apidocSignatureSpan">couchbase.</span>SearchQuery.PhraseQuery (terms)](#apidoc.element.couchbase.SearchQuery.PhraseQuery)
- description and source-code
```javascript
function PhraseQuery(terms) {
  this.data = {
    terms: terms
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.SearchQuery.PrefixQuery"></a>[function <span class="apidocSignatureSpan">couchbase.</span>SearchQuery.PrefixQuery (prefix)](#apidoc.element.couchbase.SearchQuery.PrefixQuery)
- description and source-code
```javascript
function PrefixQuery(prefix) {
  this.data = {
    prefix: prefix
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.SearchQuery.QueryStringQuery"></a>[function <span class="apidocSignatureSpan">couchbase.</span>SearchQuery.QueryStringQuery (query)](#apidoc.element.couchbase.SearchQuery.QueryStringQuery)
- description and source-code
```javascript
function QueryStringQuery(query) {
  this.data = {
    query: query
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.SearchQuery.RegexpQuery"></a>[function <span class="apidocSignatureSpan">couchbase.</span>SearchQuery.RegexpQuery (regexp)](#apidoc.element.couchbase.SearchQuery.RegexpQuery)
- description and source-code
```javascript
function RegexpQuery(regexp) {
  this.data = {
    regexp: regexp
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.SearchQuery.TermQuery"></a>[function <span class="apidocSignatureSpan">couchbase.</span>SearchQuery.TermQuery (term)](#apidoc.element.couchbase.SearchQuery.TermQuery)
- description and source-code
```javascript
function TermQuery(term) {
  this.data = {
    term: term
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.SearchQuery.WildcardQuery"></a>[function <span class="apidocSignatureSpan">couchbase.</span>SearchQuery.WildcardQuery (wildcard)](#apidoc.element.couchbase.SearchQuery.WildcardQuery)
- description and source-code
```javascript
function WildcardQuery(wildcard) {
  this.data = {
    wildcard: wildcard
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.SpatialQuery"></a>[function <span class="apidocSignatureSpan">couchbase.</span>SpatialQuery ()](#apidoc.element.couchbase.SpatialQuery)
- description and source-code
```javascript
function SpatialQuery() {
  this.ddoc = null;
  this.name = null;
  this.options = {};
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.ViewQuery"></a>[function <span class="apidocSignatureSpan">couchbase.</span>ViewQuery ()](#apidoc.element.couchbase.ViewQuery)
- description and source-code
```javascript
function ViewQuery() {
  this.ddoc = null;
  this.name = null;
  this.options = {};
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.bucketmgr"></a>[function <span class="apidocSignatureSpan">couchbase.</span>bucketmgr (bucket)](#apidoc.element.couchbase.bucketmgr)
- description and source-code
```javascript
function BucketManager(bucket) {
  this._bucket = bucket;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.clustermgr"></a>[function <span class="apidocSignatureSpan">couchbase.</span>clustermgr (cluster, username, password)](#apidoc.element.couchbase.clustermgr)
- description and source-code
```javascript
function ClusterManager(cluster, username, password) {
  this._cluster = cluster;
  this._username = username;
  this._password = password;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.couchbase.BucketImpl"></a>[module couchbase.BucketImpl](#apidoc.module.couchbase.BucketImpl)

#### <a name="apidoc.element.couchbase.BucketImpl.BucketImpl"></a>[function <span class="apidocSignatureSpan">couchbase.</span>BucketImpl (options)](#apidoc.element.couchbase.BucketImpl.BucketImpl)
- description and source-code
```javascript
function Bucket(options) {
  // We normalize both for consistency as well as to
  //  create a duplicate object to use
  options.dsnObj = connStr.normalize(options.dsnObj);

  var bucketDsn = connStr.stringify(options.dsnObj);
  var bucketUser = options.username;
  var bucketPass = options.password;

  this._name = options.dsnObj.bucket;
  this._username = options.username;
  this._password = options.password;

  this._cb = new CBpp(bucketDsn, bucketUser, bucketPass);

  this.connected = null;
  this._cb.setConnectCallback(function(err) {
    if (err) {
      this.connected = false;
      return this.emit('error', err);
    }
    this.connected = true;
    this.emit('connect');
  }.bind(this));

  this.waitQueue = [];
  this.on('connect', function() {
    for (var i = 0; i < this.waitQueue.length; ++i) {
      var itm = this.waitQueue[i];
      this._invoke(itm[0], itm[1]);
    }
    this.waitQueue = [];
  });
  this.on('error', function(err) {
    for (var i = 0; i < this.waitQueue.length; ++i) {
      var itm = this.waitQueue[i];
      itm[1][itm[1].length-1](err, null);
    }
    this.waitQueue = [];
  });

  this.httpAgent = new http.Agent();
  this.httpAgent.maxSockets = 250;

<span class="apidocCodeCommentSpan">  /* istanbul ignore else  */
</span>  if (options.dsnObj.hosts.length !== 1 ||
      options.dsnObj.hosts[0][1] ||
      (options.dsnObj.scheme !== 'couchbase' &&
        options.dsnObj.scheme !== 'couchbases')) {
    // We perform the connect on the next tick to ensure
    //   consistent behaviour between SRV and non-SRV.
    process.nextTick(function() {
      this._cb.connect();
    }.bind(this));
  } else {
    var srvHost = options.dsnObj.hosts[0][0];
    var srvPrefix = '_' + options.dsnObj.scheme;

    dns.resolveSrv(srvPrefix + '.' + srvHost, function(err, addrs) {
      if (!err) {
        options.dsnObj.hosts = [];
        for (var i = 0; i < addrs.length; ++i) {
          options.dsnObj.hosts.push([addrs[i].name, addrs[i].port]);
        }
        var srvDsn = connStr.stringify(options.dsnObj);
        this._cb.control(CONST.CNTL_REINIT_DSN, CONST.CNTL_SET, srvDsn);
      }

      this._cb.connect();
    }.bind(this));
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.BucketImpl.FtsQueryResponse"></a>[function <span class="apidocSignatureSpan">couchbase.BucketImpl.</span>FtsQueryResponse ()](#apidoc.element.couchbase.BucketImpl.FtsQueryResponse)
- description and source-code
```javascript
function FtsQueryResponse() {
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.BucketImpl.N1qlQueryResponse"></a>[function <span class="apidocSignatureSpan">couchbase.BucketImpl.</span>N1qlQueryResponse ()](#apidoc.element.couchbase.BucketImpl.N1qlQueryResponse)
- description and source-code
```javascript
function N1qlQueryResponse() {
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.BucketImpl.super_"></a>[function <span class="apidocSignatureSpan">couchbase.BucketImpl.</span>super_ ()](#apidoc.element.couchbase.BucketImpl.super_)
- description and source-code
```javascript
function EventEmitter() {
  EventEmitter.init.call(this);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.couchbase.BucketImpl.FtsQueryResponse"></a>[module couchbase.BucketImpl.FtsQueryResponse](#apidoc.module.couchbase.BucketImpl.FtsQueryResponse)

#### <a name="apidoc.element.couchbase.BucketImpl.FtsQueryResponse.FtsQueryResponse"></a>[function <span class="apidocSignatureSpan">couchbase.BucketImpl.</span>FtsQueryResponse ()](#apidoc.element.couchbase.BucketImpl.FtsQueryResponse.FtsQueryResponse)
- description and source-code
```javascript
function FtsQueryResponse() {
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.BucketImpl.FtsQueryResponse.super_"></a>[function <span class="apidocSignatureSpan">couchbase.BucketImpl.FtsQueryResponse.</span>super_ ()](#apidoc.element.couchbase.BucketImpl.FtsQueryResponse.super_)
- description and source-code
```javascript
function EventEmitter() {
  EventEmitter.init.call(this);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.couchbase.BucketImpl.N1qlQueryResponse"></a>[module couchbase.BucketImpl.N1qlQueryResponse](#apidoc.module.couchbase.BucketImpl.N1qlQueryResponse)

#### <a name="apidoc.element.couchbase.BucketImpl.N1qlQueryResponse.N1qlQueryResponse"></a>[function <span class="apidocSignatureSpan">couchbase.BucketImpl.</span>N1qlQueryResponse ()](#apidoc.element.couchbase.BucketImpl.N1qlQueryResponse.N1qlQueryResponse)
- description and source-code
```javascript
function N1qlQueryResponse() {
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.BucketImpl.N1qlQueryResponse.super_"></a>[function <span class="apidocSignatureSpan">couchbase.BucketImpl.N1qlQueryResponse.</span>super_ ()](#apidoc.element.couchbase.BucketImpl.N1qlQueryResponse.super_)
- description and source-code
```javascript
function EventEmitter() {
  EventEmitter.init.call(this);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.couchbase.BucketImpl.prototype"></a>[module couchbase.BucketImpl.prototype](#apidoc.module.couchbase.BucketImpl.prototype)

#### <a name="apidoc.element.couchbase.BucketImpl.prototype._capiRequest"></a>[function <span class="apidocSignatureSpan">couchbase.BucketImpl.prototype.</span>_capiRequest (path, method, callback)](#apidoc.element.couchbase.BucketImpl.prototype._capiRequest)
- description and source-code
```javascript
_capiRequest = function (path, method, callback) {
  var nodeUri = this._execAndUriParse(this._cb.getViewNode);
  var reqOpts = {
    agent: this.httpAgent,
    hostname: nodeUri.hostname,
    port: nodeUri.port,
    path: '/' + this._name + '/' + path,
    method: method,
    headers: { 'Content-Type': 'application/json' }
  };
  if (this._password) {
    reqOpts.auth = this._username + ':' + this._password;
  }
  callback(null, http.request(reqOpts));
}
```
- example usage
```shell
...
 *
 * @since 2.0.0
 * @committed
 */
BucketManager.prototype.upsertDesignDocument = function(name, data, callback) {
  var path = '_design/' + name;

  this._capiRequest(path, 'PUT', function(err, httpReq) {
if (err) {
  return callback(err, null);
}

httpReq.on('response', _respRead(function(err, resp, data) {
  if (err) {
    return callback(err);
...
```

#### <a name="apidoc.element.couchbase.BucketImpl.prototype._checkCasOption"></a>[function <span class="apidocSignatureSpan">couchbase.BucketImpl.prototype.</span>_checkCasOption (options)](#apidoc.element.couchbase.BucketImpl.prototype._checkCasOption)
- description and source-code
```javascript
_checkCasOption = function (options) {
  if (options.cas !== undefined) {
    if (typeof options.cas !== 'object' && typeof options.cas !== 'string') {
      throw new TypeError('cas option needs to be a CAS object or string.');
    }
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.BucketImpl.prototype._checkDuraOptions"></a>[function <span class="apidocSignatureSpan">couchbase.BucketImpl.prototype.</span>_checkDuraOptions (options)](#apidoc.element.couchbase.BucketImpl.prototype._checkDuraOptions)
- description and source-code
```javascript
_checkDuraOptions = function (options) {
  if (options.persist_to !== undefined) {
    if (typeof options.persist_to !== 'number' ||
      options.persist_to < 0 || options.persist_to > 8) {
      throw new TypeError(
        'persist_to option needs to be an integer between 0 and 8.');
    }
  }
  if (options.replicate_to !== undefined) {
    if (typeof options.replicate_to !== 'number' ||
      options.replicate_to < 0 || options.replicate_to > 8) {
      throw new TypeError(
        'replicate_to option needs to be an integer between 0 and 8.');
    }
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.BucketImpl.prototype._checkExpiryOption"></a>[function <span class="apidocSignatureSpan">couchbase.BucketImpl.prototype.</span>_checkExpiryOption (options)](#apidoc.element.couchbase.BucketImpl.prototype._checkExpiryOption)
- description and source-code
```javascript
_checkExpiryOption = function (options) {
  if (options.expiry !== undefined) {
    if (typeof options.expiry !== 'number') {
      throw new TypeError('expiry option needs to be a number.');
    }
    if (options.expiry < 0 || options.expiry > 2147483647) {
      throw new TypeError('expiry option needs to between 0 and 2147483647.');
    }
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.BucketImpl.prototype._checkHashkeyOption"></a>[function <span class="apidocSignatureSpan">couchbase.BucketImpl.prototype.</span>_checkHashkeyOption (options)](#apidoc.element.couchbase.BucketImpl.prototype._checkHashkeyOption)
- description and source-code
```javascript
_checkHashkeyOption = function (options) {
  if (options.hashkey !== undefined) {
    if (!this._isValidKey(options.hashkey)) {
      throw new TypeError('hashkey option needs to be a string or buffer.');
    }
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.BucketImpl.prototype._ctl"></a>[function <span class="apidocSignatureSpan">couchbase.BucketImpl.prototype.</span>_ctl (cc, value)](#apidoc.element.couchbase.BucketImpl.prototype._ctl)
- description and source-code
```javascript
_ctl = function (cc, value) {
  if (value !== undefined) {
    return this._cb.control.call(this._cb, cc, CONST.CNTL_SET, value);
  } else {
    return this._cb.control.call(this._cb, cc, CONST.CNTL_GET);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.BucketImpl.prototype._execAndUriParse"></a>[function <span class="apidocSignatureSpan">couchbase.BucketImpl.prototype.</span>_execAndUriParse (fn)](#apidoc.element.couchbase.BucketImpl.prototype._execAndUriParse)
- description and source-code
```javascript
_execAndUriParse = function (fn) {
  var uri = fn.call(this._cb);
  if (uri.substr(0, 7) === 'http://' ||
      uri.substr(0, 8) === 'https://') {
    return url.parse(uri);
  } else {
    return url.parse('http://' + uri);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.BucketImpl.prototype._fts"></a>[function <span class="apidocSignatureSpan">couchbase.BucketImpl.prototype.</span>_fts (query, callback)](#apidoc.element.couchbase.BucketImpl.prototype._fts)
- description and source-code
```javascript
_fts = function (query, callback) {
  var req = new FtsQueryResponse();

  var invokeCb = callback;
  if (!invokeCb) {
    invokeCb = function(err) {
      req.emit('error', err);
    };
  }

  this._maybeInvoke(this._ftsReq.bind(this),
      [query, req, invokeCb]);

  if (callback) {
    req.on('rows', function(rows, meta) {
      callback(null, rows, meta);
    });
    req.on('error', function(err) {
      callback(err, null, null);
    });
  }

  return req;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.BucketImpl.prototype._ftsReq"></a>[function <span class="apidocSignatureSpan">couchbase.BucketImpl.prototype.</span>_ftsReq (q, emitter)](#apidoc.element.couchbase.BucketImpl.prototype._ftsReq)
- description and source-code
```javascript
_ftsReq = function (q, emitter) {
  var rows = [];
  this._cb.ftsQuery(
      q,
      function(errCode, val) {
        if (errCode === -1) { // Row
          var row = val;
          if (rows) {
            if (events.EventEmitter.listenerCount(emitter, 'rows') > 0) {
              rows.push(row);
            } else {
              rows = null;
            }
          }
          emitter.emit('row', row);
        } else if (errCode === 0) { // Success
          var meta = val;
          if (meta instanceof Object) {
            meta.totalHits = meta.total_hits;
            meta.maxScore = meta.max_score;
            delete meta.total_hits;
            delete meta.max_score;
          }
          if (rows) {
            emitter.emit('rows', rows, meta);
          }
          emitter.emit('end', meta);
        } else { // Error
          var err = new Error('An FTS error occured: ' + val);
          emitter.emit('error', err);
        }
      });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.BucketImpl.prototype._interceptEndure"></a>[function <span class="apidocSignatureSpan">couchbase.BucketImpl.prototype.</span>_interceptEndure (key, options, is_delete, callback)](#apidoc.element.couchbase.BucketImpl.prototype._interceptEndure)
- description and source-code
```javascript
_interceptEndure = function (key, options, is_delete, callback) {
  if (!options.persist_to && !options.replicate_to) {
    // leave early if we can
    return callback;
  }

  // Return our interceptor
  var _this = this;
  return function(err, res) {
    if (err) {
      callback(err, res);
      return;
    }

    _this._cb.durability.call(_this._cb, key, options.hashkey, res.cas,
        options.persist_to, options.replicate_to, is_delete,
        function(endure_err) {
      if(endure_err) {
        callback(_endureError(endure_err), res);
        return;
      }

      callback(err, res);
    });
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.BucketImpl.prototype._invoke"></a>[function <span class="apidocSignatureSpan">couchbase.BucketImpl.prototype.</span>_invoke (fn, args)](#apidoc.element.couchbase.BucketImpl.prototype._invoke)
- description and source-code
```javascript
_invoke = function (fn, args) {
  try {
    fn.apply(this._cb, args);
  } catch(e) {
    args[args.length-1](e, null);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.BucketImpl.prototype._isValidKey"></a>[function <span class="apidocSignatureSpan">couchbase.BucketImpl.prototype.</span>_isValidKey (key)](#apidoc.element.couchbase.BucketImpl.prototype._isValidKey)
- description and source-code
```javascript
_isValidKey = function (key) {
  return typeof key === 'string' || key instanceof Buffer;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.BucketImpl.prototype._isValidPath"></a>[function <span class="apidocSignatureSpan">couchbase.BucketImpl.prototype.</span>_isValidPath (path)](#apidoc.element.couchbase.BucketImpl.prototype._isValidPath)
- description and source-code
```javascript
_isValidPath = function (path) {
  return typeof path === 'string';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.BucketImpl.prototype._lookupIn"></a>[function <span class="apidocSignatureSpan">couchbase.BucketImpl.prototype.</span>_lookupIn (builder, callback)](#apidoc.element.couchbase.BucketImpl.prototype._lookupIn)
- description and source-code
```javascript
_lookupIn = function (builder, callback) {
  if (typeof callback !== 'function') {
    throw new TypeError('Execute argument needs to be a callback.');
  }

  var data = builder.data.concat([function(err, res) {
    callback(err, new DocumentFragment(res, builder.opPaths));
  }]);
  this._maybeInvoke(this._cb.lookupIn, data);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.BucketImpl.prototype._maybeInvoke"></a>[function <span class="apidocSignatureSpan">couchbase.BucketImpl.prototype.</span>_maybeInvoke (fn, args)](#apidoc.element.couchbase.BucketImpl.prototype._maybeInvoke)
- description and source-code
```javascript
_maybeInvoke = function (fn, args) {
  if (this.connected === true) {
    this._invoke(fn, args);
  } else if (this.connected === false) {
    throw new Error('cannot perform operations on a shutdown bucket');
  } else {
    this.waitQueue.push([fn, args]);
  }
}
```
- example usage
```shell
...
* @param callback
*
* @private
* @ignore
*/
BucketManager.prototype._mgmtRequest = function(path, method, callback) {
 var b = this._bucket;
 b._maybeInvoke(b._mgmtRequest.bind(b), [path, method, callback]);
};

/**
* Method for performing a http capi request using the underlying bucket.
*
* @param path
* @param method
...
```

#### <a name="apidoc.element.couchbase.BucketImpl.prototype._mgmtRequest"></a>[function <span class="apidocSignatureSpan">couchbase.BucketImpl.prototype.</span>_mgmtRequest (path, method, callback)](#apidoc.element.couchbase.BucketImpl.prototype._mgmtRequest)
- description and source-code
```javascript
_mgmtRequest = function (path, method, callback) {
  var nodeUri = this._execAndUriParse(this._cb.getMgmtNode);
  var reqOpts = {
    hostname: nodeUri.hostname,
    port: nodeUri.port,
    path: '/' + path,
    method: method,
    headers: { 'Content-Type': 'application/json' }
  };
  if (this._password) {
    reqOpts.auth = this._username + ':' + this._password;
  }
  callback(null, http.request(reqOpts));
}
```
- example usage
```shell
...
 *
 * @since 2.0.0
 * @committed
 */
BucketManager.prototype.getDesignDocuments = function(callback) {
  var path = 'pools/default/buckets/' + this._bucket._name + '/ddocs';

  this._mgmtRequest(path, 'GET', function(err, httpReq) {
if (err) {
  return callback(err, null);
}

httpReq.on('response', _respRead(function (err, resp, data) {
  if (err) {
    return callback(err);
...
```

#### <a name="apidoc.element.couchbase.BucketImpl.prototype._mutateIn"></a>[function <span class="apidocSignatureSpan">couchbase.BucketImpl.prototype.</span>_mutateIn (builder, callback)](#apidoc.element.couchbase.BucketImpl.prototype._mutateIn)
- description and source-code
```javascript
_mutateIn = function (builder, callback) {
  if (typeof callback !== 'function') {
    throw new TypeError('Execute argument needs to be a callback.');
  }

  var data = builder.data.concat([function(err, res) {
    callback(err, new DocumentFragment(res, builder.opPaths));
  }]);
  this._maybeInvoke(this._cb.mutateIn, data);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.BucketImpl.prototype._n1ql"></a>[function <span class="apidocSignatureSpan">couchbase.BucketImpl.prototype.</span>_n1ql (query, params, callback)](#apidoc.element.couchbase.BucketImpl.prototype._n1ql)
- description and source-code
```javascript
_n1ql = function (query, params, callback) {
  var host;
  if (this.queryhosts) {
    var qhosts = this.queryhosts;
    host = qhosts[Math.floor(Math.random() * qhosts.length)];
    if (host.indexOf(':') === -1) {
      host = host + ':8093';
    }
  }

  var req = new N1qlQueryResponse();

  var invokeCb = callback;
  if (!invokeCb) {
    invokeCb = function(err) {
      req.emit('error', err);
    };
  }

  this._maybeInvoke(this._n1qlReq.bind(this),
      [host, query.toObject(params), query.isAdhoc, req, invokeCb]);

  if (callback) {
    req.on('rows', function(rows, meta) {
      callback(null, rows, meta);
    });
    req.on('error', function(err) {
      callback(err, null, null);
    });
  }

  return req;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.BucketImpl.prototype._n1qlReq"></a>[function <span class="apidocSignatureSpan">couchbase.BucketImpl.prototype.</span>_n1qlReq (host, q, adhoc, emitter)](#apidoc.element.couchbase.BucketImpl.prototype._n1qlReq)
- description and source-code
```javascript
_n1qlReq = function (host, q, adhoc, emitter) {
  var rows = [];
  this._cb.n1qlQuery(
      host, q, adhoc,
  function(errCode, val) {
    if (errCode === -1) { // Row
      var row = val;
      if (rows) {
        if (events.EventEmitter.listenerCount(emitter, 'rows') > 0) {
          rows.push(row);
        } else {
          rows = null;
        }
      }
      emitter.emit('row', row);
    } else if (errCode === 0) { // Success
      var meta = val;
      if (rows) {
        emitter.emit('rows', rows, meta);
      }
      emitter.emit('end', meta);
    } else { // Error
      var errStr = val;
      var jsonError = null;
      try {
        jsonError = JSON.parse(errStr);
      } catch(e) { }
      var err;
      if (jsonError && jsonError.errors && jsonError.errors.length > 0) {
        var firstErr = jsonError.errors[0];
        err = new Error(firstErr.msg);
        err.requestID = jsonError.requestID;
        err.code = firstErr.code;
        err.otherErrors = [];

        for (var i = 1; i < jsonError.errors.length; ++i) {
          var nextErr = jsonError.errors[i];
          var otherErr = new Error(nextErr.msg);
          otherErr.code = nextErr.code;
          err.otherErrors.push(otherErr);
        }
      } else {
        err = new Error('An unknown N1QL error occured.' +
            ' This is usually related to an out-of-memory condition.');
      }

      emitter.emit('error', err);
    }
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.BucketImpl.prototype._store"></a>[function <span class="apidocSignatureSpan">couchbase.BucketImpl.prototype.</span>_store (key, value, options, callback, opType)](#apidoc.element.couchbase.BucketImpl.prototype._store)
- description and source-code
```javascript
_store = function (key, value, options, callback, opType) {
  if (options instanceof Function) {
    callback = arguments[2];
    options = {};
  }

  if (!this._isValidKey(key)) {
    throw new TypeError('First argument needs to be a string or buffer.');
  }
  if (value === undefined) {
    throw new TypeError('Second argument must not be undefined.');
  }
  if (typeof options !== 'object') {
    throw new TypeError('Third argument needs to be an object or callback.');
  }
  if (typeof callback !== 'function') {
    throw new TypeError('Fourth argument needs to be a callback.');
  }
  this._checkHashkeyOption(options);
  this._checkExpiryOption(options);
  this._checkCasOption(options);
  this._checkDuraOptions(options);

  this._maybeInvoke(this._cb.store,
    [key, options.hashkey, value, options.expiry, options.cas, opType,
      this._interceptEndure(key, options, 0, callback)]);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.BucketImpl.prototype._view"></a>[function <span class="apidocSignatureSpan">couchbase.BucketImpl.prototype.</span>_view (viewtype, ddoc, name, q, callback)](#apidoc.element.couchbase.BucketImpl.prototype._view)
- description and source-code
```javascript
_view = function (viewtype, ddoc, name, q, callback) {
  var path = '_design/' + ddoc + '/' + viewtype + '/' +
      name + '?' + qs.stringify(q);

  var req = new ViewQueryResponse();

  var invokeCb = callback;
  if (!invokeCb) {
    invokeCb = function(err) {
      req.emit('error', err);
    };
  }

  this._maybeInvoke(this._viewReq.bind(this),
      [viewtype, ddoc, name, q, req, invokeCb]);

  if (callback) {
    req.on('rows', function(rows, meta) {
      callback(null, rows, meta);
    });
    req.on('error', function(err) {
      callback(err, null, null);
    });
  }

  return req;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.BucketImpl.prototype._viewReq"></a>[function <span class="apidocSignatureSpan">couchbase.BucketImpl.prototype.</span>_viewReq (viewtype, ddoc, name, q, emitter)](#apidoc.element.couchbase.BucketImpl.prototype._viewReq)
- description and source-code
```javascript
_viewReq = function (viewtype, ddoc, name, q, emitter) {
  var isSpatial = false;
  if (viewtype === '_spatial') {
    isSpatial = true;
  }

  var includeDocs = false;
  var opts = {};
  for (var i in q) {
    if (q.hasOwnProperty(i)) {
      if (i === 'include_docs') {
        if (q[i] && q[i] === 'true') {
          includeDocs = true;
        } else {
          includeDocs = false;
        }
      } else {
        opts[i] = q[i];
      }
    }
  }

  var rows = [];
  this._cb.viewQuery(
      isSpatial,
      ddoc, name,
      qs.stringify(opts),
      includeDocs,
  function(errCode, val) {
    if (errCode === -1) {
      var row = val;
      if (rows) {
        if (events.EventEmitter.listenerCount(emitter, 'rows') > 0) {
          rows.push(row);
        } else {
          rows = null;
        }
      }
      emitter.emit('row', row);
    } else if (errCode === 0) {
      var meta = val;
      if (rows) {
        emitter.emit('rows', rows, meta);
      }
      emitter.emit('end', meta);
    } else {
      var errStr = val;
      var jsonError = JSON.parse(errStr);
      var errorMessage = 'unknown error : error parsing failed';
      if (jsonError) {
        errorMessage = jsonError.message;
        if (jsonError.error || jsonError.reason) {
          var subError = jsonError.error + ': ' + jsonError.reason;
          if (!errorMessage) {
            errorMessage = subError;
          } else {
            errorMessage += ' (' + subError + ')';
          }
        }
      }
      emitter.emit('error', new Error(errorMessage));
    }
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.BucketImpl.prototype.append"></a>[function <span class="apidocSignatureSpan">couchbase.BucketImpl.prototype.</span>append (key, fragment, options, callback)](#apidoc.element.couchbase.BucketImpl.prototype.append)
- description and source-code
```javascript
append = function (key, fragment, options, callback) {
  this._store(key, fragment, options, callback, CONST.APPEND);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.BucketImpl.prototype.counter"></a>[function <span class="apidocSignatureSpan">couchbase.BucketImpl.prototype.</span>counter (key, delta, options, callback)](#apidoc.element.couchbase.BucketImpl.prototype.counter)
- description and source-code
```javascript
counter = function (key, delta, options, callback) {
  if (options instanceof Function) {
    callback = arguments[2];
    options = {};
  }

  if (!this._isValidKey(key)) {
    throw new TypeError('First argument needs to be a string or buffer.');
  }
  if (typeof delta !== 'number' || delta === 0) {
    throw new TypeError('Second argument must be a non-zero integer.');
  }
  if (typeof options !== 'object') {
    throw new TypeError('Third argument needs to be an object or callback.');
  }
  if (typeof callback !== 'function') {
    throw new TypeError('Fourth argument needs to be a callback.');
  }
  if (options.initial) {
    if (typeof options.initial !== 'number' || options.initial < 0) {
      throw new TypeError('initial option must be 0 or a positive integer.');
    }
  }
  this._checkHashkeyOption(options);
  this._checkExpiryOption(options);
  this._checkDuraOptions(options);

  this._maybeInvoke(this._cb.arithmetic,
    [key, options.hashkey, options.expiry, delta, options.initial,
      this._interceptEndure(key, options, 0, callback)]);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.BucketImpl.prototype.disconnect"></a>[function <span class="apidocSignatureSpan">couchbase.BucketImpl.prototype.</span>disconnect ()](#apidoc.element.couchbase.BucketImpl.prototype.disconnect)
- description and source-code
```javascript
disconnect = function () {
  if (this.connected !== false) {
    this.connected = false;
    this._cb.shutdown();
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.BucketImpl.prototype.enableN1ql"></a>[function <span class="apidocSignatureSpan">couchbase.BucketImpl.prototype.</span>enableN1ql (hosts)](#apidoc.element.couchbase.BucketImpl.prototype.enableN1ql)
- description and source-code
```javascript
enableN1ql = function (hosts) {
  if (Array.isArray(hosts)) {
    this.queryhosts = hosts;
  } else {
    this.queryhosts = [hosts];
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.BucketImpl.prototype.get"></a>[function <span class="apidocSignatureSpan">couchbase.BucketImpl.prototype.</span>get (key, options, callback)](#apidoc.element.couchbase.BucketImpl.prototype.get)
- description and source-code
```javascript
get = function (key, options, callback) {
  if (options instanceof Function) {
    callback = arguments[1];
    options = {};
  }

  if (!this._isValidKey(key)) {
    throw new TypeError('First argument needs to be a string or buffer.');
  }
  if (typeof options !== 'object') {
    throw new TypeError('Second argument needs to be an object or callback.');
  }
  if (typeof callback !== 'function') {
    throw new TypeError('Third argument needs to be a callback.');
  }
  this._checkHashkeyOption(options);

  this._maybeInvoke(this._cb.get, [key, options.hashkey, 0, 0, callback]);
}
```
- example usage
```shell
...
var couchbase = require('couchbase');
var cluster = new couchbase.Cluster('couchbase://127.0.0.1');
var bucket = cluster.openBucket('default');

bucket.upsert('testdoc', {name:'Frank'}, function(err, result) {
  if (err) throw err;

  bucket.get('testdoc', function(err, result) {
    if (err) throw err;

    console.log(result.value);
    // {name: Frank}
  });
});
'''
...
```

#### <a name="apidoc.element.couchbase.BucketImpl.prototype.getAndLock"></a>[function <span class="apidocSignatureSpan">couchbase.BucketImpl.prototype.</span>getAndLock (key, options, callback)](#apidoc.element.couchbase.BucketImpl.prototype.getAndLock)
- description and source-code
```javascript
getAndLock = function (key, options, callback) {
  if (options instanceof Function) {
    callback = arguments[1];
    options = {};
  }

  if (!this._isValidKey(key)) {
    throw new TypeError('First argument needs to be a string or buffer.');
  }
  if (typeof options !== 'object') {
    throw new TypeError('Second argument needs to be an object or callback.');
  }
  if (typeof callback !== 'function') {
    throw new TypeError('Third argument needs to be a callback.');
  }
  if (options.lockTime !== undefined) {
    if (typeof options.lockTime !== 'number' || options.lockTime < 1) {
      throw new TypeError('lockTime option needs to be a positive integer.');
    }
  }
  this._checkHashkeyOption(options);

  this._maybeInvoke(this._cb.get,
    [key, options.hashkey, options.lockTime, 1, callback]);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.BucketImpl.prototype.getAndTouch"></a>[function <span class="apidocSignatureSpan">couchbase.BucketImpl.prototype.</span>getAndTouch (key, expiry, options, callback)](#apidoc.element.couchbase.BucketImpl.prototype.getAndTouch)
- description and source-code
```javascript
getAndTouch = function (key, expiry, options, callback) {
  if (options instanceof Function) {
    callback = arguments[2];
    options = {};
  }

  if (typeof key !== 'string' && !(key instanceof Buffer)) {
    throw new TypeError('First argument needs to be a string or buffer.');
  }
  if (typeof expiry !== 'number' || expiry < 0) {
    throw new TypeError('Second argument needs to be 0 or a positive integer.');
  }
  if (typeof options !== 'object') {
    throw new TypeError('Third argument needs to be an object or callback.');
  }
  if (typeof callback !== 'function') {
    throw new TypeError('Fourth argument needs to be a callback.');
  }
  this._checkHashkeyOption(options);
  this._checkDuraOptions(options);

  this._maybeInvoke(this._cb.get, [key, options.hashkey, expiry, 0, callback]);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.BucketImpl.prototype.getMulti"></a>[function <span class="apidocSignatureSpan">couchbase.BucketImpl.prototype.</span>getMulti (keys, options, callback)](#apidoc.element.couchbase.BucketImpl.prototype.getMulti)
- description and source-code
```javascript
getMulti = function (keys, options, callback) {
  if (options instanceof Function) {
    callback = arguments[1];
    options = {};
  }

  if (!Array.isArray(keys) || keys.length === 0) {
    throw new TypeError('First argument needs to be an array of length > 0.');
  }
  if (typeof options !== 'object') {
    throw new TypeError('Second argument needs to be an object or callback.');
  }
  if (typeof callback !== 'function') {
    throw new TypeError('Third argument needs to be a callback.');
  }

  if (!options.batch_size) {
    options.batch_size = keys.length;
  }

  var self = this;
  var outMap = {};
  var sentCount = 0;
  var resCount = 0;
  var errCount = 0;
  function getOne() {
    var key = keys[sentCount++];
    self.get(key, function(err, res) {
      resCount++;
      if (err) {
        errCount++;
        outMap[key] = { error: err };
      } else {
        outMap[key] = res;
      }
      if (sentCount < keys.length) {
        getOne();
        return;
      } else if (resCount === keys.length) {
        callback(errCount, outMap);
        return;
      }
    });
  }
  for (var i = 0; i < options.batch_size; ++i) {
    getOne();
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.BucketImpl.prototype.getReplica"></a>[function <span class="apidocSignatureSpan">couchbase.BucketImpl.prototype.</span>getReplica (key, options, callback)](#apidoc.element.couchbase.BucketImpl.prototype.getReplica)
- description and source-code
```javascript
getReplica = function (key, options, callback) {
  if (options instanceof Function) {
    callback = arguments[1];
    options = {};
  }
  if (typeof key !== 'string' && !(key instanceof Buffer)) {
    throw new TypeError('First argument needs to be a string or buffer.');
  }
  if (typeof options !== 'object') {
    throw new TypeError('Second argument needs to be an object or callback.');
  }
  if (typeof callback !== 'function') {
    throw new TypeError('Third argument needs to be a callback.');
  }
  if (options.hashkey !== undefined) {
    if (!this._isValidKey(options.hashkey)) {
      throw new TypeError('hashkey option needs to be a string or buffer.');
    }
  }
  this._checkHashkeyOption(options);

  this._maybeInvoke(this._cb.getReplica,
    [key, options.hashkey, options.index, callback]);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.BucketImpl.prototype.insert"></a>[function <span class="apidocSignatureSpan">couchbase.BucketImpl.prototype.</span>insert (key, value, options, callback)](#apidoc.element.couchbase.BucketImpl.prototype.insert)
- description and source-code
```javascript
insert = function (key, value, options, callback) {
  this._store(key, value, options, callback, CONST.ADD);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.BucketImpl.prototype.listAppend"></a>[function <span class="apidocSignatureSpan">couchbase.BucketImpl.prototype.</span>listAppend (key, value, options, callback)](#apidoc.element.couchbase.BucketImpl.prototype.listAppend)
- description and source-code
```javascript
listAppend = function (key, value, options, callback) {
  if (options instanceof Function) {
    callback = arguments[2];
    options = {};
  }

  var self = this;
  this.mutateIn(key, options).arrayAppend('', value, false)
      .execute(function(err, res) {
    if (err) {
      if (err.code === errors.keyNotFound && options.createList) {
        var data = [];
        data.push(value);

        self.insert(key, data, options, function(err, insertRes) {
          if (err) {
            if (err.code === errors.keyAlreadyExists) {
              self.listAppend(key, value, options, callback);
              return;
            }

            callback(err, null);
            return;
          }

          callback(null, insertRes);
        });
        return;
      }

      callback(err, null);
      return;
    }

    callback(null, res);
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.BucketImpl.prototype.listGet"></a>[function <span class="apidocSignatureSpan">couchbase.BucketImpl.prototype.</span>listGet (key, index, options, callback)](#apidoc.element.couchbase.BucketImpl.prototype.listGet)
- description and source-code
```javascript
listGet = function (key, index, options, callback) {
  if (options instanceof Function) {
    callback = arguments[2];
    options = {};
  }

  this.lookupIn(key, options).get('[' + index + ']')
      .execute(function(err, res) {
    if (err) {
      callback(err, null);
      return;
    }

    try {
      res.value = res.contentByIndex(0);
    } catch (e) {
      callback(e, null);
      return;
    }


    callback(null, res);
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.BucketImpl.prototype.listPrepend"></a>[function <span class="apidocSignatureSpan">couchbase.BucketImpl.prototype.</span>listPrepend (key, value, options, callback)](#apidoc.element.couchbase.BucketImpl.prototype.listPrepend)
- description and source-code
```javascript
listPrepend = function (key, value, options, callback) {
  if (options instanceof Function) {
    callback = arguments[2];
    options = {};
  }

  var self = this;
  this.mutateIn(key, options).arrayPrepend('', value, false)
      .execute(function(err, res) {
    if (err) {
      if (err.code === errors.keyNotFound && options.createList) {
        var data = [value];

        self.insert(key, data, options, function(err, insertRes) {
          if (err) {
            if (err.code === errors.keyAlreadyExists) {
              self.listPrepend(key, value, options, callback);
              return;
            }

            callback(err, null);
            return;
          }

          callback(null, insertRes);
        });
        return;
      }

      callback(err, null);
      return;
    }

    callback(null, res);
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.BucketImpl.prototype.listPush"></a>[function <span class="apidocSignatureSpan">couchbase.BucketImpl.prototype.</span>listPush (key, value, options, callback)](#apidoc.element.couchbase.BucketImpl.prototype.listPush)
- description and source-code
```javascript
listPush = function (key, value, options, callback) {
  if (options instanceof Function) {
    callback = arguments[2];
    options = {};
  }

  var self = this;
  this.mutateIn(key, options).arrayAppend('', value, false)
      .execute(function(err, res) {
    if (err) {
      if (err.code === errors.keyNotFound && options.createList) {
        var data = [];
        data.push(value);

        self.insert(key, data, options, function(err, insertRes) {
          if (err) {
            if (err.code === errors.keyAlreadyExists) {
              self.listAppend(key, value, options, callback);
              return;
            }

            callback(err, null);
            return;
          }

          callback(null, insertRes);
        });
        return;
      }

      callback(err, null);
      return;
    }

    callback(null, res);
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.BucketImpl.prototype.listRemove"></a>[function <span class="apidocSignatureSpan">couchbase.BucketImpl.prototype.</span>listRemove (key, index, options, callback)](#apidoc.element.couchbase.BucketImpl.prototype.listRemove)
- description and source-code
```javascript
listRemove = function (key, index, options, callback) {
  if (options instanceof Function) {
    callback = arguments[2];
    options = {};
  }

  this.mutateIn(key, options).remove('[' + index + ']')
      .execute(function(err, res) {
    if (err) {
      callback(err, null);
      return;
    }

    callback(null, res);
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.BucketImpl.prototype.listSet"></a>[function <span class="apidocSignatureSpan">couchbase.BucketImpl.prototype.</span>listSet (key, index, value, options, callback)](#apidoc.element.couchbase.BucketImpl.prototype.listSet)
- description and source-code
```javascript
listSet = function (key, index, value, options, callback) {
  if (options instanceof Function) {
    callback = arguments[3];
    options = {};
  }

  this.mutateIn(key, options).replace('[' + index + ']', value)
      .execute(function(err, res) {
    if (err) {
      callback(err, null);
      return;
    }

    callback(null, res);
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.BucketImpl.prototype.listShift"></a>[function <span class="apidocSignatureSpan">couchbase.BucketImpl.prototype.</span>listShift (key, value, options, callback)](#apidoc.element.couchbase.BucketImpl.prototype.listShift)
- description and source-code
```javascript
listShift = function (key, value, options, callback) {
  if (options instanceof Function) {
    callback = arguments[2];
    options = {};
  }

  var self = this;
  this.mutateIn(key, options).arrayPrepend('', value, false)
      .execute(function(err, res) {
    if (err) {
      if (err.code === errors.keyNotFound && options.createList) {
        var data = [value];

        self.insert(key, data, options, function(err, insertRes) {
          if (err) {
            if (err.code === errors.keyAlreadyExists) {
              self.listPrepend(key, value, options, callback);
              return;
            }

            callback(err, null);
            return;
          }

          callback(null, insertRes);
        });
        return;
      }

      callback(err, null);
      return;
    }

    callback(null, res);
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.BucketImpl.prototype.listSize"></a>[function <span class="apidocSignatureSpan">couchbase.BucketImpl.prototype.</span>listSize (key, options, callback)](#apidoc.element.couchbase.BucketImpl.prototype.listSize)
- description and source-code
```javascript
listSize = function (key, options, callback) {
  if (options instanceof Function) {
    callback = arguments[1];
    options = {};
  }

  this.get(key, options, function(err, res) {
    if (err) {
      callback(err, null);
      return;
    }

    res.value = res.value.length;
    callback(null, res);
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.BucketImpl.prototype.lookupIn"></a>[function <span class="apidocSignatureSpan">couchbase.BucketImpl.prototype.</span>lookupIn (key, options)](#apidoc.element.couchbase.BucketImpl.prototype.lookupIn)
- description and source-code
```javascript
lookupIn = function (key, options) {
  if (!options) {
    options = {};
  }

  if (!this._isValidKey(key)) {
    throw new TypeError('First argument needs to be a string or buffer.');
  }
  if (typeof options !== 'object') {
    throw new TypeError('Second argument needs to be an object if set.');
  }
  this._checkHashkeyOption(options);

  return new LookupInBuilder(this, [key, options.hashkey]);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.BucketImpl.prototype.manager"></a>[function <span class="apidocSignatureSpan">couchbase.BucketImpl.prototype.</span>manager ()](#apidoc.element.couchbase.BucketImpl.prototype.manager)
- description and source-code
```javascript
manager = function () {
  return new BucketManager(this);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.BucketImpl.prototype.mapAdd"></a>[function <span class="apidocSignatureSpan">couchbase.BucketImpl.prototype.</span>mapAdd (key, path, value, options, callback)](#apidoc.element.couchbase.BucketImpl.prototype.mapAdd)
- description and source-code
```javascript
mapAdd = function (key, path, value, options, callback) {
  if (options instanceof Function) {
    callback = arguments[3];
    options = {};
  }

  var self = this;
  this.mutateIn(key, options).insert(path, value, false)
      .execute(function(err, res) {
    if (err) {
      if (err.code === errors.keyNotFound && options.createMap) {
        var data = {};
        data[path] = value;

        self.insert(key, data, options, function(err, insertRes) {
          if (err) {
            if (err.code === errors.keyAlreadyExists) {
              self.mapAdd(key, path, value, options, callback);
              return;
            }

            callback(err, null);
            return;
          }

          callback(null, insertRes);
        });
        return;
      }

      callback(err, null);
      return;
    }

    callback(null, res);
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.BucketImpl.prototype.mapGet"></a>[function <span class="apidocSignatureSpan">couchbase.BucketImpl.prototype.</span>mapGet (key, path, options, callback)](#apidoc.element.couchbase.BucketImpl.prototype.mapGet)
- description and source-code
```javascript
mapGet = function (key, path, options, callback) {
  if (options instanceof Function) {
    callback = arguments[2];
    options = {};
  }

  this.lookupIn(key, options).get(path).execute(function(err, res) {
    if (err) {
      callback(err, null);
      return;
    }

    try {
      res.value = res.contentByIndex(0);
    } catch (e) {
      callback(e, null);
      return;
    }

    callback(null, res);
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.BucketImpl.prototype.mapRemove"></a>[function <span class="apidocSignatureSpan">couchbase.BucketImpl.prototype.</span>mapRemove (key, path, options, callback)](#apidoc.element.couchbase.BucketImpl.prototype.mapRemove)
- description and source-code
```javascript
mapRemove = function (key, path, options, callback) {
  if (options instanceof Function) {
    callback = arguments[2];
    options = {};
  }

  this.mutateIn(key, options).remove(path).execute(function(err, res) {
    if (err) {
      callback(err, null);
      return;
    }

    callback(null, res);
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.BucketImpl.prototype.mapSize"></a>[function <span class="apidocSignatureSpan">couchbase.BucketImpl.prototype.</span>mapSize (key, options, callback)](#apidoc.element.couchbase.BucketImpl.prototype.mapSize)
- description and source-code
```javascript
mapSize = function (key, options, callback) {
  if (options instanceof Function) {
    callback = arguments[1];
    options = {};
  }

  this.get(key, options, function(err, res) {
    if (err) {
      callback(err, null);
      return;
    }

    var mapValues = res.value;
    res.value = 0;

    for (var i in mapValues) {
      if (mapValues.hasOwnProperty(i)) {
        res.value++;
      }
    }

    callback(null, res);
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.BucketImpl.prototype.mutateIn"></a>[function <span class="apidocSignatureSpan">couchbase.BucketImpl.prototype.</span>mutateIn (key, options)](#apidoc.element.couchbase.BucketImpl.prototype.mutateIn)
- description and source-code
```javascript
mutateIn = function (key, options) {
  if (!options) {
    options = {};
  }

  if (!this._isValidKey(key)) {
    throw new TypeError('First argument needs to be a string or buffer.');
  }
  if (typeof options !== 'object') {
    throw new TypeError('Second argument needs to be an object if set.');
  }
  this._checkHashkeyOption(options);
  this._checkExpiryOption(options);
  this._checkCasOption(options);

  return new MutateInBuilder(this,
      [key, options.hashkey, options.expiry, options.cas]);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.BucketImpl.prototype.prepend"></a>[function <span class="apidocSignatureSpan">couchbase.BucketImpl.prototype.</span>prepend (key, fragment, options, callback)](#apidoc.element.couchbase.BucketImpl.prototype.prepend)
- description and source-code
```javascript
prepend = function (key, fragment, options, callback) {
  this._store(key, fragment, options, callback, CONST.PREPEND);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.BucketImpl.prototype.query"></a>[function <span class="apidocSignatureSpan">couchbase.BucketImpl.prototype.</span>query (query, params, callback)](#apidoc.element.couchbase.BucketImpl.prototype.query)
- description and source-code
```javascript
query = function (query, params, callback) {
  if (params instanceof Function) {
    callback = arguments[1];
    params = undefined;
  }

  if (query instanceof ViewQuery) {
    return this._view(
        '_view', query.ddoc, query.name, query.options, callback);
  } else if (query instanceof SpatialQuery) {
    return this._view(
        '_spatial', query.ddoc, query.name, query.options, callback);
  } else if (query instanceof N1qlQuery) {
    return this._n1ql(
        query, params, callback
    );
  } else if (query instanceof SearchQuery) {
    return this._fts(
        query, callback
    );
  } else {
    throw new TypeError(
        'First argument needs to be a ViewQuery, SpatialQuery or N1qlQuery.');
  }
}
```
- example usage
```shell
...
  }
  qs += ')';
}
if (options.deferred) {
  qs += ' WITH {"defer_build": true}';
}

this._bucket.query(N1qlQuery.fromString(qs), function(err, rows) {
  if (err) {
    if (err.message.indexOf('already exist') !== -1 &&
        options.ignoreIfExists) {
      callback(null);
      return;
    }
...
```

#### <a name="apidoc.element.couchbase.BucketImpl.prototype.queuePop"></a>[function <span class="apidocSignatureSpan">couchbase.BucketImpl.prototype.</span>queuePop (key, options, callback)](#apidoc.element.couchbase.BucketImpl.prototype.queuePop)
- description and source-code
```javascript
queuePop = function (key, options, callback) {
  if (options instanceof Function) {
    callback = arguments[1];
    options = {};
  }

  var self = this;

  self.lookupIn(key, options).get('[-1]').execute(function(err, res) {
    if (err) {
      callback(err, null);
      return;
    }

    var removeOpts = {};
    for (var j in options) {
      if (options.hasOwnProperty(j)) {
        removeOpts[j] = options[j];
      }
    }

    if (removeOpts.cas === undefined) {
      removeOpts.cas = res.cas;
    }

    var poppedValue = res.contentByIndex(0);

    self.mutateIn(key, removeOpts).remove('[-1]').execute(function(err, res) {
      if (err) {
        if (err.code === errors.keyAlreadyExists && options.cas === undefined) {
          self.queuePop(key, options, callback);
          return;
        }

        callback(err, null);
        return;
      }

      callback(null, {
        cas: res.cas,
        value: poppedValue,
        token: res.token
      });
    });
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.BucketImpl.prototype.queuePush"></a>[function <span class="apidocSignatureSpan">couchbase.BucketImpl.prototype.</span>queuePush (key, value, options, callback)](#apidoc.element.couchbase.BucketImpl.prototype.queuePush)
- description and source-code
```javascript
queuePush = function (key, value, options, callback) {
  if (options instanceof Function) {
    callback = arguments[2];
    options = {};
  }

  var listOptions = {};
  for (var i in options) {
    if (options.hasOwnProperty(i)) {
      listOptions[i] = options[i];
    }
  }
  listOptions.createList = listOptions.createQueue;

  return this.listPrepend(key, value, options, callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.BucketImpl.prototype.queueSize"></a>[function <span class="apidocSignatureSpan">couchbase.BucketImpl.prototype.</span>queueSize (key, options, callback)](#apidoc.element.couchbase.BucketImpl.prototype.queueSize)
- description and source-code
```javascript
queueSize = function (key, options, callback) {
  if (options instanceof Function) {
    callback = arguments[1];
    options = {};
  }

  this.get(key, options, function(err, res) {
    if (err) {
      callback(err, null);
      return;
    }

    res.value = res.value.length;
    callback(null, res);
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.BucketImpl.prototype.remove"></a>[function <span class="apidocSignatureSpan">couchbase.BucketImpl.prototype.</span>remove (key, options, callback)](#apidoc.element.couchbase.BucketImpl.prototype.remove)
- description and source-code
```javascript
remove = function (key, options, callback) {
  if (options instanceof Function) {
    callback = arguments[1];
    options = {};
  }

  if (!this._isValidKey(key)) {
    throw new TypeError('First argument needs to be a string or buffer.');
  }
  if (typeof options !== 'object') {
    throw new TypeError('Second argument needs to be an object or callback.');
  }
  if (typeof callback !== 'function') {
    throw new TypeError('Third argument needs to be a callback.');
  }
  this._checkHashkeyOption(options);
  this._checkCasOption(options);
  this._checkDuraOptions(options);

  this._maybeInvoke(this._cb.remove,
      [key, options.hashkey, options.cas,
        this._interceptEndure(key, options, 1, callback)]);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.BucketImpl.prototype.replace"></a>[function <span class="apidocSignatureSpan">couchbase.BucketImpl.prototype.</span>replace (key, value, options, callback)](#apidoc.element.couchbase.BucketImpl.prototype.replace)
- description and source-code
```javascript
replace = function (key, value, options, callback) {
  this._store(key, value, options, callback, CONST.REPLACE);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.BucketImpl.prototype.setAdd"></a>[function <span class="apidocSignatureSpan">couchbase.BucketImpl.prototype.</span>setAdd (key, value, options, callback)](#apidoc.element.couchbase.BucketImpl.prototype.setAdd)
- description and source-code
```javascript
setAdd = function (key, value, options, callback) {
  if (options instanceof Function) {
    callback = arguments[2];
    options = {};
  }

  var self = this;
  this.mutateIn(key, options).arrayAddUnique('', value, false)
      .execute(function(err, res) {
    if (err) {
      if (err.code === errors.keyNotFound && options.createSet) {
        var data = [value];

        self.insert(key, data, options, function(err, insertRes) {
          if (err) {
            if (err.code === errors.keyAlreadyExists) {
              self.setAdd(key, value, options, callback);
              return;
            }

            callback(err, null);
            return;
          }

          callback(null, insertRes);
        });
        return;
      }

      callback(err, null);
      return;
    }

    callback(null, res);
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.BucketImpl.prototype.setExists"></a>[function <span class="apidocSignatureSpan">couchbase.BucketImpl.prototype.</span>setExists (key, value, options, callback)](#apidoc.element.couchbase.BucketImpl.prototype.setExists)
- description and source-code
```javascript
setExists = function (key, value, options, callback) {
  if (options instanceof Function) {
    callback = arguments[2];
    options = {};
  }

  this.get(key, options, function(err, res) {
    if (err) {
      callback(err, null);
      return;
    }

    var setValues = res.value;
    res.value = false;

    for(var i in setValues) {
      if (setValues.hasOwnProperty(i)) {
        if (setValues[i] === value) {
          res.value = true;
        }
      }
    }

    callback(null, res);
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.BucketImpl.prototype.setRemove"></a>[function <span class="apidocSignatureSpan">couchbase.BucketImpl.prototype.</span>setRemove (key, value, options, callback)](#apidoc.element.couchbase.BucketImpl.prototype.setRemove)
- description and source-code
```javascript
setRemove = function (key, value, options, callback) {
  if (options instanceof Function) {
    callback = arguments[2];
    options = {};
  }

  var self = this;
  this.get(key, options, function(err, res) {
    if (err) {
      callback(err, null);
      return;
    }

    var newValues = [];

    for (var i = 0; i < res.value.length; ++i) {
      if (res.value[i] !== value) {
        newValues.push(res.value[i]);
      }
    }

    var replaceOpts = {};
    for (var j in options) {
      if (options.hasOwnProperty(j)) {
        replaceOpts[j] = options[j];
      }
    }

    if (replaceOpts.cas === undefined) {
      replaceOpts.cas = res.cas;
    }

    self.replace(key, newValues, options, function(err, replaceRes) {
      if (err) {
        if (err.code === errors.keyAlreadyExists && options.cas === undefined) {
          self.setRemove(key, value, options, callback);
          return;
        }

        callback(err, null);
        return;
      }

      callback(null, replaceRes);
    });
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.BucketImpl.prototype.setSize"></a>[function <span class="apidocSignatureSpan">couchbase.BucketImpl.prototype.</span>setSize (key, options, callback)](#apidoc.element.couchbase.BucketImpl.prototype.setSize)
- description and source-code
```javascript
setSize = function (key, options, callback) {
  if (options instanceof Function) {
    callback = arguments[1];
    options = {};
  }

  this.get(key, options, function(err, res) {
    if (err) {
      callback(err, null);
      return;
    }

    res.value = res.value.length;
    callback(null, res);
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.BucketImpl.prototype.setTranscoder"></a>[function <span class="apidocSignatureSpan">couchbase.BucketImpl.prototype.</span>setTranscoder (encoder, decoder)](#apidoc.element.couchbase.BucketImpl.prototype.setTranscoder)
- description and source-code
```javascript
setTranscoder = function (encoder, decoder) {
  this._cb.setTranscoder(encoder, decoder);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.BucketImpl.prototype.touch"></a>[function <span class="apidocSignatureSpan">couchbase.BucketImpl.prototype.</span>touch (key, expiry, options, callback)](#apidoc.element.couchbase.BucketImpl.prototype.touch)
- description and source-code
```javascript
touch = function (key, expiry, options, callback) {
  if (options instanceof Function) {
    callback = arguments[2];
    options = {};
  }

  if (!this._isValidKey(key)) {
    throw new TypeError('First argument needs to be a string or buffer.');
  }
  if (typeof expiry !== 'number' || expiry < 0) {
    throw new TypeError('Second argument needs to be 0 or a positive integer.');
  }
  if (typeof options !== 'object') {
    throw new TypeError('Third argument needs to be an object or callback.');
  }
  if (typeof callback !== 'function') {
    throw new TypeError('Fourth argument needs to be a callback.');
  }
  this._checkHashkeyOption(options);
  this._checkCasOption(options);
  this._checkDuraOptions(options);

  this._maybeInvoke(this._cb.get, [key, options.hashkey, expiry, 0, callback]);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.BucketImpl.prototype.unlock"></a>[function <span class="apidocSignatureSpan">couchbase.BucketImpl.prototype.</span>unlock (key, cas, options, callback)](#apidoc.element.couchbase.BucketImpl.prototype.unlock)
- description and source-code
```javascript
unlock = function (key, cas, options, callback) {
  if (options instanceof Function) {
    callback = arguments[2];
    options = {};
  }
  if (typeof key !== 'string' && !(key instanceof Buffer)) {
    throw new TypeError('First argument needs to be a string or buffer.');
  }
  if (typeof cas !== 'object') {
    throw new TypeError('Second argument needs to be a CAS object.');
  }
  if (typeof options !== 'object') {
    throw new TypeError('Third argument needs to be an object or callback.');
  }
  if (typeof callback !== 'function') {
    throw new TypeError('Fourth argument needs to be a callback.');
  }
  this._checkHashkeyOption(options);

  this._maybeInvoke(this._cb.unlock, [key, options.hashkey, cas, callback]);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.BucketImpl.prototype.upsert"></a>[function <span class="apidocSignatureSpan">couchbase.BucketImpl.prototype.</span>upsert (key, value, options, callback)](#apidoc.element.couchbase.BucketImpl.prototype.upsert)
- description and source-code
```javascript
upsert = function (key, value, options, callback) {
  this._store(key, value, options, callback, CONST.SET);
}
```
- example usage
```shell
...
into the bucket and then retrieving its contents:

'''javascript
var couchbase = require('couchbase');
var cluster = new couchbase.Cluster('couchbase://127.0.0.1');
var bucket = cluster.openBucket('default');

bucket.upsert('testdoc', {name:'Frank'}, function(err, result) {
  if (err) throw err;

  bucket.get('testdoc', function(err, result) {
if (err) throw err;

console.log(result.value);
// {name: Frank}
...
```



# <a name="apidoc.module.couchbase.CbasQuery"></a>[module couchbase.CbasQuery](#apidoc.module.couchbase.CbasQuery)

#### <a name="apidoc.element.couchbase.CbasQuery.CbasQuery"></a>[function <span class="apidocSignatureSpan">couchbase.</span>CbasQuery ()](#apidoc.element.couchbase.CbasQuery.CbasQuery)
- description and source-code
```javascript
function CbasQuery() {
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.CbasQuery.Direct"></a>[function <span class="apidocSignatureSpan">couchbase.CbasQuery.</span>Direct (str)](#apidoc.element.couchbase.CbasQuery.Direct)
- description and source-code
```javascript
function CbasStringQuery(str) {
  this.options = {
    statement: str
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.CbasQuery.fromString"></a>[function <span class="apidocSignatureSpan">couchbase.CbasQuery.</span>fromString (str)](#apidoc.element.couchbase.CbasQuery.fromString)
- description and source-code
```javascript
fromString = function (str) {
  return new CbasStringQuery(str);
}
```
- example usage
```shell
...
  }
  qs += ')';
}
if (options.deferred) {
  qs += ' WITH {"defer_build": true}';
}

this._bucket.query(N1qlQuery.fromString(qs), function(err, rows) {
  if (err) {
    if (err.message.indexOf('already exist') !== -1 &&
        options.ignoreIfExists) {
      callback(null);
      return;
    }
...
```



# <a name="apidoc.module.couchbase.CbasQuery.Direct"></a>[module couchbase.CbasQuery.Direct](#apidoc.module.couchbase.CbasQuery.Direct)

#### <a name="apidoc.element.couchbase.CbasQuery.Direct.Direct"></a>[function <span class="apidocSignatureSpan">couchbase.CbasQuery.</span>Direct (str)](#apidoc.element.couchbase.CbasQuery.Direct.Direct)
- description and source-code
```javascript
function CbasStringQuery(str) {
  this.options = {
    statement: str
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.CbasQuery.Direct.super_"></a>[function <span class="apidocSignatureSpan">couchbase.CbasQuery.Direct.</span>super_ ()](#apidoc.element.couchbase.CbasQuery.Direct.super_)
- description and source-code
```javascript
function CbasQuery() {
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.couchbase.CbasQuery.Direct.prototype"></a>[module couchbase.CbasQuery.Direct.prototype](#apidoc.module.couchbase.CbasQuery.Direct.prototype)

#### <a name="apidoc.element.couchbase.CbasQuery.Direct.prototype.toObject"></a>[function <span class="apidocSignatureSpan">couchbase.CbasQuery.Direct.prototype.</span>toObject (args)](#apidoc.element.couchbase.CbasQuery.Direct.prototype.toObject)
- description and source-code
```javascript
toObject = function (args) {
  if (args) {
    throw new Error('CBAS queries do not yet support parameterization');
  }

  return this.options;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.CbasQuery.Direct.prototype.toString"></a>[function <span class="apidocSignatureSpan">couchbase.CbasQuery.Direct.prototype.</span>toString (args)](#apidoc.element.couchbase.CbasQuery.Direct.prototype.toString)
- description and source-code
```javascript
toString = function (args) {
  return qs.stringify(this.toObject(args));
}
```
- example usage
```shell
...
        callback(new Error(errData.reason), null);
        return;
      }
      callback(null, true);
    }));
    httpReq.write(JSON.stringify(data, function(key, value) {
      if (value instanceof Function) {
        return value.toString();
      }
      return value;
    }));
    httpReq.end();
  });
};
...
```



# <a name="apidoc.module.couchbase.CbasQuery.prototype"></a>[module couchbase.CbasQuery.prototype](#apidoc.module.couchbase.CbasQuery.prototype)

#### <a name="apidoc.element.couchbase.CbasQuery.prototype.toString"></a>[function <span class="apidocSignatureSpan">couchbase.CbasQuery.prototype.</span>toString ()](#apidoc.element.couchbase.CbasQuery.prototype.toString)
- description and source-code
```javascript
toString = function () {
  throw new Error('Must use CbasQuery subclasses only.');
}
```
- example usage
```shell
...
        callback(new Error(errData.reason), null);
        return;
      }
      callback(null, true);
    }));
    httpReq.write(JSON.stringify(data, function(key, value) {
      if (value instanceof Function) {
        return value.toString();
      }
      return value;
    }));
    httpReq.end();
  });
};
...
```



# <a name="apidoc.module.couchbase.Cluster"></a>[module couchbase.Cluster](#apidoc.module.couchbase.Cluster)

#### <a name="apidoc.element.couchbase.Cluster.Cluster"></a>[function <span class="apidocSignatureSpan">couchbase.</span>Cluster (cnstr, options)](#apidoc.element.couchbase.Cluster.Cluster)
- description and source-code
```javascript
function Cluster(cnstr, options) {
  this.dsnObj = connstr.parse(cnstr);
  this.auther = null;
  this.connectingBuckets = [];
  this.connectedBuckets = [];
  this.waitQueue = [];

  this.cbasHosts = null;

  // Copy passed options into the connection string
  if (options instanceof Object) {
    for (var i in options) {
      if (options.hasOwnProperty(i)) {
        this.dsnObj.options[i] = encodeURIComponent(options[i]);
      }
    }
  }
}
```
- example usage
```shell
...
until the connection is successfully established.

Here is a simple example of instantiating a connection, adding a new document
into the bucket and then retrieving its contents:

'''javascript
var couchbase = require('couchbase');
var cluster = new couchbase.Cluster('couchbase://127.0.0.1');
var bucket = cluster.openBucket('default');

bucket.upsert('testdoc', {name:'Frank'}, function(err, result) {
if (err) throw err;

bucket.get('testdoc', function(err, result) {
  if (err) throw err;
...
```

#### <a name="apidoc.element.couchbase.Cluster.CbasQueryResponse"></a>[function <span class="apidocSignatureSpan">couchbase.Cluster.</span>CbasQueryResponse ()](#apidoc.element.couchbase.Cluster.CbasQueryResponse)
- description and source-code
```javascript
function CbasQueryResponse() {
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.couchbase.Cluster.CbasQueryResponse"></a>[module couchbase.Cluster.CbasQueryResponse](#apidoc.module.couchbase.Cluster.CbasQueryResponse)

#### <a name="apidoc.element.couchbase.Cluster.CbasQueryResponse.CbasQueryResponse"></a>[function <span class="apidocSignatureSpan">couchbase.Cluster.</span>CbasQueryResponse ()](#apidoc.element.couchbase.Cluster.CbasQueryResponse.CbasQueryResponse)
- description and source-code
```javascript
function CbasQueryResponse() {
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.Cluster.CbasQueryResponse.super_"></a>[function <span class="apidocSignatureSpan">couchbase.Cluster.CbasQueryResponse.</span>super_ ()](#apidoc.element.couchbase.Cluster.CbasQueryResponse.super_)
- description and source-code
```javascript
function EventEmitter() {
  EventEmitter.init.call(this);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.couchbase.Cluster.prototype"></a>[module couchbase.Cluster.prototype](#apidoc.module.couchbase.Cluster.prototype)

#### <a name="apidoc.element.couchbase.Cluster.prototype._cbas"></a>[function <span class="apidocSignatureSpan">couchbase.Cluster.prototype.</span>_cbas (query, params, callback)](#apidoc.element.couchbase.Cluster.prototype._cbas)
- description and source-code
```javascript
_cbas = function (query, params, callback) {
  if (!this.cbasHosts) {
    throw new Error('You must use enableCbas to specify CBAS hosts.');
  }
  var host = this.cbasHosts[Math.floor(Math.random() * this.cbasHosts.length)];

  var req = new Bucket.N1qlQueryResponse();

  var self = this;
  setImmediate(function() {
    self._cbasReq(host, query.toObject(params), req);
  });

  if (callback) {
    req.on('rows', function(rows, meta) {
      callback(null, rows, meta);
    });
    req.on('error', function(err) {
      callback(err, null, null);
    });
  }

  return req;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.Cluster.prototype._cbasReq"></a>[function <span class="apidocSignatureSpan">couchbase.Cluster.prototype.</span>_cbasReq (host, q, emitter)](#apidoc.element.couchbase.Cluster.prototype._cbasReq)
- description and source-code
```javascript
_cbasReq = function (host, q, emitter) {
  var uri = 'http://' + host + '/query/service';

  request({
    method: 'post',
    uri: uri,
    body: q,
    json: true
  }, function (err, resp, body) {
    if (err) {
      emitter.emit('error', err);
      return;
    }

    if (!body || body.status !== 'success') {
      if (body && body.errors && body.errors.length > 0) {
        var firstErr = body.errors[0];
        err = new Error(firstErr.msg);
        err.requestID = body.requestID;
        err.code = firstErr.code;
        err.otherErrors = [];

        for (var i = 1; i < body.errors.length; ++i) {
          var nextErr = body.errors[i];
          var otherErr = new Error(nextErr.msg);
          otherErr.code = nextErr.code;
          err.otherErrors.push(otherErr);
        }
      } else {
        err = new Error('An unknown CBAS error occured.' +
            ' This is usually related to an out-of-memory condition.');
      }

      emitter.emit('error', err);
      return;
    }

    // Emit each row
    for (var j = 0; j < body.results.length; ++j) {
      emitter.emit('row', body.results[j]);
    }

    // Emit all the rows, this is easy since we already have them
    //  all, in the future with streaming we will need to copy N1QL.
    emitter.emit('rows', body.results);

    // Emit the end meta
    delete body.results;
    emitter.emit('end', body);
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.Cluster.prototype._fts"></a>[function <span class="apidocSignatureSpan">couchbase.Cluster.prototype.</span>_fts (query, callback)](#apidoc.element.couchbase.Cluster.prototype._fts)
- description and source-code
```javascript
_fts = function (query, callback) {
  var req = new Bucket.FtsQueryResponse();

  var invokeCb = callback;
  if (!invokeCb) {
    invokeCb = function(err) {
      req.emit('error', err);
    };
  }

  this._maybeInvoke(this._ftsReq.bind(this),
      [query, req, invokeCb]);

  if (callback) {
    req.on('rows', function(rows, meta) {
      callback(null, rows, meta);
    });
    req.on('error', function(err) {
      callback(err, null, null);
    });
  }

  return req;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.Cluster.prototype._ftsReq"></a>[function <span class="apidocSignatureSpan">couchbase.Cluster.prototype.</span>_ftsReq (q, emitter)](#apidoc.element.couchbase.Cluster.prototype._ftsReq)
- description and source-code
```javascript
_ftsReq = function (q, emitter) {
  var bucket = this.connectedBuckets[0];
  bucket._ftsReq(q, emitter);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.Cluster.prototype._invoke"></a>[function <span class="apidocSignatureSpan">couchbase.Cluster.prototype.</span>_invoke (fn, args)](#apidoc.element.couchbase.Cluster.prototype._invoke)
- description and source-code
```javascript
_invoke = function (fn, args) {
  try {
    fn.apply(this._cb, args);
  } catch(e) {
    args[args.length-1](e, null);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.Cluster.prototype._maybeInvoke"></a>[function <span class="apidocSignatureSpan">couchbase.Cluster.prototype.</span>_maybeInvoke (fn, args)](#apidoc.element.couchbase.Cluster.prototype._maybeInvoke)
- description and source-code
```javascript
_maybeInvoke = function (fn, args) {
  if (this.connected === true) {
    this._invoke(fn, args);
  } else if (this.connected === false) {
    throw new Error('cannot perform operations on a shutdown bucket');
  } else {
    this.waitQueue.push([fn, args]);
  }
}
```
- example usage
```shell
...
* @param callback
*
* @private
* @ignore
*/
BucketManager.prototype._mgmtRequest = function(path, method, callback) {
 var b = this._bucket;
 b._maybeInvoke(b._mgmtRequest.bind(b), [path, method, callback]);
};

/**
* Method for performing a http capi request using the underlying bucket.
*
* @param path
* @param method
...
```

#### <a name="apidoc.element.couchbase.Cluster.prototype._n1ql"></a>[function <span class="apidocSignatureSpan">couchbase.Cluster.prototype.</span>_n1ql (query, params, callback)](#apidoc.element.couchbase.Cluster.prototype._n1ql)
- description and source-code
```javascript
_n1ql = function (query, params, callback) {
  var req = new Bucket.N1qlQueryResponse();

  var invokeCb = callback;
  if (!invokeCb) {
    invokeCb = function(err) {
      req.emit('error', err);
    };
  }

  this._maybeInvoke(this._n1qlReq.bind(this),
      [undefined, query.toObject(params), query.isAdhoc, req, invokeCb]);

  if (callback) {
    req.on('rows', function(rows, meta) {
      callback(null, rows, meta);
    });
    req.on('error', function(err) {
      callback(err, null, null);
    });
  }

  return req;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.Cluster.prototype._n1qlReq"></a>[function <span class="apidocSignatureSpan">couchbase.Cluster.prototype.</span>_n1qlReq (host, q, adhoc, emitter)](#apidoc.element.couchbase.Cluster.prototype._n1qlReq)
- description and source-code
```javascript
_n1qlReq = function (host, q, adhoc, emitter) {
  var bucket = this.connectedBuckets[0];
  bucket._n1qlReq(host, q, adhoc, emitter);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.Cluster.prototype.authenticate"></a>[function <span class="apidocSignatureSpan">couchbase.Cluster.prototype.</span>authenticate (auther)](#apidoc.element.couchbase.Cluster.prototype.authenticate)
- description and source-code
```javascript
authenticate = function (auther) {
  this.auther = auther;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.Cluster.prototype.enableCbas"></a>[function <span class="apidocSignatureSpan">couchbase.Cluster.prototype.</span>enableCbas (hosts)](#apidoc.element.couchbase.Cluster.prototype.enableCbas)
- description and source-code
```javascript
enableCbas = function (hosts) {
  if (!Array.isArray(hosts)) {
    hosts = [hosts];
  }

  this.cbasHosts = hosts;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.Cluster.prototype.manager"></a>[function <span class="apidocSignatureSpan">couchbase.Cluster.prototype.</span>manager (username, password)](#apidoc.element.couchbase.Cluster.prototype.manager)
- description and source-code
```javascript
manager = function (username, password) {
  if (username === undefined && this.auther instanceof Object) {
    username = this.auther.username;
  }
  if (password === undefined && this.auther instanceof Object) {
    password = this.auther.password;
  }
  return new ClusterManager(this, username, password);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.Cluster.prototype.openBucket"></a>[function <span class="apidocSignatureSpan">couchbase.Cluster.prototype.</span>openBucket (name, password, callback)](#apidoc.element.couchbase.Cluster.prototype.openBucket)
- description and source-code
```javascript
openBucket = function (name, password, callback) {
  if (password instanceof Function) {
    callback = arguments[1];
    password = '';
  }

  var bucketDsnObj = connstr.normalize(this.dsnObj);
  bucketDsnObj.bucket = name;
  if (this.auther instanceof Object && this.auther.buckets instanceof Object) {
    var bucketCreds = [];
    for (var i in this.auther.buckets) {
      if (this.auther.buckets.hasOwnProperty(i)) {
        bucketCreds.push(JSON.stringify([i, this.auther.buckets[i]]));
      }
    }
    if (bucketCreds.length > 0) {
      bucketDsnObj.options.bucket_cred = bucketCreds;
    }
  }
  bucketDsnObj.options.client_string =
      'couchnode/' + require('../package.json').version;
  this.dsnObj = bucketDsnObj;

  var bucket = new Bucket({
    dsnObj: bucketDsnObj,
    username: name,
    password: password
  });
  if (callback) {
    bucket.on('connect', callback);
    bucket.on('error', callback);
  }

  var self = this;
  this.connectingBuckets.push(bucket);
  bucket.on('connect', function() {
    self.connectingBuckets = _arrayRemove(self.connectingBuckets, bucket);
    self.connectedBuckets.push(bucket);
    for (var i = 0; i < self.waitQueue.length; ++i) {
      var itm = self.waitQueue[i];
      self._invoke(itm[0], itm[1]);
    }
    self.waitQueue = [];
  });
  bucket.on('error', function() {
    self.connectingBuckets = _arrayRemove(self.connectingBuckets, bucket);
    if (self.connectingBuckets.length > 0) {
      return;
    }

    var err = new Error('You cannot perform a cluster-level query without' +
        ' at least one bucket open.');
    for (var i = 0; i < self.waitQueue.length; ++i) {
      var itm = self.waitQueue[i];
      itm[1][itm[1].length-1](err, null);
    }
    self.waitQueue = [];
  });

  return bucket;
}
```
- example usage
```shell
...

Here is a simple example of instantiating a connection, adding a new document
into the bucket and then retrieving its contents:

'''javascript
var couchbase = require('couchbase');
var cluster = new couchbase.Cluster('couchbase://127.0.0.1');
var bucket = cluster.openBucket('default');

bucket.upsert('testdoc', {name:'Frank'}, function(err, result) {
if (err) throw err;

bucket.get('testdoc', function(err, result) {
  if (err) throw err;
...
```

#### <a name="apidoc.element.couchbase.Cluster.prototype.query"></a>[function <span class="apidocSignatureSpan">couchbase.Cluster.prototype.</span>query (query, params, callback)](#apidoc.element.couchbase.Cluster.prototype.query)
- description and source-code
```javascript
query = function (query, params, callback) {
  if (params instanceof Function) {
    callback = arguments[1];
    params = undefined;
  }

  if (query instanceof CbasQuery) {
    return this._cbas(
        query, params, callback);
  }

  if (!(this.auther instanceof Object)) {
    var errC = new Error('You cannot perform a cluster-level query without' +
        ' specifying credentials with Cluster.authenticate.');
    setImmediate(function() {
      if (callback) {
        callback(errC);
      }
    });
    return;
  }

  if (this.connectedBuckets.length === 0 &&
      this.connectingBuckets.length === 0) {
    var errB = new Error('You cannot perform a cluster-level query without' +
        ' at least one bucket open.');
    setImmediate(function() {
      if (callback) {
        callback(errB);
      }
    });
    return;
  }

  if (query instanceof N1qlQuery) {
    return this._n1ql(
        query, params, callback
    );
  } else if (query instanceof SearchQuery) {
    return this._fts(
        query, callback
    );
  } else {
    throw new TypeError(
        'First argument needs to be a N1qlQuery.');
  }
}
```
- example usage
```shell
...
  }
  qs += ')';
}
if (options.deferred) {
  qs += ' WITH {"defer_build": true}';
}

this._bucket.query(N1qlQuery.fromString(qs), function(err, rows) {
  if (err) {
    if (err.message.indexOf('already exist') !== -1 &&
        options.ignoreIfExists) {
      callback(null);
      return;
    }
...
```



# <a name="apidoc.module.couchbase.Error"></a>[module couchbase.Error](#apidoc.module.couchbase.Error)

#### <a name="apidoc.element.couchbase.Error.Error"></a>[function <span class="apidocSignatureSpan">couchbase.</span>Error (message)](#apidoc.element.couchbase.Error.Error)
- description and source-code
```javascript
function CouchbaseError(message) {
  Error.call(this);
  Error.captureStackTrace(this, CouchbaseError);
  this.message = message;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.Error.super_"></a>[function <span class="apidocSignatureSpan">couchbase.Error.</span>super_ ()](#apidoc.element.couchbase.Error.super_)
- description and source-code
```javascript
function Error() { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.couchbase.Error.super_"></a>[module couchbase.Error.super_](#apidoc.module.couchbase.Error.super_)

#### <a name="apidoc.element.couchbase.Error.super_.super_"></a>[function <span class="apidocSignatureSpan">couchbase.Error.</span>super_ ()](#apidoc.element.couchbase.Error.super_.super_)
- description and source-code
```javascript
function Error() { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.Error.super_.captureStackTrace"></a>[function <span class="apidocSignatureSpan">couchbase.Error.super_.</span>captureStackTrace ()](#apidoc.element.couchbase.Error.super_.captureStackTrace)
- description and source-code
```javascript
function captureStackTrace() { [native code] }
```
- example usage
```shell
...
 * @type {CouchbaseBinding}
 * @ignore
 */
var couchnode = require('bindings')('couchbase_impl');

function CouchbaseError(message) {
  Error.call(this);
  Error.captureStackTrace(this, CouchbaseError);
  this.message = message;
}
util.inherits(CouchbaseError, Error);
CouchbaseError.prototype.name = 'CouchbaseError';
couchnode._setErrorClass(CouchbaseError);
couchnode.Error = CouchbaseError;
...
```



# <a name="apidoc.module.couchbase.Mock"></a>[module couchbase.Mock](#apidoc.module.couchbase.Mock)

#### <a name="apidoc.element.couchbase.Mock.Cluster"></a>[function <span class="apidocSignatureSpan">couchbase.Mock.</span>Cluster (cnstr)](#apidoc.element.couchbase.Mock.Cluster)
- description and source-code
```javascript
function MockCluster(cnstr) {
  this.dsnObj = connstr.parse(cnstr);
}
```
- example usage
```shell
...
until the connection is successfully established.

Here is a simple example of instantiating a connection, adding a new document
into the bucket and then retrieving its contents:

'''javascript
var couchbase = require('couchbase');
var cluster = new couchbase.Cluster('couchbase://127.0.0.1');
var bucket = cluster.openBucket('default');

bucket.upsert('testdoc', {name:'Frank'}, function(err, result) {
if (err) throw err;

bucket.get('testdoc', function(err, result) {
  if (err) throw err;
...
```

#### <a name="apidoc.element.couchbase.Mock.Error"></a>[function <span class="apidocSignatureSpan">couchbase.Mock.</span>Error (message, code)](#apidoc.element.couchbase.Mock.Error)
- description and source-code
```javascript
function CbError(message, code) {
  Error.captureStackTrace(this, this.constructor);
  this.name = this.constructor.name;
  this.message = message;
  this.code = code;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.Mock.N1qlQuery"></a>[function <span class="apidocSignatureSpan">couchbase.Mock.</span>N1qlQuery ()](#apidoc.element.couchbase.Mock.N1qlQuery)
- description and source-code
```javascript
function N1qlQuery() {
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.Mock.SpatialQuery"></a>[function <span class="apidocSignatureSpan">couchbase.Mock.</span>SpatialQuery ()](#apidoc.element.couchbase.Mock.SpatialQuery)
- description and source-code
```javascript
function SpatialQuery() {
  this.ddoc = null;
  this.name = null;
  this.options = {};
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.Mock.ViewQuery"></a>[function <span class="apidocSignatureSpan">couchbase.Mock.</span>ViewQuery ()](#apidoc.element.couchbase.Mock.ViewQuery)
- description and source-code
```javascript
function ViewQuery() {
  this.ddoc = null;
  this.name = null;
  this.options = {};
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.couchbase.Mock.Cluster"></a>[module couchbase.Mock.Cluster](#apidoc.module.couchbase.Mock.Cluster)

#### <a name="apidoc.element.couchbase.Mock.Cluster.Cluster"></a>[function <span class="apidocSignatureSpan">couchbase.Mock.</span>Cluster (cnstr)](#apidoc.element.couchbase.Mock.Cluster.Cluster)
- description and source-code
```javascript
function MockCluster(cnstr) {
  this.dsnObj = connstr.parse(cnstr);
}
```
- example usage
```shell
...
until the connection is successfully established.

Here is a simple example of instantiating a connection, adding a new document
into the bucket and then retrieving its contents:

'''javascript
var couchbase = require('couchbase');
var cluster = new couchbase.Cluster('couchbase://127.0.0.1');
var bucket = cluster.openBucket('default');

bucket.upsert('testdoc', {name:'Frank'}, function(err, result) {
if (err) throw err;

bucket.get('testdoc', function(err, result) {
  if (err) throw err;
...
```



# <a name="apidoc.module.couchbase.Mock.Cluster.prototype"></a>[module couchbase.Mock.Cluster.prototype](#apidoc.module.couchbase.Mock.Cluster.prototype)

#### <a name="apidoc.element.couchbase.Mock.Cluster.prototype.manager"></a>[function <span class="apidocSignatureSpan">couchbase.Mock.Cluster.prototype.</span>manager (username, password)](#apidoc.element.couchbase.Mock.Cluster.prototype.manager)
- description and source-code
```javascript
manager = function (username, password) {
  return new MockClusterManager(this, username, password);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.Mock.Cluster.prototype.openBucket"></a>[function <span class="apidocSignatureSpan">couchbase.Mock.Cluster.prototype.</span>openBucket (name, password, callback)](#apidoc.element.couchbase.Mock.Cluster.prototype.openBucket)
- description and source-code
```javascript
openBucket = function (name, password, callback) {
  if (password instanceof Function) {
    callback = arguments[1];
    password = arguments[9];
  }

  var bucketDsnObj = connstr.normalize(this.dsnObj);
  bucketDsnObj.bucket = name;

  var bucket = new MockBucket({
    dsnObj: bucketDsnObj,
    username: name,
    password: password
  });
  if (callback) {
    bucket.on('connect', callback);
    bucket.on('error', callback);
  }
  return bucket;
}
```
- example usage
```shell
...

Here is a simple example of instantiating a connection, adding a new document
into the bucket and then retrieving its contents:

'''javascript
var couchbase = require('couchbase');
var cluster = new couchbase.Cluster('couchbase://127.0.0.1');
var bucket = cluster.openBucket('default');

bucket.upsert('testdoc', {name:'Frank'}, function(err, result) {
if (err) throw err;

bucket.get('testdoc', function(err, result) {
  if (err) throw err;
...
```



# <a name="apidoc.module.couchbase.MutationState"></a>[module couchbase.MutationState](#apidoc.module.couchbase.MutationState)

#### <a name="apidoc.element.couchbase.MutationState.MutationState"></a>[function <span class="apidocSignatureSpan">couchbase.</span>MutationState ()](#apidoc.element.couchbase.MutationState.MutationState)
- description and source-code
```javascript
function MutationState() {
  this._data = {};
  for (var i = 0; i < arguments.length; ++i) {
    this._addSingle(arguments[i]);
  }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.couchbase.MutationState.prototype"></a>[module couchbase.MutationState.prototype](#apidoc.module.couchbase.MutationState.prototype)

#### <a name="apidoc.element.couchbase.MutationState.prototype._addSingle"></a>[function <span class="apidocSignatureSpan">couchbase.MutationState.prototype.</span>_addSingle (token)](#apidoc.element.couchbase.MutationState.prototype._addSingle)
- description and source-code
```javascript
_addSingle = function (token) {
  if (!token) {
    return;
  }
  if (token.token) {
    token = token.token;
  }
  var tokenData = token.toString().split(':');
  if (tokenData.length < 4 || tokenData[3] === '') {
    return;
  }
  var vbId = tokenData[0];
  var vbUuid = tokenData[1];
  var vbSeqNo = parseInt(tokenData[2], 10);
  var bucketName = tokenData[3];

  if (!this._data[bucketName]) {
    this._data[bucketName] = {};
  }
  if (!this._data[bucketName][vbId]) {
    this._data[bucketName][vbId] = [vbSeqNo, vbUuid];
  } else {
    var info = this._data[bucketName][vbId];
    if (info[0] < vbSeqNo) {
      info[0] = vbSeqNo;
    }
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.MutationState.prototype.add"></a>[function <span class="apidocSignatureSpan">couchbase.MutationState.prototype.</span>add ()](#apidoc.element.couchbase.MutationState.prototype.add)
- description and source-code
```javascript
add = function () {
  for (var i = 0; i < arguments.length; ++i) {
    this._addSingle(arguments[i]);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.MutationState.prototype.inspect"></a>[function <span class="apidocSignatureSpan">couchbase.MutationState.prototype.</span>inspect ()](#apidoc.element.couchbase.MutationState.prototype.inspect)
- description and source-code
```javascript
inspect = function () {
  var tokens = '';
  for (var bucket in this._data) {
    if (this._data.hasOwnProperty(bucket)) {
      for (var vbid in this._data[bucket]) {
        if (this._data[bucket].hasOwnProperty(vbid)) {
          var info = this._data[bucket][vbid];
          if (tokens !== '') {
            tokens += ';';
          }
          tokens += vbid + ':' + info[0] + ':' +
              info[1] + ':' + bucket;
        }
      }
    }
  }
  return 'MutationState<' + tokens + '>';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.MutationState.prototype.toJSON"></a>[function <span class="apidocSignatureSpan">couchbase.MutationState.prototype.</span>toJSON ()](#apidoc.element.couchbase.MutationState.prototype.toJSON)
- description and source-code
```javascript
toJSON = function () {
  return this._data;
}
```
- example usage
```shell
...
 */
BooleanQuery.prototype.toJSON = function() {
var out = {};
if (this.data.must) {
  out.must = this.data.must;
}
if (this.data.should) {
  var shouldData = this.data.should.toJSON();
  shouldData.min = this.shouldMin;
  out.should = shouldData;
}
if (this.data.must_not) {
  out.must_not = this.data.must_not;
}
return out;
...
```



# <a name="apidoc.module.couchbase.N1qlQuery"></a>[module couchbase.N1qlQuery](#apidoc.module.couchbase.N1qlQuery)

#### <a name="apidoc.element.couchbase.N1qlQuery.N1qlQuery"></a>[function <span class="apidocSignatureSpan">couchbase.</span>N1qlQuery ()](#apidoc.element.couchbase.N1qlQuery.N1qlQuery)
- description and source-code
```javascript
function N1qlQuery() {
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.N1qlQuery.Direct"></a>[function <span class="apidocSignatureSpan">couchbase.N1qlQuery.</span>Direct (str)](#apidoc.element.couchbase.N1qlQuery.Direct)
- description and source-code
```javascript
function N1qlStringQuery(str) {
  this.options = {
    statement: str
  };
  this.isAdhoc = true;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.N1qlQuery.fromString"></a>[function <span class="apidocSignatureSpan">couchbase.N1qlQuery.</span>fromString (str)](#apidoc.element.couchbase.N1qlQuery.fromString)
- description and source-code
```javascript
fromString = function (str) {
  return new N1qlStringQuery(str);
}
```
- example usage
```shell
...
  }
  qs += ')';
}
if (options.deferred) {
  qs += ' WITH {"defer_build": true}';
}

this._bucket.query(N1qlQuery.fromString(qs), function(err, rows) {
  if (err) {
    if (err.message.indexOf('already exist') !== -1 &&
        options.ignoreIfExists) {
      callback(null);
      return;
    }
...
```



# <a name="apidoc.module.couchbase.N1qlQuery.Direct"></a>[module couchbase.N1qlQuery.Direct](#apidoc.module.couchbase.N1qlQuery.Direct)

#### <a name="apidoc.element.couchbase.N1qlQuery.Direct.Direct"></a>[function <span class="apidocSignatureSpan">couchbase.N1qlQuery.</span>Direct (str)](#apidoc.element.couchbase.N1qlQuery.Direct.Direct)
- description and source-code
```javascript
function N1qlStringQuery(str) {
  this.options = {
    statement: str
  };
  this.isAdhoc = true;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.N1qlQuery.Direct.super_"></a>[function <span class="apidocSignatureSpan">couchbase.N1qlQuery.Direct.</span>super_ ()](#apidoc.element.couchbase.N1qlQuery.Direct.super_)
- description and source-code
```javascript
function N1qlQuery() {
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.couchbase.N1qlQuery.Direct.prototype"></a>[module couchbase.N1qlQuery.Direct.prototype](#apidoc.module.couchbase.N1qlQuery.Direct.prototype)

#### <a name="apidoc.element.couchbase.N1qlQuery.Direct.prototype.adhoc"></a>[function <span class="apidocSignatureSpan">couchbase.N1qlQuery.Direct.prototype.</span>adhoc (adhoc)](#apidoc.element.couchbase.N1qlQuery.Direct.prototype.adhoc)
- description and source-code
```javascript
adhoc = function (adhoc) {
  this.isAdhoc = !!adhoc;
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.N1qlQuery.Direct.prototype.consistency"></a>[function <span class="apidocSignatureSpan">couchbase.N1qlQuery.Direct.prototype.</span>consistency (val)](#apidoc.element.couchbase.N1qlQuery.Direct.prototype.consistency)
- description and source-code
```javascript
consistency = function (val) {
  if (this.options.scan_vectors !== undefined) {
    throw new Error('consistency and consistentWith must be use exclusively.');
  }

  if (val === N1qlQuery.Consistency.NOT_BOUNDED) {
    this.options.scan_consistency = 'not_bounded';
  } else if (val === N1qlQuery.Consistency.REQUEST_PLUS) {
    this.options.scan_consistency = 'request_plus';
  } else if (val === N1qlQuery.Consistency.STATEMENT_PLUS) {
    this.options.scan_consistency = 'statement_plus';
  } else {
    throw new TypeError('invalid option passed.');
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.N1qlQuery.Direct.prototype.consistentWith"></a>[function <span class="apidocSignatureSpan">couchbase.N1qlQuery.Direct.prototype.</span>consistentWith (state)](#apidoc.element.couchbase.N1qlQuery.Direct.prototype.consistentWith)
- description and source-code
```javascript
consistentWith = function (state) {
  if (this.options.scan_consistency !== undefined) {
    throw new Error('consistency and consistentWith must be use exclusively.');
  }

  this.options.scan_consistency = 'at_plus';
  this.options.scan_vectors = state;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.N1qlQuery.Direct.prototype.pretty"></a>[function <span class="apidocSignatureSpan">couchbase.N1qlQuery.Direct.prototype.</span>pretty (pretty)](#apidoc.element.couchbase.N1qlQuery.Direct.prototype.pretty)
- description and source-code
```javascript
pretty = function (pretty) {
  this.options.pretty = !!pretty;
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.N1qlQuery.Direct.prototype.toObject"></a>[function <span class="apidocSignatureSpan">couchbase.N1qlQuery.Direct.prototype.</span>toObject (args)](#apidoc.element.couchbase.N1qlQuery.Direct.prototype.toObject)
- description and source-code
```javascript
toObject = function (args) {
  if (!args) {
    return this.options;
  }

  var out = {};
  for (var i in this.options) {
    if (this.options.hasOwnProperty(i)) {
      out[i] = this.options[i];
    }
  }

  if (Array.isArray(args)) {
    out.args = args;
  } else {
    for (var j in args) {
      if (args.hasOwnProperty(j)) {
        out['$' + j] = args[j];
      }
    }
  }

  return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.N1qlQuery.Direct.prototype.toString"></a>[function <span class="apidocSignatureSpan">couchbase.N1qlQuery.Direct.prototype.</span>toString (args)](#apidoc.element.couchbase.N1qlQuery.Direct.prototype.toString)
- description and source-code
```javascript
toString = function (args) {
  return qs.stringify(this.toObject(args));
}
```
- example usage
```shell
...
        callback(new Error(errData.reason), null);
        return;
      }
      callback(null, true);
    }));
    httpReq.write(JSON.stringify(data, function(key, value) {
      if (value instanceof Function) {
        return value.toString();
      }
      return value;
    }));
    httpReq.end();
  });
};
...
```



# <a name="apidoc.module.couchbase.N1qlQuery.prototype"></a>[module couchbase.N1qlQuery.prototype](#apidoc.module.couchbase.N1qlQuery.prototype)

#### <a name="apidoc.element.couchbase.N1qlQuery.prototype.toString"></a>[function <span class="apidocSignatureSpan">couchbase.N1qlQuery.prototype.</span>toString ()](#apidoc.element.couchbase.N1qlQuery.prototype.toString)
- description and source-code
```javascript
toString = function () {
  throw new Error('Must use N1qlQuery subclasses only.');
}
```
- example usage
```shell
...
        callback(new Error(errData.reason), null);
        return;
      }
      callback(null, true);
    }));
    httpReq.write(JSON.stringify(data, function(key, value) {
      if (value instanceof Function) {
        return value.toString();
      }
      return value;
    }));
    httpReq.end();
  });
};
...
```



# <a name="apidoc.module.couchbase.SearchFacet"></a>[module couchbase.SearchFacet](#apidoc.module.couchbase.SearchFacet)

#### <a name="apidoc.element.couchbase.SearchFacet.DateFacet"></a>[function <span class="apidocSignatureSpan">couchbase.SearchFacet.</span>DateFacet (field, size)](#apidoc.element.couchbase.SearchFacet.DateFacet)
- description and source-code
```javascript
function DateFacet(field, size) {
  this.field = field;
  this.size = size;
  this.date_ranges = [];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.SearchFacet.NumericFacet"></a>[function <span class="apidocSignatureSpan">couchbase.SearchFacet.</span>NumericFacet (field, size)](#apidoc.element.couchbase.SearchFacet.NumericFacet)
- description and source-code
```javascript
function NumericFacet(field, size) {
  this.field = field;
  this.size = size;
  this.numeric_ranges = [];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.SearchFacet.TermFacet"></a>[function <span class="apidocSignatureSpan">couchbase.SearchFacet.</span>TermFacet (field, size)](#apidoc.element.couchbase.SearchFacet.TermFacet)
- description and source-code
```javascript
function TermFacet(field, size) {
  this.field = field;
  this.size = size;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.SearchFacet.date"></a>[function <span class="apidocSignatureSpan">couchbase.SearchFacet.</span>date (field, size)](#apidoc.element.couchbase.SearchFacet.date)
- description and source-code
```javascript
date = function (field, size) {
  return new DateFacet(field, size);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.SearchFacet.numeric"></a>[function <span class="apidocSignatureSpan">couchbase.SearchFacet.</span>numeric (field, size)](#apidoc.element.couchbase.SearchFacet.numeric)
- description and source-code
```javascript
numeric = function (field, size) {
  return new NumericFacet(field, size);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.SearchFacet.term"></a>[function <span class="apidocSignatureSpan">couchbase.SearchFacet.</span>term (field, size)](#apidoc.element.couchbase.SearchFacet.term)
- description and source-code
```javascript
term = function (field, size) {
  return new TermFacet(field, size);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.couchbase.SearchFacet.DateFacet"></a>[module couchbase.SearchFacet.DateFacet](#apidoc.module.couchbase.SearchFacet.DateFacet)

#### <a name="apidoc.element.couchbase.SearchFacet.DateFacet.DateFacet"></a>[function <span class="apidocSignatureSpan">couchbase.SearchFacet.</span>DateFacet (field, size)](#apidoc.element.couchbase.SearchFacet.DateFacet.DateFacet)
- description and source-code
```javascript
function DateFacet(field, size) {
  this.field = field;
  this.size = size;
  this.date_ranges = [];
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.couchbase.SearchFacet.DateFacet.prototype"></a>[module couchbase.SearchFacet.DateFacet.prototype](#apidoc.module.couchbase.SearchFacet.DateFacet.prototype)

#### <a name="apidoc.element.couchbase.SearchFacet.DateFacet.prototype.addRange"></a>[function <span class="apidocSignatureSpan">couchbase.SearchFacet.DateFacet.prototype.</span>addRange (name, start, end)](#apidoc.element.couchbase.SearchFacet.DateFacet.prototype.addRange)
- description and source-code
```javascript
addRange = function (name, start, end) {
  this.date_ranges.push({
    name: name,
    start: start,
    end: end
  });
  return this;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.couchbase.SearchFacet.NumericFacet"></a>[module couchbase.SearchFacet.NumericFacet](#apidoc.module.couchbase.SearchFacet.NumericFacet)

#### <a name="apidoc.element.couchbase.SearchFacet.NumericFacet.NumericFacet"></a>[function <span class="apidocSignatureSpan">couchbase.SearchFacet.</span>NumericFacet (field, size)](#apidoc.element.couchbase.SearchFacet.NumericFacet.NumericFacet)
- description and source-code
```javascript
function NumericFacet(field, size) {
  this.field = field;
  this.size = size;
  this.numeric_ranges = [];
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.couchbase.SearchFacet.NumericFacet.prototype"></a>[module couchbase.SearchFacet.NumericFacet.prototype](#apidoc.module.couchbase.SearchFacet.NumericFacet.prototype)

#### <a name="apidoc.element.couchbase.SearchFacet.NumericFacet.prototype.addRange"></a>[function <span class="apidocSignatureSpan">couchbase.SearchFacet.NumericFacet.prototype.</span>addRange (name, start, end)](#apidoc.element.couchbase.SearchFacet.NumericFacet.prototype.addRange)
- description and source-code
```javascript
addRange = function (name, start, end) {
  this.numeric_ranges.push({
    name: name,
    start: start,
    end: end
  });
  return this;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.couchbase.SearchQuery"></a>[module couchbase.SearchQuery](#apidoc.module.couchbase.SearchQuery)

#### <a name="apidoc.element.couchbase.SearchQuery.SearchQuery"></a>[function <span class="apidocSignatureSpan">couchbase.</span>SearchQuery (indexName, query)](#apidoc.element.couchbase.SearchQuery.SearchQuery)
- description and source-code
```javascript
function SearchQuery(indexName, query) {
  this.data = {
    indexName: indexName,
    query: query
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.SearchQuery.BooleanFieldQuery"></a>[function <span class="apidocSignatureSpan">couchbase.SearchQuery.</span>BooleanFieldQuery (val)](#apidoc.element.couchbase.SearchQuery.BooleanFieldQuery)
- description and source-code
```javascript
function BooleanFieldQuery(val) {
  this.data = {
    bool: val
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.SearchQuery.BooleanQuery"></a>[function <span class="apidocSignatureSpan">couchbase.SearchQuery.</span>BooleanQuery ()](#apidoc.element.couchbase.SearchQuery.BooleanQuery)
- description and source-code
```javascript
function BooleanQuery() {
  this.data = {};
  this.shouldMin = undefined;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.SearchQuery.ConjunctionQuery"></a>[function <span class="apidocSignatureSpan">couchbase.SearchQuery.</span>ConjunctionQuery (queries)](#apidoc.element.couchbase.SearchQuery.ConjunctionQuery)
- description and source-code
```javascript
function ConjunctionQuery(queries) {
  queries = cbutils.unpackArgs(queries, arguments);
  this.data = {
    conjuncts: []
  };
  this.and(queries);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.SearchQuery.DateRangeQuery"></a>[function <span class="apidocSignatureSpan">couchbase.SearchQuery.</span>DateRangeQuery ()](#apidoc.element.couchbase.SearchQuery.DateRangeQuery)
- description and source-code
```javascript
function DateRangeQuery() {
  this.data = {};
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.SearchQuery.DisjunctionQuery"></a>[function <span class="apidocSignatureSpan">couchbase.SearchQuery.</span>DisjunctionQuery (queries)](#apidoc.element.couchbase.SearchQuery.DisjunctionQuery)
- description and source-code
```javascript
function DisjunctionQuery(queries) {
  queries = cbutils.unpackArgs(queries);
  this.data = {
    disjuncts: []
  };
  this.or(queries);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.SearchQuery.DocIdQuery"></a>[function <span class="apidocSignatureSpan">couchbase.SearchQuery.</span>DocIdQuery (ids)](#apidoc.element.couchbase.SearchQuery.DocIdQuery)
- description and source-code
```javascript
function DocIdQuery(ids) {
  ids = cbutils.unpackArgs(ids, arguments);
  this.data = {
    ids: []
  };
  this.addDocIds(ids);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.SearchQuery.MatchAllQuery"></a>[function <span class="apidocSignatureSpan">couchbase.SearchQuery.</span>MatchAllQuery ()](#apidoc.element.couchbase.SearchQuery.MatchAllQuery)
- description and source-code
```javascript
function MatchAllQuery() {
  this.data = {
    match_all: null
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.SearchQuery.MatchNoneQuery"></a>[function <span class="apidocSignatureSpan">couchbase.SearchQuery.</span>MatchNoneQuery ()](#apidoc.element.couchbase.SearchQuery.MatchNoneQuery)
- description and source-code
```javascript
function MatchNoneQuery() {
  this.data = {
    match_none: null
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.SearchQuery.MatchPhraseQuery"></a>[function <span class="apidocSignatureSpan">couchbase.SearchQuery.</span>MatchPhraseQuery (phrase)](#apidoc.element.couchbase.SearchQuery.MatchPhraseQuery)
- description and source-code
```javascript
function MatchPhraseQuery(phrase) {
  this.data = {
    match_phrase: phrase
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.SearchQuery.MatchQuery"></a>[function <span class="apidocSignatureSpan">couchbase.SearchQuery.</span>MatchQuery (match)](#apidoc.element.couchbase.SearchQuery.MatchQuery)
- description and source-code
```javascript
function MatchQuery(match) {
  this.data = {
    match: match
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.SearchQuery.NumericRangeQuery"></a>[function <span class="apidocSignatureSpan">couchbase.SearchQuery.</span>NumericRangeQuery ()](#apidoc.element.couchbase.SearchQuery.NumericRangeQuery)
- description and source-code
```javascript
function NumericRangeQuery() {
  this.data = {};
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.SearchQuery.PhraseQuery"></a>[function <span class="apidocSignatureSpan">couchbase.SearchQuery.</span>PhraseQuery (terms)](#apidoc.element.couchbase.SearchQuery.PhraseQuery)
- description and source-code
```javascript
function PhraseQuery(terms) {
  this.data = {
    terms: terms
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.SearchQuery.PrefixQuery"></a>[function <span class="apidocSignatureSpan">couchbase.SearchQuery.</span>PrefixQuery (prefix)](#apidoc.element.couchbase.SearchQuery.PrefixQuery)
- description and source-code
```javascript
function PrefixQuery(prefix) {
  this.data = {
    prefix: prefix
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.SearchQuery.QueryStringQuery"></a>[function <span class="apidocSignatureSpan">couchbase.SearchQuery.</span>QueryStringQuery (query)](#apidoc.element.couchbase.SearchQuery.QueryStringQuery)
- description and source-code
```javascript
function QueryStringQuery(query) {
  this.data = {
    query: query
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.SearchQuery.RegexpQuery"></a>[function <span class="apidocSignatureSpan">couchbase.SearchQuery.</span>RegexpQuery (regexp)](#apidoc.element.couchbase.SearchQuery.RegexpQuery)
- description and source-code
```javascript
function RegexpQuery(regexp) {
  this.data = {
    regexp: regexp
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.SearchQuery.TermQuery"></a>[function <span class="apidocSignatureSpan">couchbase.SearchQuery.</span>TermQuery (term)](#apidoc.element.couchbase.SearchQuery.TermQuery)
- description and source-code
```javascript
function TermQuery(term) {
  this.data = {
    term: term
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.SearchQuery.WildcardQuery"></a>[function <span class="apidocSignatureSpan">couchbase.SearchQuery.</span>WildcardQuery (wildcard)](#apidoc.element.couchbase.SearchQuery.WildcardQuery)
- description and source-code
```javascript
function WildcardQuery(wildcard) {
  this.data = {
    wildcard: wildcard
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.SearchQuery.boolean"></a>[function <span class="apidocSignatureSpan">couchbase.SearchQuery.</span>boolean ()](#apidoc.element.couchbase.SearchQuery.boolean)
- description and source-code
```javascript
boolean = function () {
  return new BooleanQuery();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.SearchQuery.booleanField"></a>[function <span class="apidocSignatureSpan">couchbase.SearchQuery.</span>booleanField (val)](#apidoc.element.couchbase.SearchQuery.booleanField)
- description and source-code
```javascript
booleanField = function (val) {
  return new BooleanFieldQuery(val);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.SearchQuery.conjuncts"></a>[function <span class="apidocSignatureSpan">couchbase.SearchQuery.</span>conjuncts (queries)](#apidoc.element.couchbase.SearchQuery.conjuncts)
- description and source-code
```javascript
conjuncts = function (queries) {
  queries = cbutils.unpackArgs(queries, arguments);
  return new ConjunctionQuery(queries);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.SearchQuery.dateRange"></a>[function <span class="apidocSignatureSpan">couchbase.SearchQuery.</span>dateRange ()](#apidoc.element.couchbase.SearchQuery.dateRange)
- description and source-code
```javascript
dateRange = function () {
  return new DateRangeQuery();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.SearchQuery.disjuncts"></a>[function <span class="apidocSignatureSpan">couchbase.SearchQuery.</span>disjuncts (queries)](#apidoc.element.couchbase.SearchQuery.disjuncts)
- description and source-code
```javascript
disjuncts = function (queries) {
  queries = cbutils.unpackArgs(queries, arguments);
  return new DisjunctionQuery(queries);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.SearchQuery.docIds"></a>[function <span class="apidocSignatureSpan">couchbase.SearchQuery.</span>docIds (ids)](#apidoc.element.couchbase.SearchQuery.docIds)
- description and source-code
```javascript
docIds = function (ids) {
  ids = cbutils.unpackArgs(ids, arguments);
  return new DocIdQuery(ids);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.SearchQuery.match"></a>[function <span class="apidocSignatureSpan">couchbase.SearchQuery.</span>match (match)](#apidoc.element.couchbase.SearchQuery.match)
- description and source-code
```javascript
match = function (match) {
  return new MatchQuery(match);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.SearchQuery.matchAll"></a>[function <span class="apidocSignatureSpan">couchbase.SearchQuery.</span>matchAll ()](#apidoc.element.couchbase.SearchQuery.matchAll)
- description and source-code
```javascript
matchAll = function () {
  return new MatchAllQuery();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.SearchQuery.matchNone"></a>[function <span class="apidocSignatureSpan">couchbase.SearchQuery.</span>matchNone ()](#apidoc.element.couchbase.SearchQuery.matchNone)
- description and source-code
```javascript
matchNone = function () {
  return new MatchNoneQuery();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.SearchQuery.matchPhrase"></a>[function <span class="apidocSignatureSpan">couchbase.SearchQuery.</span>matchPhrase (phrase)](#apidoc.element.couchbase.SearchQuery.matchPhrase)
- description and source-code
```javascript
matchPhrase = function (phrase) {
  return new MatchPhraseQuery(phrase);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.SearchQuery.new"></a>[function <span class="apidocSignatureSpan">couchbase.SearchQuery.</span>new (indexName, query)](#apidoc.element.couchbase.SearchQuery.new)
- description and source-code
```javascript
new = function (indexName, query) {
  return new SearchQuery(indexName, query);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.SearchQuery.numericRange"></a>[function <span class="apidocSignatureSpan">couchbase.SearchQuery.</span>numericRange ()](#apidoc.element.couchbase.SearchQuery.numericRange)
- description and source-code
```javascript
numericRange = function () {
  return new NumericRangeQuery();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.SearchQuery.phrase"></a>[function <span class="apidocSignatureSpan">couchbase.SearchQuery.</span>phrase (terms)](#apidoc.element.couchbase.SearchQuery.phrase)
- description and source-code
```javascript
phrase = function (terms) {
  return new PhraseQuery(terms);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.SearchQuery.prefix"></a>[function <span class="apidocSignatureSpan">couchbase.SearchQuery.</span>prefix (prefix)](#apidoc.element.couchbase.SearchQuery.prefix)
- description and source-code
```javascript
prefix = function (prefix) {
  return new PrefixQuery(prefix);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.SearchQuery.queryString"></a>[function <span class="apidocSignatureSpan">couchbase.SearchQuery.</span>queryString (query)](#apidoc.element.couchbase.SearchQuery.queryString)
- description and source-code
```javascript
queryString = function (query) {
  return new QueryStringQuery(query);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.SearchQuery.regexp"></a>[function <span class="apidocSignatureSpan">couchbase.SearchQuery.</span>regexp (regexp)](#apidoc.element.couchbase.SearchQuery.regexp)
- description and source-code
```javascript
regexp = function (regexp) {
  return new RegexpQuery(regexp);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.SearchQuery.term"></a>[function <span class="apidocSignatureSpan">couchbase.SearchQuery.</span>term (term)](#apidoc.element.couchbase.SearchQuery.term)
- description and source-code
```javascript
term = function (term) {
  return new TermQuery(term);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.SearchQuery.wildcard"></a>[function <span class="apidocSignatureSpan">couchbase.SearchQuery.</span>wildcard (wildcard)](#apidoc.element.couchbase.SearchQuery.wildcard)
- description and source-code
```javascript
wildcard = function (wildcard) {
  return new WildcardQuery(wildcard);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.couchbase.SearchQuery.BooleanQuery"></a>[module couchbase.SearchQuery.BooleanQuery](#apidoc.module.couchbase.SearchQuery.BooleanQuery)

#### <a name="apidoc.element.couchbase.SearchQuery.BooleanQuery.BooleanQuery"></a>[function <span class="apidocSignatureSpan">couchbase.SearchQuery.</span>BooleanQuery ()](#apidoc.element.couchbase.SearchQuery.BooleanQuery.BooleanQuery)
- description and source-code
```javascript
function BooleanQuery() {
  this.data = {};
  this.shouldMin = undefined;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.couchbase.SearchQuery.BooleanQuery.prototype"></a>[module couchbase.SearchQuery.BooleanQuery.prototype](#apidoc.module.couchbase.SearchQuery.BooleanQuery.prototype)

#### <a name="apidoc.element.couchbase.SearchQuery.BooleanQuery.prototype.boost"></a>[function <span class="apidocSignatureSpan">couchbase.SearchQuery.BooleanQuery.prototype.</span>boost (boost)](#apidoc.element.couchbase.SearchQuery.BooleanQuery.prototype.boost)
- description and source-code
```javascript
boost = function (boost) {
  this.data.boost = boost;
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.SearchQuery.BooleanQuery.prototype.must"></a>[function <span class="apidocSignatureSpan">couchbase.SearchQuery.BooleanQuery.prototype.</span>must (query)](#apidoc.element.couchbase.SearchQuery.BooleanQuery.prototype.must)
- description and source-code
```javascript
must = function (query) {
  if (!(query instanceof ConjunctionQuery)) {
    query = new ConjunctionQuery([query]);
  }
  this.data.must = query;
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.SearchQuery.BooleanQuery.prototype.mustNot"></a>[function <span class="apidocSignatureSpan">couchbase.SearchQuery.BooleanQuery.prototype.</span>mustNot (query)](#apidoc.element.couchbase.SearchQuery.BooleanQuery.prototype.mustNot)
- description and source-code
```javascript
mustNot = function (query) {
  if (!(query instanceof DisjunctionQuery)) {
    query = new DisjunctionQuery([query]);
  }
  this.data.must_not = query;
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.SearchQuery.BooleanQuery.prototype.should"></a>[function <span class="apidocSignatureSpan">couchbase.SearchQuery.BooleanQuery.prototype.</span>should (query)](#apidoc.element.couchbase.SearchQuery.BooleanQuery.prototype.should)
- description and source-code
```javascript
should = function (query) {
  if (!(query instanceof DisjunctionQuery)) {
    query = new DisjunctionQuery([query]);
  }
  this.data.should = query;
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.SearchQuery.BooleanQuery.prototype.shouldMin"></a>[function <span class="apidocSignatureSpan">couchbase.SearchQuery.BooleanQuery.prototype.</span>shouldMin (shouldMin)](#apidoc.element.couchbase.SearchQuery.BooleanQuery.prototype.shouldMin)
- description and source-code
```javascript
shouldMin = function (shouldMin) {
  this.shouldMin = shouldMin;
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.SearchQuery.BooleanQuery.prototype.toJSON"></a>[function <span class="apidocSignatureSpan">couchbase.SearchQuery.BooleanQuery.prototype.</span>toJSON ()](#apidoc.element.couchbase.SearchQuery.BooleanQuery.prototype.toJSON)
- description and source-code
```javascript
toJSON = function () {
  var out = {};
  if (this.data.must) {
    out.must = this.data.must;
  }
  if (this.data.should) {
    var shouldData = this.data.should.toJSON();
    shouldData.min = this.shouldMin;
    out.should = shouldData;
  }
  if (this.data.must_not) {
    out.must_not = this.data.must_not;
  }
  return out;
}
```
- example usage
```shell
...
 */
BooleanQuery.prototype.toJSON = function() {
var out = {};
if (this.data.must) {
  out.must = this.data.must;
}
if (this.data.should) {
  var shouldData = this.data.should.toJSON();
  shouldData.min = this.shouldMin;
  out.should = shouldData;
}
if (this.data.must_not) {
  out.must_not = this.data.must_not;
}
return out;
...
```



# <a name="apidoc.module.couchbase.SearchQuery.ConjunctionQuery"></a>[module couchbase.SearchQuery.ConjunctionQuery](#apidoc.module.couchbase.SearchQuery.ConjunctionQuery)

#### <a name="apidoc.element.couchbase.SearchQuery.ConjunctionQuery.ConjunctionQuery"></a>[function <span class="apidocSignatureSpan">couchbase.SearchQuery.</span>ConjunctionQuery (queries)](#apidoc.element.couchbase.SearchQuery.ConjunctionQuery.ConjunctionQuery)
- description and source-code
```javascript
function ConjunctionQuery(queries) {
  queries = cbutils.unpackArgs(queries, arguments);
  this.data = {
    conjuncts: []
  };
  this.and(queries);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.couchbase.SearchQuery.ConjunctionQuery.prototype"></a>[module couchbase.SearchQuery.ConjunctionQuery.prototype](#apidoc.module.couchbase.SearchQuery.ConjunctionQuery.prototype)

#### <a name="apidoc.element.couchbase.SearchQuery.ConjunctionQuery.prototype.and"></a>[function <span class="apidocSignatureSpan">couchbase.SearchQuery.ConjunctionQuery.prototype.</span>and (queries)](#apidoc.element.couchbase.SearchQuery.ConjunctionQuery.prototype.and)
- description and source-code
```javascript
and = function (queries) {
  queries = cbutils.unpackArgs(queries, arguments);
  for (var i = 0; i < queries.length; ++i) {
    this.data.conjuncts.push(queries[i]);
  }
  return this;
}
```
- example usage
```shell
...
* @memberof SearchQuery
*/
function ConjunctionQuery(queries) {
 queries = cbutils.unpackArgs(queries, arguments);
 this.data = {
   conjuncts: []
 };
 this.and(queries);
}
SearchQuery.ConjunctionQuery = ConjunctionQuery;

/**
* conjuncts creates a ConjunctionQuery for matching all of a list of
* subqueries in an index.
*
...
```

#### <a name="apidoc.element.couchbase.SearchQuery.ConjunctionQuery.prototype.boost"></a>[function <span class="apidocSignatureSpan">couchbase.SearchQuery.ConjunctionQuery.prototype.</span>boost (boost)](#apidoc.element.couchbase.SearchQuery.ConjunctionQuery.prototype.boost)
- description and source-code
```javascript
boost = function (boost) {
  this.data.boost = boost;
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.SearchQuery.ConjunctionQuery.prototype.toJSON"></a>[function <span class="apidocSignatureSpan">couchbase.SearchQuery.ConjunctionQuery.prototype.</span>toJSON ()](#apidoc.element.couchbase.SearchQuery.ConjunctionQuery.prototype.toJSON)
- description and source-code
```javascript
toJSON = function () {
  return this.data;
}
```
- example usage
```shell
...
 */
BooleanQuery.prototype.toJSON = function() {
var out = {};
if (this.data.must) {
  out.must = this.data.must;
}
if (this.data.should) {
  var shouldData = this.data.should.toJSON();
  shouldData.min = this.shouldMin;
  out.should = shouldData;
}
if (this.data.must_not) {
  out.must_not = this.data.must_not;
}
return out;
...
```



# <a name="apidoc.module.couchbase.SearchQuery.DateRangeQuery"></a>[module couchbase.SearchQuery.DateRangeQuery](#apidoc.module.couchbase.SearchQuery.DateRangeQuery)

#### <a name="apidoc.element.couchbase.SearchQuery.DateRangeQuery.DateRangeQuery"></a>[function <span class="apidocSignatureSpan">couchbase.SearchQuery.</span>DateRangeQuery ()](#apidoc.element.couchbase.SearchQuery.DateRangeQuery.DateRangeQuery)
- description and source-code
```javascript
function DateRangeQuery() {
  this.data = {};
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.couchbase.SearchQuery.DateRangeQuery.prototype"></a>[module couchbase.SearchQuery.DateRangeQuery.prototype](#apidoc.module.couchbase.SearchQuery.DateRangeQuery.prototype)

#### <a name="apidoc.element.couchbase.SearchQuery.DateRangeQuery.prototype.boost"></a>[function <span class="apidocSignatureSpan">couchbase.SearchQuery.DateRangeQuery.prototype.</span>boost (boost)](#apidoc.element.couchbase.SearchQuery.DateRangeQuery.prototype.boost)
- description and source-code
```javascript
boost = function (boost) {
  this.data.boost = boost;
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.SearchQuery.DateRangeQuery.prototype.dateTimeParser"></a>[function <span class="apidocSignatureSpan">couchbase.SearchQuery.DateRangeQuery.prototype.</span>dateTimeParser (dateTimeParser)](#apidoc.element.couchbase.SearchQuery.DateRangeQuery.prototype.dateTimeParser)
- description and source-code
```javascript
dateTimeParser = function (dateTimeParser) {
  this.data.datetime_parser = dateTimeParser;
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.SearchQuery.DateRangeQuery.prototype.toJSON"></a>[function <span class="apidocSignatureSpan">couchbase.SearchQuery.DateRangeQuery.prototype.</span>toJSON ()](#apidoc.element.couchbase.SearchQuery.DateRangeQuery.prototype.toJSON)
- description and source-code
```javascript
toJSON = function () {
  return this.data;
}
```
- example usage
```shell
...
 */
BooleanQuery.prototype.toJSON = function() {
var out = {};
if (this.data.must) {
  out.must = this.data.must;
}
if (this.data.should) {
  var shouldData = this.data.should.toJSON();
  shouldData.min = this.shouldMin;
  out.should = shouldData;
}
if (this.data.must_not) {
  out.must_not = this.data.must_not;
}
return out;
...
```



# <a name="apidoc.module.couchbase.SearchQuery.DisjunctionQuery"></a>[module couchbase.SearchQuery.DisjunctionQuery](#apidoc.module.couchbase.SearchQuery.DisjunctionQuery)

#### <a name="apidoc.element.couchbase.SearchQuery.DisjunctionQuery.DisjunctionQuery"></a>[function <span class="apidocSignatureSpan">couchbase.SearchQuery.</span>DisjunctionQuery (queries)](#apidoc.element.couchbase.SearchQuery.DisjunctionQuery.DisjunctionQuery)
- description and source-code
```javascript
function DisjunctionQuery(queries) {
  queries = cbutils.unpackArgs(queries);
  this.data = {
    disjuncts: []
  };
  this.or(queries);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.couchbase.SearchQuery.DisjunctionQuery.prototype"></a>[module couchbase.SearchQuery.DisjunctionQuery.prototype](#apidoc.module.couchbase.SearchQuery.DisjunctionQuery.prototype)

#### <a name="apidoc.element.couchbase.SearchQuery.DisjunctionQuery.prototype.boost"></a>[function <span class="apidocSignatureSpan">couchbase.SearchQuery.DisjunctionQuery.prototype.</span>boost (boost)](#apidoc.element.couchbase.SearchQuery.DisjunctionQuery.prototype.boost)
- description and source-code
```javascript
boost = function (boost) {
  this.data.boost = boost;
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.SearchQuery.DisjunctionQuery.prototype.or"></a>[function <span class="apidocSignatureSpan">couchbase.SearchQuery.DisjunctionQuery.prototype.</span>or (queries)](#apidoc.element.couchbase.SearchQuery.DisjunctionQuery.prototype.or)
- description and source-code
```javascript
or = function (queries) {
  queries = cbutils.unpackArgs(queries, arguments);
  for (var i = 0; i < queries.length; ++i) {
    this.data.disjuncts.push(queries[i]);
  }
  return this;
}
```
- example usage
```shell
...
* @memberof SearchQuery
*/
function DisjunctionQuery(queries) {
 queries = cbutils.unpackArgs(queries);
 this.data = {
   disjuncts: []
 };
 this.or(queries);
}
SearchQuery.DisjunctionQuery = DisjunctionQuery;

/**
* disjuncts creates a DisjunctionQuery for matching any of a list of
* subqueries in an index.
*
...
```

#### <a name="apidoc.element.couchbase.SearchQuery.DisjunctionQuery.prototype.toJSON"></a>[function <span class="apidocSignatureSpan">couchbase.SearchQuery.DisjunctionQuery.prototype.</span>toJSON ()](#apidoc.element.couchbase.SearchQuery.DisjunctionQuery.prototype.toJSON)
- description and source-code
```javascript
toJSON = function () {
  return this.data;
}
```
- example usage
```shell
...
 */
BooleanQuery.prototype.toJSON = function() {
var out = {};
if (this.data.must) {
  out.must = this.data.must;
}
if (this.data.should) {
  var shouldData = this.data.should.toJSON();
  shouldData.min = this.shouldMin;
  out.should = shouldData;
}
if (this.data.must_not) {
  out.must_not = this.data.must_not;
}
return out;
...
```



# <a name="apidoc.module.couchbase.SearchQuery.DocIdQuery"></a>[module couchbase.SearchQuery.DocIdQuery](#apidoc.module.couchbase.SearchQuery.DocIdQuery)

#### <a name="apidoc.element.couchbase.SearchQuery.DocIdQuery.DocIdQuery"></a>[function <span class="apidocSignatureSpan">couchbase.SearchQuery.</span>DocIdQuery (ids)](#apidoc.element.couchbase.SearchQuery.DocIdQuery.DocIdQuery)
- description and source-code
```javascript
function DocIdQuery(ids) {
  ids = cbutils.unpackArgs(ids, arguments);
  this.data = {
    ids: []
  };
  this.addDocIds(ids);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.couchbase.SearchQuery.DocIdQuery.prototype"></a>[module couchbase.SearchQuery.DocIdQuery.prototype](#apidoc.module.couchbase.SearchQuery.DocIdQuery.prototype)

#### <a name="apidoc.element.couchbase.SearchQuery.DocIdQuery.prototype.addDocIds"></a>[function <span class="apidocSignatureSpan">couchbase.SearchQuery.DocIdQuery.prototype.</span>addDocIds (ids)](#apidoc.element.couchbase.SearchQuery.DocIdQuery.prototype.addDocIds)
- description and source-code
```javascript
addDocIds = function (ids) {
  ids = cbutils.unpackArgs(ids, arguments);
  for (var i = 0; i < ids.length; ++i) {
    this.data.ids.push(ids);
  }
}
```
- example usage
```shell
...
* @memberof SearchQuery
*/
function DocIdQuery(ids) {
 ids = cbutils.unpackArgs(ids, arguments);
 this.data = {
   ids: []
 };
 this.addDocIds(ids);
}
SearchQuery.DocIdQuery = DocIdQuery;

/**
* docIds creates a DocIdQuery which allows you to match a list of
* document ids in an index.
*
...
```

#### <a name="apidoc.element.couchbase.SearchQuery.DocIdQuery.prototype.boost"></a>[function <span class="apidocSignatureSpan">couchbase.SearchQuery.DocIdQuery.prototype.</span>boost (boost)](#apidoc.element.couchbase.SearchQuery.DocIdQuery.prototype.boost)
- description and source-code
```javascript
boost = function (boost) {
  this.data.boost = boost;
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.SearchQuery.DocIdQuery.prototype.field"></a>[function <span class="apidocSignatureSpan">couchbase.SearchQuery.DocIdQuery.prototype.</span>field (field)](#apidoc.element.couchbase.SearchQuery.DocIdQuery.prototype.field)
- description and source-code
```javascript
field = function (field) {
  this.data.field = field;
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.SearchQuery.DocIdQuery.prototype.toJSON"></a>[function <span class="apidocSignatureSpan">couchbase.SearchQuery.DocIdQuery.prototype.</span>toJSON ()](#apidoc.element.couchbase.SearchQuery.DocIdQuery.prototype.toJSON)
- description and source-code
```javascript
toJSON = function () {
  return this.data;
}
```
- example usage
```shell
...
 */
BooleanQuery.prototype.toJSON = function() {
var out = {};
if (this.data.must) {
  out.must = this.data.must;
}
if (this.data.should) {
  var shouldData = this.data.should.toJSON();
  shouldData.min = this.shouldMin;
  out.should = shouldData;
}
if (this.data.must_not) {
  out.must_not = this.data.must_not;
}
return out;
...
```



# <a name="apidoc.module.couchbase.SearchQuery.MatchAllQuery"></a>[module couchbase.SearchQuery.MatchAllQuery](#apidoc.module.couchbase.SearchQuery.MatchAllQuery)

#### <a name="apidoc.element.couchbase.SearchQuery.MatchAllQuery.MatchAllQuery"></a>[function <span class="apidocSignatureSpan">couchbase.SearchQuery.</span>MatchAllQuery ()](#apidoc.element.couchbase.SearchQuery.MatchAllQuery.MatchAllQuery)
- description and source-code
```javascript
function MatchAllQuery() {
  this.data = {
    match_all: null
  };
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.couchbase.SearchQuery.MatchAllQuery.prototype"></a>[module couchbase.SearchQuery.MatchAllQuery.prototype](#apidoc.module.couchbase.SearchQuery.MatchAllQuery.prototype)

#### <a name="apidoc.element.couchbase.SearchQuery.MatchAllQuery.prototype.toJSON"></a>[function <span class="apidocSignatureSpan">couchbase.SearchQuery.MatchAllQuery.prototype.</span>toJSON ()](#apidoc.element.couchbase.SearchQuery.MatchAllQuery.prototype.toJSON)
- description and source-code
```javascript
toJSON = function () {
  return this.data;
}
```
- example usage
```shell
...
 */
BooleanQuery.prototype.toJSON = function() {
var out = {};
if (this.data.must) {
  out.must = this.data.must;
}
if (this.data.should) {
  var shouldData = this.data.should.toJSON();
  shouldData.min = this.shouldMin;
  out.should = shouldData;
}
if (this.data.must_not) {
  out.must_not = this.data.must_not;
}
return out;
...
```



# <a name="apidoc.module.couchbase.SearchQuery.MatchNoneQuery"></a>[module couchbase.SearchQuery.MatchNoneQuery](#apidoc.module.couchbase.SearchQuery.MatchNoneQuery)

#### <a name="apidoc.element.couchbase.SearchQuery.MatchNoneQuery.MatchNoneQuery"></a>[function <span class="apidocSignatureSpan">couchbase.SearchQuery.</span>MatchNoneQuery ()](#apidoc.element.couchbase.SearchQuery.MatchNoneQuery.MatchNoneQuery)
- description and source-code
```javascript
function MatchNoneQuery() {
  this.data = {
    match_none: null
  };
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.couchbase.SearchQuery.MatchNoneQuery.prototype"></a>[module couchbase.SearchQuery.MatchNoneQuery.prototype](#apidoc.module.couchbase.SearchQuery.MatchNoneQuery.prototype)

#### <a name="apidoc.element.couchbase.SearchQuery.MatchNoneQuery.prototype.toJSON"></a>[function <span class="apidocSignatureSpan">couchbase.SearchQuery.MatchNoneQuery.prototype.</span>toJSON ()](#apidoc.element.couchbase.SearchQuery.MatchNoneQuery.prototype.toJSON)
- description and source-code
```javascript
toJSON = function () {
  return this.data;
}
```
- example usage
```shell
...
 */
BooleanQuery.prototype.toJSON = function() {
var out = {};
if (this.data.must) {
  out.must = this.data.must;
}
if (this.data.should) {
  var shouldData = this.data.should.toJSON();
  shouldData.min = this.shouldMin;
  out.should = shouldData;
}
if (this.data.must_not) {
  out.must_not = this.data.must_not;
}
return out;
...
```



# <a name="apidoc.module.couchbase.SearchQuery.MatchPhraseQuery"></a>[module couchbase.SearchQuery.MatchPhraseQuery](#apidoc.module.couchbase.SearchQuery.MatchPhraseQuery)

#### <a name="apidoc.element.couchbase.SearchQuery.MatchPhraseQuery.MatchPhraseQuery"></a>[function <span class="apidocSignatureSpan">couchbase.SearchQuery.</span>MatchPhraseQuery (phrase)](#apidoc.element.couchbase.SearchQuery.MatchPhraseQuery.MatchPhraseQuery)
- description and source-code
```javascript
function MatchPhraseQuery(phrase) {
  this.data = {
    match_phrase: phrase
  };
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.couchbase.SearchQuery.MatchPhraseQuery.prototype"></a>[module couchbase.SearchQuery.MatchPhraseQuery.prototype](#apidoc.module.couchbase.SearchQuery.MatchPhraseQuery.prototype)

#### <a name="apidoc.element.couchbase.SearchQuery.MatchPhraseQuery.prototype.analyzer"></a>[function <span class="apidocSignatureSpan">couchbase.SearchQuery.MatchPhraseQuery.prototype.</span>analyzer (analyzer)](#apidoc.element.couchbase.SearchQuery.MatchPhraseQuery.prototype.analyzer)
- description and source-code
```javascript
analyzer = function (analyzer) {
  this.data.analyzer = analyzer;
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.SearchQuery.MatchPhraseQuery.prototype.boost"></a>[function <span class="apidocSignatureSpan">couchbase.SearchQuery.MatchPhraseQuery.prototype.</span>boost (boost)](#apidoc.element.couchbase.SearchQuery.MatchPhraseQuery.prototype.boost)
- description and source-code
```javascript
boost = function (boost) {
  this.data.boost = boost;
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.SearchQuery.MatchPhraseQuery.prototype.field"></a>[function <span class="apidocSignatureSpan">couchbase.SearchQuery.MatchPhraseQuery.prototype.</span>field (field)](#apidoc.element.couchbase.SearchQuery.MatchPhraseQuery.prototype.field)
- description and source-code
```javascript
field = function (field) {
  this.data.field = field;
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.SearchQuery.MatchPhraseQuery.prototype.toJSON"></a>[function <span class="apidocSignatureSpan">couchbase.SearchQuery.MatchPhraseQuery.prototype.</span>toJSON ()](#apidoc.element.couchbase.SearchQuery.MatchPhraseQuery.prototype.toJSON)
- description and source-code
```javascript
toJSON = function () {
  return this.data;
}
```
- example usage
```shell
...
 */
BooleanQuery.prototype.toJSON = function() {
var out = {};
if (this.data.must) {
  out.must = this.data.must;
}
if (this.data.should) {
  var shouldData = this.data.should.toJSON();
  shouldData.min = this.shouldMin;
  out.should = shouldData;
}
if (this.data.must_not) {
  out.must_not = this.data.must_not;
}
return out;
...
```



# <a name="apidoc.module.couchbase.SearchQuery.MatchQuery"></a>[module couchbase.SearchQuery.MatchQuery](#apidoc.module.couchbase.SearchQuery.MatchQuery)

#### <a name="apidoc.element.couchbase.SearchQuery.MatchQuery.MatchQuery"></a>[function <span class="apidocSignatureSpan">couchbase.SearchQuery.</span>MatchQuery (match)](#apidoc.element.couchbase.SearchQuery.MatchQuery.MatchQuery)
- description and source-code
```javascript
function MatchQuery(match) {
  this.data = {
    match: match
  };
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.couchbase.SearchQuery.MatchQuery.prototype"></a>[module couchbase.SearchQuery.MatchQuery.prototype](#apidoc.module.couchbase.SearchQuery.MatchQuery.prototype)

#### <a name="apidoc.element.couchbase.SearchQuery.MatchQuery.prototype.analyzer"></a>[function <span class="apidocSignatureSpan">couchbase.SearchQuery.MatchQuery.prototype.</span>analyzer (analyzer)](#apidoc.element.couchbase.SearchQuery.MatchQuery.prototype.analyzer)
- description and source-code
```javascript
analyzer = function (analyzer) {
  this.data.analyzer = analyzer;
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.SearchQuery.MatchQuery.prototype.boost"></a>[function <span class="apidocSignatureSpan">couchbase.SearchQuery.MatchQuery.prototype.</span>boost (boost)](#apidoc.element.couchbase.SearchQuery.MatchQuery.prototype.boost)
- description and source-code
```javascript
boost = function (boost) {
  this.data.boost = boost;
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.SearchQuery.MatchQuery.prototype.field"></a>[function <span class="apidocSignatureSpan">couchbase.SearchQuery.MatchQuery.prototype.</span>field (field)](#apidoc.element.couchbase.SearchQuery.MatchQuery.prototype.field)
- description and source-code
```javascript
field = function (field) {
  this.data.field = field;
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.SearchQuery.MatchQuery.prototype.fuzziness"></a>[function <span class="apidocSignatureSpan">couchbase.SearchQuery.MatchQuery.prototype.</span>fuzziness (fuzziness)](#apidoc.element.couchbase.SearchQuery.MatchQuery.prototype.fuzziness)
- description and source-code
```javascript
fuzziness = function (fuzziness) {
  this.data.fuzziness = fuzziness;
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.SearchQuery.MatchQuery.prototype.prefixLength"></a>[function <span class="apidocSignatureSpan">couchbase.SearchQuery.MatchQuery.prototype.</span>prefixLength (prefixLength)](#apidoc.element.couchbase.SearchQuery.MatchQuery.prototype.prefixLength)
- description and source-code
```javascript
prefixLength = function (prefixLength) {
  this.data.prefix_length = prefixLength;
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.SearchQuery.MatchQuery.prototype.toJSON"></a>[function <span class="apidocSignatureSpan">couchbase.SearchQuery.MatchQuery.prototype.</span>toJSON ()](#apidoc.element.couchbase.SearchQuery.MatchQuery.prototype.toJSON)
- description and source-code
```javascript
toJSON = function () {
  return this.data;
}
```
- example usage
```shell
...
 */
BooleanQuery.prototype.toJSON = function() {
var out = {};
if (this.data.must) {
  out.must = this.data.must;
}
if (this.data.should) {
  var shouldData = this.data.should.toJSON();
  shouldData.min = this.shouldMin;
  out.should = shouldData;
}
if (this.data.must_not) {
  out.must_not = this.data.must_not;
}
return out;
...
```



# <a name="apidoc.module.couchbase.SearchQuery.NumericRangeQuery"></a>[module couchbase.SearchQuery.NumericRangeQuery](#apidoc.module.couchbase.SearchQuery.NumericRangeQuery)

#### <a name="apidoc.element.couchbase.SearchQuery.NumericRangeQuery.NumericRangeQuery"></a>[function <span class="apidocSignatureSpan">couchbase.SearchQuery.</span>NumericRangeQuery ()](#apidoc.element.couchbase.SearchQuery.NumericRangeQuery.NumericRangeQuery)
- description and source-code
```javascript
function NumericRangeQuery() {
  this.data = {};
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.couchbase.SearchQuery.NumericRangeQuery.prototype"></a>[module couchbase.SearchQuery.NumericRangeQuery.prototype](#apidoc.module.couchbase.SearchQuery.NumericRangeQuery.prototype)

#### <a name="apidoc.element.couchbase.SearchQuery.NumericRangeQuery.prototype.boost"></a>[function <span class="apidocSignatureSpan">couchbase.SearchQuery.NumericRangeQuery.prototype.</span>boost (boost)](#apidoc.element.couchbase.SearchQuery.NumericRangeQuery.prototype.boost)
- description and source-code
```javascript
boost = function (boost) {
  this.data.boost = boost;
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.SearchQuery.NumericRangeQuery.prototype.toJSON"></a>[function <span class="apidocSignatureSpan">couchbase.SearchQuery.NumericRangeQuery.prototype.</span>toJSON ()](#apidoc.element.couchbase.SearchQuery.NumericRangeQuery.prototype.toJSON)
- description and source-code
```javascript
toJSON = function () {
  return this.data;
}
```
- example usage
```shell
...
 */
BooleanQuery.prototype.toJSON = function() {
var out = {};
if (this.data.must) {
  out.must = this.data.must;
}
if (this.data.should) {
  var shouldData = this.data.should.toJSON();
  shouldData.min = this.shouldMin;
  out.should = shouldData;
}
if (this.data.must_not) {
  out.must_not = this.data.must_not;
}
return out;
...
```



# <a name="apidoc.module.couchbase.SearchQuery.PhraseQuery"></a>[module couchbase.SearchQuery.PhraseQuery](#apidoc.module.couchbase.SearchQuery.PhraseQuery)

#### <a name="apidoc.element.couchbase.SearchQuery.PhraseQuery.PhraseQuery"></a>[function <span class="apidocSignatureSpan">couchbase.SearchQuery.</span>PhraseQuery (terms)](#apidoc.element.couchbase.SearchQuery.PhraseQuery.PhraseQuery)
- description and source-code
```javascript
function PhraseQuery(terms) {
  this.data = {
    terms: terms
  };
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.couchbase.SearchQuery.PhraseQuery.prototype"></a>[module couchbase.SearchQuery.PhraseQuery.prototype](#apidoc.module.couchbase.SearchQuery.PhraseQuery.prototype)

#### <a name="apidoc.element.couchbase.SearchQuery.PhraseQuery.prototype.boost"></a>[function <span class="apidocSignatureSpan">couchbase.SearchQuery.PhraseQuery.prototype.</span>boost (boost)](#apidoc.element.couchbase.SearchQuery.PhraseQuery.prototype.boost)
- description and source-code
```javascript
boost = function (boost) {
  this.data.boost = boost;
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.SearchQuery.PhraseQuery.prototype.field"></a>[function <span class="apidocSignatureSpan">couchbase.SearchQuery.PhraseQuery.prototype.</span>field (field)](#apidoc.element.couchbase.SearchQuery.PhraseQuery.prototype.field)
- description and source-code
```javascript
field = function (field) {
  this.data.field = field;
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.SearchQuery.PhraseQuery.prototype.toJSON"></a>[function <span class="apidocSignatureSpan">couchbase.SearchQuery.PhraseQuery.prototype.</span>toJSON ()](#apidoc.element.couchbase.SearchQuery.PhraseQuery.prototype.toJSON)
- description and source-code
```javascript
toJSON = function () {
  return this.data;
}
```
- example usage
```shell
...
 */
BooleanQuery.prototype.toJSON = function() {
var out = {};
if (this.data.must) {
  out.must = this.data.must;
}
if (this.data.should) {
  var shouldData = this.data.should.toJSON();
  shouldData.min = this.shouldMin;
  out.should = shouldData;
}
if (this.data.must_not) {
  out.must_not = this.data.must_not;
}
return out;
...
```



# <a name="apidoc.module.couchbase.SearchQuery.PrefixQuery"></a>[module couchbase.SearchQuery.PrefixQuery](#apidoc.module.couchbase.SearchQuery.PrefixQuery)

#### <a name="apidoc.element.couchbase.SearchQuery.PrefixQuery.PrefixQuery"></a>[function <span class="apidocSignatureSpan">couchbase.SearchQuery.</span>PrefixQuery (prefix)](#apidoc.element.couchbase.SearchQuery.PrefixQuery.PrefixQuery)
- description and source-code
```javascript
function PrefixQuery(prefix) {
  this.data = {
    prefix: prefix
  };
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.couchbase.SearchQuery.PrefixQuery.prototype"></a>[module couchbase.SearchQuery.PrefixQuery.prototype](#apidoc.module.couchbase.SearchQuery.PrefixQuery.prototype)

#### <a name="apidoc.element.couchbase.SearchQuery.PrefixQuery.prototype.boost"></a>[function <span class="apidocSignatureSpan">couchbase.SearchQuery.PrefixQuery.prototype.</span>boost (boost)](#apidoc.element.couchbase.SearchQuery.PrefixQuery.prototype.boost)
- description and source-code
```javascript
boost = function (boost) {
  this.data.boost = boost;
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.SearchQuery.PrefixQuery.prototype.field"></a>[function <span class="apidocSignatureSpan">couchbase.SearchQuery.PrefixQuery.prototype.</span>field (field)](#apidoc.element.couchbase.SearchQuery.PrefixQuery.prototype.field)
- description and source-code
```javascript
field = function (field) {
  this.data.field = field;
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.SearchQuery.PrefixQuery.prototype.toJSON"></a>[function <span class="apidocSignatureSpan">couchbase.SearchQuery.PrefixQuery.prototype.</span>toJSON ()](#apidoc.element.couchbase.SearchQuery.PrefixQuery.prototype.toJSON)
- description and source-code
```javascript
toJSON = function () {
  return this.data;
}
```
- example usage
```shell
...
 */
BooleanQuery.prototype.toJSON = function() {
var out = {};
if (this.data.must) {
  out.must = this.data.must;
}
if (this.data.should) {
  var shouldData = this.data.should.toJSON();
  shouldData.min = this.shouldMin;
  out.should = shouldData;
}
if (this.data.must_not) {
  out.must_not = this.data.must_not;
}
return out;
...
```



# <a name="apidoc.module.couchbase.SearchQuery.QueryStringQuery"></a>[module couchbase.SearchQuery.QueryStringQuery](#apidoc.module.couchbase.SearchQuery.QueryStringQuery)

#### <a name="apidoc.element.couchbase.SearchQuery.QueryStringQuery.QueryStringQuery"></a>[function <span class="apidocSignatureSpan">couchbase.SearchQuery.</span>QueryStringQuery (query)](#apidoc.element.couchbase.SearchQuery.QueryStringQuery.QueryStringQuery)
- description and source-code
```javascript
function QueryStringQuery(query) {
  this.data = {
    query: query
  };
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.couchbase.SearchQuery.QueryStringQuery.prototype"></a>[module couchbase.SearchQuery.QueryStringQuery.prototype](#apidoc.module.couchbase.SearchQuery.QueryStringQuery.prototype)

#### <a name="apidoc.element.couchbase.SearchQuery.QueryStringQuery.prototype.boost"></a>[function <span class="apidocSignatureSpan">couchbase.SearchQuery.QueryStringQuery.prototype.</span>boost (boost)](#apidoc.element.couchbase.SearchQuery.QueryStringQuery.prototype.boost)
- description and source-code
```javascript
boost = function (boost) {
  this.data.boost = boost;
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.SearchQuery.QueryStringQuery.prototype.toJSON"></a>[function <span class="apidocSignatureSpan">couchbase.SearchQuery.QueryStringQuery.prototype.</span>toJSON ()](#apidoc.element.couchbase.SearchQuery.QueryStringQuery.prototype.toJSON)
- description and source-code
```javascript
toJSON = function () {
  return this.data;
}
```
- example usage
```shell
...
 */
BooleanQuery.prototype.toJSON = function() {
var out = {};
if (this.data.must) {
  out.must = this.data.must;
}
if (this.data.should) {
  var shouldData = this.data.should.toJSON();
  shouldData.min = this.shouldMin;
  out.should = shouldData;
}
if (this.data.must_not) {
  out.must_not = this.data.must_not;
}
return out;
...
```



# <a name="apidoc.module.couchbase.SearchQuery.RegexpQuery"></a>[module couchbase.SearchQuery.RegexpQuery](#apidoc.module.couchbase.SearchQuery.RegexpQuery)

#### <a name="apidoc.element.couchbase.SearchQuery.RegexpQuery.RegexpQuery"></a>[function <span class="apidocSignatureSpan">couchbase.SearchQuery.</span>RegexpQuery (regexp)](#apidoc.element.couchbase.SearchQuery.RegexpQuery.RegexpQuery)
- description and source-code
```javascript
function RegexpQuery(regexp) {
  this.data = {
    regexp: regexp
  };
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.couchbase.SearchQuery.RegexpQuery.prototype"></a>[module couchbase.SearchQuery.RegexpQuery.prototype](#apidoc.module.couchbase.SearchQuery.RegexpQuery.prototype)

#### <a name="apidoc.element.couchbase.SearchQuery.RegexpQuery.prototype.boost"></a>[function <span class="apidocSignatureSpan">couchbase.SearchQuery.RegexpQuery.prototype.</span>boost (boost)](#apidoc.element.couchbase.SearchQuery.RegexpQuery.prototype.boost)
- description and source-code
```javascript
boost = function (boost) {
  this.data.boost = boost;
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.SearchQuery.RegexpQuery.prototype.field"></a>[function <span class="apidocSignatureSpan">couchbase.SearchQuery.RegexpQuery.prototype.</span>field (field)](#apidoc.element.couchbase.SearchQuery.RegexpQuery.prototype.field)
- description and source-code
```javascript
field = function (field) {
  this.data.field = field;
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.SearchQuery.RegexpQuery.prototype.toJSON"></a>[function <span class="apidocSignatureSpan">couchbase.SearchQuery.RegexpQuery.prototype.</span>toJSON ()](#apidoc.element.couchbase.SearchQuery.RegexpQuery.prototype.toJSON)
- description and source-code
```javascript
toJSON = function () {
  return this.data;
}
```
- example usage
```shell
...
 */
BooleanQuery.prototype.toJSON = function() {
var out = {};
if (this.data.must) {
  out.must = this.data.must;
}
if (this.data.should) {
  var shouldData = this.data.should.toJSON();
  shouldData.min = this.shouldMin;
  out.should = shouldData;
}
if (this.data.must_not) {
  out.must_not = this.data.must_not;
}
return out;
...
```



# <a name="apidoc.module.couchbase.SearchQuery.TermQuery"></a>[module couchbase.SearchQuery.TermQuery](#apidoc.module.couchbase.SearchQuery.TermQuery)

#### <a name="apidoc.element.couchbase.SearchQuery.TermQuery.TermQuery"></a>[function <span class="apidocSignatureSpan">couchbase.SearchQuery.</span>TermQuery (term)](#apidoc.element.couchbase.SearchQuery.TermQuery.TermQuery)
- description and source-code
```javascript
function TermQuery(term) {
  this.data = {
    term: term
  };
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.couchbase.SearchQuery.TermQuery.prototype"></a>[module couchbase.SearchQuery.TermQuery.prototype](#apidoc.module.couchbase.SearchQuery.TermQuery.prototype)

#### <a name="apidoc.element.couchbase.SearchQuery.TermQuery.prototype.boost"></a>[function <span class="apidocSignatureSpan">couchbase.SearchQuery.TermQuery.prototype.</span>boost (boost)](#apidoc.element.couchbase.SearchQuery.TermQuery.prototype.boost)
- description and source-code
```javascript
boost = function (boost) {
  this.data.boost = boost;
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.SearchQuery.TermQuery.prototype.field"></a>[function <span class="apidocSignatureSpan">couchbase.SearchQuery.TermQuery.prototype.</span>field (field)](#apidoc.element.couchbase.SearchQuery.TermQuery.prototype.field)
- description and source-code
```javascript
field = function (field) {
  this.data.field = field;
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.SearchQuery.TermQuery.prototype.fuzziness"></a>[function <span class="apidocSignatureSpan">couchbase.SearchQuery.TermQuery.prototype.</span>fuzziness (fuzziness)](#apidoc.element.couchbase.SearchQuery.TermQuery.prototype.fuzziness)
- description and source-code
```javascript
fuzziness = function (fuzziness) {
  this.data.fuzziness = fuzziness;
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.SearchQuery.TermQuery.prototype.prefixLength"></a>[function <span class="apidocSignatureSpan">couchbase.SearchQuery.TermQuery.prototype.</span>prefixLength (prefixLength)](#apidoc.element.couchbase.SearchQuery.TermQuery.prototype.prefixLength)
- description and source-code
```javascript
prefixLength = function (prefixLength) {
  this.data.prefix_length = prefixLength;
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.SearchQuery.TermQuery.prototype.toJSON"></a>[function <span class="apidocSignatureSpan">couchbase.SearchQuery.TermQuery.prototype.</span>toJSON ()](#apidoc.element.couchbase.SearchQuery.TermQuery.prototype.toJSON)
- description and source-code
```javascript
toJSON = function () {
  return this.data;
}
```
- example usage
```shell
...
 */
BooleanQuery.prototype.toJSON = function() {
var out = {};
if (this.data.must) {
  out.must = this.data.must;
}
if (this.data.should) {
  var shouldData = this.data.should.toJSON();
  shouldData.min = this.shouldMin;
  out.should = shouldData;
}
if (this.data.must_not) {
  out.must_not = this.data.must_not;
}
return out;
...
```



# <a name="apidoc.module.couchbase.SearchQuery.WildcardQuery"></a>[module couchbase.SearchQuery.WildcardQuery](#apidoc.module.couchbase.SearchQuery.WildcardQuery)

#### <a name="apidoc.element.couchbase.SearchQuery.WildcardQuery.WildcardQuery"></a>[function <span class="apidocSignatureSpan">couchbase.SearchQuery.</span>WildcardQuery (wildcard)](#apidoc.element.couchbase.SearchQuery.WildcardQuery.WildcardQuery)
- description and source-code
```javascript
function WildcardQuery(wildcard) {
  this.data = {
    wildcard: wildcard
  };
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.couchbase.SearchQuery.WildcardQuery.prototype"></a>[module couchbase.SearchQuery.WildcardQuery.prototype](#apidoc.module.couchbase.SearchQuery.WildcardQuery.prototype)

#### <a name="apidoc.element.couchbase.SearchQuery.WildcardQuery.prototype.boost"></a>[function <span class="apidocSignatureSpan">couchbase.SearchQuery.WildcardQuery.prototype.</span>boost (boost)](#apidoc.element.couchbase.SearchQuery.WildcardQuery.prototype.boost)
- description and source-code
```javascript
boost = function (boost) {
  this.data.boost = boost;
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.SearchQuery.WildcardQuery.prototype.field"></a>[function <span class="apidocSignatureSpan">couchbase.SearchQuery.WildcardQuery.prototype.</span>field (field)](#apidoc.element.couchbase.SearchQuery.WildcardQuery.prototype.field)
- description and source-code
```javascript
field = function (field) {
  this.data.field = field;
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.SearchQuery.WildcardQuery.prototype.toJSON"></a>[function <span class="apidocSignatureSpan">couchbase.SearchQuery.WildcardQuery.prototype.</span>toJSON ()](#apidoc.element.couchbase.SearchQuery.WildcardQuery.prototype.toJSON)
- description and source-code
```javascript
toJSON = function () {
  return this.data;
}
```
- example usage
```shell
...
 */
BooleanQuery.prototype.toJSON = function() {
var out = {};
if (this.data.must) {
  out.must = this.data.must;
}
if (this.data.should) {
  var shouldData = this.data.should.toJSON();
  shouldData.min = this.shouldMin;
  out.should = shouldData;
}
if (this.data.must_not) {
  out.must_not = this.data.must_not;
}
return out;
...
```



# <a name="apidoc.module.couchbase.SearchQuery.prototype"></a>[module couchbase.SearchQuery.prototype](#apidoc.module.couchbase.SearchQuery.prototype)

#### <a name="apidoc.element.couchbase.SearchQuery.prototype.addFacet"></a>[function <span class="apidocSignatureSpan">couchbase.SearchQuery.prototype.</span>addFacet (name, facet)](#apidoc.element.couchbase.SearchQuery.prototype.addFacet)
- description and source-code
```javascript
addFacet = function (name, facet) {
  if (!this.data.facets) {
    this.data.facets = {};
  }
  this.data.facets[name] = facet;
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.SearchQuery.prototype.consistency"></a>[function <span class="apidocSignatureSpan">couchbase.SearchQuery.prototype.</span>consistency (val)](#apidoc.element.couchbase.SearchQuery.prototype.consistency)
- description and source-code
```javascript
consistency = function (val) {
  if (!this.data.ctl) {
    this.data.ctl = {};
  }
  if (!this.data.ctl.consistency) {
    this.data.ctl.consistency = {};
  }

  if (this.data.ctl.consistency.level !== undefined) {
    throw new Error('consistency and consistentWith must be use exclusively.');
  }


  if (val === SearchQuery.Consistency.NOT_BOUNDED) {
    this.data.ctl.consistency.level = 'not_bounded';
  } else {
    throw new TypeError('invalid option passed.');
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.SearchQuery.prototype.consistentWith"></a>[function <span class="apidocSignatureSpan">couchbase.SearchQuery.prototype.</span>consistentWith (state)](#apidoc.element.couchbase.SearchQuery.prototype.consistentWith)
- description and source-code
```javascript
consistentWith = function (state) {
  if (!this.data.ctl) {
    this.data.ctl = {};
  }
  if (!this.data.ctl.consistency) {
    this.data.ctl.consistency = {};
  }

  if (this.data.ctl.consistency.level !== undefined) {
    throw new Error('consistency and consistentWith must be use exclusively.');
  }

  this.data.ctl.consistency.level = 'at_plus';
  this.data.ctl.consistency.vectors = state;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.SearchQuery.prototype.explain"></a>[function <span class="apidocSignatureSpan">couchbase.SearchQuery.prototype.</span>explain (explain)](#apidoc.element.couchbase.SearchQuery.prototype.explain)
- description and source-code
```javascript
explain = function (explain) {
  this.data.explain = explain;
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.SearchQuery.prototype.fields"></a>[function <span class="apidocSignatureSpan">couchbase.SearchQuery.prototype.</span>fields (fields)](#apidoc.element.couchbase.SearchQuery.prototype.fields)
- description and source-code
```javascript
fields = function (fields) {
  fields = cbutils.unpackArgs(fields, arguments);

  this.data.fields = fields;
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.SearchQuery.prototype.highlight"></a>[function <span class="apidocSignatureSpan">couchbase.SearchQuery.prototype.</span>highlight (style, fields)](#apidoc.element.couchbase.SearchQuery.prototype.highlight)
- description and source-code
```javascript
highlight = function (style, fields) {
  fields = cbutils.unpackArgs(fields, arguments, 1);

  if (!this.data.highlight) {
    this.data.highlight = {};
  }

  this.data.highlight.style = style;
  this.data.highlight.fields = fields;
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.SearchQuery.prototype.limit"></a>[function <span class="apidocSignatureSpan">couchbase.SearchQuery.prototype.</span>limit (limit)](#apidoc.element.couchbase.SearchQuery.prototype.limit)
- description and source-code
```javascript
limit = function (limit) {
  this.data.size = limit;
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.SearchQuery.prototype.skip"></a>[function <span class="apidocSignatureSpan">couchbase.SearchQuery.prototype.</span>skip (skip)](#apidoc.element.couchbase.SearchQuery.prototype.skip)
- description and source-code
```javascript
skip = function (skip) {
  this.data.from = skip;
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.SearchQuery.prototype.sort"></a>[function <span class="apidocSignatureSpan">couchbase.SearchQuery.prototype.</span>sort (fields)](#apidoc.element.couchbase.SearchQuery.prototype.sort)
- description and source-code
```javascript
sort = function (fields) {
  fields = cbutils.unpackArgs(fields, arguments);

  this.data.sort = fields;
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.SearchQuery.prototype.timeout"></a>[function <span class="apidocSignatureSpan">couchbase.SearchQuery.prototype.</span>timeout (timeout)](#apidoc.element.couchbase.SearchQuery.prototype.timeout)
- description and source-code
```javascript
timeout = function (timeout) {
  if (!this.data.ctl) {
    this.data.ctl = {};
  }

  this.data.ctl.timeout = timeout;
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.SearchQuery.prototype.toJSON"></a>[function <span class="apidocSignatureSpan">couchbase.SearchQuery.prototype.</span>toJSON ()](#apidoc.element.couchbase.SearchQuery.prototype.toJSON)
- description and source-code
```javascript
toJSON = function () {
  return this.data;
}
```
- example usage
```shell
...
 */
BooleanQuery.prototype.toJSON = function() {
var out = {};
if (this.data.must) {
  out.must = this.data.must;
}
if (this.data.should) {
  var shouldData = this.data.should.toJSON();
  shouldData.min = this.shouldMin;
  out.should = shouldData;
}
if (this.data.must_not) {
  out.must_not = this.data.must_not;
}
return out;
...
```



# <a name="apidoc.module.couchbase.SpatialQuery"></a>[module couchbase.SpatialQuery](#apidoc.module.couchbase.SpatialQuery)

#### <a name="apidoc.element.couchbase.SpatialQuery.SpatialQuery"></a>[function <span class="apidocSignatureSpan">couchbase.</span>SpatialQuery ()](#apidoc.element.couchbase.SpatialQuery.SpatialQuery)
- description and source-code
```javascript
function SpatialQuery() {
  this.ddoc = null;
  this.name = null;
  this.options = {};
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.SpatialQuery.from"></a>[function <span class="apidocSignatureSpan">couchbase.SpatialQuery.</span>from (ddoc, name)](#apidoc.element.couchbase.SpatialQuery.from)
- description and source-code
```javascript
from = function (ddoc, name) {
  return (new SpatialQuery()).from(ddoc, name);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.couchbase.SpatialQuery.prototype"></a>[module couchbase.SpatialQuery.prototype](#apidoc.module.couchbase.SpatialQuery.prototype)

#### <a name="apidoc.element.couchbase.SpatialQuery.prototype.bbox"></a>[function <span class="apidocSignatureSpan">couchbase.SpatialQuery.prototype.</span>bbox (bbox)](#apidoc.element.couchbase.SpatialQuery.prototype.bbox)
- description and source-code
```javascript
bbox = function (bbox) {
  this.options.bbox = bbox.join(',');
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.SpatialQuery.prototype.custom"></a>[function <span class="apidocSignatureSpan">couchbase.SpatialQuery.prototype.</span>custom (opts)](#apidoc.element.couchbase.SpatialQuery.prototype.custom)
- description and source-code
```javascript
custom = function (opts) {
  for (var i in opts) {
<span class="apidocCodeCommentSpan">    /* istanbul ignore else */
</span>    if (opts.hasOwnProperty(i)) {
      this.options[i] = opts[i];
    }
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.SpatialQuery.prototype.from"></a>[function <span class="apidocSignatureSpan">couchbase.SpatialQuery.prototype.</span>from (ddoc, name)](#apidoc.element.couchbase.SpatialQuery.prototype.from)
- description and source-code
```javascript
from = function (ddoc, name) {
  this.ddoc = ddoc;
  this.name = name;
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.SpatialQuery.prototype.limit"></a>[function <span class="apidocSignatureSpan">couchbase.SpatialQuery.prototype.</span>limit (limit)](#apidoc.element.couchbase.SpatialQuery.prototype.limit)
- description and source-code
```javascript
limit = function (limit) {
  this.options.limit = limit;
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.SpatialQuery.prototype.skip"></a>[function <span class="apidocSignatureSpan">couchbase.SpatialQuery.prototype.</span>skip (skip)](#apidoc.element.couchbase.SpatialQuery.prototype.skip)
- description and source-code
```javascript
skip = function (skip) {
  this.options.skip = skip;
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.SpatialQuery.prototype.stale"></a>[function <span class="apidocSignatureSpan">couchbase.SpatialQuery.prototype.</span>stale (stale)](#apidoc.element.couchbase.SpatialQuery.prototype.stale)
- description and source-code
```javascript
stale = function (stale) {
  if (stale === SpatialQuery.Update.BEFORE) {
    this.options.stale = 'false';
  } else if (stale === SpatialQuery.Update.NONE) {
    this.options.stale = 'ok';
  } else if (stale === SpatialQuery.Update.AFTER) {
    this.options.stale = 'update_after';
  } else {
    throw new TypeError('invalid option passed.');
  }
  return this;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.couchbase.ViewQuery"></a>[module couchbase.ViewQuery](#apidoc.module.couchbase.ViewQuery)

#### <a name="apidoc.element.couchbase.ViewQuery.ViewQuery"></a>[function <span class="apidocSignatureSpan">couchbase.</span>ViewQuery ()](#apidoc.element.couchbase.ViewQuery.ViewQuery)
- description and source-code
```javascript
function ViewQuery() {
  this.ddoc = null;
  this.name = null;
  this.options = {};
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.ViewQuery.Default"></a>[function <span class="apidocSignatureSpan">couchbase.ViewQuery.</span>Default ()](#apidoc.element.couchbase.ViewQuery.Default)
- description and source-code
```javascript
function ViewQuery() {
  this.ddoc = null;
  this.name = null;
  this.options = {};
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.ViewQuery.Spatial"></a>[function <span class="apidocSignatureSpan">couchbase.ViewQuery.</span>Spatial ()](#apidoc.element.couchbase.ViewQuery.Spatial)
- description and source-code
```javascript
function SpatialQuery() {
  this.ddoc = null;
  this.name = null;
  this.options = {};
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.ViewQuery.from"></a>[function <span class="apidocSignatureSpan">couchbase.ViewQuery.</span>from (ddoc, name)](#apidoc.element.couchbase.ViewQuery.from)
- description and source-code
```javascript
from = function (ddoc, name) {
  return (new ViewQuery()).from(ddoc, name);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.ViewQuery.fromSpatial"></a>[function <span class="apidocSignatureSpan">couchbase.ViewQuery.</span>fromSpatial (ddoc, name)](#apidoc.element.couchbase.ViewQuery.fromSpatial)
- description and source-code
```javascript
fromSpatial = function (ddoc, name) {
  return (new SpatialQuery()).from(ddoc, name);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.couchbase.ViewQuery.prototype"></a>[module couchbase.ViewQuery.prototype](#apidoc.module.couchbase.ViewQuery.prototype)

#### <a name="apidoc.element.couchbase.ViewQuery.prototype.custom"></a>[function <span class="apidocSignatureSpan">couchbase.ViewQuery.prototype.</span>custom (opts)](#apidoc.element.couchbase.ViewQuery.prototype.custom)
- description and source-code
```javascript
custom = function (opts) {
  for (var i in opts) {
<span class="apidocCodeCommentSpan">    /* istanbul ignore else */
</span>    if (opts.hasOwnProperty(i)) {
      this.options[i] = opts[i];
    }
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.ViewQuery.prototype.from"></a>[function <span class="apidocSignatureSpan">couchbase.ViewQuery.prototype.</span>from (ddoc, name)](#apidoc.element.couchbase.ViewQuery.prototype.from)
- description and source-code
```javascript
from = function (ddoc, name) {
  this.ddoc = ddoc;
  this.name = name;
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.ViewQuery.prototype.full_set"></a>[function <span class="apidocSignatureSpan">couchbase.ViewQuery.prototype.</span>full_set (full_set)](#apidoc.element.couchbase.ViewQuery.prototype.full_set)
- description and source-code
```javascript
full_set = function (full_set) {
  if (full_set === undefined || full_set) {
    this.options.full_set = 'true';
  } else {
    delete this.options.full_set;
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.ViewQuery.prototype.group"></a>[function <span class="apidocSignatureSpan">couchbase.ViewQuery.prototype.</span>group (group)](#apidoc.element.couchbase.ViewQuery.prototype.group)
- description and source-code
```javascript
group = function (group) {
  if (group === undefined || group === true) {
    this.options.group = true;
  } else if (group === false) {
    this.options.group = false;

  // For backwards compatibility
  } else if (group >= 0) {
    this.options.group = false;
    this.options.group_level = group;
  } else {
    this.options.group = true;
    this.options.group_level = 0;
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.ViewQuery.prototype.group_level"></a>[function <span class="apidocSignatureSpan">couchbase.ViewQuery.prototype.</span>group_level (group_level)](#apidoc.element.couchbase.ViewQuery.prototype.group_level)
- description and source-code
```javascript
group_level = function (group_level) {
  if (group_level !== undefined) {
    this.options.group_level = group_level;
  } else {
    delete this.options.group_level;
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.ViewQuery.prototype.id_range"></a>[function <span class="apidocSignatureSpan">couchbase.ViewQuery.prototype.</span>id_range (start, end)](#apidoc.element.couchbase.ViewQuery.prototype.id_range)
- description and source-code
```javascript
id_range = function (start, end) {
  this.options.startkey_docid = start;
  this.options.endkey_docid = end;
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.ViewQuery.prototype.include_docs"></a>[function <span class="apidocSignatureSpan">couchbase.ViewQuery.prototype.</span>include_docs (include_docs)](#apidoc.element.couchbase.ViewQuery.prototype.include_docs)
- description and source-code
```javascript
include_docs = function (include_docs) {
  if (include_docs === undefined || include_docs) {
    this.options.include_docs = 'true';
  } else {
    delete this.options.include_docs;
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.ViewQuery.prototype.key"></a>[function <span class="apidocSignatureSpan">couchbase.ViewQuery.prototype.</span>key (key)](#apidoc.element.couchbase.ViewQuery.prototype.key)
- description and source-code
```javascript
key = function (key) {
  this.options.key = JSON.stringify(key);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.ViewQuery.prototype.keys"></a>[function <span class="apidocSignatureSpan">couchbase.ViewQuery.prototype.</span>keys (keys)](#apidoc.element.couchbase.ViewQuery.prototype.keys)
- description and source-code
```javascript
keys = function (keys) {
  this.options.keys = JSON.stringify(keys);
  return this;
}
```
- example usage
```shell
...

var errMessage = null;
if (errData._) {
  // return errData._
  errMessage = errData._;
} else if (errData.errors) {
  // join values (messages) of all properties in errData.errors object
  errMessage = Object.keys(errData.errors).map(function(errKey) {
    return errData.errors[errKey];
  }).join(' ');
} else if (errData !== null && typeof errData === 'object') {
  // join values (messages) of all properties in errData object
  errMessage = Object.keys(errData).map(function(errKey) {
    return errData[errKey];
  }).join(' ');
...
```

#### <a name="apidoc.element.couchbase.ViewQuery.prototype.limit"></a>[function <span class="apidocSignatureSpan">couchbase.ViewQuery.prototype.</span>limit (limit)](#apidoc.element.couchbase.ViewQuery.prototype.limit)
- description and source-code
```javascript
limit = function (limit) {
  this.options.limit = limit;
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.ViewQuery.prototype.on_error"></a>[function <span class="apidocSignatureSpan">couchbase.ViewQuery.prototype.</span>on_error (mode)](#apidoc.element.couchbase.ViewQuery.prototype.on_error)
- description and source-code
```javascript
on_error = function (mode) {
  if (mode === ViewQuery.ErrorMode.CONTINUE) {
    this.options.on_error = 'continue';
  } else if (mode === ViewQuery.ErrorMode.STOP) {
    this.options.on_error = 'stop';
  } else {
    throw new TypeError('invalid option passed.');
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.ViewQuery.prototype.order"></a>[function <span class="apidocSignatureSpan">couchbase.ViewQuery.prototype.</span>order (order)](#apidoc.element.couchbase.ViewQuery.prototype.order)
- description and source-code
```javascript
order = function (order) {
  if (order === ViewQuery.Order.ASCENDING) {
    this.options.descending = false;
  } else if (order === ViewQuery.Order.DESCENDING) {
    this.options.descending = true;
  } else {
    throw new TypeError('invalid option passed.');
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.ViewQuery.prototype.range"></a>[function <span class="apidocSignatureSpan">couchbase.ViewQuery.prototype.</span>range (start, end, inclusive_end)](#apidoc.element.couchbase.ViewQuery.prototype.range)
- description and source-code
```javascript
range = function (start, end, inclusive_end) {
  this.options.startkey = JSON.stringify(start);
  this.options.endkey = JSON.stringify(end);
  if (inclusive_end) {
    this.options.inclusive_end = 'true';
  } else {
    delete this.options.inclusive_end;
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.ViewQuery.prototype.reduce"></a>[function <span class="apidocSignatureSpan">couchbase.ViewQuery.prototype.</span>reduce (reduce)](#apidoc.element.couchbase.ViewQuery.prototype.reduce)
- description and source-code
```javascript
reduce = function (reduce) {
  this.options.reduce = reduce;
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.ViewQuery.prototype.skip"></a>[function <span class="apidocSignatureSpan">couchbase.ViewQuery.prototype.</span>skip (skip)](#apidoc.element.couchbase.ViewQuery.prototype.skip)
- description and source-code
```javascript
skip = function (skip) {
  this.options.skip = skip;
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.ViewQuery.prototype.stale"></a>[function <span class="apidocSignatureSpan">couchbase.ViewQuery.prototype.</span>stale (stale)](#apidoc.element.couchbase.ViewQuery.prototype.stale)
- description and source-code
```javascript
stale = function (stale) {
  if (stale === ViewQuery.Update.BEFORE) {
    this.options.stale = 'false';
  } else if (stale === ViewQuery.Update.NONE) {
    this.options.stale = 'ok';
  } else if (stale === ViewQuery.Update.AFTER) {
    this.options.stale = 'update_after';
  } else {
    throw new TypeError('invalid option passed.');
  }
  return this;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.couchbase.auth"></a>[module couchbase.auth](#apidoc.module.couchbase.auth)

#### <a name="apidoc.element.couchbase.auth.ClassicAuthenticator"></a>[function <span class="apidocSignatureSpan">couchbase.auth.</span>ClassicAuthenticator (buckets, username, password)](#apidoc.element.couchbase.auth.ClassicAuthenticator)
- description and source-code
```javascript
function ClassicAuthenticator(buckets, username, password) {
  this.buckets = buckets;
  this.username = username;
  this.password = password;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.couchbase.binding"></a>[module couchbase.binding](#apidoc.module.couchbase.binding)

#### <a name="apidoc.element.couchbase.binding.CouchbaseImpl"></a>[function <span class="apidocSignatureSpan">couchbase.binding.</span>CouchbaseImpl ()](#apidoc.element.couchbase.binding.CouchbaseImpl)
- description and source-code
```javascript
function CouchbaseImpl() { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.binding.Error"></a>[function <span class="apidocSignatureSpan">couchbase.binding.</span>Error (message)](#apidoc.element.couchbase.binding.Error)
- description and source-code
```javascript
function CouchbaseError(message) {
  Error.call(this);
  Error.captureStackTrace(this, CouchbaseError);
  this.message = message;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.binding._setErrorClass"></a>[function <span class="apidocSignatureSpan">couchbase.binding.</span>_setErrorClass ()](#apidoc.element.couchbase.binding._setErrorClass)
- description and source-code
```javascript
function _setErrorClass() { [native code] }
```
- example usage
```shell
...
function CouchbaseError(message) {
  Error.call(this);
  Error.captureStackTrace(this, CouchbaseError);
  this.message = message;
}
util.inherits(CouchbaseError, Error);
CouchbaseError.prototype.name = 'CouchbaseError';
couchnode._setErrorClass(CouchbaseError);
couchnode.Error = CouchbaseError;

module.exports = couchnode;
...
```



# <a name="apidoc.module.couchbase.bucketmgr"></a>[module couchbase.bucketmgr](#apidoc.module.couchbase.bucketmgr)

#### <a name="apidoc.element.couchbase.bucketmgr.bucketmgr"></a>[function <span class="apidocSignatureSpan">couchbase.</span>bucketmgr (bucket)](#apidoc.element.couchbase.bucketmgr.bucketmgr)
- description and source-code
```javascript
function BucketManager(bucket) {
  this._bucket = bucket;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.couchbase.bucketmgr.prototype"></a>[module couchbase.bucketmgr.prototype](#apidoc.module.couchbase.bucketmgr.prototype)

#### <a name="apidoc.element.couchbase.bucketmgr.prototype._capiRequest"></a>[function <span class="apidocSignatureSpan">couchbase.bucketmgr.prototype.</span>_capiRequest (path, method, callback)](#apidoc.element.couchbase.bucketmgr.prototype._capiRequest)
- description and source-code
```javascript
_capiRequest = function (path, method, callback) {
  var b = this._bucket;
  b._maybeInvoke(b._capiRequest.bind(b), [path, method, callback]);
}
```
- example usage
```shell
...
 *
 * @since 2.0.0
 * @committed
 */
BucketManager.prototype.upsertDesignDocument = function(name, data, callback) {
  var path = '_design/' + name;

  this._capiRequest(path, 'PUT', function(err, httpReq) {
if (err) {
  return callback(err, null);
}

httpReq.on('response', _respRead(function(err, resp, data) {
  if (err) {
    return callback(err);
...
```

#### <a name="apidoc.element.couchbase.bucketmgr.prototype._checkIndexesActive"></a>[function <span class="apidocSignatureSpan">couchbase.bucketmgr.prototype.</span>_checkIndexesActive (checkList, callback)](#apidoc.element.couchbase.bucketmgr.prototype._checkIndexesActive)
- description and source-code
```javascript
_checkIndexesActive = function (checkList, callback) {
  this.getIndexes(function(err, indexes) {
    if (err) {
      callback(err, false);
      return;
    }

    var checkIndexes = [];
    for (var i = 0; i < indexes.length; i++) {
      if (checkList.indexOf(indexes[i].name) !== -1) {
        checkIndexes.push(indexes[i]);
      }
    }

    if (checkIndexes.length !== checkList.length) {
      callback(new Error('index not found'), false);
      return;
    }

    for (var j = 0; j < checkIndexes.length; ++j) {
      if (checkIndexes[j].state !== 'online') {
        callback(null, false);
        return;
      }
    }

    callback(null, true);
  });
}
```
- example usage
```shell
...
  if (options.timeout) {
    timeoutTime = Date.now() + options.timeout;
  }

  var self = this;
  var curInterval = 50;
  (function _checkIndexes() {
    self._checkIndexesActive(watchList, function(err, allActive) {
if (err) {
  callback(err);
  return;
}

if (allActive) {
  callback(null);
...
```

#### <a name="apidoc.element.couchbase.bucketmgr.prototype._createIndex"></a>[function <span class="apidocSignatureSpan">couchbase.bucketmgr.prototype.</span>_createIndex (options, callback)](#apidoc.element.couchbase.bucketmgr.prototype._createIndex)
- description and source-code
```javascript
_createIndex = function (options, callback) {
  if (!options.fields) {
    options.fields = [];
  }

  var qs = '';

  if (options.fields.length === 0) {
    qs += 'CREATE PRIMARY INDEX';
  } else {
    qs += 'CREATE INDEX';
  }
  if (options.name !== '') {
    qs += ' '' + options.name + ''';
  }
  qs += ' ON '' + this._bucket._name + ''';
  if (options.fields.length > 0) {
    qs += '(';
    for (var i = 0; i < options.fields.length; ++i) {
      if (i > 0) {
        qs += ', ';
      }
      qs += ''' + options.fields[i] + ''';
    }
    qs += ')';
  }
  if (options.deferred) {
    qs += ' WITH {"defer_build": true}';
  }

  this._bucket.query(N1qlQuery.fromString(qs), function(err, rows) {
    if (err) {
      if (err.message.indexOf('already exist') !== -1 &&
          options.ignoreIfExists) {
        callback(null);
        return;
      }

      callback(err);
      return;
    }

    callback(null);
  });
}
```
- example usage
```shell
...
    callback = arguments[2];
    options = undefined;
  }
  if (!options) {
    options = {};
  }

  return this._createIndex({
    name: indexName,
    fields: fields,
    ignoreIfExists: options.ignoreIfExists,
    deferred: options.deferred
  }, callback);
};
...
```

#### <a name="apidoc.element.couchbase.bucketmgr.prototype._dropIndex"></a>[function <span class="apidocSignatureSpan">couchbase.bucketmgr.prototype.</span>_dropIndex (options, callback)](#apidoc.element.couchbase.bucketmgr.prototype._dropIndex)
- description and source-code
```javascript
_dropIndex = function (options, callback) {
  var qs = '';

  if (!options.name) {
    qs += 'DROP PRIMARY INDEX '' + this._bucket._name + ''';
  } else {
    qs += 'DROP INDEX '' + this._bucket._name + ''.'' + options.name + ''';
  }

  this._bucket.query(N1qlQuery.fromString(qs), function(err) {
    if (err) {
      if (err.message.indexOf('not found') !== -1 &&
          options.ignoreIfNotExists) {
        callback(null);
        return;
      }

      callback(err);
      return;
    }

    callback(null);
  });
}
```
- example usage
```shell
...
   callback = arguments[1];
   options = undefined;
 }
 if (!options) {
   options = {};
 }

 return this._dropIndex({
   name: indexName,
   ignoreIfNotExists: options.ignoreIfNotExists
 }, callback);
};

/**
* Drops a primary GSI index
...
```

#### <a name="apidoc.element.couchbase.bucketmgr.prototype._mgmtRequest"></a>[function <span class="apidocSignatureSpan">couchbase.bucketmgr.prototype.</span>_mgmtRequest (path, method, callback)](#apidoc.element.couchbase.bucketmgr.prototype._mgmtRequest)
- description and source-code
```javascript
_mgmtRequest = function (path, method, callback) {
  var b = this._bucket;
  b._maybeInvoke(b._mgmtRequest.bind(b), [path, method, callback]);
}
```
- example usage
```shell
...
 *
 * @since 2.0.0
 * @committed
 */
BucketManager.prototype.getDesignDocuments = function(callback) {
  var path = 'pools/default/buckets/' + this._bucket._name + '/ddocs';

  this._mgmtRequest(path, 'GET', function(err, httpReq) {
if (err) {
  return callback(err, null);
}

httpReq.on('response', _respRead(function (err, resp, data) {
  if (err) {
    return callback(err);
...
```

#### <a name="apidoc.element.couchbase.bucketmgr.prototype.buildDeferredIndexes"></a>[function <span class="apidocSignatureSpan">couchbase.bucketmgr.prototype.</span>buildDeferredIndexes (callback)](#apidoc.element.couchbase.bucketmgr.prototype.buildDeferredIndexes)
- description and source-code
```javascript
buildDeferredIndexes = function (callback) {
  this.getIndexes(function(err, indexes) {
    if (err) {
      callback(err, null);
      return;
    }

    var deferredList = [];
    for (var i = 0; i < indexes.length; ++i) {
      if (indexes[i].state === 'deferred' || indexes[i].state === 'pending') {
        deferredList.push(indexes[i].name);
      }
    }

    if (deferredList.length === 0) {
      callback(null, deferredList);
      return;
    }

    var qs = '';
    qs += 'BUILD INDEX ON '' + this._bucket._name + ''(';
    for (var j = 0; j < deferredList.length; ++i) {
      if (j > 0) {
        qs += ', ';
      }
      qs += ''' + deferredList[j] + ''';
    }

    this._bucket.query(N1qlQuery.fromString(qs), function(err) {
      if (err) {
        callback(err, deferredList);
        return;
      }

      callback(null, deferredList);
    });
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.bucketmgr.prototype.createIndex"></a>[function <span class="apidocSignatureSpan">couchbase.bucketmgr.prototype.</span>createIndex (indexName, fields, options, callback)](#apidoc.element.couchbase.bucketmgr.prototype.createIndex)
- description and source-code
```javascript
createIndex = function (indexName, fields, options, callback) {
  if (options instanceof Function) {
    callback = arguments[2];
    options = undefined;
  }
  if (!options) {
    options = {};
  }

  return this._createIndex({
    name: indexName,
    fields: fields,
    ignoreIfExists: options.ignoreIfExists,
    deferred: options.deferred
  }, callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.bucketmgr.prototype.createPrimaryIndex"></a>[function <span class="apidocSignatureSpan">couchbase.bucketmgr.prototype.</span>createPrimaryIndex (options, callback)](#apidoc.element.couchbase.bucketmgr.prototype.createPrimaryIndex)
- description and source-code
```javascript
createPrimaryIndex = function (options, callback) {
  if (options instanceof Function) {
    callback = arguments[0];
    options = undefined;
  }
  if (!options) {
    options = {};
  }

  return this._createIndex({
    name: options.name,
    ignoreIfExists: options.ignoreIfExists,
    deferred: options.deferred
  }, callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.bucketmgr.prototype.dropIndex"></a>[function <span class="apidocSignatureSpan">couchbase.bucketmgr.prototype.</span>dropIndex (indexName, options, callback)](#apidoc.element.couchbase.bucketmgr.prototype.dropIndex)
- description and source-code
```javascript
dropIndex = function (indexName, options, callback) {
  if (options instanceof Function) {
    callback = arguments[1];
    options = undefined;
  }
  if (!options) {
    options = {};
  }

  return this._dropIndex({
    name: indexName,
    ignoreIfNotExists: options.ignoreIfNotExists
  }, callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.bucketmgr.prototype.dropPrimaryIndex"></a>[function <span class="apidocSignatureSpan">couchbase.bucketmgr.prototype.</span>dropPrimaryIndex (options, callback)](#apidoc.element.couchbase.bucketmgr.prototype.dropPrimaryIndex)
- description and source-code
```javascript
dropPrimaryIndex = function (options, callback) {
  if (options instanceof Function) {
    callback = arguments[1];
    options = undefined;
  }
  if (!options) {
    options = {};
  }

  return this._dropIndex({
    name: options.name,
    ignoreIfNotExists: options.ignoreIfNotExists
  }, callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.bucketmgr.prototype.flush"></a>[function <span class="apidocSignatureSpan">couchbase.bucketmgr.prototype.</span>flush (callback)](#apidoc.element.couchbase.bucketmgr.prototype.flush)
- description and source-code
```javascript
flush = function (callback) {
  var path = 'pools/default/buckets/' +
      this._bucket._name + '/controller/doFlush';

  this._mgmtRequest(path, 'POST', function(err, httpReq) {
    if (err) {
      return callback(err, null);
    }

    httpReq.on('response', _respRead(function(err, resp, data) {
      if (err) {
        return callback(err);
      }
      if (resp.statusCode !== 200) {
        var errData = null;
        try {
          errData = JSON.parse(data);
        } catch(e) {
        }

        if (!errData) {
          callback(new Error(
              'operation failed (' + resp.statusCode +')'), null);
          return;
        }

        callback(new Error(errData.reason), null);
        return;
      }
      callback(null, true);
    }));
    httpReq.end();
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.bucketmgr.prototype.getDesignDocument"></a>[function <span class="apidocSignatureSpan">couchbase.bucketmgr.prototype.</span>getDesignDocument (name, callback)](#apidoc.element.couchbase.bucketmgr.prototype.getDesignDocument)
- description and source-code
```javascript
getDesignDocument = function (name, callback) {
  var path = '_design/' + name;

  this._capiRequest(path, 'GET', function(err, httpReq) {
    if (err) {
      return callback(err, null);
    }

    httpReq.on('response', _respRead(function(err, resp, data) {
      if (err) {
        return callback(err);
      }
      var ddocData = JSON.parse(data);
      if (resp.statusCode !== 200) {
        var errData = null;
        try {
          errData = JSON.parse(data);
        } catch(e) {
        }

        if (!errData) {
          callback(new Error(
              'operation failed (' + resp.statusCode +')'), null);
          return;
        }

        callback(new Error(errData.reason), null);
        return;
      }
      callback(null, ddocData);
    }));
    httpReq.end();
  });
}
```
- example usage
```shell
...
 * @param callback
 *
 * @since 2.0.0
 * @committed
 */
BucketManager.prototype.insertDesignDocument = function(name, data, callback) {
  var self = this;
  this.getDesignDocument(name, function(err, res) {
    if (!err) {
      return callback(new Error('design document already exists'), null);
    }
    self.upsertDesignDocument(name, data, callback);
  });
};
...
```

#### <a name="apidoc.element.couchbase.bucketmgr.prototype.getDesignDocuments"></a>[function <span class="apidocSignatureSpan">couchbase.bucketmgr.prototype.</span>getDesignDocuments (callback)](#apidoc.element.couchbase.bucketmgr.prototype.getDesignDocuments)
- description and source-code
```javascript
getDesignDocuments = function (callback) {
  var path = 'pools/default/buckets/' + this._bucket._name + '/ddocs';

  this._mgmtRequest(path, 'GET', function(err, httpReq) {
    if (err) {
      return callback(err, null);
    }

    httpReq.on('response', _respRead(function (err, resp, data) {
      if (err) {
        return callback(err);
      }
      if (resp.statusCode !== 200) {
        var errData = null;
        try {
          errData = JSON.parse(data);
        } catch(e) {
        }

        if (!errData) {
          callback(new Error(
              'operation failed (' + resp.statusCode +')'), null);
          return;
        }

        callback(new Error(errData.reason), null);
        return;
      }
      var ddocData = JSON.parse(data);
      var ddocs = {};
      for (var i = 0; i < ddocData.rows.length; ++i) {
        var ddoc = ddocData.rows[i].doc;
        var ddocName = ddoc.meta.id.substr(8);
        ddocs[ddocName] = ddoc.json;
      }
      callback(null, ddocs);
    }));
    httpReq.end();
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.bucketmgr.prototype.getIndexes"></a>[function <span class="apidocSignatureSpan">couchbase.bucketmgr.prototype.</span>getIndexes (callback)](#apidoc.element.couchbase.bucketmgr.prototype.getIndexes)
- description and source-code
```javascript
getIndexes = function (callback) {
  var qs = 'SELECT 'indexes'.* FROM system:indexes';
  this._bucket.query(N1qlQuery.fromString(qs), function(err, rows) {
    if (err) {
      callback(err, null);
      return;
    }

    callback(null, rows);
  });
}
```
- example usage
```shell
...
 *
 * @param callback
 *
 * @since 2.1.6
 * @committed
 */
BucketManager.prototype.buildDeferredIndexes = function(callback) {
  this.getIndexes(function(err, indexes) {
if (err) {
  callback(err, null);
  return;
}

var deferredList = [];
for (var i = 0; i < indexes.length; ++i) {
...
```

#### <a name="apidoc.element.couchbase.bucketmgr.prototype.insertDesignDocument"></a>[function <span class="apidocSignatureSpan">couchbase.bucketmgr.prototype.</span>insertDesignDocument (name, data, callback)](#apidoc.element.couchbase.bucketmgr.prototype.insertDesignDocument)
- description and source-code
```javascript
insertDesignDocument = function (name, data, callback) {
  var self = this;
  this.getDesignDocument(name, function(err, res) {
    if (!err) {
      return callback(new Error('design document already exists'), null);
    }
    self.upsertDesignDocument(name, data, callback);
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.bucketmgr.prototype.removeDesignDocument"></a>[function <span class="apidocSignatureSpan">couchbase.bucketmgr.prototype.</span>removeDesignDocument (name, callback)](#apidoc.element.couchbase.bucketmgr.prototype.removeDesignDocument)
- description and source-code
```javascript
removeDesignDocument = function (name, callback) {
  var path = '_design/' + name;

  this._capiRequest(path, 'DELETE', function(err, httpReq) {
    if (err) {
      return callback(err, null);
    }

    httpReq.on('response', _respRead(function(err, resp, data) {
      if (err) {
        return callback(err);
      }
      if (resp.statusCode !== 200) {
        var errData = null;
        try {
          errData = JSON.parse(data);
        } catch(e) {
        }

        if (!errData) {
          callback(new Error(
              'operation failed (' + resp.statusCode +')'), null);
          return;
        }

        callback(new Error(errData.reason), null);
        return;
      }
      callback(null, true);
    }));
    httpReq.end();
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.bucketmgr.prototype.upsertDesignDocument"></a>[function <span class="apidocSignatureSpan">couchbase.bucketmgr.prototype.</span>upsertDesignDocument (name, data, callback)](#apidoc.element.couchbase.bucketmgr.prototype.upsertDesignDocument)
- description and source-code
```javascript
upsertDesignDocument = function (name, data, callback) {
  var path = '_design/' + name;

  this._capiRequest(path, 'PUT', function(err, httpReq) {
    if (err) {
      return callback(err, null);
    }

    httpReq.on('response', _respRead(function(err, resp, data) {
      if (err) {
        return callback(err);
      }
      if (resp.statusCode !== 201) {
        var errData = null;
        try {
          errData = JSON.parse(data);
        } catch(e) {
        }

        if (!errData) {
          callback(new Error(
              'operation failed (' + resp.statusCode +')'), null);
          return;
        }

        callback(new Error(errData.reason), null);
        return;
      }
      callback(null, true);
    }));
    httpReq.write(JSON.stringify(data, function(key, value) {
      if (value instanceof Function) {
        return value.toString();
      }
      return value;
    }));
    httpReq.end();
  });
}
```
- example usage
```shell
...
*/
BucketManager.prototype.insertDesignDocument = function(name, data, callback) {
 var self = this;
 this.getDesignDocument(name, function(err, res) {
   if (!err) {
     return callback(new Error('design document already exists'), null);
   }
   self.upsertDesignDocument(name, data, callback);
 });
};

/**
* Registers a design document to this bucket, overwriting any existing
* design document that was previously registered.
*
...
```

#### <a name="apidoc.element.couchbase.bucketmgr.prototype.watchIndexes"></a>[function <span class="apidocSignatureSpan">couchbase.bucketmgr.prototype.</span>watchIndexes (watchList, options, callback)](#apidoc.element.couchbase.bucketmgr.prototype.watchIndexes)
- description and source-code
```javascript
watchIndexes = function (watchList, options, callback) {
  if (options instanceof Function) {
    callback = arguments[1];
    options = undefined;
  }
  if (!options) {
    options = {};
  }

  var timeoutTime = 0;
  if (options.timeout) {
    timeoutTime = Date.now() + options.timeout;
  }

  var self = this;
  var curInterval = 50;
  (function _checkIndexes() {
    self._checkIndexesActive(watchList, function(err, allActive) {
      if (err) {
        callback(err);
        return;
      }

      if (allActive) {
        callback(null);
        return;
      }

      if (timeoutTime > 0 && Date.now() + curInterval > timeoutTime) {
        callback(new Error('timeout'));
        return;
      }

      setTimeout(function() {
        curInterval += 500;
        if (curInterval > 1000) {
          curInterval = 1000;
        }

        _checkIndexes();
      }, curInterval);
    });
  })();
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.couchbase.clustermgr"></a>[module couchbase.clustermgr](#apidoc.module.couchbase.clustermgr)

#### <a name="apidoc.element.couchbase.clustermgr.clustermgr"></a>[function <span class="apidocSignatureSpan">couchbase.</span>clustermgr (cluster, username, password)](#apidoc.element.couchbase.clustermgr.clustermgr)
- description and source-code
```javascript
function ClusterManager(cluster, username, password) {
  this._cluster = cluster;
  this._username = username;
  this._password = password;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.couchbase.clustermgr.prototype"></a>[module couchbase.clustermgr.prototype](#apidoc.module.couchbase.clustermgr.prototype)

#### <a name="apidoc.element.couchbase.clustermgr.prototype._mgmtRequest"></a>[function <span class="apidocSignatureSpan">couchbase.clustermgr.prototype.</span>_mgmtRequest (path, method, uses_qs)](#apidoc.element.couchbase.clustermgr.prototype._mgmtRequest)
- description and source-code
```javascript
_mgmtRequest = function (path, method, uses_qs) {
  var clusterHosts = this._cluster.dsnObj.hosts;
  var myHost = clusterHosts[Math.floor(Math.random()*clusterHosts.length)];
  var reqOpts = {
    hostname: myHost[0],
    port: myHost[1] ? myHost[1] : 8091,
    path: '/' + path,
    method: method,
    headers: {
      'Content-Type': (uses_qs ? 'application/x-www-form-urlencoded' :
        'application/json' )
    }
  };
  if (this._password) {
    reqOpts.auth = this._username + ':' + this._password;
  }
  return http.request(reqOpts);
}
```
- example usage
```shell
...
 *
 * @since 2.0.0
 * @committed
 */
BucketManager.prototype.getDesignDocuments = function(callback) {
  var path = 'pools/default/buckets/' + this._bucket._name + '/ddocs';

  this._mgmtRequest(path, 'GET', function(err, httpReq) {
if (err) {
  return callback(err, null);
}

httpReq.on('response', _respRead(function (err, resp, data) {
  if (err) {
    return callback(err);
...
```

#### <a name="apidoc.element.couchbase.clustermgr.prototype.createBucket"></a>[function <span class="apidocSignatureSpan">couchbase.clustermgr.prototype.</span>createBucket (name, opts, callback)](#apidoc.element.couchbase.clustermgr.prototype.createBucket)
- description and source-code
```javascript
createBucket = function (name, opts, callback) {
  var myOpts = {
    name: name,
    authType: 'sasl',
    bucketType: 'couchbase',
    ramQuotaMB: 100,
    replicaNumber: 1
  };
  for (var i in opts) {
    if (opts.hasOwnProperty(i)) {
      myOpts[i] = opts[i];
    }
  }

  var path = 'pools/default/buckets';

  var httpReq = this._mgmtRequest(path, 'POST', true);
  httpReq.on('response', _respRead(function (err, resp, data) {
    if (err) {
      callback(err);
      return;
    }

    err = _respParseError(resp, data);
    if (err) {
      callback(err);
      return;
    }

    callback(null, true);
  }));
  httpReq.write(qs.stringify(myOpts));
  httpReq.end();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.clustermgr.prototype.getUsers"></a>[function <span class="apidocSignatureSpan">couchbase.clustermgr.prototype.</span>getUsers (callback)](#apidoc.element.couchbase.clustermgr.prototype.getUsers)
- description and source-code
```javascript
getUsers = function (callback) {
  var httpReq = this._mgmtRequest('/settings/rbac/users', 'GET');
  httpReq.on('response', _respRead(function(err, resp, data) {
    if (err) {
      callback(err);
      return;
    }

    err = _respParseError(resp, data);
    if (err) {
      callback(err);
      return;
    }

    var users;
    try {
      users = JSON.parse(data);
    } catch (e) {
      err = e;
    }

    if (err) {
      callback(err, null);
      return;
    }

    callback(null, users);
  }));
  httpReq.end();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.clustermgr.prototype.listBuckets"></a>[function <span class="apidocSignatureSpan">couchbase.clustermgr.prototype.</span>listBuckets (callback)](#apidoc.element.couchbase.clustermgr.prototype.listBuckets)
- description and source-code
```javascript
listBuckets = function (callback) {
  var path = 'pools/default/buckets';

  var httpReq = this._mgmtRequest(path, 'GET');
  httpReq.on('response', _respRead(function(err, resp, data) {
    if (err) {
      callback(err);
      return;
    }

    err = _respParseError(resp, data);
    if (err) {
      callback(err);
      return;
    }

    var bucketInfo;
    try {
      bucketInfo = JSON.parse(data);
    } catch (e) {
      err = e;
    }

    if (err) {
      callback(err);
      return;
    }

    callback(null, bucketInfo);
  }));
  httpReq.end();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.clustermgr.prototype.removeBucket"></a>[function <span class="apidocSignatureSpan">couchbase.clustermgr.prototype.</span>removeBucket (name, callback)](#apidoc.element.couchbase.clustermgr.prototype.removeBucket)
- description and source-code
```javascript
removeBucket = function (name, callback) {
  var path = 'pools/default/buckets/' + name;

  var httpReq = this._mgmtRequest(path, 'DELETE');
  httpReq.on('response', _respRead(function(err, resp, data) {
    if (err) {
      callback(err);
      return;
    }

    err = _respParseError(resp, data);
    if (err) {
      callback(err);
      return;
    }

    callback(null, true);
  }));
  httpReq.end();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.clustermgr.prototype.removeUser"></a>[function <span class="apidocSignatureSpan">couchbase.clustermgr.prototype.</span>removeUser (userid, callback)](#apidoc.element.couchbase.clustermgr.prototype.removeUser)
- description and source-code
```javascript
removeUser = function (userid, callback) {
  var httpReq =
      this._mgmtRequest('/settings/rbac/users/builtin/' + userid, 'DELETE');
  httpReq.on('response', _respRead(function(err, resp, data) {
    if (err) {
      callback(err);
      return;
    }

    err = _respParseError(resp, data);
    if (err) {
      callback(err);
      return;
    }

    callback(null, true);
  }));
  httpReq.end();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.clustermgr.prototype.upsertUser"></a>[function <span class="apidocSignatureSpan">couchbase.clustermgr.prototype.</span>upsertUser (userid, settings, callback)](#apidoc.element.couchbase.clustermgr.prototype.upsertUser)
- description and source-code
```javascript
upsertUser = function (userid, settings, callback) {
  var httpReq =
      this._mgmtRequest('/settings/rbac/users/builtin/' + userid, 'PUT');
  httpReq.on('response', _respRead(function(err, resp, data) {
    if (err) {
      callback(err);
      return;
    }

    err = _respParseError(resp, data);
    if (err) {
      callback(err);
      return;
    }

    callback(null, true);
  }));
  var qsroles = [];
  for (var i = 0; i < settings.roles.length; ++i) {
    var role = settings.roles[i];
    qsroles.push(role.role + '[' + role.bucket_name + ']');
  }
  var qssettings = {
    name: settings.name,
    password: settings.password,
    roles: qsroles.join(',')
  };
  httpReq.setHeader('Content-Type', 'application/x-www-form-urlencoded');
  httpReq.write(qs.stringify(qssettings));
  httpReq.end();
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.couchbase.searchquery_queries"></a>[module couchbase.searchquery_queries](#apidoc.module.couchbase.searchquery_queries)

#### <a name="apidoc.element.couchbase.searchquery_queries.BooleanFieldQuery"></a>[function <span class="apidocSignatureSpan">couchbase.searchquery_queries.</span>BooleanFieldQuery (val)](#apidoc.element.couchbase.searchquery_queries.BooleanFieldQuery)
- description and source-code
```javascript
function BooleanFieldQuery(val) {
  this.data = {
    bool: val
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.searchquery_queries.BooleanQuery"></a>[function <span class="apidocSignatureSpan">couchbase.searchquery_queries.</span>BooleanQuery ()](#apidoc.element.couchbase.searchquery_queries.BooleanQuery)
- description and source-code
```javascript
function BooleanQuery() {
  this.data = {};
  this.shouldMin = undefined;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.searchquery_queries.ConjunctionQuery"></a>[function <span class="apidocSignatureSpan">couchbase.searchquery_queries.</span>ConjunctionQuery (queries)](#apidoc.element.couchbase.searchquery_queries.ConjunctionQuery)
- description and source-code
```javascript
function ConjunctionQuery(queries) {
  queries = cbutils.unpackArgs(queries, arguments);
  this.data = {
    conjuncts: []
  };
  this.and(queries);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.searchquery_queries.DateRangeQuery"></a>[function <span class="apidocSignatureSpan">couchbase.searchquery_queries.</span>DateRangeQuery ()](#apidoc.element.couchbase.searchquery_queries.DateRangeQuery)
- description and source-code
```javascript
function DateRangeQuery() {
  this.data = {};
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.searchquery_queries.DisjunctionQuery"></a>[function <span class="apidocSignatureSpan">couchbase.searchquery_queries.</span>DisjunctionQuery (queries)](#apidoc.element.couchbase.searchquery_queries.DisjunctionQuery)
- description and source-code
```javascript
function DisjunctionQuery(queries) {
  queries = cbutils.unpackArgs(queries);
  this.data = {
    disjuncts: []
  };
  this.or(queries);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.searchquery_queries.DocIdQuery"></a>[function <span class="apidocSignatureSpan">couchbase.searchquery_queries.</span>DocIdQuery (ids)](#apidoc.element.couchbase.searchquery_queries.DocIdQuery)
- description and source-code
```javascript
function DocIdQuery(ids) {
  ids = cbutils.unpackArgs(ids, arguments);
  this.data = {
    ids: []
  };
  this.addDocIds(ids);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.searchquery_queries.MatchAllQuery"></a>[function <span class="apidocSignatureSpan">couchbase.searchquery_queries.</span>MatchAllQuery ()](#apidoc.element.couchbase.searchquery_queries.MatchAllQuery)
- description and source-code
```javascript
function MatchAllQuery() {
  this.data = {
    match_all: null
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.searchquery_queries.MatchNoneQuery"></a>[function <span class="apidocSignatureSpan">couchbase.searchquery_queries.</span>MatchNoneQuery ()](#apidoc.element.couchbase.searchquery_queries.MatchNoneQuery)
- description and source-code
```javascript
function MatchNoneQuery() {
  this.data = {
    match_none: null
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.searchquery_queries.MatchPhraseQuery"></a>[function <span class="apidocSignatureSpan">couchbase.searchquery_queries.</span>MatchPhraseQuery (phrase)](#apidoc.element.couchbase.searchquery_queries.MatchPhraseQuery)
- description and source-code
```javascript
function MatchPhraseQuery(phrase) {
  this.data = {
    match_phrase: phrase
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.searchquery_queries.MatchQuery"></a>[function <span class="apidocSignatureSpan">couchbase.searchquery_queries.</span>MatchQuery (match)](#apidoc.element.couchbase.searchquery_queries.MatchQuery)
- description and source-code
```javascript
function MatchQuery(match) {
  this.data = {
    match: match
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.searchquery_queries.NumericRangeQuery"></a>[function <span class="apidocSignatureSpan">couchbase.searchquery_queries.</span>NumericRangeQuery ()](#apidoc.element.couchbase.searchquery_queries.NumericRangeQuery)
- description and source-code
```javascript
function NumericRangeQuery() {
  this.data = {};
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.searchquery_queries.PhraseQuery"></a>[function <span class="apidocSignatureSpan">couchbase.searchquery_queries.</span>PhraseQuery (terms)](#apidoc.element.couchbase.searchquery_queries.PhraseQuery)
- description and source-code
```javascript
function PhraseQuery(terms) {
  this.data = {
    terms: terms
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.searchquery_queries.PrefixQuery"></a>[function <span class="apidocSignatureSpan">couchbase.searchquery_queries.</span>PrefixQuery (prefix)](#apidoc.element.couchbase.searchquery_queries.PrefixQuery)
- description and source-code
```javascript
function PrefixQuery(prefix) {
  this.data = {
    prefix: prefix
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.searchquery_queries.QueryStringQuery"></a>[function <span class="apidocSignatureSpan">couchbase.searchquery_queries.</span>QueryStringQuery (query)](#apidoc.element.couchbase.searchquery_queries.QueryStringQuery)
- description and source-code
```javascript
function QueryStringQuery(query) {
  this.data = {
    query: query
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.searchquery_queries.RegexpQuery"></a>[function <span class="apidocSignatureSpan">couchbase.searchquery_queries.</span>RegexpQuery (regexp)](#apidoc.element.couchbase.searchquery_queries.RegexpQuery)
- description and source-code
```javascript
function RegexpQuery(regexp) {
  this.data = {
    regexp: regexp
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.searchquery_queries.TermQuery"></a>[function <span class="apidocSignatureSpan">couchbase.searchquery_queries.</span>TermQuery (term)](#apidoc.element.couchbase.searchquery_queries.TermQuery)
- description and source-code
```javascript
function TermQuery(term) {
  this.data = {
    term: term
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.searchquery_queries.WildcardQuery"></a>[function <span class="apidocSignatureSpan">couchbase.searchquery_queries.</span>WildcardQuery (wildcard)](#apidoc.element.couchbase.searchquery_queries.WildcardQuery)
- description and source-code
```javascript
function WildcardQuery(wildcard) {
  this.data = {
    wildcard: wildcard
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.searchquery_queries.boolean"></a>[function <span class="apidocSignatureSpan">couchbase.searchquery_queries.</span>boolean ()](#apidoc.element.couchbase.searchquery_queries.boolean)
- description and source-code
```javascript
boolean = function () {
  return new BooleanQuery();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.searchquery_queries.booleanField"></a>[function <span class="apidocSignatureSpan">couchbase.searchquery_queries.</span>booleanField (val)](#apidoc.element.couchbase.searchquery_queries.booleanField)
- description and source-code
```javascript
booleanField = function (val) {
  return new BooleanFieldQuery(val);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.searchquery_queries.conjuncts"></a>[function <span class="apidocSignatureSpan">couchbase.searchquery_queries.</span>conjuncts (queries)](#apidoc.element.couchbase.searchquery_queries.conjuncts)
- description and source-code
```javascript
conjuncts = function (queries) {
  queries = cbutils.unpackArgs(queries, arguments);
  return new ConjunctionQuery(queries);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.searchquery_queries.dateRange"></a>[function <span class="apidocSignatureSpan">couchbase.searchquery_queries.</span>dateRange ()](#apidoc.element.couchbase.searchquery_queries.dateRange)
- description and source-code
```javascript
dateRange = function () {
  return new DateRangeQuery();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.searchquery_queries.disjuncts"></a>[function <span class="apidocSignatureSpan">couchbase.searchquery_queries.</span>disjuncts (queries)](#apidoc.element.couchbase.searchquery_queries.disjuncts)
- description and source-code
```javascript
disjuncts = function (queries) {
  queries = cbutils.unpackArgs(queries, arguments);
  return new DisjunctionQuery(queries);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.searchquery_queries.docIds"></a>[function <span class="apidocSignatureSpan">couchbase.searchquery_queries.</span>docIds (ids)](#apidoc.element.couchbase.searchquery_queries.docIds)
- description and source-code
```javascript
docIds = function (ids) {
  ids = cbutils.unpackArgs(ids, arguments);
  return new DocIdQuery(ids);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.searchquery_queries.match"></a>[function <span class="apidocSignatureSpan">couchbase.searchquery_queries.</span>match (match)](#apidoc.element.couchbase.searchquery_queries.match)
- description and source-code
```javascript
match = function (match) {
  return new MatchQuery(match);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.searchquery_queries.matchAll"></a>[function <span class="apidocSignatureSpan">couchbase.searchquery_queries.</span>matchAll ()](#apidoc.element.couchbase.searchquery_queries.matchAll)
- description and source-code
```javascript
matchAll = function () {
  return new MatchAllQuery();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.searchquery_queries.matchNone"></a>[function <span class="apidocSignatureSpan">couchbase.searchquery_queries.</span>matchNone ()](#apidoc.element.couchbase.searchquery_queries.matchNone)
- description and source-code
```javascript
matchNone = function () {
  return new MatchNoneQuery();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.searchquery_queries.matchPhrase"></a>[function <span class="apidocSignatureSpan">couchbase.searchquery_queries.</span>matchPhrase (phrase)](#apidoc.element.couchbase.searchquery_queries.matchPhrase)
- description and source-code
```javascript
matchPhrase = function (phrase) {
  return new MatchPhraseQuery(phrase);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.searchquery_queries.numericRange"></a>[function <span class="apidocSignatureSpan">couchbase.searchquery_queries.</span>numericRange ()](#apidoc.element.couchbase.searchquery_queries.numericRange)
- description and source-code
```javascript
numericRange = function () {
  return new NumericRangeQuery();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.searchquery_queries.phrase"></a>[function <span class="apidocSignatureSpan">couchbase.searchquery_queries.</span>phrase (terms)](#apidoc.element.couchbase.searchquery_queries.phrase)
- description and source-code
```javascript
phrase = function (terms) {
  return new PhraseQuery(terms);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.searchquery_queries.prefix"></a>[function <span class="apidocSignatureSpan">couchbase.searchquery_queries.</span>prefix (prefix)](#apidoc.element.couchbase.searchquery_queries.prefix)
- description and source-code
```javascript
prefix = function (prefix) {
  return new PrefixQuery(prefix);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.searchquery_queries.queryString"></a>[function <span class="apidocSignatureSpan">couchbase.searchquery_queries.</span>queryString (query)](#apidoc.element.couchbase.searchquery_queries.queryString)
- description and source-code
```javascript
queryString = function (query) {
  return new QueryStringQuery(query);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.searchquery_queries.regexp"></a>[function <span class="apidocSignatureSpan">couchbase.searchquery_queries.</span>regexp (regexp)](#apidoc.element.couchbase.searchquery_queries.regexp)
- description and source-code
```javascript
regexp = function (regexp) {
  return new RegexpQuery(regexp);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.searchquery_queries.term"></a>[function <span class="apidocSignatureSpan">couchbase.searchquery_queries.</span>term (term)](#apidoc.element.couchbase.searchquery_queries.term)
- description and source-code
```javascript
term = function (term) {
  return new TermQuery(term);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.couchbase.searchquery_queries.wildcard"></a>[function <span class="apidocSignatureSpan">couchbase.searchquery_queries.</span>wildcard (wildcard)](#apidoc.element.couchbase.searchquery_queries.wildcard)
- description and source-code
```javascript
wildcard = function (wildcard) {
  return new WildcardQuery(wildcard);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.couchbase.utils"></a>[module couchbase.utils](#apidoc.module.couchbase.utils)

#### <a name="apidoc.element.couchbase.utils.unpackArgs"></a>[function <span class="apidocSignatureSpan">couchbase.utils.</span>unpackArgs (first, args, first_index)](#apidoc.element.couchbase.utils.unpackArgs)
- description and source-code
```javascript
function unpackArgs(first, args, first_index) {
  if (!first_index) {
    first_index = 0;
  }
  if (!Array.isArray(first)) {
    first = [first];
    for (var i = first_index + 1; i < args.length; ++i) {
      first.push(args[i]);
    }
  }
  return first;
}
```
- example usage
```shell
...
/**
 * @constructor
 *
 * @private
 * @memberof SearchQuery
 */
function ConjunctionQuery(queries) {
  queries = cbutils.unpackArgs(queries, arguments);
  this.data = {
    conjuncts: []
  };
  this.and(queries);
}
SearchQuery.ConjunctionQuery = ConjunctionQuery;
...
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
