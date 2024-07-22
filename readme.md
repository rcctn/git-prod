# Learn and config git/github.

## Creation Files

1) Create a new folder in your desktop, and opening VSCode to create a new **Markdown File**:

       Ex: readme.md
---
2) Now just go to your new file, **Left-clicking** them, and **Open Whit**:

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

### Road to 'Push' 

  1)  ***To Call***

          Ex: git add readme.md 
              git add name-file 
              git add .               
  - *Add files to **staging***
---
  2) **To See them** 

          git status 
  - *List of **staging's***
---
  3) **To Name**: 
      
          git commit -m "commit-name"
  - *Create a **Commit*** 
---
  4) **To Push**:

          Ex: git push -u origin 'main' 
              git push -u origin 'second-branch'  
              git push -u origin 'branch-name'
- ***Sending** the commit and **creating** a **document version***

### Link's between git's

1) Acess your github and create a new repository, paste the link in terminal linkin them:

        Ex: git remote add origin https://github.com/rcctn/git-prod.git 
            git remote add origin <link.git>
---
2) ***Clone your code*** to another workspace:

        Ex: git clone https://github.com/rcctn/git-prod.git
            git clone <link.git>

3) Acess the ***main branch folder***: 

        Ex: cd git-prod
            cd 'folder-name'   
---         
4) ***Switch betwenn*** branch's:

          Ex: git checkout main
              git checkout txt.ts
              git checkout 'branch-name'
---
5) Creating another ***Branch's***:

          Ex: git checkout -b 'txt-st' 
              git checkout -b 'branch-name'
---
6) To ***merge branch's***

          Ex: git merge 'txt-st'
              git merge 'branch-name'
          
 
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

Step by step

- To call: 
        
        git add 'file-name'
- To see:  
  
        git status 

- To name: 
 
        git commit -m 'commit-name'               
- To send: 

        git push -u origin 'branch-name'
