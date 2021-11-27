## JS Recap
- Three way to evoke JS
  - `alert()`
  - `console.log()`
  - DOM
  ```js
  let name = new URL(document.URL).searchParams.get("name");
  document.querySelector('h1').innerHTML = "Hello " + name;
  ```
- Where to put js
	- `<script>`
- Trigger mechanism
	- Before loading: `<head>`
	- after loading:
		- EventListener
		```js
		document.addEventListener("DOMContentLoaded", function(event) {
			// Your code to run since DOM is loaded and ready
		});
		```
		- At the end of `<body>`
	- `onclick=`
- variables
  - `let/var`
  ```js
  let x = 3
  x // 3
  let y = x + 3
  y // 6
  ```
  - Variable rules
  ```js
  x = 0
  let XJD = x
  let 28dhs = x
  let as@df = x
  let df-34 = x
  let df_34 = x
  let d34 = x
  
  ```
- functions
  - `() => {}`
  ```js
  let y = (x) => {return x + 3}
  let y = (x) => x + 3
  let y = x => x + 3
  let y = function (x) {
	  return x + 3
  }
  function y(x) {
	  return x + 3
  }
  y(3) // 6
  y(-1) // 2
  
  let a = 12
  y(a) // 15
  let a = 22
  y(a) // 25
  ```
  - function assignment `let xxx = () => {}`
- arrays
  - assignment syntax
  - indexing
  ```js
	let listOfFruits = ["apple", "banana", "mayonnaise"]
	listOfFruits[0] // "apple"
	listOfFruits[1] // "banana"
	listOfFruits[2] // "mayonnaise"
	listOfFruits.length // 3
	let someNumbers = [1, 1, 2, 3, 5, 8]
  ```
- type
  - numbers
  	- basic math
		```js
		let x = 1
		let y = 2
		x + y // 3
		```
  - strings
  	- quotation in strings
		```js
		"This is an cat"
		'This is an cat'
		"I can't do it"
		'I can't do it'
		'I said "Hello"'
		```
  	- string concatentation
		```js
		let x = "1"
		let y = "2"
		x + y // "12"
		y.length // 1
		```
	- number/string conversion
		- implicit conversion (not recommended)
		```js
		"12" + 12 // "1212"
		+ "1212" // "1212"
		```
		- explicit conversion
			- `parseInt`
			```js
			let x = "12"
			x // "12"
			parseInt(x) // 12
			```
			- `parseFloat`
			```js
			let x = "12.75"
			x // "12.75"
			parseInt(x) // 12
			parseFloat(x) // 12.75
			```
			- `toString`
			```js
			let x = 12.75
			x // 12.75
			x.toString() // "12.75"
			```
			
- undefined/NaN
  ```js
  x10 // undefined
  parseInt("abc")
  ```