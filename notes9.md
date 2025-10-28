# How to connect specific branch of a git repo to a folder

1. open a empty folder and select its path in terminal.
2. git init
3. git remote add origin https://github.com/username/repository.git
4. git remote -v 
    (verify the link)
5. git fetch origin 
    ( this will fetch all branches from origin but 
    only the branches will be fetched no code would be pulled from this nothing will merge.
    just the branches will come in staging area from where you can select a branch that you want to 
    connect.)
6. git checkout <branch>  
    ( content of that branch will auto load and only that branch will connect.)