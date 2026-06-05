# Git Notes
## 1. git add
    - Used to tell Git which changes to add in my next save
    - git add .
    - I used this command after making changes/editing a file before committing

## 2. git checkout 
    - Used to switch from one branch to another
    - git checkout feature-branch
    - I used this command to switch to different versions of the repository

## 3. git clone
    - Used to clone/download a copy of the repository
    - git clone https://github.com/varnikasingh/learning-tasks.git
    - git clone https://github.com/varnikasingh/learning-tasks.git my-learning
    - I used it to clone and rename the folder locally available, so i can make changes locally.

## 4. git commit
    - Used to save my work with a message describing the changes
    - git commit -m "Added Introduction"
    - I used it to commit to a change i made in a repository.

## 5. git config
    - Used to tell Git who i am 
    - Setup name:
        * git config --global user.name "Varnika Singh"
    - Setup email:
        * git config --global user.email "sing.varnika@gmail.com"
    - These details are added to my commit

## 6. .gitignore
    - Used to tell git which files to not track.   
    - *.md
        * Now the .md files will not be listed when you check git status
        * However if git is already tracking a file, it will continue to track it even after .gitignore
            - Eg: git add. e01-git.md
                  git commit -m "Updated"
                  *.md
                  **The e01-git.md file will still be tracked**
        * To fix this:
                 git rm --cached e01-git.md

## 7. gitk
    - Used to have a graphical representaion of the commits and branches
    - gitk
    - I was not able to practice this command as i do not have the required version to use the command

## 8. git init
    - Used to create new git repo
    - git init
    - I used git init at the beginning to tell Git to start tracking my project

## 9. git log
    - Used to view older commits
    - git log
    - I used it to see the history of my commits

## 10. git merge
    - Used to combine two branches changes into one
    - git merge feature

## 11. git pull
    - used to get latest version of the repo
    - git pull
    - I used it to pull the e01-git.md repository to edit it

## 12. git push
    - Used to push/ upload my new work to the repository
    - git push
    - I used it to push this file after i was done editing it.

## 13. git remote
    - Used to manage connections between local(on my comp) and remote(on github) repos
    - git remote -v

## 14. git stash
    - used to temporarily store changes without commit
    - git stash
    - git stash pop

## 15. git status
    - Used to check what changes made in git
    - git status

## 16. 