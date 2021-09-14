# GIT CHEAT SHEET


## Basics
- git help <command>: get help for a git command   
- git init: creates a new git repo, with data stored in the .git directory
- git status: tells you what’s going on
- git add <filename>: adds files to staging area
- git commit -m "commit msg": creates a new commit
- git log: shows a flattened log of history
- git checkout <revision>: updates HEAD and current branch

![](img/git_tavle.JPG)

## Branching and merging
- git branch: shows branches
- git branch <name>: creates a branch
- git checkout -b <name>: creates a branch and switches to it
	- same as git branch <name>; git checkout <name>
- git merge <revision>: merges into current branch

### Configuration
- .gitignore: file for specifying which files should not be included in commits
	- [example (simple):](materialer/gitignore_simple.txt)
	- [example (IntelliJ):](materialer/gitignore.txt)
	


## Remotes (Github)
__kommer senere__


