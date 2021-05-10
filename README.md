# Al's ESLint Config

This is a config for React and TypeScript.

1. To install, run:
```
npm i--save-dev eslint-config-al
```

2. In your `.eslintrc` file, add:
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