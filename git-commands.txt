# testing
git remote  # list remove connection you have to the repositories
git remote -v same as above but inlcude URL
git remote add <name> URL  # name is the shortcut for long URL
git remote rm <name>
git remote <old	name> <new name>
git remote add john http://....
git fetch <remote> # fetch all branches	from remote
git fetch remote branch
git branch -r #	 to view	remote branches	
git fetch origin
git checkout master
git log	     origin/master
git merge origin/master

git reset <commit> # this reset	the staging area to match but leaves the
      	                working directory alone
git reset --hard   # reset both	the staging and	working	directory

You should never use git rest <commit> when any	snapshot after commit
has been pushed to public repository

git checkout master
git checkout <commit> file  e.g. git checkout a1e88b4 hello.py
git log	     -- oneline
git checkout <commit>
git revert HEAD	 # To revert to	commit just created
get reset <file> # To remove the specified file	from staging area
      	            but leave the working directory unchanged. This
      		                 unstage the file without overwriting	any changes

git init
git add
git commit
git clone git://github.com/..../tcigit.git

cd ticgit
git remote origin
git remote -v show you rrl git has stored for short hand
git push <remote-name> <brnach-name> # git push	    origin master



detached head
cherry pick
