*EXPERIMENT NO. 2*

*1. Experiment Title:* Pushing and Cloning a Repository

*2. Aim:*
To send your commits to a second repository on your computer and make a copy of it with clone.

*3. Software / Tools Required:*
- Visual Studio Code
- Git Bash
- File Explorer

*4. Theory:*
`git init --bare` creates an empty bare repository that acts like a remote server (like GitHub but on your own PC). `git remote add origin <path>` links your main lab folder to that remote. `git push origin main` sends all your commits to the remote. `git clone <remote> <new-folder>` makes a complete copy of the remote repository with full history.

*5. Algorithm / Procedure:*
1. Open terminal inside `js-lab` folder
2. Create bare repo next to it: `git init --bare ../js-remote`
3. Add it as origin: `git remote add origin ../js-remote`
4. Check remote: `git remote -v`
5. Push commits: `git push origin main` (if branch is master then use master)
6. Go one folder back: `cd ..`
7. Clone remote into new folder: `git clone js-remote js-copy`
8. Go into js-copy and run `git log --oneline` to verify

*6. Program / Queries / Commands:*
Commands used:

cd js-lab
git init --bare ../js-remote
git remote add origin ../js-remote
git remote -v
git push origin main
cd ..
git clone js-remote js-copy
cd js-copy
git log --oneline
*7. Input:*
Existing folder: `js-lab` with 2 commits from Assignment 1, Remote folder to be created: `js-remote`, Clone folder to be created: `js-copy`

*8. Output:*
- `git remote -v` shows:
`origin  ../js-remote (fetch)`
`origin  ../js-remote (push)`
- `git push` ends with line: `main -> main` or `master -> master`
- `git clone` shows `Cloning into 'js-copy'... done.`
- `git log --oneline` in js-copy shows same 2 commits as in js-lab
- Screenshot saved in `images/` folder

*9. Result:*
Experiment performed successfully. Remote repository created, commits pushed to origin and repository cloned successfully with same history.

*10. Viva-Voce Questions:*
1. What is the use of `git init --bare`?
2. What is the difference between `git push` and `git clone`?
3. What does `origin` mean in Git?
4. What is the difference between normal repo and bare repo?
5. Why do we need `git remote -v`?