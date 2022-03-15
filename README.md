# TestMerge
This is a test repository for understanding how merging works
### Merge Command
General process:
```
git checkout {branch}
git merge main{or branchname}
```
##### Example
The following is an example of how to merge the main files (main) to a branch (testbranch) 
First pull the changes to main branch, this can be skipped if you want to avoid changing local copy of main
```
git checkout main
git pull
```
Then checkout to the branch you want to merge
```
git checkout testbranch
git merge main
```

