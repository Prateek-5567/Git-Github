# git clone [url]
    - clone a repo on our local machine.
    local machine means my laptop/device.
<br>

# git status 
    - displays the state of the code i.e any modification in code as compared to last saved checkpoint.
 <br> types of status:-
            Untracked - new files that git doesn't yet tracked.
            Modified - changes in tracked files.
            UnModified - unchanged all files.
            Staged - after you add any file (git add files) they go in staging area ( Staged Files ).
<br>
remote means - on github server.
<br>

-> M : modified file.
-> U : untracked file.

# to save changes on github is a two step process : 
    add  ->  commit

after <git add . > files goes into staging area.
now after doing git add <filename> if you check status ; the staged files will look green and others red as usual if any.
after staging files are ready to be commited.

# NOW TO PUSH THE CHANGES WHICH ARE SAVED ON OUR LOCAL DEVICE TO REMOTE SERVER I.E TO GITHUB WE HAVE TO USE git push origin main (or push to any other branch.)

<git push origin main>  : mostly this is used to push all changes upto last commit to github repository that is cloned on your github. 
{local -> remote}
here 'origin' : means jaha se hamne repo ko clone kia tha i.e the origin of our repo.
'main' : it is origin in origin of our repo we can create more branches also.

<git log>
The git log command is used to display the commit history of a Git repository, showing a list of all commits made in reverse chronological order, starting with the most recent one