### Configuration Commands

| Command | Description |
| --- | ----------- |
| ```git config --global -l``` | Shows current global configurations. |
| ```git config --global user.name <name>``` | Sets global user name. |
| ```git config --global user.mail <mail>``` | Sets global user mail. |
| ⚠️ ```git config --global core.editor <editor name>``` | Sets default editor. |

### General Commands

| Command | Description |
| --- | ----------- |
| ```git init``` | Initialize git repository. |
| ```git status``` | Shows current status of staging area. |
| ```git add <file name>``` or ```git add .``` | Current working directory changes or untraced files adds in staging area. |
| ```git rm --cached <file name>``` | Removes the file only from the Git repository, but not from the file system. |
|⚠️ ```git restore <file name>``` | Unstage or even discard uncommitted local changes. |
| ```git commit -a -m <message>``` | Commits all changes in repository without staging area adding. |
| ```git log``` | Shows commit history. 
| ```git commit --amend -m <message>``` | Changes last commits message. |
| ```git checkout <commit hash>``` | Back to specified commit. |
| ```git checkout <branch>``` | Switching between branches. | 
| ```git reset <filename>``` | Staging area changes back to the working directory. | 
| ```git branch``` | Shows all and active branch. | 
| ```git branch -v``` | Shows all branchs with last commit hash and messages. | 
| ```git branch <name>``` | Creates new branch with specified name. | 
| ```git checkout -b <name>``` | Creates new banch with specified name and activate branch. | 
| ```git branch -d <name>``` | Removes specified branch. | 
| ```git checkout <name>``` | Activate specified branch. |

### Stash Commands

| Command | Description |
| --- | ----------- |
| ```git stash``` | Temporarily saves changes without committing |
| ```git stash list``` | Shows stash list |
| ```git stash pop``` | Pulls the most recent stash from history, makes the appropriate changes to files in the local workspace and then deletes that entry from the stash history. |
| ```git stash apply <stash@{x}>``` | Applies specified stash in the local workspace without removing stash list. |
| ```git stash drop "stash@{x}" ``` | Removes specified stash from stash list. |

### Other Commands

| Command | Description |
| --- | ----------- |
| ```git config --global alias.<alias name> '<git commands>'``` | Creates shortcuts to frequently used Git commands. |
| ⚠️ ```git diff``` | Shows changed files contents between working directory and staging area. |
| ```git diff HEAD``` | Shows changed files contents between working directory and last commit. |
| ```git diff --staged HEAD``` | Shows changed files contents between staging area and last commit. |
| ```git diff <1th commit hash> <2th commit hash>``` | Shows changed files contents between specified two commits. |
| ```git merge <branch> --no-ff``` | In fast forward case disables fast forward merge. |
| ```git clone <project link>``` | Clones git project from remote repository. |
| ```git remote -v``` | Shows related remote repository links with current git project. |
| ```git remote add <alias> <repo link>``` | Adds alias to specified remote repository link. |
| ```git push <repo alias>``` or ```<repo link> <remote branch name>``` | Pushs commits to remote repository with specified remote branch. |

| ``` ``` |  |
| ``` ``` |  |
| ``` ``` |  |
| ``` ``` |  |
| ``` ``` |  |
| ``` ``` |  |
| ``` ``` |  |


















