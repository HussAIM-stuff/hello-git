Set your name:
$ git config --global user.name "Your Name"
Now set your email:
$ git config --global user.email "youremail@example.com"

Turn Git on for a folder
$ git init

Check status of changes to a repository
$ git status
View changes to files
$ git diff
Add a file's changes to be committed
$ git add <FILENAME>
To add all files changes
$ git add .
To commit (aka save) the changes you've added with a short message describing the changes
$ git commit -m "your commit message"

Add your GitHub username to your Git configuration:
$ git config --global user.username <USerNamE>

Add remote connections
$ git remote add <REMOTENAME> <URL>
Set a URL to a remote
$ git remote set-url <REMOTENAME> <URL>
Pull in changes
$ git pull <REMOTENAME> <BRANCHNAME>
View remote addresses
$ git remote -v
Push changes
$ git push <REMOTENAME> <BRANCH>

View remote connections
$ git remote -v

You can create and switch to a branch in one line
$ git checkout -b <BRANCHNAME>
Create a new branch
$ git branch <BRANCHNAME>
Move onto a branch
$ git checkout <BRANCHNAME>
List the branches
$ git branch
Rename a branch you're currently on
$ git branch -m <NEWBRANCHNAME>
Verify what branch you're working on
$ git status

Pull in changes from a remote branch
$ git pull <REMOTENAME> <REMOTEBRANCH>
See changes to the remote before you pull in
$ git fetch --dry-run

Merge a branch into current branch
$ git merge <BRANCHNAME>
Change the branch you're working on
$ git checkout <BRANCHNAME>
Delete a local branch
$ git branch -d <BRANCHNAME>
Delete a remote branch
$ git push <REMOTENAME> --delete <BRANCHNAME>
Pull from a remote branch
$ git pull <REMOTENAME> <BRANCHNAME>
