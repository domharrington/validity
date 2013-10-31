# validity - Validation framework

[![NPM Details](https://nodei.co/npm/validity.png?stars&downloads)](https://npmjs.org/package/validity)

[![build status](https://api.travis-ci.org/serby/validity.png)](http://travis-ci.org/serby/validity)


An extendible validation framework for validating the properties of an object. Also contains a number of standard validators.

## Installation

      npm install validity

## Run Tests

      make tests

## Validators

Validity comes with some very basic example validators (required, email, integer, length and a few others). No more validators
will be added to this repo (in fact some of the more obscure ones may be removed in future). They should be built as individual
npm modules (with their own tests) so that applications can pick and choose which they use. Validators should be added to npm
repo with the `validity-` prefix so that people can find them with a quick [npm search](https://npmjs.org/search?q=validity-)
(or via the cli: `npm search validity-`).

The are a few validators that currently exist and can be used for reference:

- [validity-date-before-property](https://npmjs.org/package/validity-date-before-property)
- [validity-number-in-range](https://npmjs.org/package/validity-number-in-range)

## Credits
[Paul Serby](https://github.com/serby/) follow me on twitter [@serby](http://twitter.com/serby)

## Licence
Licenced under the [New BSD License](http://opensource.org/licenses/bsd-license.php)
