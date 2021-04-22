This is a compilation of the commands we've been using in git:
git init                              is used to start a new local repository with git
	git init
git clone <link to repository>        is used to create a copy of an existing repository
	git clone https://github.com/github/training-kit.git
git add <file name.file type>         is used to add certain files to the staging area
	git add file.c
<asterisk>                            basically, a replacement when you mean any type or any name of files
	git add *
git commit -m "<commit name>"         creating and naming a commit
	git commit -m "new commit"
git status                            show the current status of the files inside the directory
	git status
git diff                              show the changes made since the last commit
	git diff
git log                               shows the commits made so far
	git log
git log -p                            shows the changes made in the commits
	git log -p
git log -2                            shows the last commit
	git log -2
git reset                             takes out of staging area
	git reset
git reset HEAD                        takes last commit out of staging area
	git reset HEAD

REMOTE REPOSITORY
git remote add origin <link to remote repository>       adds a server where it is possible to push the commits
git remote -v                                           list all configured remote repositories
git pull                                                merge changes from remote repository to local
Git push                                                send changes in local to remote repository
Git push origin <branch name>                           send branch to remote repository
Git remote                                              shows the remote repository origin
Git fetch                                               shows the changes made to a remote repository

BRANCHES
Git branch <branch name>                        create new branch
Git checkout <branch name>                      move to a different branch
Git branch -d <branch name>                     delete branch 
Git merge <branch name>                         merges that branch into the main branch
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

