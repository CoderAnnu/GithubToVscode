<h2>Connection between Github to Vscode With secure connection with SSH key </h2>

Git is a Version controll software it is used to create your project version 
to update your projects version like 1.0.0 is tyour old version and you update
some functionalty in your project like 1.0.1 then you have to upgrade your
project version then we will use the git software to update your version to commit the latest version of your projects.


Download Git Software => https://git-scm.com/download/win => 
Deffrence between git and Github => 

Git is a version controll software they are provide to push your code in github repositry
Github is a website they are store our projects in github repositry

1. $ git config --global user.name coderannu
2. $ git config --global user.email "akrajput01206@gmail.com"
3. $ touch .gitignore to create file
4. $ git init
5. $ git add .
6. $ git commit -m "initial commit"
7. $ git status
8. $ git remote add origin git@github.com:CoderAnnu/ballons.git
9. $ git push origin master
10. $ ssh-keygen -t ed25519 -C "akrajput01206@gmail.com" enter enter
11. $ cat /c/Users/pc/.ssh/id_ed25519.pub //(to create SSh Key)
12. $ git push origin master
13. $ git status

create file $ touch .gitignore or you can put your file name

if you wanna ignore file then you have to put file name in your/ .gitignore file

if you are using Vscode then use these command 

1. git init <to initialize> 
2. git add . / or git add <file-name>
3. git commit -m “whatever-commit-message”
4. git push origin master <code push request>
5. git status <for check status of your project>
6. git remote <to check your project connection>
7. ls ~/.ssh <to check ssh connetion>
8. git help <to check git commands>

