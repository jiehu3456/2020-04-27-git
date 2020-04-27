# 2020-04-27-git

- init: creates a git repository in current directory
	- you should only do this once in a repository (i.e., no nested git repos)
- status: tells you what is going on
- add: put files into the staging area
- commit: commit the staging area with a message
	- `commit -m`: commit with the message without opening up text editor
- log: look at the commit history you've been doing
	- `log --oneline`: simple oneline log view
- diff: look at differences between current state and what git knows
- checkout: moving our head
	- `checkout <HASH> <file>`: restores files from the <HASH>
	- `checkout <HASH>`: moves HEAD to that location
		- `checkout master`: go back to our original place
- HEAD: place we're looking at right now on our computer
- remote: a place where the git repo is stored, e.g., GitHub
	- `remote add origin <URL>`: add a remote
- `push origin master`: push the master branch on our loacal computer to the remote name origin
- editing lines in different places is okay. You might get a merge conflict if you edited in the same location
