# My CSS Learning Journey

## Basic CSS
### 3 Ways to add CSS into HTML
```
1. Inline CSS
    Example <h1 style="color: #000; background-color: #f4f4f4;">Welcome<h1>. It will change text color to black and backround color
2. Internal CSS
    Use <style> tag in header and apply all css rule between that tag. Example
    <head>
    //...other tag
    <style>
        h1 { color: #000; background-color: #f4f4f}
    </style>
    </head>
3. External CSS - Best Practice
    Create css file e.g main.css apply all css rules inside the file and import css file into html file
    A. main.css
        h1 { color: #000; background-color: #f4f4f}
    B . index.html
        <head>
        //...other tag
            <link rel="stylesheet" href="main.css">
        </head>
```