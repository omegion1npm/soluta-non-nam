# @omegion1npm/soluta-non-nam <sup>[![Version Badge][npm-version-svg]][package-url]</sup>

[![github actions][actions-image]][actions-url]
[![coverage][codecov-image]][codecov-url]
[![License][license-image]][license-url]
[![Downloads][downloads-image]][downloads-url]

[![npm badge][npm-badge-png]][package-url]

A simple list of possible Typed Array names.

## Example

```js
const assert = require('assert');

const names = require('@omegion1npm/soluta-non-nam');

assert(Array.isArray(names));
assert(names.every(name => (
    typeof name === 'string'
    && typeof globalThis[name] === 'function'
    && globalThis[name].name === name
)));
```

## Tests
Simply clone the repo, `npm install`, and run `npm test`

## Security

Please email [@ljharb](https://github.com/ljharb) or see https://tidelift.com/security if you have a potential security vulnerability to report.

[package-url]: https://npmjs.org/package/@omegion1npm/soluta-non-nam
[npm-version-svg]: https://versionbadg.es/ljharb/@omegion1npm/soluta-non-nam.svg
[deps-svg]: https://david-dm.org/ljharb/@omegion1npm/soluta-non-nam.svg
[deps-url]: https://david-dm.org/ljharb/@omegion1npm/soluta-non-nam
[dev-deps-svg]: https://david-dm.org/ljharb/@omegion1npm/soluta-non-nam/dev-status.svg
[dev-deps-url]: https://david-dm.org/ljharb/@omegion1npm/soluta-non-nam#info=devDependencies
[npm-badge-png]: https://nodei.co/npm/@omegion1npm/soluta-non-nam.png?downloads=true&stars=true
[license-image]: https://img.shields.io/npm/l/@omegion1npm/soluta-non-nam.svg
[license-url]: LICENSE
[downloads-image]: https://img.shields.io/npm/dm/@omegion1npm/soluta-non-nam.svg
[downloads-url]: https://npm-stat.com/charts.html?package=@omegion1npm/soluta-non-nam
[codecov-image]: https://codecov.io/gh/ljharb/@omegion1npm/soluta-non-nam/branch/main/graphs/badge.svg
[codecov-url]: https://app.codecov.io/gh/ljharb/@omegion1npm/soluta-non-nam/
[actions-image]: https://img.shields.io/endpoint?url=https://github-actions-badge-u3jn4tfpocch.runkit.sh/ljharb/@omegion1npm/soluta-non-nam
[actions-url]: https://github.com/omegion1npm/soluta-non-nam/actions
