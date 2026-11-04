STANDARD LAB PRACTICAL EXPERIMENT FORMAT

EXPERIMENT NO. 10

1. Experiment Title: Flexbox Basics

2. Aim:
Use Flexbox to put items in a row and in a row with wrapping.

3. Software / Tools Required:
Visual Studio Code, Chrome Browser

4. Theory:
display:flex makes container flex. flex-direction:row arranges items in row. flex-wrap:wrap allows items to go next line when no space. gap gives space between items.

5. Program / Queries / Commands:
flex-row.html:
<!-- Name: Arif Khan | Roll No: 2510303124 | Ass: 10 -->
<!DOCTYPE html>
<html>
<head><title>Flex Row</title>
<style>
.container{display:flex; flex-direction:row; gap:10px;}
.item{width:80px; height:80px; background:skyblue; text-align:center; line-height:80px;}
</style>
</head>
<body>
<div class="container"><div class="item">1</div><div class="item">2</div><div class="item">3</div></div>
</body>
</html>

flex-wrap.html:
<style>
.container{display:flex; flex-wrap:wrap; gap:10px;}
.item{width:100px; height:80px; background:lightgreen; text-align:center; line-height:80px;}
</style>
<div class="container">
<div class="item">1</div><div class="item">2</div><div class="item">3</div><div class="item">4</div><div class="item">5</div><div class="item">6</div>
</div>

6. Input:
File names: flex-row.html, flex-wrap.html

7. Output:
flex-row.html shows 3 boxes in one row. flex-wrap.html shows 6 boxes, when screen small they wrap to next line. Screenshots in images folder.

8. Result:
Experiment performed successfully.

9. Viva-Voce Questions:
1. What is flexbox?
2. What is difference between flex-direction row and column?
3. What is flex-wrap?
4. What is use of gap?
5. What is display flex?