
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
