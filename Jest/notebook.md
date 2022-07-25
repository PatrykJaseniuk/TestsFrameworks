# Jest Tets Framework

[jest helloworld](https://jestjs.io/docs/getting-started)

## installing jest module

To install Jest run:
```bash
npm install --save-dev jest
```
# Adding code coverage raport

add to `jest.config.js` proper value. I done it by calling:
```bash
npx jest --init
```
and answer questions.
Don't use type script for jest.config.

# Runing tests
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
