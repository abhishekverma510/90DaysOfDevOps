   - **Setup & Config**  
      1. git init
      2. git config --global user.name "abhishekverma510"
      3. git config --global user.email "user.email"
   - **Basic Workflow**
      1. git clone ssh-url 
   - **Viewing Changes**
      1. git status
      2. git log 
   - **All common git commands**
       1. git add filename
       2. git commit -m "Message passed"
       3. git branch - to check current branch 
       4. git checkout -b feature-1 - to create a branch and switch on a single command
       5. git switch feature-2 - to switch branch
       6. git branch -d feature-1 -> To delete a branch softly but you should not run delete command on same branch.  
       8. git push origin --delete feature-1 -> to delete a branch on remote
          ### NOTE : Always create a branch when you connected(clone) with remote repo otherwise , it will not work.  
       9. git restore --staged index.html -> to restore the file from stage to unsatge
      10. git pull origin main
      11. git push origin main
      12. git clean -f -> to clean Untracked files from status , it will work when conflicts created during merge process.
      13. git reset --hard 50b5487 -> its deleted all the logs which are created from intial commit.
      14. git revert -> git revert b68c56c - Always revert from the head or last changes because it is working recurvisely. 
       
      