# Learn and config git/github.

## Creation Files

1) Create a new folder in your desktop, and opening VSCode to create a new **Markdown File**:

       Ex: readme.md
---
  1) Now just go to your new file, **Left-clicking** them, and **Open Whit**:

    'GIT BASH HERE' 
  - *to open file in Terminal git.*

## Git/GitHub
### The Structure
  1) Use this comand in terminal to "initialized empty git repository": 

          git init 

  - *This gone initialized a **'*master/main' branch*** in your git.*
---  
  2)  To change **'master'** to **'main'** **branch** just past in terminal: 
      
          git branch -m main

### Link's between git's

1) Acess your github and create a new repository, paste the link in terminal linkin them:

        Ex: git remote add origin https://github.com/rcctn/git-prod.git 
        
            git remote add origin <link.git>
---            
2) Creating another ***Branch's***

          Ex: git checkout -b 'txt-st' 
              git checkout -b 'branch-name'

### Road to 'Push' 

  3)  ***To Call***

          Ex: git add readme.md
              git add name-file
              git add .               
  - *Add files to **staging***
---
  4) **To See them** 

         Ex: git status 
  - *List of **staging's***
---
  5) **To Name**: 
      
          Ex: git commit -m "commit-name"
  - *Create a **Commit*** 
---
  6) **To Push**:

           Ex: git push -u origin 'main'
               git push -u origin 'second-branch' 
               git push -u origin 'branch-name'
- ***Sending** the commit and **creating** a **document version***
   
 
### Font's
---
#### GitHub
- echo "# git-prod" >> README.md
- git init
- git add README.md
- git commit -m "first commit"
- git branch -M main
- git remote add origin https://github.com/rcctn/-git-prod.git
- git push -u origin main
- Create a new branch: git checkout -b 'branch-name'

---

myself - Step by step

- git add readme.md                       --To call
- git status                              --To see
- git commit -m 'anotações'               --To name
- git push -u origin 'main(branch name)'  --To send
