# Nomenclature
- Comments
```js
// This is a comment
// let x = 3
```
- Variable
```js
let x = 3  // Declaration
console.log(x)
```
- Scope
```js
let x = 3 // Outer scope
{
	let y = 3   // Inner scope
	console.log(y) // Inner scope
}
console.log(x) // Outer scope
console.log(y) // Outer scope
```
- Function Declaration/Evaluation
```js
let plusOne = x => x + 1 // Declaration
plusOne(3) // Evaluation
```
- Types
	- numbers
		```js
		let x = 1
		```
	- boolean
		```js
		let x = true
		let y = (3 === 4) // y = false
		```
	- string
		```js
		let x = "1"
		```
	- array
		```js
		let x = [2, 3, 4]
		console.log(x.length) // 3
		console.log(x[2]) // 4
		```

JS execute sequence
```js
let a = 1
let b = a
let c = b + 1
let a = 3
let b = c + 2
let times2 = (b) => b * 2
let c = times2(b)
```
? a, b, c