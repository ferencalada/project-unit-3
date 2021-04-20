This is a compilation of the commands we've been using in git:
git init                              is used to create a new local repository with git
git clone <link to repository>        is used to create a copy of an existing repository
git add <file name.file type>         is used to add certain files to the staging area
<asterisk>                            basically, a replacement when you mean any type or any name of files
git commit -m "<commit name>"         creating and naming a commit
git status                            show the current status of the files inside the directory
git diff                              show the changes made isnce the last commit
git log                               shows the commits made so far
Git log -p                            shows the changes made in the commits
Git log -2                            shows the last commit
Git reset                             takes out of staging area
git reset HEAD                        takes last commit out of staging area

REMOTE REPOSITORY
git remote add origin <link to remote repository>       adds a server where it is possible to push the commits
git remote -v                                           list all configured remote repositories
git pull                                                merge changes from remote repository to local
Git push                                                send changes in local to remote repository
Git push origin <branch name>                           send branch to remote repository
Git remote                                              shows the remote repository origin
Git fetch                                               shows the changes made to a remote repository

