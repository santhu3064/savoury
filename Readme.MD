http://www.webdesigncourse.co/omnifood/index.php
https://ionicons.com/
https://css-tricks.com/snippets/html/glyphs/

# Inital setup

Always set margin and padding size to zero and box sizing to border box.

Set default font for all html intially  size,family weight and color

Add Normalize.css in vendors css.Normalize.css makes browsers render all elements more consistently and in line with modern standards. It precisely targets only the styles that need normalizing

```
* {
    margin: 0px;
    padding: 0px;
    box-sizing: border-box;
}

html {
    background-color: #ffffff;
    color: #555555;
    font-family: 'Lato', sans-serif;
    font-size: 20px;
    font-weight: 300;
    text-rendering: optimizeLegibility;
}
```