You can call function itself inside the same function

```js
let factorial = n => {
  if (n === 0) {return 1}
  else {return factorial(n - 1) * n}
}
```