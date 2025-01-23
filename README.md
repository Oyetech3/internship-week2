I created a repository in my local machine with git init and connected to remotely in my command line
I created a README file and save it with git add .
Then i committed the changes in the repo with git commit -m "committed"
I made sure of the branch i was in wit git branch -M main
Then i pushed the changes to the repo with git push -u origin main
Then i deleted the file in my local machine 
I cloned it back from my repo with git clone https://...
I made some changes and pushed it again
Then i manually made some changes in the repo , and i pulled it in my local machine
git pull origin main , then it matches
I created a new branch with git branch new-branch and moved to it with git checkout  new-branch
I created another with git checkout -b third-branch to create and move automatically 
I check all my branches with git branch
I committed and reverted the commit with git reset --soft HEAD~1
I set track on  the remote branch with git push --set-upstream origin main
I fetch update with git fetch
Then i merged the new-branch and third-branch together with git merge new-branch
I renamed the third-branch with git branch -m another
Then i deleted it with git push origin --delete another afer being updated
Then i push the new branch and set upstream git push origin -u new-branch
I reverted a pull request with git revert -m 1 "revert"
I used some commands like git logs, diff , stash,etc
