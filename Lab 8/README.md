Ye le Arif, *Lab 8* ka README - bilkul wahi pehle wale format me.

`Assignment 8 / README.md` me daal de.

---

### *STANDARD LAB PRACTICAL EXPERIMENT FORMAT*

*EXPERIMENT NO. 8*

*1. Experiment Title:* Semantic HTML Tags

*2. Aim:*
To create a webpage using semantic HTML tags like header, nav, section, article and footer.

*3. Software / Tools Required:*
- Visual Studio Code
- Web Browser
- Git Bash (optional)

*4. Theory:*
Semantic tags wo tags hote hain jinka naam se hi unka matlab samajh aata hai. Jaise `<header>`, `<nav>`, `<section>`, `<article>`, `<footer>`. Ye non-semantic tags jaise `<div>` se alag hote hain. Semantic tags SEO aur accessibility ke liye bahut important hain. Ye search engine aur screen reader ko page ka structure samajhne me help karte hain.

*5. Program / Queries / Commands:*
// Name: Arif Khan | Roll No: 2510303124 | Ass: 8

<!DOCTYPE html>
<html>
<head>
    <title>Lab 8 - Semantic Tags</title>
</head>
<body>
    <header>
        <h1>ARIF KHAN - Portfolio</h1>
    </header>

    <nav>
        <a href="#">Home</a> |
        <a href="#">About</a> |
        <a href="#">Contact</a>
    </nav>

    <section>
        <h2>About Me</h2>
        <article>
            <p>I am B.Tech CSE Student at Invertis University. I am learning HTML and CSS.</p>
        </article>
    </section>

    <aside>
        <h3>Skills</h3>
        <p>HTML, CSS, JavaScript</p>
    </aside>

    <footer>
        <p>© 2026 Arif Khan | All Rights Reserved</p>
    </footer>
</body>
</html>
*Commands used:*
git status
git add index.html
git commit -m "Lab 8 Semantic Tags Added"
git log --oneline

*6. Input:*
Folder name: `Assignment-8`, File name: `index.html`

*7. Output:*
- Browser me header me naam dikhega
- Nav me Home, About, Contact links dikhenge
- Section me About Me ka content dikhega
- Aside me Skills aur Footer me copyright dikhega
- Screenshot saved in `images/` folder
- `git log --oneline` shows commit "Lab 8 Semantic Tags Added"

*8. Result:*
Experiment performed successfully. Webpage using semantic tags was created and displayed successfully.

*9. Viva-Voce Questions:*
1. What are semantic tags? Give examples.
2. Difference between `<div>` and `<section>`?
3. Why semantic tags are important for SEO?
4. What is the use of `<nav>` tag?
5. What is the use of `<footer>` tag?
