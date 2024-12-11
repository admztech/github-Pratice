# git init command:

when we create the new folder or project in our local system. that is not automatically a Git repository.
It is just regular folder.

To make it git respository use the command "git init". This is initializes that new created folder. we navigate folder and
write the "git init command" and press enter. Now git will used to track changes.

Once the respository is initialized, you can use commond like .

- git add
- git commit
- git push

The git init make the folder or respository Git respository locally on your system. not on the
Github.
How can to push the folder or Project onto GitHub remotally. because is only on our local system.

# git remote add origin <repository-link>

how can we new resposity to push onto the GetHub account.
To add the respository onto github we need to set new repositor on our GitHub account that respository is empty we did not
add any file init. and copy that repository link . We set that respository link as the remote using the "git remote add origin<repository-link>
git remote add origin <repository-link>.

- using "git remote -v " command check the link is set or not
- git branch : used to check the current branch.
- git bran -M : used to rename the branch
  now after set the remote link we need to push that respository to the remotely .

# git push origin main

Now we can push the localy repository changes to the remotely to origin . That origin is the link we set.
that is done now

# Git Branches

Branch is used to create the copy of respository or the project. Why we create the copy of project or respository.
We can work on the copy of project or respositoy so the main branch or main respositoy safe durining the changes.
All changes effect on the new created branch. We can perform following task on new created branch

- add feature
- test ideas
- fix mistake
  So our main branch will be remain safe or un effective untill the all change is is clear. if the new changes are good then we
  can combine that change our main branch or if not we can delete the new reate branch.

## branches commands

- git branch : That command is used to check the Current branch.
- git checkout : That command is used to navigate from one branch to anoth branch we write the 'git checkout' then menion the branch name

- git checkout -b : that command used to create the new branch "git checkout -b 'newbranchName'.
- git branch -d : That command used to delete the branch . we mention that branch name after it. if we want to delete the branch.
- git push --set-upstream origin : that command used to push your lcal branch to remote origin . that set the upstream new branch.
