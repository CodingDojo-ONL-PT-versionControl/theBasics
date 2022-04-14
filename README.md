# The Basics

Terminal aliases - .zshrc for mac or .bashrc for windows (you might have to create)
lines 44-51 are for mac to show folder path and git branch (windows shows these by default) (suggest to be for your mac)

## Terminal Command Basics
- ls => provides a list of what in the current location
- ls -a => shows hidden too
- pwd => pwd
- cd => moves you around between folders
- mkdir => creates a folder (be sure to leave no spaces)
- rm => remove or delete
- rmdir => to remove folder
- touch => creates a blank file in given location
- code => will either open requested file or create and open

https://python-instructormelissa.github.io/terminalGit/

## Git Command Basics
- git init => creates a local repository (when using this create the git repo with NO readme or gitignore)
- git clone => https://(token)@github.com(rest of repo link).git
- git status => shows what files have been added, deleted, or modified since last talking to github
- git add (file name) or * or . (* and . will add all changes) - gitignore doesn't always get added through * or .
- git commit -m "" => between quotes goes a relevant message and this command creates a snapshot
- git push => pushes the committed changes to github or other version control services
- git pull => brings all changes on the remote repo down to your device


to add the repo link to a repo you created locally first => git remote set-url origin https://<token>@github.com/<username>/<reponame>.git



Just adding content