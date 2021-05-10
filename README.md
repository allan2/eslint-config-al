# Al's ESLint Config

This is a config for React and TypeScript.
Based off of the [NextJS config](https://github.com/vercel/next.js/blob/canary/.eslintrc.json) with some modifications.


1. To install, run:
```
npm i -D eslint-config-al
```

2. In your `.eslintrc.js` file, add:
```js
{
  extends: 'eslint-config-al'
}
```

The file should look like:
```js
// index.js

modules.exports = {
  root: true,
  extends: 'eslint-config-al'  
}
```
