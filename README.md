# JsonDumpReader

[![Build Status](https://secure.travis-ci.org/JeroenDeDauw/JsonDumpReader.png?branch=master)](http://travis-ci.org/JeroenDeDauw/JsonDumpReader)
[![Scrutinizer Code Quality](https://scrutinizer-ci.com/g/JeroenDeDauw/JsonDumpReader/badges/quality-score.png?b=master)](https://scrutinizer-ci.com/g/JeroenDeDauw/JsonDumpReader/?branch=master)
[![Code Coverage](https://scrutinizer-ci.com/g/JeroenDeDauw/JsonDumpReader/badges/coverage.png?b=master)](https://scrutinizer-ci.com/g/JeroenDeDauw/JsonDumpReader/?branch=master)
[![Dependency Status](https://www.versioneye.com/php/jeroen:json-dump-reader/dev-master/badge.svg)](https://www.versioneye.com/php/jeroen:json-dump-reader/dev-master)

[![Download count](https://poser.pugx.org/jeroen/json-dump-reader/d/total.png)](https://packagist.org/packages/jeroen/json-dump-reader)
[![Latest Stable Version](https://poser.pugx.org/jeroen/json-dump-reader/version.png)](https://packagist.org/packages/jeroen/json-dump-reader)

**JsonDumpReader** provides ways to read from and iterate through the [Wikibase](http://wikiba.se/)
entities in a Wikibase Repository JSON dump.

## Installation

To add this package as a local, per-project dependency to your project, simply add a
dependency on `jeroen/json-dump-reader` to your project's `composer.json` file.
Here is a minimal example of a `composer.json` file that just defines a dependency on
JsonDumpReader 1.0:

```js
{
    "require": {
        "jeroen/json-dump-reader": "1.0.*"
    }
}
```

## Release notes

### Version 0.1.0 (2014-10-22)

Initial release with

* `JsonDumpReader` to read entity JSON from the dump
* `JsonDumpIterator` to iterate through the dump as if it was a collection of `EntityDocument`