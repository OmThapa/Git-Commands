# Git-Commands
Simple daily used git commands

## GET & CREATE PROJECTS
<table border=0>
  <tr>
    <td>git init</td>
    <td>-	Initialize a local Git repository</td>
  </tr>
  <tr>
    <td>git clone</td>
    <td>ssh://git@github.com/[username]/[repository-name].git	(Create a local copy of a remote repository)</td>
  </tr>
  </table>


## DAILY USED GIT COMMANDS
<table border=0>
  <tr>
    <td>git status</td>
    <td>- Check status</td>
  </tr>
  <tr>
    <td>git add [file-name.txt]</td>
    <td>-	Add a file to the staging area</td>
  </tr>
  <tr>
    <td>git add -A</td>
    <td>- Add all new and changed files to the staging area</td>
  </tr>
  <tr>
    <td>git commit -m "[commit message]"</td>
    <td>- Commit changes</td>
  </tr>
  <tr>
    <td>git rm -r [file-name.txt]</td>
    <td>-	Remove a file (or folder)</td>
  </tr>
  </table>


## LOG
<table border=0>
  <tr>
    <td>git log --summary	</td>
    <td>- View changes (detailed)</td>
  </tr>
  <tr>
    <td>git log --oneline	</td>
    <td>- View changes (briefly)</td>
  </tr>
  <tr>
    <td>
      git diff [source branch] [target branch]</td>
    <td>- Preview changes before merging</td>
  </tr>
  </table>


## BRANCH
<table border=1>
  <tr>
git branch	                              - List branches (the asterisk denotes the current branch)
git branch -a	                            - List all branches (local and remote)
git branch [branch name]	                - Create a new branch
git branch -d [branch name]	              - Delete a branch
git push origin --delete [branch name]	  - Delete a remote branch
  </tr>
  </table>

## CHECKOUT
<table border=1>
  <tr>
git checkout -b [branch name]	                      - Create a new branch and switch to it
git checkout -b [branch name] origin/[branch name]	- Clone a remote branch and switch to it
git branch -m [old branch name] [new branch name]	  - Rename a local branch
git checkout [branch name]	                        - Switch to a branch
git checkout -	                                    - Switch to the branch last checked out
git checkout -- [file-name.txt]	                    - Discard changes to a file
  </tr>
  </table>

## MERGE
<table border=1>
  <tr>
git merge [branch name]	                            - Merge a branch into the active branch
git merge [source branch] [target branch]	          - Merge a branch into a target branch
git stash	                                          - Stash changes in a dirty working directory
git stash clear	                                    - Remove all stashed entries
  </tr>
  </table>
  
  
## PUSH
<table border=1>
  <tr>
git push origin [branch name]	                      - Push a branch to your remote repository
git push -u origin [branch name]	                  - Push changes to remote repository (and remember the branch)
git push	                                          - Push changes to remote repository (remembered branch)
git push origin --delete [branch name]	            - Delete a remote branch
git pull	                                          - Update local repository to the newest commit
git pull origin [branch name]	                      - Pull changes from remote repository
  </tr>
  </table>
  
  
## REMOTE
<table border=1>
  <tr>
git remote add origin ssh://git@github.com/[username]/[repository-name].git	(Add a remote repository)
git remote set-url origin ssh://git@github.com/[username]/[repository-name].git	(Set a repository's origin branch to SSH)
      </tr>
  </table>
