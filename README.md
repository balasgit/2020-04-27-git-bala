
# GIT Lessons

## Notes for Local 

-int : create a git repository in current directory
  - no nested git repo
  - 
-status : Tells you whats going on
-add : put files in the stagging area
- commit: commit the stageing area with a message
-log : Look at all commit history you have been doing
- diff : look at differences between current state and what git knows
- Checkout: Moving out head
     - checkout <HASH> <file> : restores files from the <hash>
     - checkout <HASH> : move head to that location

## Notes for remote
- remote: a place where a git repo is stored

- git push origin master: to push a master brnach on our local computer to remote name

##Branches

- `git branch <branch_name>` : Create a new branch
- `git switch <branch_name>` : Move to a branch
    - `git checkout <branch_name>

- `git stash`: temp saves current state as a commit so you can `checkout` or `switch`
      - `git stash apply` to apply the last stash from the stack

##Pull Requests (Online Merge)

- `git push origin <branchname>` : pushes branch to the remote
     - this is from you will create the PR (online)
     - you merge PR by accepting and merging PR
- Dont forget to clean up your branches
- `git fetch --prune`: clean up references in your git log --online --graph
- `git branch -d <Branch_name>`: delete branch

