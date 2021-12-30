# int

<a href="https://www.npmjs.com/package/@jellybeanci/int/"><img src="res/npm-banner.png" width="300" alt="npm"/></a>

Integer type caster module for JavaScript/TypeScript.

```bash
npm i @jellybeanci/int
```

### import module
```js
// ES6 Syntax
import {int} from "@jellybeanci/int";

// Commonjs Syntax
const {int} = require("@jellybeanci/int");

// Commonjs with custom name
const integer = require("@jellybeanci/int").int;
```
### usage
```js
const integerNumber = int(floatingPointNumber);

const parsedIntegerNumber = int(stringNumber);
```

### demo
```js
console.log(int(3.1415)); // 3

console.log(int(-6.2342)); // -6

console.log(int("25.3")); // 25

console.log(int("not a number")); // 0
```

### types
```ts
type intFunctionType = (numberValue: number | string) => number;
```