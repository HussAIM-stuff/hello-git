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
