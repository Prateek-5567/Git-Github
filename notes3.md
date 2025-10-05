# lets say our main branch that we cloned had only REACT repository now we came out of REACT repo 
# and created a new directory/folder/repo on same level or higher level than 'REACT'

In this folder (here) to initialise git use : git init (this is now initialised repository).
if you do : ls -a   ; you will see .git means it is a git repo.

now it has become a git repo and other things after this are same
    - same steps that we followed in a cloned repository
git status ; git add . ; git commit ; git push origin main  ;
BUT BUT BUT : AS THIS IS ALSO A REPO YOU CAN NOT COMMIT IT INTO THE SAME CLONED REPO - "REACT" 
YOU NEED TO CREATE ANOTHER DEMO REPOSITORY THEN COMMIT THIS REPO THERE.

if you are ever stuck in vim editor of git press esc to come out of insert mode then type ":q!" + return.

now create a new repository and that must be empty totally without any readme.md file otherwise git clone krna hoga 
but what I WANT ki mera ye folder kisi git repo me chla jaye naki koi git ki repo meri cwd me aajaye.
git clone : git repo bring in my cwd
git init and git remote add origin : send my current folder to any git repo.

## To undo a commit in Git, choose the method based on whether the commit has been pushed to the remote repository or not:

# For Local (Not Pushed) Commits
a. Keep changes from the commit but remove the commit:

    git reset --soft HEAD~1
    
    This will undo the last commit, but your changes will remain staged for commit.

b. Remove the commit and discard changes:

    git reset --hard HEAD~1
    
    This command deletes the last commit and all related changes in the working directory.

In Git, HEAD~1 means "the commit before the current HEAD". 

