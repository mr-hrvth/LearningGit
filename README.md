# LearningGit
Create scenarios to better understand the workings of git

## Scenarios

## Simulate two developers using the same branch (example1)
1. Create folder dev1 and dev2 by copying the repository
2. dev1 adds its changes and commits locally
3. dev2 adds its changes and commits locally
4. dev1 pushes its changes to remote
5. dev2 pushes its changes to remote and fails git reports you have to pull first.
6. dev2 pulls the changes and git tries to create new commit with message "Merge branch 'example1' of https://github.com/mr-hrvth/LearningGitExamples into example1" and reports that there are merge conflicts that need to be resolved.
7. dev2 manually creates the final state of the file by resolving the conflicts and can finalize the previous commit
8. dev2 pushes his final state to remote

## Two developers using their own branch
We always create two branches from the original, do some changes and merge them back to original branch

### Change only new branches non conflicting way
We add/change/remove different lines

### Change only new branches conflicting way
We add/change/remove the same lines with different content

### Change original branch as well non conflicting way

#### Before changes in new branches

#### After changes in new branches

#### Somewhere during the changes in the new branches
