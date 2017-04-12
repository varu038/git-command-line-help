
Working with remote branch : 

For making changes to the remote branch first clone it to your local machine : 

git clone https://github.com/varu038/git-command-line-help.git

Once done either 

a. make changes to master branch itself and push from there or 
    Edit the file you want to make changes into.
    
    To see the diff try : 
    git diff

    To check status:
    git status

    Once changes are done and everything is fine, add the changes to staging area or index.
    git add -A (add everything under this)

    Then to git commit to commit changes to the local master branch.
    git commit -m "msg for commit"

    Then to push the changes to remote master branch : 
    git push

    Once done go to the project on github create pull request and merge the changes to master.


b. create a new branch and push the new branch to remote.
    To see which is your current branch you are working on : 
    git branch
    git branch -a (To see all the branches made from this repository)

    To create a new branch and change into that branch :  
    git checkout -b newBranch
    
    make changes and same steps to commit to local branch as above.

    Once the changes are done committed to local branch to push the branch to remote repository : 
    git push --set-upstream origin newBranch

    Once these changes are done and newBranch is created on remote repository to merge changes to master create pull request and merge the change into master.

