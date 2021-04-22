
# This is a compilation of the commands we've been using in git:

-GIT CONFIG <br>
-git config --global user.name             sets an username for the user 
-	git config --global user.name "ferencalada"
-git config --global user.email            sets an email for the user
-	git config --global user.email user@gmail.com
-
-MORE GIT COMMANDS
-git init                              is used to start a new local repository with git
-	git init
-git clone <link to repository>        is used to create a copy of an existing repository
-	git clone https://github.com/github/training-kit.git
-git add <file name.file type>         is used to add certain files to the staging area
-	git add file.c
-<asterisk>                            basically, a replacement when you mean any type or any name of files
-	git add *
-git commit -m "<commit name>"         creating and naming a commit
-	git commit -m "new commit"
-git status                            show the current status of the files inside the directory
-	git status
-git diff                              show the changes made since the last commit
-	git diff
-git log                               shows the commits made so far
-	git log
-git log -p                            shows the changes made in the commits
-	git log -p
-git log -2                            shows the last commit
-	git log -2
-git reset                             takes out of staging area
-	git reset
-git reset HEAD                        takes last commit out of staging area
-	git reset HEAD
-
REMOTE REPOSITORY
git remote add origin <link to remote repository>       adds a server where it is possible to push the commits
	git remote add origin https://github.com/github/training-kit.git
git remote -v                                           list all configured remote repositories
	git remote -v
git pull                                                merge changes from remote repository to local
	git pull
git push                                                send changes in local to configured remote repository
	git push
git push origin <branch name>                           send branch to remote repository
	git push origin main
git remote                                              shows the remote repository origin
	git remote
git fetch                                               recuperates the changes made to a remote repository without making local changes

BRANCHES
git branch <branch name>                        create new branch
	git branch main
git checkout <branch name>                      move to a different branch
	git checkout main
git branch -d <branch name>                     delete branch
	git branch -d main 
git merge <branch name>                         merges that branch into the main branch
	git merge second

GITFLOW
apt-get install git-flow                         install gitFlow in linux
	apt-get install git-flow
git flow init                                    initialize git flow
	git flow init
git flow feature start                           start a new feature branch and switch to it
	git flow feature start MYFEATURE
git flow feature finish                          merge feature branch to main develop branch
	git flow feature finish MYFEATURE
git flow feature publish                         push a feature branch to remote rep
	git flow feature publish MYFEATURE
git flow release start                           start a release
	git flow release start MYRELEASE
git flow release publish                         publish a release branch
	git flow release publish MYRELEASE
git flow release track                           track remote release
	git flow release track MYRELEASE
git flow release finish                          finish a release
	git flow release finish MYRELEASE

----------------------------------------------------------------------------------------------------------
These are commands we learned for working in the command line:
mkdir                                          create a new directory 
	mkdir newdirectory                                    
rmdir                                          remove directory
	Rmdir newdirectory
rm -r                                          remove directory & content
	Rm -r newdirectory
rm                                             remove
	Rm filename
cat                                            display lines of a file
        cat filename
History                                        displays the commands that have been used so far
	History
dir                                            displays the directories in the current directory
	dir
ls                                             displays the directories and files inside the current
	ls
cd                                             enters a directory
	cd directory
cd ..                                          Moves back one directory
	cd ..
pwd                                            shows the current location of the user
	pwd
nano                                           opens an editor for files
	nano filename
vim                                            opens an editor for files
	vim filename

