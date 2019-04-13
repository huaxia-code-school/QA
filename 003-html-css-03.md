# Styling HTML with CSS
## CSS stands for Cascading Style Sheets.
### 3 ways:
* Inline - by using the style attribute in HTML elements
* Internal - by using a `<style>` element in the `<head>` section
* External - by using an external CSS file

## Inline CSS
```
<h1 style="color:blue;">This is a Blue Heading</h1>
```

## Internal CSS (can reuse style/save typing)
```
<!DOCTYPE html>
<html>
<head>
<style>
body {background-color: powderblue;}
h1   {color: blue;}
p    {color: red;}
</style>
</head>
<body>

<h1>This is a heading</h1>
<p>This is a paragraph.</p>

</body>
</html>
```

## External CSS (separate: developers works on html, designers work on css)
```
<!DOCTYPE html>
<html>
<head>
  <link rel="stylesheet" href="styles.css">
</head>
<body>

<h1>This is a heading</h1>
<p>This is a paragraph.</p>

</body>
</html>
```
The `styles.css` file:
```
body {
  background-color: powderblue;
}
h1 {
  color: blue;
}
p {
  color: red;
}
```

## More css style
### Fonts
```
<!DOCTYPE html>
<html>
<head>
<style>
h1 {
  color: blue;
  font-family: verdana;
  font-size: 300%;
}
p  {
  color: red;
  font-family: courier;
  font-size: 160%;
}
</style>
</head>
<body>

<h1>This is a heading</h1>
<p>This is a paragraph.</p>

</body>
</html>
```

### Border
```
p {
  border: 1px solid powderblue;
}
```

### Padding (inside)
```
p {
  border: 1px solid powderblue;
  padding: 30px;
}
```

### Margin (outside)
```
p {
  border: 1px solid powderblue;
  margin: 50px;
}
```

### The id attribute and `#` selector
```
<p id="p01">I am different</p>
#p01 {
  color: blue;
}
```

### The class and `.` selector
```
<p class="error">I am different</p>
p.error {
  color: red;
}
```

### Tag selector
```
p {
  border: 1px solid powderblue;
  padding: 30px;
}
```
