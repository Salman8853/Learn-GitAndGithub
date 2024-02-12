Git Commands
This Gist contains all the useful commands for Git
Build Status

Version control is a system that records changes to a file or set of files over time so that you can recall specific versions later.

If you are a developer and want to keep every version of your code/project (which you would most certainly want to), a Version Control System (VCS) is a very wise thing to use.

All the commands used for Git
Compatibility with GitHub
✨Magic ✨
Commands
Set global username and email for Git (Locally).

git config --global user.name "<your username>"
git config --global user.email "<your email>"
Initialise an empty Git Repository

git init
Clone an existing Git Repository

git clone <repository URL>
Add file/stage to git

git add <filename>
Add all the files to git

git add .
Commit all the staged files to git

git commit -m "<your commit message>"
Restore the file from being modified to Tracked

git restore <filename>
git checkout <filename>
Show the status of your Git respository

git status
Show the branches of your git repository

git branch
Checkout to a new branch

git checkout -b <branch name>
Checkout to an existing branch

git checkout <branch name>
Remove a branch from Git

git branch -d <branch name>
Show remote origin URL

git remote -v
Add remote origin URL

git remote add origin <your remote git URL>
Remove remote origin URL

git remote remove origin 
Fetch all the remote branches

git fetch
Push your local changes to remote branch

git push origin <branch name>
Pull your remote changes to local branch

git pull origin <branch name>
Check you git commits and logs

git log
Happy Learning!
