# Necessary Commands for Github
1. **Check git on pc**<br>
    git --version<br>
2. **Configuring Github**<br>
    git config --global user.name "My name"<br>
    git config --global user.email "someone@email.com"<br>
    git config --list<br>
3. **Clone - Cloning a repository on our local machine**<br>
    git clone <-some link-><br>
4. **Status - displays the state of the code**<br>
    git status<br>
5. **Add - adds new or changed files in your working directory to the Git staging area**<br>
    git add <-file name-><br>
6. **Commit - it is the record of change**<br>
    git commit -m "some message"<br>
7. **Push - upload local repo content to remote repo**<br>
    git push origin main<br>
8. **Init - used to create a new git repo**<br>
    git init<br>
    git remote add origin <-link-><br>
    git remote -v  (to verify remote)<br>
    git branch  (to check branch)<br>
    git branch -M main  (to rename branch)<br>
    git push origin main<br>
9. **Branch Commands**<br>
    git branch  (to check branch)<br>
    git branch -M main      (to rename branch)<br>
    git checkout <-branch name->    (to navigate)<br>
    git checkout <-new branch name->   (to create new branch)<br>
    git branch -d <-branch name->    (to delete branch)<br>
10. **Merge Commands**<br>
    *Way 1:*<br>
    git diff <-branch name->    (to compare commits,branches,files & more)<br>
    git merge <-branch name->   (to merge two branches)<br>
    *Way 2:*<br>
    Create a PR<br>
11. **Undoing changes**<br>
    *Case 1: Staged changes*<br>
    git reset <-file name-><br>
    git reset<br>
    *Case 2: Commited changes (for one commit)*<br>
    git reset HEAD~1<br>
    *Case 3: Commited changes (for many commits)*<br>
    git reset <-commit hash-><br>
    git reset --hard <-commit hash-><br>
