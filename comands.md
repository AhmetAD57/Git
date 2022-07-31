### Configuration Comands

| Comand | Description |
| --- | ----------- |
| ```git config --global -l``` | Shows current global configurations. |
| ```git config --global user.name <name>``` | Sets global user name. |
| ```git config --global user.mail <mail>``` | Sets global user mail. |
| ⚠️ ```git config --global core.editor <editor name>``` | Sets default editor. |

### Comands

| Comand | Description |
| --- | ----------- |
| ```git init``` | Initialize git repostory. |
| ```git status``` | Shows current status of staging area. |
| ```git add <file name>``` or ```git add .``` | Current working directory changes or untraced files adds in staging area. |
| ```git rm --cached <file name>``` | Removes the file only from the Git repository, but not from the filesystem. |
|⚠️ ```git restore <file name>``` | Unstage or even discard uncommitted local changes. |
| ```git commit -a -m <message>``` | Commits all changes in repostory without staging area adding. |
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
| ```git checkout <name>``` | activate specified branch. |
















