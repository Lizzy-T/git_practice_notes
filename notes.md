#typed notes

terminal commands

. is current directory

1) get init
- make it a git repo
- pay attention to project and check changes in project

2) work!

3) git status
git status
-> git is a tracking system
-> this tells you the changes in the file
-> red if unsaved
-> green if saved
-> working tree is green : you commited your file!

4) git add <filename>
    git add notes.md
    -> stages this file (tracks changes)
    -> shorthand: git add .

5) git commit -m "..."
    -> saves
    -> '-m' message flag
    -> in "..." a description of what the commit does
    -> so you can see what each save does

6) redo and repeat until ready to push code up to remote

7) check if local is linked to remote
    git remote -v
    - what remote repo is linked
    - if nothing is linke will be blank- main one is origian
    - origin is name of remote repo that lives in 
    
8) to link to git hub (if not linked)
- go to git hub and add a new repo
- name repo
- copy paste
- git remote add origin git@github.com:Lizzy-T/git_practice_notes.git
- OR -
- clone
- <copy>
- git add remote origin <paste>

9) to push to git hub
- local to remote
- git push origin master
    -> pushes local file to remote repo

now it will show up in your github repos