## Types
When you see a `x`
- numbers 数字
	```js
	let x = 1
	```
- strings 字符串
	```js
	let x = "hello, 1"
	```
- array 数组
	``` js
	let x = [2, 3, 4]
	```
- boolean 布尔值
   ```js
   let x = true
   let x = 4 === 4
   ```
- functions 函数
	```js
	let x = y => y + 1
	```

## Conversions
- [[Easy String Number Conversion]]
- string to array
```js
"hello world".split(" ") // ["hello", "world"]
```
[[String helpers]]

- array to string
```js
["asd", "adsfa"].join("") // "asdadsfa"
```
[[Array helpers]]

- number to array
```js
let range = n => [...Array(n).keys()]

range(9)

```
[[range, map with index]]

- number/string/array to boolean
```js
3 === 3 //true
"3" === "3" //true
```
[[Boolean]]

- boolean to boolean
```js
true && true // true
```
[[Boolean]]


## Function input and output types

Input and output type of functions can be one of the types.

- `alert` inputs string, outputs nothing,
but there will be side effects.
- `console.log` inputs string, outputs nothing
- `x => x + 1` inputs number, output number
- `x => [x, 1, 2]` inputs Anything, output Array
- `[2, 3, 4].map` inputs function(input number, output anything), output Array
- `[2, 3, 4].filter` same as map
- `["3", "4"].join` inputs string, output string
