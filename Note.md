git init - Create Git Repository

Cloning Git Repository-----------------
git clone <repository URL>   - Download the repository to the local machine (computer)

Creating Files in the repository
cd repository   - Get in the repository folder

touch 'new file' - Create a new file in the repository (We need to use Git Bash Terminal)

Adding one file or multiple files to the tracking stages ------------------------
git add <new file name> - let Git know that it should be keeping track of the new file

git add .  - track all file within a current directory


Commit------------------
git commit -m "commited message" - To commit the changes made to the repository


git status - to see how our code compares to the code on theremote repository

Push to Github online ------------------
git push - to publish our local commits to Github


If you’ve only changed existing files and not created new ones, instead of using--------------------
git add .
and then
git commit -m "Some Message"

You can use this one :--------------
git commit -am "somemessage"

git pull - to pull any remotechanges to your repository.


Merge Conflits-------------------------------

Get the history of all commits --------------------------------
git log - To get all commit history of the repository


Revert to a specifice commit (version)-------------------------
One Way
git reset --hard <commit hash>  - reverts your code to exactly how it was after thespecified commit.


git reset --hard origin/master - reverts your code to the version currently storedonline on Github.

Branching==========================================================
git branch - To check which branch you are working on

git checkout -b <new branch name> - To make a new branch

git checkout <branch name> - To switch between branches

When we’re ready to merge our two branches together, we’ll check out the branch wewish to keep (almost always the master branch) and then run the command. This will be treated similarly to a push or pull, and mergeconflicts may appear.===============================================================
git merge <other branch name>



