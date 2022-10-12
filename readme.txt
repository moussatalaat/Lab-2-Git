1- Download & Install git.
2- Open ITI folder, right-click and open Git Bash Here.
3- Create Git-cource folder with mkdir Git-cource.
4- Create several file with different extensions with touch command : a- index.html.
                                                                      b- style.css.
                                                                      c-app.js.
                                                                      d-readme.txt.
5- Init Git in our directory : git init.
6- Chack for our directory status : git status.
7- Add files : git add. 
8- Auther identity: git config --global user.email "moussa.talaat@gmail.com".
9- Commit : git commit -m "Hello Git".                           
10- git status.
11- git add.     
12- Commit : git commit -m "Hello World".
13- git status
14- git add .
15- git log --oneline
    ->  b06c631 (HEAD -> master) Hello ITI
        a206204 Hello Front-end Developers
        2311452 Adding Hello World
        89c36b5 Hello Git

16- git reset a206204 --hard
    ->  a206204 (HEAD -> master) Hello Front-end Developers
        2311452 Adding Hello World
        89c36b5 Hello Git
                                   