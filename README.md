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
       
       
