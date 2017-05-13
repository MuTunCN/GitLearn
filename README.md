#git learn demo
1. git init
2. git add `file`OR`.`(mean all file)
3. git commit
4. git status
5. git diff `file`
6. git log (--graph can see branch)
7. git reset `HEAD^`(`^`'s number mean how many version you reset) OR `commit id`
8. git reflog (commed history)
9. git checkout -- `file` (reset all change)
10. git reset HEAD `file`(reset all chage after `add`)
11. git rm `file` (delete file)
12. git remote add origin `address`
13. git push -u origin master (the first push use `-u`)
14. git clone `address`
15. git checkout -b `dev` (equal git branch `dev`;git checkout `dev` )
16. git merge master (merge dev in master)
17. git merge master --no-ff -m "commit content" `dev`(merge forbid fast forward )
18. git branch -d dev(delete dev branch use -D dev can delete unmerge branch)
19. git stash (save this branch add version return to last commit)
20. git stash list
21. git stash pop (equals git stash apply ; git stash drop)
22. git remote -v (show remote git address)
23. git push origin master 
