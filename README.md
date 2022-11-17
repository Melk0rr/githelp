# Git Helper
## New git repo
1. mkdir ProjectName
2. git init
3. git add README.md
4. git commit -m "first commit"
5. git branch -M main
6. git remote add origin git@github.com:myprofile/myproject.git
7. ssh-keygen -t rsa -b 4096 -C "my.email@domain.com"
8. (choose key file name)
9. (choose passphrase)
10. ssh-add -K ~/.ssh/key_file_name
11. (enter passphrase)
12. cat ~/.ssh/key_file_name.pub
13. copy/paste to github
14. git push -u origin main

## Useful git command
- Checkout changes: `git status`
- Add specified files to the upcomming commit: `git add <files>`
- Commit the previously added files: `git commit -a <all> -m <message>`
- Push commits to remote branch: `git push`
- Force push `git push -f origin <branchname>`
- To see the local branches: `git branch`
- Delete the given branch: `git branch -D <branchname>`
- Checkout the given branch: `git checkout <branchname>`
- Create a new branch with the given name: `git checkout -b <newbranchname>`
- Merge the specified branch into the current one: `git merge <branchname>`
- Pull the modifications from the remote branch: `git pull`
- Update the base of the current branch with the last version of the specified one: `git rebase <branchname>`
- Revert the given commit: `git revert <commitId>`
- Reset current branch to its base: `git reset --hard`
- Recreate master branch: `git checkout -B master origin/master`
- Display the commit difference between the current branch and the specified one: `git cherry -v <branchname>`
- Show all the past operations: `git reflog`
