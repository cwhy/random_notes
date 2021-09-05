## HTML is a tree
For the code below
```html
<html>
<head>
	<title> SampleDocument </title>
</head>
<body>
<h1> An HTML Document </h1>
<p> This is a <i> simple </i> document </p>
</body>
</html>
```

The tree structure is:
![[HTMLStructure.png]]

## Attributes: IDs and class

```html
<div id="name-1" class="box"></div>
<div id="name-2" class="box"></div>
<div id="name-3" class="box"></div>
<style>
#name-1 {
	background: #123456;
}
.box {
	border: solid 2px gray;
	border-radius: 10px;
}
</style>
```