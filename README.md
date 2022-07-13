# jonathan-git

## 1: Create a Repository on github
## 2: Create a Branch 
## 3: Clong code on local machine
        - git clone https://github.com/mUsman3/jonathan-git.git
        - cd jonathan-git #change directory(Folder) to jonathan-git
## 4: To show, on which branch currently you are on
        - git branch
## 5: To list all the branches
        - git branch -r
## 6: To change from one branch to another branch
        - git checkout branch_name
## 7: To create and edit a file 
        - touch file1.txt # creating file
        - nano file1.txt # nano is an editor, used to edit file
        - CTRL + X then Type Y and then hit Enter #  after writing you have to follow this to   save and exit
        - cat file1.txt # to see the content of the file
## 8: To start tracking your chnages
        - git add .  or git add file_name   
        - git commit -m 'you meaning message'  # here -m is used for message
        - git push origin branch_name # This command will push you changes to github to spefied branch
