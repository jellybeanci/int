# index

<a href="https://www.npmjs.com/package/@jellybeanci/index/"><img src="res/npm-banner.png" width="300" alt="npm"/></a>

Integer type caster module for JavaScript/TypeScript.

```bash
npm i @jellybeanci/index
```

### import module
```js
// ES6 Syntax
import {index} from "@jellybeanci/index";

// Commonjs Syntax
const {index} = require("@jellybeanci/index");

// Commonjs with custom name
const integer = require("@jellybeanci/index").index;
```
### usage

```js
const integerNumber = index(floatingPointNumber);

const parsedIntegerNumber = index(stringNumber);
```

### demo

```js
console.log(index(3.1415)); // 3

console.log(index(-6.2342)); // -6

console.log(index("25.3")); // 25

console.log(index("not a number")); // 0
```

### types
```ts
type intFunctionType = (numberValue: number | string) => number;
```