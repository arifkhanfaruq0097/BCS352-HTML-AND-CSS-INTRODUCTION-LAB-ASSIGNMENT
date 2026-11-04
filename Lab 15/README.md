STANDARD LAB PRACTICAL EXPERIMENT FORMAT

EXPERIMENT NO. 15

1. Experiment Title: CSS Grid Basics

2. Aim:
Use CSS Grid to make a 3-column layout and a simple page layout.

3. Software / Tools Required:
Visual Studio Code, Chrome Browser

4. Theory:
display:grid makes grid container. grid-template-columns defines columns, 1fr 1fr 1fr means 3 equal columns. gap gives space. Grid areas can make header footer sidebar layout.

5. Program / Queries / Commands:
grid-3col.html:
<!-- Name: Arif Khan | Roll No: 2510303124 | Ass: 15 -->
<!DOCTYPE html>
<html>
<head><title>3 Col</title>
<style>
.container{display:grid; grid-template-columns:1fr 1fr 1fr; gap:10px;}
.item{background:skyblue; padding:20px; text-align:center;}
</style>
</head>
<body>
<div class="container"><div class="item">1</div><div class="item">2</div><div class="item">3</div></div>
</body>
</html>

grid-layout.html:
<style>
.layout{display:grid; grid-template-columns:200px 1fr; grid-template-rows:60px 1fr 60px; grid-template-areas:"header header" "sidebar main" "footer footer"; height:100vh; gap:5px;}
.header{grid-area:header; background:yellow;}
.sidebar{grid-area:sidebar; background:lightgreen;}
.main{grid-area:main; background:lightblue;}
.footer{grid-area:footer; background:orange;}
</style>
<div class="layout">
<div class="header">Header</div><div class="sidebar">Sidebar</div><div class="main">Main</div><div class="footer">Footer</div>
</div>

6. Input:
File names: grid-3col.html, grid-layout.html

7. Output:
First file shows 3 equal columns in a row. Second file shows full page layout with header top, sidebar left, main right, footer bottom. Screenshots in images folder.

8. Result:
Experiment performed successfully.

9. Viva-Voce Questions:
1. What is CSS Grid?
2. What is grid-template-columns?
3. What is 1fr?
4. Difference between flex and grid?
5. What is grid-template-areas?