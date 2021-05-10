# Al's ESLint Config

This is a config for React and TypeScript.
It's based off of the [Next.js config](https://github.com/vercel/next.js/blob/canary/.eslintrc.json) with some minor modifications.

The source code is available on GitHub [here](https://github.com/allan2/eslint-config-al).

Note: dep dependencies are not installed automatically. To install the dependencies, you can copy them from this package's [`package.json`](https://github.com/allan2/eslint-config-al/blob/main/package.json).


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

The file should look like this:
```js
// .eslintrc.js

module.exports = {
  root: true,
  extends: 'eslint-config-al'  
}
```

3. In `package.json`, add a line to command for linting. The file should look something like this:
```json
{
  "scripts": {
    "dev": "next dev",
    "build": "next build",
    "start": "next start",
    "lint": "eslint . --ext js,jsx,ts,tsx --max-warnings=0"
  },
}
```

4. To run the linter:
```
npm run lint
```
