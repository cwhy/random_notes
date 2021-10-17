## Helper String functions
- `[]`
```js
let z = "123"
z[2] // 3
```

- `length`
```js
let z = "123"
z.length // 3
```
- `===`
```js
let text1 = "   hi    "
let text2 = "hi"
text1 === text2  // false
```
- `+`/`concat`
```js
let text1 = "hello"
let text2 = "world"
text1 + text2 // "helloworld"
```

- `split`
```js
let text = "hello world"
text.split(" ") // ["hello", "world"]
let arr = "123, 234, 3444, 23, 111".split(", ")
arr.filter((x)=>x.length === 3) // ["123", "234", "111"]

"abc".split("") //["a", "b", "c"]
```

- `toUpperCase`/`toLowerCase`
```js
let text1 = "Hello World!"
text1.toUpperCase() // "HELLO WORLD"
```

- `replace`
```js
let str = "This is an sentence and"
str.replace("an", "a")    // "This is a sentence and"
```

- `replaceAll`
```js
let str = "This is an sentence and"
str.replaceAll("an", "a")    // "This is a sentence ad"
```

- `trim`
```js
let str = "      This is an sentence    "
str.trim() // "This is an sentence"
```

- `slice`
```js
let str = "Apple, Banana, Kiwi"
str.slice(7, 13)    // Banana
```