

## `+=` `-=` `*=` `/=` shorthand
```js
let x = 1
x = x + 1
x += 1
x          // 2
```

```js
let x = 10

let y = 1
let s = ""
while (x > 1) {
	 x -= 1
	 y *= x
	 s += "y=" + y + ", "
}
```
## `const`: Constant that cannot be changed 
```js
const x = 1
x = x + 1 // Error
x += 1 // Error
```
