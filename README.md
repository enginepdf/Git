VCS(Version Control System), Configuration Management Tool

Github : git web hosting service

## Flows

Git Flow : feature > develop > release > hotfix > main

GitHub Flow : branch name represents the things on working related at the moment
              push, pull request, merge into main, deployment after

GitLab Flow : Production branch added

## Traits 

1. Distributed development

2. Strong support for non-linear development

3. Efficient handling of large projects

4. Cryptographic authentication of history

5. Toolkit design


## Keywords

 - Repository(Git Directory) : a space for data with history, tag, branch

 - Working Tree : a specific version Checkout-ed from git directory
   (Repository), working directory

    Working directory -> (git add) -> Staged Snapshot -> (git commit) -> Committed Snapshots

 - Staging Area(Index area) : ready for committing, save the state 
   at the moment to 'index'
   
   'git add' command adds a change in the working directory to the staging area
   
 - Commit : save to the head(modified -> git add(staged) -> git commit -> head)

 - Head : currently working branch

 - Branch : independent working area

 - Merge : merging different two branches into one


