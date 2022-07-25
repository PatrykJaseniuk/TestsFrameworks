# Jest Test Framework with TypeScript

[jest with typescript](https://jestjs.io/docs/en/typescript)

instal module `ts-jest`
``` bash
npm install --save-dev ts-jest
```

when you run test right now it will wont work.

config jest by adding to `jest.config.js` value:
```js
preset: 'ts-jest',
```
i have done it by calling:
```bash
npx ts-jest config:init
```
now run tests:
```bash
npx jest
```
or add to package.json script:
```json
"scripts": {
  "test": "jest"
}
```
and run tests:
```bash
npm test
```

## Test Coverage Badge

install:
 ```
 npm install --save jest-coverage-badges
 ```
[![borys](./coverage/badge-branches.svg)](./coverage/lcov-report/index.html)
