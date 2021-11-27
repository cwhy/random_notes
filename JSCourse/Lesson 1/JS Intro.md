## How to insert JS in HTML

## 3 Ways of "Hello World" in JS
- `alert()`
- `console.log()`
- DOM
```js
let name = new URL(document.URL).searchParams.get("name");
document.querySelector('h1').innerHTML = "Hello " + name;
```

## DOM 
- selection
```js
var x = document.getElementById("mySelect");
```
- manipulation
```js
document.getElementById("one").firstChild.data = "two";
text.innerHTML = 'two'
var para = document.createElement('p');
para.appendChild(document.createTextNode('Hello, '));
var newtext = document.createTextNode(text),
  p1 = document.getElementById("p1");

p1.appendChild(newtext);
```

## JS basics
https://github.com/MarcoWorms/learn.js

## Use eval to make a calculator