<!-- Branching -->
What command do you use to create a branch?
- "git branch <branch-name>" or "git branch -b <branch-name>" to create a new branch and checkout the new branch
What command do you use to use a different branch?
- "git checkout <branch-name>"
Why would you want to use a branch other than the default master?
- The default master branch should be left to production code. Using a branch other than the default master while developing adds an additional safe guard to the development process and puts in place another round of verification before pushing the code to the public. 

<!-- Initializing, tracking, and committing -->
What command do you use to setup a git repository inside of your folder?
- "git init" #=> will initialize a git repository inside of the respective folder
What command do you use to ask git to start tracking a file?
- "git add <file>" #=> tells git which file(s) to track and stage 
What command do you use to ask git to move your file from the staging area to the repository?
- "git commit" #=> moves the files from the staging area to the repo (-m, allows a message describing the changes to be attached to the commit for faster referencing)
