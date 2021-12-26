```js
const range = n => [...Array(n).keys()]
```

- `map` with index

```js
["a", "b", "c"].map((e, i) => i)
// [0, 1, 2]
```

- `filter` with index
```js
["a", "b", "c"].filter((e, i) => i==2)
// ["c"]
```