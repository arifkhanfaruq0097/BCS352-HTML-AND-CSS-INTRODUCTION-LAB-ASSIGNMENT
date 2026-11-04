STANDARD LAB PRACTICAL EXPERIMENT FORMAT

EXPERIMENT NO. 9

1. Experiment Title: Box Model and Display

2. Aim:
Show the box model (content, padding, border, margin) and change display types.

3. Software / Tools Required:
Visual Studio Code, Chrome Browser

4. Theory:
Box model has content, padding, border, margin. padding is inside space, border is boundary, margin is outside space. display:block takes full width, display:inline takes only content width, inline-block allows width height.

5. Program / Queries / Commands:
box-model.html:
<!-- Name: Arif Khan | Roll No: 2510303124 | Ass: 9 -->
<!DOCTYPE html>
<html>
<head><title>Box Model</title>
<style>
.box{width:200px; padding:20px; border:5px solid black; margin:20px; background:lightgray;}
</style>
</head>
<body><div class="box">Box Content</div></body>
</html>

display.html:
<style>
.block{display:block; background:yellow;}
.inline{display:inline; background:lightblue;}
.inline-block{display:inline-block; width:100px; height:50px; background:lightgreen;}
</style>
<div class="block">Block</div>
<span class="inline">Inline 1</span>
<span class="inline">Inline 2</span>
<div class="inline-block">Inline-Block</div>

6. Input:
File names: box-model.html, display.html

7. Output:
box-model.html shows box with padding inside and margin outside with black border. display.html shows block on new line, inline side by side, inline-block with fixed size. Screenshots in images folder.

8. Result:
Experiment performed successfully.

9. Viva-Voce Questions:
1. What are parts of box model?
2. Difference between padding and margin?
3. Difference between block and inline?
4. What is inline-block?
5. What is border?