### basic function 基本函数语法
```js
x => x + 1
(a, b) => a + b
```

### let = 赋值
```js
let x = 3
let something = 8.5
let y = x => x + 1
```
Same syntax applies to `var` / `const`

### // comments 注释
```js
let y = 0
// let y = 1
y // 0
```

### () as math brackets 括号
```js
let y = (x => x + 1)
let y = (x => (x + 1))
let x = 3 * (2 + 4)
```

### () as function application 函数调用
```js
let y = x => x + 1
y(2) // 3
(x => x + 1)(2) // 3
```

### "": string 字符串
```js
let x = "hi~"
let y = "how are you"
x + y  // "hi~how are you"
```

### []: Array literals 数组声明
```js
let arr1 = [2, 3, 4]
let arr2 = [2, 3, "4"]
```

### []: Array indexing 数组取值
```js
let arr1 = [2, 3, 4]
arr1[2] // 4
```

### []: Array destruction 数组分解
```js
let [x, y] = [1, 2]

x

y
```
### {}: code block 代码块
```js
let x = 4
if(x == 3) {
  alert("I see a 3!")
} else {
  alert("I did not see a 3!")
}

let plus = function(a, b) {
	return a + b
}
```

### {:}: object declaration 对象声明
```js
let exampleObject = {
  "property": "value",
  "anotherProperty": 2,
}
```

### .: object indexing 对象取值
```js
let exampleObject = {
  "property": "value",
  "anotherProperty": 2,
}
exampleObject.property  // "value"
```

re