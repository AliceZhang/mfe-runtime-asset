# Dynamic Module Federation Assets

Assets used by dynamic module federation repositories.

## Usage

**`index.html`**

```js
<script preload src="https://unpkg.com/regenerator-runtime@0.13.1/runtime.js"></script>
<script preload src="https://cdn.jsdelivr.net/gh/waldronmatt/dynamic-module-federation-assets/dist/bootstrap-entries.js"></script>
```

## Getting Started

See the [readme file](https://github.com/waldronmatt/dynamic-host-module-federation#guide---an-approach-to-module-federation-for-enterprise) for more information.

## Files

### dist/map.config.json

A JSON object containing a global reference of host and remote `entrypoint` URLs.

### dist/bootstrap.entries.js

A pre-build script that serves local and remote `entrypoints` dynamically at runtime.

**Note**: `src/bootstrap.entries.js` is an un-minified, non-transpiled version with comments.

## License

MIT
