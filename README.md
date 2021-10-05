# usefull_github_commands
    How to upload an entire folder?
    Try GIT Bash, use the following codes to upload the whole folder.
    you need to use git developer settings Personal Access Tokens based login credentials
    Open Git Bash.
    cd projectname
    git init
    git remote add origin https://github.com/<username>/<repo>.git
    git remote -v (for checking current repository)
    git add -A (add all files)
    git commit -m 'Add files via upload'
    git pull --rebase origin master
    git push origin master
