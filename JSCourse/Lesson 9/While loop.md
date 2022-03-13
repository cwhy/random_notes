### Syntax
```js
let x = 0
while (x < 5) {
  console.log(x)
  x = x + 1
}
// Will log 0, 1, 2, 3, 4 in separate lines in  console
```
### Examples
```js
let arr = "asfdasdfasdfasdfasdsfasdf".split("")
let x = 0
let counter = 0
while (x < arr.length) {
	x = x + 1
	if (arr[x] === "a") {
		counter = counter + 1
	}
}
```

#### Implement map with while
```js
let myMap = (arr, fn) => {
	let newArray = new Array
	let i = 0
	while (i < arr.length) {
		newArray[i] = fn(arr[i])
		i += 1
	}
}
let numArr = [3, 4, 5]
let y = x => x + 1

myMap(numArr, y) // [4, 5, 6]

```

### From 1 to 100
```js
let i = 0
let sum = 0
while (i < 100) {
	i = i + 1
	sum = sum + i
}
sum // 5050
```