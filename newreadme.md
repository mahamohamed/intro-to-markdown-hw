# How to write an HTML Boilerplate

### HTML, the standard markup language for the web, structures content using tags. It defines the hierarchy of elements on a webpage, enabling the creation of structured and accessible web content. When combined with CSS for styling and JavaScript for interactivity, HTML forms the basis for modern web development.

![htmlcode]![alt text](image-1.png)
_1. HTML Boilerplate:_

```js
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Your Page Title</title>
</head>
<body>
<!-- Your content goes here -->
<script src="script.js"></script>
</body>
</html>
```

### The HTML boilerplate includes essential elements like <!DOCTYPE html>, <html>, <head>, and <body>, providing the basic structure for a webpage.

Tips highlight the importance of declaring the document type, setting character encoding, using the viewport meta tag for responsiveness, and defining a meaningful page title.

> Tips:
> DOCTYPE Declaration: Always start with `<!DOCTYPE html>` to declare the document type.
> Character Encoding: Set the character encoding with `<meta charset="UTF-8">.`
> Viewport Meta Tag: Include `<meta name="viewport" content="width=device-width, initial-scale=1.0">` for responsive design.
> Title: Define a meaningful `<title>` for your webpage.

_2-Linking HTML, CSS, and JavaScript:_

```js
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Your Page Title</title>
</head>
<body>
<!-- Your content goes here -->
<script src="script.js"></script>
</body>
</html>
```

- **HTML Boilerplate:**

### The HTML boilerplate includes essential elements like <!DOCTYPE html>, <html>, <head>, and <body>, providing the basic structure for a webpage.

> Tips highlight the importance of declaring the document type, setting character encoding, using the viewport meta tag for responsiveness, and defining a meaningful page title.

- **Linking Style CSS:**

### Demonstrates how to link an external CSS file using the <link> tag with the rel="stylesheet" attribute within the <head> section.

> Tips emphasize the placement of the <link> tag in the <head> section for proper styling of the content.

- **Linking JavaScript:**

### Shows how to link an external JavaScript file using the `<script> tag with the src attribute at the end of the <body> section.`

> Tips suggest placing the `<script> tag at the end of the <body> `for optimized page loading.
