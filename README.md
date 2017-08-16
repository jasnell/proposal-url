# WHATWG URL

Introduce the WHATWG `URL` and `URLSearchParams` APIs as intrinsic ECMAScript
objects.

## Motivation

Unify and standardize URL parsing and handling across ECMAScript environments.

*Note*: Node.js has introduced WHATWG compatible URL parsing as a stable feature in [`v8.0`](https://github.com/nodejs/node/blob/master/doc/changelogs/CHANGELOG_V8.md#8.0.0).

## Example

```js
const base = new URL('http://example.org/foo');
const url = new URL('bar', base);
```

## API

The API would be as defined by the
[WHATWG URL specification](https://url.spec.whatwg.org/#api).
