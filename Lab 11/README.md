STANDARD LAB PRACTICAL EXPERIMENT FORMAT

EXPERIMENT NO. 11

1. Experiment Title: Positioning and Sticky Header

2. Aim:
Pin a header to the top with position sticky and put a button at the bottom-right with position fixed.

3. Software / Tools Required:
Visual Studio Code, Chrome Browser

4. Theory:
position:sticky sticks when scrolling, top:0 keeps at top. position:fixed stays fixed at viewport, bottom and right sets position. z-index keeps it above other content.

5. Algorithm / Procedure:
1. Create folder Assignment 11
2. Create sticky-header.html with header position sticky top 0
3. Add long content to test scrolling
4. Create fixed-button.html with button position fixed bottom 20px right 20px
5. Open in browser and scroll to check
6. Take screenshots

6. Program / Queries / Commands:
sticky-header.html:
<!-- Name: Arif Khan | Roll No: 2510303124 | Ass: 11 -->
<!DOCTYPE html>
<html>
<head><title>Sticky</title>
<style>
header{position:sticky; top:0; background:yellow; padding:10px;}
.content{height:1000px; background:lightgray;}
</style>
</head>
<body>
<header>Sticky Header</header>
<div class="content">Scroll down... long content</div>
</body>
</html>

fixed-button.html:
<style>
.btn{position:fixed; bottom:20px; right:20px; background:blue; color:white; padding:10px; border:none;}
</style>
<button class="btn">Help</button>
<div style="height:1000px;">Long page content</div>

7. Input:
File names: sticky-header.html, fixed-button.html

8. Output:
Header stays at top when scrolling. Button stays at bottom right corner even after scrolling. Screenshots in images folder.

9. Result:
Experiment performed successfully.

10. Viva-Voce Questions:
1. Difference between sticky and fixed?
2. What is top, bottom, right?
3. What is z-index?
4. What is position relative?
5. What is position absolute?