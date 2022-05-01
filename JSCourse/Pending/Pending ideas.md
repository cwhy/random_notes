Project 3:
- Flag emoji
```js
const getFlagEmoji = (countryCode) =>  
	String.fromCodePoint(...countryCode
	    .toUpperCase()
	    .split('')
	    .map(char =>  127397 + char.charCodeAt()))
```
- Border radius
- Box shadow