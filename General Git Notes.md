# General Git Notes

push local branch to different remote branch
`git push origin local-name:remote-name`
**don't forget to pull on new branch if you want to update local branch after*

*show changes in staged commit*
`git status -v`

show changes in last commit
`git show $COMMIT`

revert to commit
`git checkout <commit>`

`git branch -d branch_name`
`git branch -D branch_name`
-d option short for --delete, deletes local branch, only if already pushed and merged with remote branches.
-D option short for --delete --force, deletes branch regardless of push and merge status, be careful using it

delete remote branch with
`git push <remote_name> --delete <branch_name>`
or
`git push <remote_name> :<branch_name>`

`






















