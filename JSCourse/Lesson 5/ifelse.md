## if/else
```js
let is23 = (x) => {
	if (x===23){
		return 42
	} else {
		return 43
	}
}
is23(32) // 43
is23(23) // 42

[22, 23, 24, 25].map(is23) // [43, 42, 43, 43]
```