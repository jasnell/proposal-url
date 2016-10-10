# WHATWG URL

Introduce the WHATWG URL and URLSearchParams APIs as intrinsic ECMAScript
objects.

## Motivation

Unify and standardize URL parsing and handling across ECMAScript environments.

*Note*: Node.js will soon introduce WHATWG compatible URL parsing as an
experimental feature.

## Example

```js
const base = new URL('http://example.org/foo');
const url = new URL('bar', base);
```

## API

The API would be as defined by the
[WHATWG URL specification](https://url.spec.whatwg.org/#api).
