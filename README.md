This package is a fork of the original package <https://www.npmjs.com/package/hugo-installer>.

## Major changes

rollup --> esbuild

copyfiles, rimraf --> shx

decompress 4.2.x --> github:XhmikosR/decompress#afe01ba

---

## memo

esbuild barner

```js
import { createRequire } from 'module';const require = createRequire(import.meta.url);
```
