File Download
```javascript
const content = "Hello world"
window.open(
	encodeURI("data:text/txt;charset=utf-8," + content)
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