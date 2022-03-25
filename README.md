# New git repo
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
