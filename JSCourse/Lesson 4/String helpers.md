## Helper String functions
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
let str = "This is an sentence"
str.replace("a", "aa")    // "This is a sentence"
```

- `trim`
```js
let str = "      This is an sentence    "
```

- `substring`
```js
let str = "Apple, Banana, Kiwi"
str.slice(7, 13)    // Banana
```