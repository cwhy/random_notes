## Map
```js
let y = x => x + 1
let numArray = [3, 4, 5]
numArray.map(y)

// one line example:
[3, 4, 5].map(x => x + 1)
```

## Boolean
```js
1 === 1 // true
1 === 2 // false
```
## Filter
```js
let isEven = x => x/2 === parseInt(x/2)
let numArray = [3, 4, 5, 6]
let z = numArray.filter(isEven)
z[1]

// one line example:
[3, 4, 5, 6].filter(x => x/2 === parseInt(x/2))
```

## Reduce
```js
let numArray = [3, 4, 5]
let sum = (a, b) => a + b
numArray.reduce(sum, 0) // 12

// one line example:
[3, 4, 5].reduce((a, b) => a + b)
```