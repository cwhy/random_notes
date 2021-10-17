## Array helpers
Won't change the array:
- `map`
```js
let y = x => x + 1
let numArray = [3, 4, 5]
numArray.map(y)
```

- `filter`
```js
let isEven = x => x/2 === parseInt(x/2)
let numArray = [3, 4, 5, 6]
let z = numArray.filter(isEven)
z[1]
```

- `reduce`
```js
let numArray = [3, 4, 5]
let sum = (a, b) => a + b
numArray.reduce(sum, 0) // 12
```

- `join`
```js
let strArray = ["a", "b", "c"]
strArray.join("-") // "a-b-c"
```

Will change the array:
- `sort`
```js
let strArray = [3, 2, 4]
strArray.sort()
strArray // [2, 3, 4] 
```

- `reverse`
```js
let strArray = [3, 2, 4]
strArray.reverse()
strArray // [4, 2, 3] 
```
