# 🧪 Git Basics Practice

This repository contains screenshots and files demonstrating the basic Git workflow as part of a hands-on practice exercise.

## 📁 Project Steps

Below are the steps I followed in the `learn_git` folder:

1. Created a folder called `learn_git` and navigated into it.
2. Created a file named `third.txt`.
3. Initialized a new Git repository.
4. Added `third.txt` to the staging area and committed it with the message `"adding third.txt"`.
5. Created `fourth.txt`, added it, and committed with the message `"adding fourth.txt"`.
6. Deleted `third.txt`, added the change to the staging area using `git add'.
7. Configured Git to show logs directly in the terminal by using:

   ```bash
   git config --global core.pager cat
   
8. Checked the commit history usingthe 'git log'.
9. View the global configuration:
        git config --global --list
10. Push the screenshots to GitHub:
        git remote add origin https://github.com/mayssamhira/git-checkpoint.git /
        git branch -M main /
        git add *.png (all the screenshots that i taked) /
        git commit -m "adding screenshots" /
        git push -u origin main
   
