# Svelte Kit adapter-lambda-edge

Adapter for Svelte Kit that creates a ready to deploy CloudFront Lambda Edge function for dynamic server rendering.

## Usage

Add `"adapter-lambda-edge": "next"` to the `devDependencies` in your `package.json` and run `npm install`.

Then in your `svelte.config.js`:

```js
const lambdaEdge = require('adapter-lambda-edge');

module.exports = {
	kit: {
		...
		adapter: lambdaEdge()
	}
};
```
