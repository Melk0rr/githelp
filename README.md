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
10. ssh-add -K ~/.ssh-/key_file_name
11.(enter passphrase)
12. cat ~/.ssh/key_file_name.pub
13. copy/paste to github
14. git push -u origin main

## Useful git command
- Checkout changes: `git status`
- Add specified files to the upcomming commit: `git add <files>`
- git commit -a (all) -m (message) // Commit the previously added files
- git push // Push the commits from local branch to the remote branch
- git push -f origin <branchname>
- git branch // To see the locally used branches
- git branch -D <branchname> // Delete the given branch
- git checkout <branchname> // Checkout the given branch
- git checkout -b <newbranchname> // Create a new branch with the given name and checkout this newly created branch
- git merge <branchname> // Merge the current branch into the given one
- git pull // Pull the modifications from the remote branch to the current branch
- git rebase <branchname> // Updates the base of the current branch with the last version of the given one
- git revert <commitId> // Revert the given commit
- git reset --hard // Reset current branch to its base
- git checkout -B master origin/master //Recreate master branch
- git cherry -v <branchname> // Displays the commit difference between the current branch and the given branch
- git reflog // Displays all the operations that have been done
