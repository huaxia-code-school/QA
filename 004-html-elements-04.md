# HTML Elements

## Links
```
<a href="url">link text</a>
```
**url**
* relative path
* full path (path from root)
* full url or external
* **anchor link** see anchor-link.html for example

### Link Colors
```
<!DOCTYPE html>
<html>
<head>
<style>
a:link {
  color: green;
  background-color: transparent;
  text-decoration: none;
}
a:visited {
  color: pink;
  background-color: transparent;
  text-decoration: none;
}
a:hover {
  color: red;
  background-color: transparent;
  text-decoration: underline;
}
a:active {
  color: yellow;
  background-color: transparent;
  text-decoration: underline;
}
</style>
</head>
<body>

<h2>Link Colors</h2>

<p>You can change the default colors of links</p>

<a href="www.google.com" target="_blank">HTML Images</a> 
</body>
</html>
```

### Use image as Link
```
<a href="https://en.wikipedia.org/wiki/Puppy">
  <img src="pics/puppy.jpg">
</a>
```
see image-as-link.html

