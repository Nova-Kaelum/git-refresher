# git-refresher
Practice with git commands and project structure 

Download git cheatsheet here: 
https://www.atlassian.com/git/tutorials/atlassian-git-cheatsheet

# Tips for practice

1. **Understand the Basics:**
   - Learn the basic commands: `git init`, `git add`, `git commit`, `git status`, `git log`, `git diff`.
   - Understand the difference between the working directory, staging area, and repository.

2. **Branching and Merging:**
   - Practice creating branches: `git branch <branch-name>`, `git checkout -b <branch-name>`.
   - Merge branches: `git merge <branch-name>`.
   - Resolve merge conflicts.

3. **Commit Messages:**
   - Write clear and concise commit messages.
   - Follow a consistent commit message style.

4. **Staging and Committing:**
   - Stage specific files: `git add <file>`.
   - Stage all changes: `git add .`.
   - Commit changes: `git commit -m "Commit message"`.

5. **Viewing History:**
   - View commit history: `git log`.
   - View changes: `git diff`.

6. **Undoing Changes:**
   - Undo changes in the working directory: `git checkout -- <file>`.
   - Unstage files: `git reset <file>`.
   - Amend the last commit: `git commit --amend`.

7. **Remote Repositories:**
   - Add a remote repository: `git remote add origin <url>`.
   - Push changes: `git push origin <branch-name>`.
   - Pull changes: `git pull origin <branch-name>`.

8. **Tagging:**
   - Create a tag: `git tag <tag-name>`.
   - Push tags to remote: `git push origin <tag-name>`.

9. **Rebasing:**
   - Rebase a branch: `git rebase <branch-name>`.
   - Understand the difference between merging and rebasing.

10. **Collaborative Workflows:**
    - Practice forking a repository and creating pull requests.
    - Review and merge pull requests.

11. **Using .gitignore:**
    - Create a .gitignore to avoid pushing directories or files that should be individual to your IDE or project for example (node modules dir, vscode dir, launch.json file...)

12. **Explore Advanced Features:**
    - Learn about Git hooks.
    - Use Git stash to save changes temporarily: `git stash`, `git stash pop`. (IMPORTANT !!)
