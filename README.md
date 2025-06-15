# learn-git

<details>

   # 🚀 Git & GitHub Cheat Sheet
    
    ## 🟢 Initialize / Clone
    ```bash
    git init                 # Initialize a new Git repo
    git clone <url>          # Clone a repo from GitHub
    git clone <url> <folder> # Clone into a specific folder
    ```


    ## 🟡 Config
    
    ```
    git config --global user.name "Your Name"        # Set global username
    git config --global user.email "you@example.com" # Set global email
    git config --list                                # Show current config
    ```

    ## 🔵 Status & Log
    
    ```
    git status            # Check repo status
    git log               # View commit history
    git log --oneline     # Compact commit history
    git log --graph       # Graph view of history
    ```

    ## 🟣 Add & Commit
    
    ```
    git add <file>        # Add file to staging
    git add .             # Add all files to staging
    git commit -m "msg"   # Commit with message
    git commit -am "msg"  # Add + commit in one step (tracked files only)
    ```
    
    ## 🟤 Branching
    
    ```
    git branch                # List branches
    git branch <name>         # Create new branch
    git checkout <name>       # Switch branch
    git checkout -b <name>    # Create + switch new branch
    git merge <branch>        # Merge branch into current
    git branch -d <name>      # Delete branch
    ```

    ## 🔴 Push / Pull / Fetch
    
    ```
    git remote add origin <url>  # Link to GitHub repo
    git push -u origin main      # First push, set upstream
    git push                     # Push to remote
    git pull                     # Pull + merge from remote
    git fetch                    # Fetch changes without merge
    ```
    
    ## 🟠 Stash
    
    ```
    git stash              # Save current work
    git stash pop          # Reapply stashed work
    git stash list         # List stashes
    git stash drop         # Remove a stash
    ```
    
    
    ## ⚫ Reset / Revert
    
    ```
    git reset --hard <commit> # Reset to commit (discard changes)
    git revert <commit>       # Create new commit that undoes commit
    ```
    
    ## ⚪ Tagging
    
    ```
    git tag                  # List tags
    git tag <tagname>        # Create tag
    git tag -a <tag> -m "msg" # Annotated tag
    git push origin <tag>    # Push tag
    git push --tags          # Push all tags
    ```
    
    
    ## 🟤 Useful
    
    ```
    git diff                 # Show unstaged changes
    git diff --staged         # Show staged changes
    git rm <file>             # Remove file + stage
    git mv <old> <new>        # Rename file + stage
    ```
    
    ## 🌍 Example GitHub workflow
    
    ```
    git init
    git add .
    git commit -m "First commit"
    git branch -M main
    git remote add origin https://github.com/yourname/yourrepo.git
    git push -u origin main
    ```

</details>


