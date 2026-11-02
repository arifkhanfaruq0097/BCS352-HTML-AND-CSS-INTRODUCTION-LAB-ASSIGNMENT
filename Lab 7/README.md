STANDARD LAB PRACTICAL EXPERIMENT FORMAT

EXPERIMENT NO. 7

1. Experiment Title: Forms

2. Aim:
Build a simple form with text inputs, a drop-down and a check-box, then check it validates.

3. Software / Tools Required:
Visual Studio Code, Chrome Browser

4. Theory:
<form> creates form, <input type="text"> for text, <input type="email"> for email with validation, <select> and <option> for drop-down, <input type="checkbox"> for check-box, <button> to submit, required attribute makes field mandatory.

5. Algorithm / Procedure:
1. Create folder Assignment 7
2. Create contact.html with form action /contact method post
3. Add text inputs for name, email with required, select for course, checkbox for agree
4. Create login.html with required email and password
5. Open in browser and test validation by submitting empty
6. Take screenshots

6. Program / Queries / Commands:
contact.html:
<!-- Name: Arif Khan | Roll No: 2510303124 | Ass: 7 -->
<!DOCTYPE html>
<html>
<head><title>Contact</title></head>
<body>
<form action="/contact" method="post">
<input type="text" name="name" required placeholder="Name">
<input type="email" name="email" required placeholder="Email">
<select name="course"><option>HTML</option><option>CSS</option><option>JS</option></select>
<label><input type="checkbox" required> I agree</label>
<button type="submit">Submit</button>
</form>
</body>
</html>

login.html:
<form>
<input type="email" required placeholder="Email">
<input type="password" required placeholder="Password">
<button type="submit">Login</button>
</form>

7. Input:
File names: contact.html, login.html

8. Output:
Form shows input boxes, drop-down and checkbox. If submit empty, browser shows Please fill out this field. Screenshots in images folder.

9. Result:
Experiment performed successfully.

10. Viva-Voce Questions:
1. What is difference between action and method?
2. What is use of required?
3. Difference between text and email input?
4. What is select and option?
5. What is checkbox?