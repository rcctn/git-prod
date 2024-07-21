Projeto para aprender e configurar o git e github.


- Create a new folder and open in VSCode. 
- Create a new file 'readme.md'(markdown file)
- Leftclick on 'markdown file' and 'Open whit GIT BASH HERE'
    "terminal git open"

    TERMINAL GIT
- Use comand 'git init' in terminal
    "initialized empty git repository"
    Files 'master/main as create in the folder '.git'
        to change master to main branch: Just past 'git branch -m main' in terminal
- Add fiel to stadin using (git add name fiel)
    Using 'git status' to see the files stadins
- To commit use (git commit -m "primeiro commit")

- Create a new repository in our github and past in terminal using:

    git remote add origin <link.git>   
    git push -u origin main


- Create a new repository in our github and cop + past to 'create a new repository on the command line'

    echo "# git-prod" >> README.md
    git init
    git add README.md
    git commit -m "first commit"
    git branch -M main
    git remote add origin https://github.com/rcctn/git-prod.git
    git push -u origin main





step by step cod

$ git add readme.md         --To call
$ git status                --To see
$ git commit -m 'anotações' --To name
$ git push -u origin main   --To send 
