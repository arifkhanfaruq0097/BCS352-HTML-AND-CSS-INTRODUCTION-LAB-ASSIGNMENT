STANDARD LAB PRACTICAL EXPERIMENT FORMAT

EXPERIMENT NO. 4

1. Experiment Title: Divs, Attributes and a Small Fix

2. Aim:
Group parts of a page with div elements, add a data attribute, and fix the errors in a broken page.

3. Software / Tools Required:
Visual Studio Code, Chrome Browser

4. Theory:
div is a container to group content. class and id are attributes to identify elements. data-* attributes store custom data not visible on page. HTML errors like missing closing tags must be fixed.

5. Algorithm / Procedure:
1. Create folder Assignment 4
2. Create layout.html with three divs class header, main, footer
3. Create attributes.html with div id profile and p with data-topic hobbies
4. Fix broken attendance code and save as attendance-fixed.html
5. Open all files in browser
6. Take screenshots

6. Program / Queries / Commands:
layout.html:
<!-- Name: Arif Khan | Roll No: 2510303124 | Ass: 4 -->
<div class="header">Header Section</div>
<div class="main">Main Content</div>
<div class="footer">Footer Section</div>

attributes.html:
<div id="profile"><p data-topic="hobbies">My hobbies are reading and coding.</p></div>

attendance-fixed.html:
<!DOCTYPE html>
<html>
<head><title>Attendance</title></head>
<body>
<h1>Attendance Report</h1>
<p>Asha: 92%</p>
<p>Rohan: 85%</p>
</body>
</html>

7. Input:
File names: layout.html, attributes