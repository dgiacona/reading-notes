# Class 14 Notes

### **Transforms**

The transform property comes in two different settings, two-dimensional and three-dimensional. Each of these come with their own individual properties and values.

- Two-dimensional transforms work on the x and y axes, known as horizontal and vertical axes.
- Three-dimensional transforms work on both the x and y axes, as well as the z axis.

### **Transitions**
With CSS3 transitions you have the potential to alter the appearance and behavior of an element whenever a state change occurs, such as when it is hovered over, focused on, active, or targeted.

### **Noted Transitions**

1. **Fade In**
```html
.fade
{
        opacity:0.5;
}
.fade:hover
{
        opacity:1;
}
```

2. **Change Color**
```html
.color:hover
{
        background:#53a7ea;
}
```

3. **Grow**
```html
.grow:hover
{
        -webkit-transform: scale(1.3);
        -ms-transform: scale(1.3);
        transform: scale(1.3);
}
```

5. **Shrink**
```html
.shrink:hover
{
        -webkit-transform: scale(0.8);
        -ms-transform: scale(0.8);
        transform: scale(0.8);
}
```

6. **Rotate elements**
```html
.rotate:hover
{
        -webkit-transform: rotateZ(-30deg);
        -ms-transform: rotateZ(-30deg);
        transform: rotateZ(-30deg);
}
```

7. **Square to circle**
```html
.circle:hover
{
        border-radius:50%;
}
```

8. **3D shadow**
```html
.threed:hover
{
        box-shadow:
                1px 1px #53a7ea,
                2px 2px #53a7ea,
                3px 3px #53a7ea;
        -webkit-transform: translateX(-3px);
        transform: translateX(-3px);
}
```