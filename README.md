# DOM Manipulation Project

This project demonstrates how to manipulate HTML elements using the Document Object Model (DOM) in JavaScript.

## Project Structure

The project consists of an HTML file, a CSS file embedded in the HTML, and a JavaScript file.

### HTML

The HTML file contains a `div` element with the class `box`.

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=.boc, initial-scale=1.0">
    <title>Document</title>
    <style>
        .box{
            border : 2px solid black;
        }
    </style>
</head>
<body>
    <div class="box"></div>
    <script src="script.js"></script>
</body>
</html>

The JavaScript file contains code that selects the div element and modifies its properties.

let tempDiv = document.querySelector(".box");
tempDiv.innerHTML = "Hi geekster!";
tempDiv.style.backgroundColor = "yellow";
tempDiv.style.margin = '20px';
tempDiv.style.padding = '10px';
tempDiv.style.fontSize = '18px';
tempDiv.style.fontWeight = "bold";
tempDiv.style.height = "200px";
tempDiv.style.width = "300px";
