STANDARD LAB PRACTICAL EXPERIMENT FORMAT

EXPERIMENT NO. 12

1. Experiment Title: Responsive Basics

2. Aim:
Make text smaller on small screens and change a layout to one column on small screens.

3. Software / Tools Required:
Visual Studio Code, Chrome Browser

4. Theory:
Media query @media checks screen size. max-width:600px applies CSS when screen is 600px or less. Responsive design adjusts layout for mobile and desktop.

5. Algorithm / Procedure:
1. Create folder Assignment 12
2. Create responsive-text.html with h1 32px and media query 600px to 20px
3. Create responsive-layout.html with two columns flex and media query to column direction
4. Open in browser and resize window to test
5. Take screenshots mobile and desktop

6. Program / Queries / Commands:
responsive-text.html:
<!-- Name: Arif Khan | Roll No: 2510303124 | Ass: 12 -->
<!DOCTYPE html>
<html>
<head><title>Responsive Text</title>
<style>
h1{font-size:32px;}
@media (max-width:600px){h1{font-size:20px;}}
</style>
</head>
<body><h1>Responsive Heading</h1></body>
</html>

responsive-layout.html:
<style>
.container{display:flex; gap:10px;}
.col{flex:1; background:lightblue; padding:20px;}
@media (max-width:600px){.container{flex-direction:column;}}
</style>
<div class="container"><div class="col">Column 1</div><div class="col">Column 2</div></div>

7. Input:
File names: responsive-text.html, responsive-layout.html

8. Output:
Desktop shows large text and two columns side by side. On mobile width below 600px text becomes small and columns become one column. Screenshots in images folder.

9. Result:
Experiment performed successfully.

10. Viva-Voce Questions:
1. What is media query?
2. What is max-width?
3. What is responsive design?
4. Difference between desktop and mobile layout?
5. How to make site responsive?