<h2>Connection between Github to Vscode With secure connection with SSH key </h2>

Git is a Version controll software it is used to create your project version 
to update your projects version like 1.0.0 is tyour old version and you update
some functionalty in your project like 1.0.1 then you have to upgrade your
project version then we will use the git software to update your version to commit the latest version of your projects.<br>


Download Git Software => https://git-scm.com/download/win <br>
Deffrence between git and Github => 

Git is a version controll software they are provide to push your code in github repositry
Github is a website they are store our projects in github repositry<br>

<h2>Git git Bash Terminologies comnmands</h2><br>

1. $ git config --global user.name coderannu<br>
2. $ git config --global user.email "exapmlemail.com"<br>
3. $ touch .gitignore to create file<br>
4. $ git init<br>
5. $ git add .<br>
6. $ git commit -m "initial commit"<br>
7. $ git status<br>
8. $ git remote add origin git@github.com:CoderAnnu/ballons.git<br>
9. $ git push origin master<br>
10. $ ssh-keygen -t ed25549 -C "example@mail.com" enter enter<br>
11. $ cat /c/Users/pc/.ssh/id_ed25549.pub //(to create SSh Key)<br>
12. $ git push origin master<br>
13. $ git status<br>

create file $ touch .gitignore or you can put your file name<br>

if you wanna ignore file then you have to put file name in your/ .gitignore file<br>

if you are using Vscode then use these command <br>

<h2>Git Terminologies in  Vscode terminal</h2><br>

<h4>Git Configuration</h4><br>

git config –global user.name <Set the username to be used for all actions><br>
git config –global user.email	<Set the email to be used for all the actions.><br>
git config –global alias.	<Create a shortcut for the Git command.><br>
git config –system core.editor	<Set the text editor for all the command actions.><br>
git config –global –edit	<Open global configuration file in the text editor for manual editing.><br>
git config –global color.ui auto	<Enable helpful colourization of command line outputs.><br>

<h4>Set Up a Git Repository</h4><br>

git init <Initialize an empty Git repo in the current project.><br>
git clone (Repo URL)	<Clone the repository from GitHub to the project folder.><br>
git clone (Repo URL) (Folder )	<Clone the repository into a specific folder.><br>
git remote add origin   <Create a remote repo pointing on your existing GitHub repository.><br>
https://github.com/username/(repo_name).git<br>

ls ~/.ssh <to check ssh connetion><br>
git remote	<Shows the name of remote repositories.><br>
git remote -v	<Shows the name and the URL of the remote repositories.><br>
git remote rm (remote repo name)	<Removes the remote repository.><br>
git remote set-url origin (git URL)	<Changes the URL of the repository.><br>
git fetch	<Get the latest changes from the origin but not merge.><br>
git pull	<Get the latest changes from the origin and merge them.><br>


<h4>Local File Changes</h4><br>

git add (file name)	<Add the current changes to the file to staging.><br>
git add .	<Add the whole directory changes to staging (no delete files).><br>
git rm (file_name)	<Removes the file and untracks (stop tracking) it.><br>
git rm –cached (file_name)	<Untracks the current file.><br>
git mv  (file_name) (new_file_name)	<Changes the filename and prepare it for Commit.><br>
git checkout <deleted file name>	<Recovers the deleted file and prepares it for Commit><br>
git status	<Shows the status of the modified files.><br>
git ls-files –other –ignored –exclude-standard	<Shows the list of all ignored files.><br>
git diff	<Shows unstaged changes in the index and the working directory.><br>
git diff –staged	<Shows file differences between staging and the last file version.><br>
git diff (file_name)	<Shows changes in a single file compared to the last Commit.><br>


<h4>Declare Commits</h4><br>

git commit -m “whatever-commit-message”<br>
git commit -m “(message)”	<Commits the changes with a custom message.><br>
git commit -am “(message)”	<Adds all changes to staging and commits them with a custom message.><br>
git checkout	<Switch to the provided Commit.><br>
git show	<Outputs the metadata and content changes of the specified Commit.><br>
git reset –hard	<Discard all the history and changes back to a given Commit.><br>
git reset –hard Head	<Discards all local changes in the working directory.><br>
git log	<Shows the history of changes.><br>
git log -p	<Shows the full display of each Commit.><br>
git log -oneline	<Shows the list of Commits with a simple message.><br>
git log –follow (file_name)	<List the history for the current file.><br>
git blame (file_name)	<Shows all changes along with the name of the user.><br>
git stash	<Temporarily saves all modified tracked files.><br>
git stash pop	<Restores the most recently stashed files.><br>
git stash list	<List all stash changedsets.><br>
git stash apply	<Apply the latest stashed contents.><br>
git stash drop	<Discard the most recently stashed files><br>
git stash apply (stash id)	<Re-apply a specific stash content by ID.><br>
git stash drop (stash_id)	<Drop a specific stash content by ID.><br>
git push	<Push changes to the Origin.><br>
git push origin (branch_name)	<Push branch to the Origin.><br>
git push -f origin (branch_name)	<Force pushes the changes to the Origin.><br>
git tag (tag_name)	<Define a tag for a version.><br>
git push	<Push changes to the Origin.><br>


<h4>Branching</h4><br>

git branch	<Shows the list of all branches.><br>
git branch	<Creates a new branch.><br>
git branch -m	<Renames the branch.><br>
git branch -a	<List all branches, local and remote.><br>
git checkout -b	<Creates a branch and switch to it.><br>
git checkout	<Switch to the provided branch.><br>
git checkout -b origin/	<Get a remote branch from origin to the local directory.><br>
git branch -d	<Delete the specified branch.><br>
git merge	<Merge the current branch into the master (first checkout to master)><br>
git rebase	<Takes all the changes of the branch and restate on others.><br>
git rebase	<Rebase the current branch onto the base. Base can be a Commit ID or a branch name.><br>
git fetch remote	<Fetches the specified branch from the repository.><br>
git diff ..	<Shows the differences between two branches.><br>
git pull –rebase	<Fetches the remote copy of the current branch and rebases it into the local copy.><br>
git push –all	<Push all the local branches to the specified remote repository.><br>
git help <to check git commands><br>

