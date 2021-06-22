# GitTutorial
A repo for Paractice Version control in Git &amp; Github

## Git Clone

1. Open a folder in Visual Studio code.
2. Open the terminal.
3. Write the Command **_git clone "link that got from git clone"_**

   

## Changeing the file

1. With the help of Visual Studio Code make changes in the folder like adding a new file or changes in existing file.

## git status

This command is used to check the Status of different file in the repo.
Status like modified, Untracked, newfile etc....
After changeing file use **_git status_** command.

## Untracked files
 
Untracked files are the new files.That means git doesn't know about this file. So we need to tell git. **A new file is here buddy :)**

1. Use **_git add filename/foldername_** To track specific file/folder.
    
    To practice this I added a **index.html** file and Test folder to this repo

2. You can also use **_git add ._** To track all the files &amp; folders.

## git commit

This command is used to committing the changes you made on a github.
**_git commit -m "commit message" -m "commit description (optional)"_**

## Linking github account and your PC

[youtube tutorial link for Linking github and your PC](https://www.youtube.com/watch?v=H5qNpRGB7Qw)
If all ready done this you can skip this step.

## git push in main branch

This command is used to push changes into your git hub repo **_git push origin main_**
There is a shortcut for this type **_git push -u origin main_**. Next time onwards you just needed to type
**_git push_**


## git Workflow(Usig web interface)

write code -> commit changes `git commit` -> pull request 


## Local Git WorkFlow

write code -> stage code `git add` -> Commit changes `git commit` -> Push changes `git push` -> make a pull Request(if your not the owner of this repo)

## Branching in Git

Branching allows each developer to branch out from the original code base and isolate their work from others. It also helps Git to easily merge versions later on.

@1 - @2 - @3 - @4 - @5 - @6   

-----------\--------/  

------------\------/

-------------#1 - #2 

`@1-6` is the `master` branch
`#1-#2` is the `feature` branch

### how to Create a Branch in git.

`git branch` command is used to see the branches

`git checkout -b "branch name"` is used to create a new branch

`git checkout "branch name` is use to switch between branches

### merging the created branch into master

`git checkout main` Comeback to main branch

`git diff branch_name` this command shows the changes in **main branch** and **practise branch**

`git merge branch_name` this command will merge the practise branch into main branch.











