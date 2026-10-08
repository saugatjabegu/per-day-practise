# For.New.Projects
1.git initialization
``` 
   Git init
2. add files and folder to git for tracking
```
   Git add .
Note: is for all files and folder, in place of . we can add file name.
3. after completing: save all codes as some version
```
Git commit -m”[your_commit_message]”
Eg: Git commit -m “day1, day2, day3 completed”
```
4. Optional step: changing main branch
Note: default branch is always “master”
```
   Git branch -M “main”[your_main_branch_name]”
```
5. add remote repo link or repository url
```
Git remote add origin “[your_repository_url]”
```
6. push the recent committed code to remote
```
Git push -u orign “[your_current_branch_name]”
```
Later (ig one pish is already dine using =u: upstream)
```
Git push

(*)for italic
(**) for bold
(`) heighlight
7. to preview the current git status
```
git status
```
8. to check linked remote url
```
git remove -v
```
9. to update the remote repo url
```
git remote set-url origin [your-repo-url]
tp verify/display added remote url:
git remote -v
```
10. to config the user.name and user.email:
```
project based config:
git config user.name [ypur-github-username]
git config user.email [your-github-email]

to verify/display config (Note: enter to view more config and q to exit the opened editor):
git config --list 
```
# after changing on project
1. git add.
2. git commit -m "[ypur-commit-message]"
3. git push
# using personal account token (PAT) on https url:
https://[PAT]@github.com/[github-username]/[project-name]
