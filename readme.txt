1. If we run [git push --set-upstream origin master], it will only push master branch. If you have other branch, then it wont push.
2. Now, run [git push origin feature/print-hello-world] and you will see this in feature/print-hello-world, but not in master.
2.5 Now you can see this in master because I have merge from feature/print-hello-world

From now on: (branch) means current branch
3. (feature/print-hello-world) [git merge master]: Means, I'm on feature/print-hello-world and I want to merge everything in master into my branch
4. If this error pops up: rror: 
"Your local changes to the following files would be overwritten by checkout:
        readme.txt
Please commit your changes or stash them before you switch branches.
Aborting"
You need to either commit or stash it first. If you complete development - commit. If in working - stash.
5. Running git stash pop make all your changes appear