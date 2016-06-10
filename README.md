# PartyOn

## Overview
Party organizer tool

## Miscellaneous
1. 
	Two branches under this git repository: experiment and master.
	Since this app is in the early stage of development
	Different branches are independent before merging
	I recommend all team members use experiment branch to play around
	and switch to master branch for app building.

	**Switch to a branch**
	'git checkout master' to switch to master branch
	'git checkout experiment' to switch to experiment branch

	More on merge upcoming later.

2. **Git Etiquette**

	1. Follow this process every time you make changes:

		1. stage any changes: 'git add filename'
			 or stage all modifications: 'git add -A'
		
		2. commit changes after staging: 'git commit -m "message"'
		   (**Must add meaningful commit messages**)

		3. push everything: 'git push origin master' if on master branch
		   'git push' on any other branch
  
  2. **Always pull before you push**
     Otherwise, there could be other ppl already pushed things which you didn't pull. Then you got a merge confict, and git would maliciously remove all the changes you teammate pushed before.
     So always pull before you push.

  3. Some useful git commands:

  	 'git stash'
  	 Erasing all local changes. Use it when you wanna switch branches but don't want to commit anything yet.

     'git status'
     See dirty state (list of all your modified files, whether commited or uncommitted)
     Very handful to use before commit, so you know what files to stage

     More info upcoming.
