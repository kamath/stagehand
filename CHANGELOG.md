# @akamath426/stagehand

## 1.3.1

### Patch Changes

- [#2](https://github.com/kamath/stagehand/pull/2) [`97f0cc0`](https://github.com/kamath/stagehand/commit/97f0cc075d0d7899334d46e0c7679dda70a3418e) Thanks [@kamath](https://github.com/kamath)! - test

- [#227](https://github.com/browserbase/stagehand/pull/227) [`647eefd`](https://github.com/kamath/stagehand/commit/647eefd651852eec495faa1b8f4dbe6b1da17999) Thanks [@kamath](https://github.com/kamath)! - Fix debugDom still showing chunks when set to false

- [#222](https://github.com/browserbase/stagehand/pull/222) [`8dff026`](https://github.com/kamath/stagehand/commit/8dff02674df7a6448f2262c7e212b58c03be57bc) Thanks [@sameelarif](https://github.com/sameelarif)! - Streamline type definitions and fix existing typescript errors

## 1.3.0

### Minor Changes

- [#195](https://github.com/browserbase/stagehand/pull/195) [`87a6305`](https://github.com/browserbase/stagehand/commit/87a6305d9a2faf1ab5915965913bc14d5cc15772) Thanks [@kamath](https://github.com/kamath)! - - Adds structured and more standardized JSON logging
  - Doesn't init cache if `enableCaching` is false, preventing `tmp/.cache` from being created
  - Updates bundling for browser-side code to support NextJS and serverless

## 1.2.0

### Minor Changes

- [#179](https://github.com/browserbase/stagehand/pull/179) [`0031871`](https://github.com/browserbase/stagehand/commit/0031871d5a6d6180f272a68b88a8634e5a991785) Thanks [@navidkpr](https://github.com/navidkpr)! - Fixes:

  The last big change we pushed out, introduced a small regression. As a result, the gray outline showing the elements Stagehand is looking out is missing. This commit fixes that. We now process selectorMap properly now (using the updated type Record<number, string[]

  Improved the action prompt:

  Improved the structure
  Made it more straightforward
  Improved working for completed arg and prioritized precision over recall

## 1.1.0

### Minor Changes

- [`9206ec6`](https://github.com/browserbase/stagehand/commit/9206ec640b2d0af9170f0a31788ab1eac448357b) Thanks [@kamath](https://github.com/kamath)! - Connect to a minor session
