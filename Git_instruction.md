## Working in the terminal ##
* **cd ..** - go to previous folder
* **cd <folder_name>** - go to folder
* **clear** - clears the terminal
* **ls** - show info about folders

## Create commits ##
* **git add *<file_name>*** - add versioning to a file
* **git add .** - add versioning to all files
* **git commit -m "massege"** - commit changes
* **git commit -am** - commit changes without command git add
* **git diff** - show the latest changes in commit

## Informations commands ##
* **git config user.name** - get user name
* **git config user.email** - get user email
* **git init** - initialize our repository
* **git status** - global status .git
* **git log** - view change history
* **git log --graph** - new view command git log
## Working with branch ##
* **git branch** - show branch with which you work
* **git branch <new_branch_name>** - create new branch
* **git checkout <hash_number>** - jumping on different versions of commits
* **git merge <branch_name>** - merge branch

## Working with GitHub ##
* **git clone < adress_repository >** - download repositories with GitHub in local git
* **git push** - transfer from local rapository to remote
* **git pull** - transfer from remote repository to local
* -> Action "Fork" - copy someone else's repository in your list
* -> Action "Contribute" -> "Open pull request" - Create pull request with changes for creator.

**! При ошибке "SSL certificate problem: self signed certificate in certificate chain"**
1. Disable SSL verification on Git globally: *git config --global http.sslVerify false*
2. Clone your repository: *git clone <your repo>*
3. Enable SSL verification on Git globally: *git config --global http.sslVerify true*
4. Change directory into your repo: *cd <your repo>*
5. Disable SSL verification only on your repository: *git config --local http.sslVerify false*
