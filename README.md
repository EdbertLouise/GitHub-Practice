**GitHub practice**

Lines:
- git add -A
- git commit -m "message"
- git push -u origin main [origin = The remote repository link]
- git checkout {branch}
- git branch {branch}
- git checkout -b {branch}
- git branch -d {branch}

Merge process:
git checkout <target-branch>    
git pull origin <target-branch>  

git checkout <feature-branch>   
git pull origin <feature-branch> 

git checkout <target-branch>   
git merge <feature-branch>

NOTE: files that aren't present in the feature branch will be deleted in the target branch
