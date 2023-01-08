# How to run Jest tests that use ES6 import syntax

1. Set the value of `type` to `"module"` in your package.json file to declare a ES6 module.

2. Set the value of `scripts.test` to `node --experimental-vm-modules node_modules/jest/bin/jest.js` instead of just `"jest"`.

3. Run `npm test`.
