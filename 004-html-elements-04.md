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
<a href="https://en.wikipedia.org/wiki/Puppy" title="A cute puppy">
  <img src="pics/puppy.jpg">
</a>
```
* where shows the title?
* see image-as-link.html

# Images
```
<img src="pic_trulli.jpg" alt="Italian Trulli">
```
* relative path, full path, external link rule apply
* `alt` text shows when image are not available

### Set size
```
<img src="img_girl.jpg" alt="Girl in a jacket" style="width:500px;height:600px;">
```

### Set map
See image-map.html
```
<img src="pics/workplace.jpg" alt="Workplace" usemap="#workmap" width="400" height="379"/>

<map name="workmap">
  <area shape="rect" coords="34,44,270,350" alt="Computer" href="https://en.wikipedia.org/wiki/Computer" title="computer">
  <area shape="rect" coords="290,172,333,250" alt="Phone" href="https://en.wikipedia.org/wiki/Telephone" title="phone">
  <area shape="circle" coords="337,300,44" alt="Cup of coffee" href="https://en.wikipedia.org/wiki/Coffee" title= "coffee">
</map>
```

### Animated gif
```
<img src="pics/tenor.gif" alt="lol">
```