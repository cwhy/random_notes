## Date and Time
```javascript
const unix_timestamp = 1549312452
const date = new Date(unix_timestamp * 1000)
const hours = date.getHours();
const minutes = "0" + date.getMinutes();
const seconds = "0" + date.getSeconds();

// Will display time in 10:30:23 format
var formattedTime = hours + ':' + minutes.substr(-2) + ':' + seconds.substr(-2);
```


## String short cut
```javascript
let soMany = 10;
let a = "This is " + soMany + " times easier"
// "This is 10 times easier!
let b = `This is ${soMany} times easier!`
// "This is 10 times easier!
```