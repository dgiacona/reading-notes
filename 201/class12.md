# Class 12 Notes

### **Controlling Sizes of Images in CSS**

You can control the size of an image using the width and heigh properties in CSS.

Setting Up 
```html
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="utf-8" />
        <title>Chart.js demo</title>
        <script src='Chart.min.js'></script>
    </head>
    <body>
    </body>
</html>
```

**Drawing a line chart**
To draw a line chart, the first thing we need to do is create a canvas element in our HTML in which Chart.js can draw our chart. So add this to the body of our HTML page:
```html
<canvas id="buyers" width="600" height="400"></canvas>
```
next step write a script that will retrieve the context of the canvas
```html
<script>
    var buyers = document.getElementById('buyers').getContext('2d');
    new Chart(buyers).Line(buyerData);
</script>
```


## Basic usage of canvas
At first sight a canvas looks like the img element, with the only clear difference being that it doesn't have the src and alt attributes. Indeed, the canvas element has only two attributes, width and height. These are both optional and can also be set using DOM properties. 

it can also be used to draw shapes and make grids to coordinate space.