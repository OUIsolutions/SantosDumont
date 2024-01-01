## Absolute Position
Absolute Position it's a position library, created for positional
elements on the screen in an extremely easy way.

## Running
for running , you just need to put the cdn script tag into your project.:
```html
  <script type="text/javascript"  src="https://cdn.jsdelivr.net/gh/OUIsolutions/AbsolutePosition@main/AbsolutePosition.js"></script>
```
## Basic Hello World

these it's the example  of a simple div
<br>

[Page of The Following Code](https://ouisolutions.github.io/AbsolutePosition/exemples/start.html)

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <script  
    type="text/javascript"
    src="https://cdn.jsdelivr.net/gh/OUIsolutions/AbsolutePosition@main/AbsolutePosition.js"></script>
</head>
<body>
        <div  APosition="$16:9(50px,100px,200px,300px" style="background-color: red;">

            Hello World
        </div>
</body>
</html>
```


## Understanding the Args 

Every time you type and **APosition** inside what ever tag , its became recognizable by the lib
after  you pass the following arguments:
#### #Example:
```html
    <div  APosition=" $16:9        ( 50px, 100px,200px, 300px)">
                      AspectRatio    Left, Top  ,Width, Height
```
#### Measures
you can use(px|%|vh|vw) as the measures (I will add more on the future)

## Operators 
With the Operators **+** and **-**  you can determine positions dynamically on the screen
#### Putting an div next to each other on Horizontal

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <script  
    type="text/javascript"
    src="https://cdn.jsdelivr.net/gh/OUIsolutions/AbsolutePosition@main/AbsolutePosition.js"></script>
</head>
<body>
        <div  APosition="$16:9(0px,100px,100px,100px" style="background-color: red;"></div>
        <div  APosition="$16:9(+100px,100px,100px,100px" style="background-color: #0033ff;"></div>
        <div  APosition="$16:9(+100px,100px,100px,100px" style="background-color: red;"></div>
        <div  APosition="$16:9(+100px,100px,100px,100px" style="background-color: #0033ff;"></div>

</body>
</html>
```
#### Putting an div next to each other on Vertical

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <script  
    type="text/javascript"
    src="https://cdn.jsdelivr.net/gh/OUIsolutions/AbsolutePosition@main/AbsolutePosition.js"></script>
</head>
<body>
        <div  APosition="$16:9(0px,0px,100px,100px" style="background-color: red;"></div>
        <div  APosition="$16:9(0px,+100px,100px,100px" style="background-color: #0033ff;"></div>
        <div  APosition="$16:9(0px,+100px,100px,100px" style="background-color: red;"></div>
        <div  APosition="$16:9(0px,+100px,100px,100px" style="background-color: #0033ff;"></div>

</body>
</html>
```





