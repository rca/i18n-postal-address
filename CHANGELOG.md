# Changelog

## 0.6.1

> May 4, 2022

- Fixes an issue with the custom formats that prevented new countries from being
  used ([#38](https://github.com/joaocarmo/i18n-postal-address/issues/38))

## 0.6.0

> Apr 3, 2022

- Implements a string parser for the node version, check the documentation for
  more information

## 0.5.0

> Mar 28, 2022

- Adds support for a full or partial preset state to be passed to the
  constructor

## 0.4.3

> Mar 21, 2021

- Marked the arguments in the `output()` method as optional

## 0.4.2

> Jan 28, 2021

- Fixes the exported typings ([#17](https://github.com/joaocarmo/i18n-postal-address/issues/17))

## 0.4.1

> Jan 9, 2021

- Fixes the [subpath exports](https://nodejs.org/api/packages.html#packages_subpath_exports)
- Combined the typings into a single file

## 0.4.0

> Nov 12, 2020

- Added support for custom formats through the new API `.addFormat()`

## 0.3.0

> Oct 18, 2020

- Added transforms and definitions to append commas in certain formats
  ([#8](https://github.com/joaocarmo/i18n-postal-address/issues/8))

## 0.2.0

> Aug 17, 2020

- Added support for Method Chaining

## 0.1.0

> Jul 26, 2020

- Updated the dependencies to resolve some security vulnerabilities
- Updated the directory structure
- Added GitHub actions for CI/CD
- Converted to TypeScript

## 0.0.7-2 (no release)

> Aug 11, 2019

- Added more tests to _Jest_
- Added a to-do list
- Updated the dependencies to resolve security vulnerabilities:
  - [CVE-2019-10744](https://github.com/lodash/lodash/pull/4336)

## 0.0.7

> Jun 13, 2019

- Updated the dependencies to resolve security vulnerabilities:
  - [WS-2019-0064](https://github.com/wycats/handlebars.js/compare/v4.1.1...v4.1.2)
  - [WS-2019-0032](https://github.com/nodeca/js-yaml/issues/475)
  - [WS-2019-0063](https://github.com/nodeca/js-yaml/pull/480)
- Should fix [Issue \#2](https://github.com/joaocarmo/i18n-postal-address/issues/2)

## 0.0.6

> Sep 8, 2018

- Should fix [Issue \#1](https://github.com/joaocarmo/i18n-postal-address/issues/1)

## 0.0.5

> Jul 24, 2018

- Removed the method _setUseTransforms_ and added it as an option to _setFormat_
- Added _Jest_ for testing

## 0.0.4

> Jul 8, 2018

- Added an option to ignore transforms
- Fixed documentation

## 0.0.3

> Jul 8, 2018

- Added a capitalization transform to some attributes

## 0.0.2

> Jul 4, 2018

- Publish to [npm](https://www.npmjs.com) repository

## 0.0.1

> Jul 1, 2018

- Initial release
