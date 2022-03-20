File Download
```javascript
const content = "Hello world"
window.open(
	encodeURI("data:text/csv;charset=utf-8," + content)
)
```

Keyboard event
```javascript
document.addEventListener('keydown', event => {
    if(event.code == "ArrowLeft") {
        alert('Left was pressed');
    }
    else if(event.code == "ArrowRight") {
        alert('Right was pressed');
    }
})
```

HTTP get request
```javascript
fetch(url).then(
	response => response.json()
).then(data => 
  console.log(data)
).catch(() =>
  console.log("No data received")
)
```

Modify CSS
```js
document.querySelector('#app').style.color = "black"
```