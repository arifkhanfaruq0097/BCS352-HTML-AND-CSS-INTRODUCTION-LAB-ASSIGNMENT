STANDARD LAB PRACTICAL EXPERIMENT FORMAT

EXPERIMENT NO. 13

1. Experiment Title: Transitions and Animations

2. Aim:
Add a smooth colour change on hover and a tiny bounce animation.

3. Software / Tools Required:
Visual Studio Code, Chrome Browser

4. Theory:
transition property makes change smooth, transition: all 0.5s ease. :hover applies when mouse over. @keyframes defines animation steps, animation property runs it with duration and infinite loop.

5. Program / Queries / Commands:
hover-transition.html:
<!-- Name: Arif Khan | Roll No: 2510303124 | Ass: 13 -->
<!DOCTYPE html>
<html>
<head><title>Hover</title>
<style>
.btn{background:blue; color:white; padding:10px 20px; transition:background 0.5s ease;}
.btn:hover{background:red;}
</style>
</head>
<body><button class="btn">Hover Me</button></body>
</html>

bounce-animation.html:
<style>
.box{width:50px; height:50px; background:orange; animation:bounce 1s infinite;}
@keyframes bounce{0%,100%{transform:translateY(0);}50%{transform:translateY(-20px);}}
</style>
<div class="box"></div>

6. Input:
File names: hover-transition.html, bounce-animation.html

7. Output:
Button changes color smoothly from blue to red on hover. Box bounces up and down continuously. Screenshots in images folder.

8. Result:
Experiment performed successfully.

9. Viva-Voce Questions:
1. What is transition?
2. What is :hover?
3. What is @keyframes?
4. Difference between transition and animation?
5. What is transform translateY?