## 2020-04-27-git Git Lesson

# Notes for local
- `git init`: creates a git repository in current directory
	- You should only do this once in a repository (i.e., no nested git repos)
- `git status`: tells you what is going on
- `git add`: puts files into the staging area
- `git commit`: commits the staging area with a message
	- `git commit -m`: commit with the message without opening up text editor
- `git log`: looks at the commit history you've been doing
	- `git log --oneline`: simple oneline log view
- `git diff`: look at differences between current state and what git knows
- `git checkout`: moving our head
	- `git checkout <HASH> <file>`: restores the file from the <HASH>
	- `git checkout <HASH>`: moves HEAD to that location
		- `git checkout master`: go back to our original place
- HEAD: place we're looking at right now on our computer

# Notes for remote
- remote: a place where the git repo is stored, e.g., GitHub
	- `git remote add origin <URL>`: add a remote
- `git push origin master`: pushes the master branch on our local computer to the remote name origin
- Editing lines in different places is okay. You might get a merge conflict if you edit the same location
