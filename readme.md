
// Installing Git
----------------------------------------------------------------

 Linux(Debian)
 $sudo apt-get install git

 Linux(Fedora)
 $sudo yum install git

 Mac
 http://git-scm.com/download/mac

 Windows
 http://git-scm.com/download/win

or use:
home brewer
npm
gitbash

// Check if git is installed
git --version

-----------------------------------------------------------------


GIT Basic Commands:
-----------------------------------------------------------------
// Initialize Local Git Repository
git init

// Add Files To Index
git add <file>

// Check status of working tree
git status

 // Commit changes in Index
 git commit

 // Push to remote repository
 git push

 // Pull the latest from remote repository
 git pull

 // Clone Repository into a new directory
 git clone

 ---------------------------------------------------------------


 GIT Example:
 ---------------------------------------------------------------
 // Config git user 
 git config --global user.name 'name'

 // Config git email
 git config --global email 'name@x.com'

 // Add /gitEx/index.html
 git add index.html

 // To know the status
 git status

 // To remove index.html - cached stage
 git rm --cached index.html

 // To know the status
 git status

 // To add all .html files
 git add *.html

git status
git rm --cached index.html
 
// To add all files in folder
git add .

git status

//change content of index.html
git status

git add .
git status

// commiting changes
git commit

git status
// add content to app.js
git status

git add.
// commiting without editing
git commit -m 'Added code to app.js'

// Creating git ignore file
touch .gitignore
touch log.txt

// Edit log.txt & .gitignore

git add .
git status

// Adding Directives
mkdir img
mkdir test

add /test to .gitignore

git add .
git status
git commit -m 'Added img'

// create a Branch to add login func without disturbing the Master
git branch login

// to see the branch
git checkout login

touch login.js
git add .
git status
git commit -m 'login'

// to go to Master
git checkout master

// to merger master & branch
git merge login

// to post it to git remote
log into github
create repository

git remote
git remote add origin addYourGenLink.git
git remote
git push -u origin master

login

git push for updated files.

done..
--------------------------