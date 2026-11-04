Samajh gaya, wahi pehla wala *college ke photo wala format* - bilkul same to same. Ye le Lab 4 usi me:

Copy karke `Assignment 4 / README.md` me daal de.

---

### *STANDARD LAB PRACTICAL EXPERIMENT FORMAT*

*EXPERIMENT NO. 4*

*1. Experiment Title:* Lists in HTML

*2. Aim:*
To create ordered list, unordered list and nested list in HTML.

*3. Software / Tools Required:*
- Visual Studio Code
- Web Browser
- Git Bash (optional)

*4. Theory:*
HTML me list ka use data ko sequence me dikhane ke liye hota hai. `<ol>` tag ordered list banata hai jisme numbers ya alphabets aate hain. `<ul>` tag unordered list banata hai jisme bullets aate hain. `<li>` tag list ke item ko define karta hai. Nested list ka matlab ek list ke andar dusri list banana hota hai.

*5. Program / Queries / Commands:*
// Name: Arif Khan | Roll No: 2510303124 | Ass: 4

<!DOCTYPE html>
<html>
<head>
    <title>Lab 4 - Lists</title>
</head>
<body>
    <h2>Ordered List</h2>
    <ol>
        <li>HTML</li>
        <li>CSS</li>
        <li>JavaScript</li>
    </ol>

    <h2>Unordered List</h2>
    <ul>
        <li>Coding</li>
        <li>Cricket</li>
    </ul>

    <h2>Nested List</h2>
    <ol>
        <li>Frontend
            <ul>
                <li>HTML</li>
                <li>CSS</li>
            </ul>
        </li>
    </ol>
</body>
</html>
*Commands used:*
git status
git add index.html
git commit -m "Lab 4 Lists Added"
git log --oneline

*6. Input:*
Folder name: `Assignment-4`, File name: `index.html`

*7. Output:*
- Browser me ordered list numbers ke saath dikhegi
- Unordered list bullets ke saath dikhegi
- Nested list me Frontend ke andar HTML/CSS dikhega
- Screenshot saved in `images/` folder
- `git log --oneline` shows commit "Lab 4 Lists Added"

*8. Result:*
Experiment performed successfully. Ordered, unordered and nested lists were created and displayed successfully.

*9. Viva-Voce Questions:*
1. What is the difference between `<ol>` and `<ul>`?
2. What is the use of `<li>` tag?
3. What is nested list?
4. What is the use of type attribute in list?
5. How to create list inside list?