# React Native Invariant
[![npm](https://img.shields.io/github/license/breeffy/react-native-invariant)](https://github.com/breeffy/react-native-invariant/blob/main/LICENSE) [![npm](https://img.shields.io/badge/types-included-blue)](https://www.npmjs.com/package/@gorhom/bottom-sheet)

`invariant` and `assert` functions with types for **React Native**.

## Overview

Two functions with the same signatures are provided. 

`invariant(condition, message, prefix)` and `assert(condition, message, prefix)`.

The only difference is in default `prefix` value.

**@param** `condition`, **type**: `any`, **description**: If it's `falsy` - exception will be thrown, otherwise TypeScript asserts condition. See [Assertion Functions](https://www.typescriptlang.org/docs/handbook/release-notes/typescript-3-7.html#assertion-functions).

**@param** `message`, **type**: `string | undefined`, **description**: Error message to use if exception will be thrown. Default is `""`.

**@param** `prefix`, **type**: `string | undefined`, **description**: Prefix string to use before error message if exception will be thrown. For `assert` default is `"[assert] "`, for `invariant` default is `"[invariant] "`.

## License
**react-native-invariant** is licensed under [Apache-2.0](LICENSE) license.

Copyright © 2021, [Victor Malov](https://github.com/likern).
