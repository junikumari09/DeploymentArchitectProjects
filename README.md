# Trailhead
Git commands 
git init -> Initialize the repo
git add. - > add to stage 
git commit -m " My commit"
To push the main repo, you first have to add the remote server to Git by running git remote add <url>
git push -u origin <branch-name>
How to Push a New Branch to Remote
If you have another branch you’ve worked at that you want to push to remote, you’ll still use the git push command, but in a slightly different way.

As a reminder, to create a new branch, you run git branch branch-name. And to switch to that branch so you can work there, you have to run git switch branch name or git checkout branch-name.

To push the branch to the remote server, run git push –u origin <branch name>. In my case, the name of that branch is bug-fixes. So, I have to run git push -u origin bug-fixes:

