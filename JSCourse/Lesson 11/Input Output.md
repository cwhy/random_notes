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
    if(event.keyCode == 37) {
        alert('Left was pressed');
    }
    else if(event.keyCode == 39) {
        alert('Right was pressed');
    }
})
```

HTTP event
```javascript
fetch(url).then(
	response => response.json()
).then(data => 
  console.log(data)
).catch(() =>
  console.log("Booo")
)
```