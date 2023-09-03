$ git init git
Initialized empty Git repository in C:/Users/Olya/Documents/git_traning/git/.git/

$ cd git

$ git pull
There is no tracking information for the current branch.
Please specify which branch you want to merge with.
See git-pull(1) for details.

git pull <remote> <branch>

 If you wish to set tracking information for this branch you can do so with:

git branch --set-upstream-to=<remote>/<branch> main


$ git remote add origin https://github.com/OlyaChernyavskaya/git.git

 $ git commit -m "contact inforamtion update"

$ git pull
	  remote: Enumerating objects: 3, done.
	  remote: Counting objects: 100% (3/3), done.
	  remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
	  Unpacking objects: 100% (3/3), 594 bytes | 15.00 KiB/s, done.
	  From https://github.com/OlyaChernyavskaya/git
	   * [new branch]      main       -> origin/main
	   There is no tracking information for the current branch.
	   Please specify which branch you want to merge with.
	   See git-pull(1) for details.

git pull <remote> <branch>

If you wish to set tracking information for this branch you can do so with:

git branch --set-upstream-to=origin/<branch> main



$ ls


$ git pull origin main
From https://github.com/OlyaChernyavskaya/git
 * branch            main       -> FETCH_HEAD


$ ls
README.md


$ touch Commands.md


$ vim Commands.md
      
$ git add Commands2.md
warning: in the working copy of 'Commands2.md', LF will be replaced by CRLF the next time Git touches it


$ git commit -m 'Commands2 added'
[main 1e6e729] Commands2 added
 1 file changed, 56 insertions(+)
 create mode 100644 Commands2.md


$ git push -u origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 893 bytes | 446.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/OlyaChernyavskaya/git.git
   ea3dd8e..1e6e729  main -> main
branch 'main' set up to track 'origin/main'.
