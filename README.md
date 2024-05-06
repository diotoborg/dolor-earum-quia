# @diotoborg/dolor-earum-quia <sup>[![Version Badge][npm-version-svg]][package-url]</sup>

[![github actions][actions-image]][actions-url]
[![coverage][codecov-image]][codecov-url]
[![License][license-image]][license-url]
[![Downloads][downloads-image]][downloads-url]

[![npm badge][npm-badge-png]][package-url]

A simple cache for a few of the JS Error constructors.

## Example

```js
const assert = require('assert');

const Base = require('@diotoborg/dolor-earum-quia');
const Eval = require('@diotoborg/dolor-earum-quia/eval');
const Range = require('@diotoborg/dolor-earum-quia/range');
const Ref = require('@diotoborg/dolor-earum-quia/ref');
const Syntax = require('@diotoborg/dolor-earum-quia/syntax');
const Type = require('@diotoborg/dolor-earum-quia/type');
const URI = require('@diotoborg/dolor-earum-quia/uri');

assert.equal(Base, Error);
assert.equal(Eval, EvalError);
assert.equal(Range, RangeError);
assert.equal(Ref, ReferenceError);
assert.equal(Syntax, SyntaxError);
assert.equal(Type, TypeError);
assert.equal(URI, URIError);
```

## Tests
Simply clone the repo, `npm install`, and run `npm test`

## Security

Please email [@ljharb](https://github.com/ljharb) or see https://tidelift.com/security if you have a potential security vulnerability to report.

[package-url]: https://npmjs.org/package/@diotoborg/dolor-earum-quia
[npm-version-svg]: https://versionbadg.es/ljharb/@diotoborg/dolor-earum-quia.svg
[deps-svg]: https://david-dm.org/ljharb/@diotoborg/dolor-earum-quia.svg
[deps-url]: https://david-dm.org/ljharb/@diotoborg/dolor-earum-quia
[dev-deps-svg]: https://david-dm.org/ljharb/@diotoborg/dolor-earum-quia/dev-status.svg
[dev-deps-url]: https://david-dm.org/ljharb/@diotoborg/dolor-earum-quia#info=devDependencies
[npm-badge-png]: https://nodei.co/npm/@diotoborg/dolor-earum-quia.png?downloads=true&stars=true
[license-image]: https://img.shields.io/npm/l/@diotoborg/dolor-earum-quia.svg
[license-url]: LICENSE
[downloads-image]: https://img.shields.io/npm/dm/@diotoborg/dolor-earum-quia.svg
[downloads-url]: https://npm-stat.com/charts.html?package=@diotoborg/dolor-earum-quia
[codecov-image]: https://codecov.io/gh/ljharb/@diotoborg/dolor-earum-quia/branch/main/graphs/badge.svg
[codecov-url]: https://app.codecov.io/gh/ljharb/@diotoborg/dolor-earum-quia/
[actions-image]: https://img.shields.io/endpoint?url=https://github-actions-badge-u3jn4tfpocch.runkit.sh/ljharb/@diotoborg/dolor-earum-quia
[actions-url]: https://github.com/diotoborg/dolor-earum-quia/actions
