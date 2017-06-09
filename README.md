# Repro for [Jest issue #3569](https://github.com/facebook/jest/issues/3569)

## Usage

`npm it`

Should produce something along the lines of:

```sh
 FAIL  __tests__/test.js
  ● Test suite failed to run

    Cannot find module 'internal/linkedlist' from 'core.js'

      at Resolver.resolveModule (node_modules/jest-resolve/build/index.js:179:17)
      at timers.js:4:11

Test Suites: 1 failed, 1 total
Tests:       0 total
Snapshots:   0 total
Time:        0.667s
Ran all test suites.
```
