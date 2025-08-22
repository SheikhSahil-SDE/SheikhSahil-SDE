# Create New Git 📄
  
  <br> - Creates a new, empty Git repository in the current directory (.git folder).: ```git init```
  <br> - Stages all changes: new, modified, and deletions across the repo.: ```git add --all```
  <br> - Interactive patch mode for the specified file: stage selected hunks of changes.: ```git commit -m "Message"```
  <br> - Records the staged snapshot with the provided message.: ```git remote add https://www.github.com/<git>.git```
  
# Git Local Changes ⬆️

<br> - Shows current branch, staged/unstaged changes, and untracked files.:```git status```
<br> - Stages all changes in the repository for the next commit — new files, modifications, and deletions.: ```git add --all```
<br> - Shows the last commit and author for each line in the file.: ```git add -p <file>```

# Git History 📝

<br> - Shows commit history for the current branch (most recent first).: ```git log```
<br> - Shows commit history affecting <file> with diffs (patches) for each commit.: ```git log -p <file>```
<br> - Shows the last commit and author for each line in the file.: ```git blame <file>```

# Git Branch 🔀

<br> - Lists all local and remote-tracking branches with their latest commits (-a) and verbose info (-v).: ```git branch -av```
<br> - Creates a new local branch pointer at the current commit.: ```git branch <new branch>```
<br> - Switches working directory to the specified branch (or commit).: ```git checkout <branch>``` 
<br> - Or Modern alternative: ```git switch <branch>``` (safer for branch switching).

# Git undo ⏪️

<br> - Resets the current branch and working tree to match the HEAD commit exactly.: ```git reset --hard HEAD```
<br> - Restores the version of <file> from HEAD into the working directory.: ```git checkout HEAD <file>```
<br> - Creates a new commit that inverts the changes introduced by ```<commitID>```, preserving history.: ```git revert <commitID>```
