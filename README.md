# Deprecated

このパッケージは非推奨となりました
今後は [anoare](https://github.com/ichiql/anoare) をご使用ください :)

This package has been deprecated.
Use https://github.com/ichiql/anoare instead.

---

# @ichiql/bigintize

```shell
pnpm add @ichiql/bigintize
npm install @ichiql/bigintize
yarn add @ichiql/bigintize
```

string や number を bigint に変換

Convert string, number, etc... to bigint

```js
import bigintize from '@ichiql/bigintize'

bigintize('123') // BigInt(123)
bigintize(123) // BigInt(123)
bigintize('$1,000') // BigInt(1000)
bigintize('invalid value') // throw error
bigintize('invalid value', BitInt(1)) // BitInt(1)
```
