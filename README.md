Command Learned Today

[git remote add TestGitHub_initFromLocal https://github.com/YulongXieGitHub/TestGitHub_initFromLocal.git]
[git remote -v show]
[git remote rm TestGitHub_initFromLocal]
[git push TestGitHub_initFromLocal master]
[git init]
[git status] 
[git log] to see commits
[git add .] to stage more than a single file	
[git rm Test02.txt] removed the already staged "Test02.txt"
[git branch MyBranch] to create a branch (it seems like only those files having not been committed will be in the branch???
[git checkout MyBranch] to checkout and work on the branch
[git checkout master]
[git merge MyBranch]
[git -a -m '###'] to to have the stage and commit steps into a single step
[git commit -a -m "change in master"] in master branch to stage and commit the change made on "Test02.csv"
[git merge master] to merge source (master) to desitination (MyBranch): Merge the change made during master branch and during MyBranch

[git stash]
[git stash apply]
[git remote add origin https://github.com/YulongXieGitHub/TestGitHub_initFromLocal.git
[git pull origin master] since there is already a "readme" file in github which is not in the local folder.
[git push origin master] to push everything created in local folder to github.com
    











# TestGitHub_initFromLocal

This exercise is to create a repository in local machine use "git init" and then push the files to the same named repository in github.com.

Process see "test02.csv"

# check the connected remote repositories

git remote --v

# disconnect a remote repository

git remote rm "destination name"

https://github.com/YulongXieGitHub/TestGitHub.git

Several Notes:


# check the connected remote repositories

git remote --v

# disconnect a remote repository

git remote rm "destination name"

https://github.com/YulongXieGitHub/TestGitHub.git

On can connect to multiple remote repositories such as:


[git remote add TestGitHub]               https://github.com/YulongXieGitHub/TestGitHub.git
[git remote add TestGitHub_initFromLocal] https://github.com/YulongXieGitHub/TestGitHub_initFromLocal.git

[git remote -v] will show:
----------------------------------------------------------------------------------------------------------------------
TestGitHub				https://github.com/YulongXieGitHub/TestGitHub.git (fetch)
TestGitHub				https://github.com/YulongXieGitHub/TestGitHub.git (push)
TestGitHub_initFromLocal		https://github.com/YulongXieGitHub/TestGitHub_initFromLocal.git (fetch)
TestGitHub_initFromLocal		https://github.com/YulongXieGitHub/TestGitHub_initFromLocal.git (push)
Origin					https://github.com/YulongXieGitHub/TestGitHub.git (fetch)
Origin					https://github.com/YulongXieGitHub/TestGitHub.git (push)
----------------------------------------------------------------------------------------------------------------------


When more than one repository is connected, push use the name instead of the [origin]


Note:  When exit from a local repository and enter another local repository, all remote connections for the previous local repository are gone.
       New remote connection to the github.com repositories need to established.
       
       
[git push TestGitHub_initFromLocal master] 