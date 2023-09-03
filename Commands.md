$ git init testOlyaChe

$ git clone https://github.com/OlyaChernyavskaya/testOlyaChe.git
Cloning into 'testOlyaChe'...
remote: Enumerating objects: 6, done.
remote: Counting objects: 100% (6/6), done.
remote: Compressing objects: 100% (4/4), done.
remote: Total 6 (delta 0), reused 3 (delta 0), pack-reused 0
Receiving objects: 100% (6/6), done.

git clone git@github.com:testrusau/testrusau.git 

cd testrusau

git push git@github.com:osukhorukova/testrusau.git main:main

$ ls
testOlyaChe/

$ cd 
.git/ testOlyaChe/

$ cd testOlyaChe/

$ ls
README.md

$ vim README.md

$ git add README.md 

$ git commit -m "name section changes"
  [main 46a8570] name section changes
  1 file changed, 2 insertions(+), 3 deletions(-)

  $ git push
  Enumerating objects: 5, done.
  Counting objects: 100% (5/5), done.
  Delta compression using up to 4 threads
  Compressing objects: 100% (2/2), done.
  Writing objects: 100% (3/3), 323 bytes | 161.00 KiB/s, done.
  Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
  remote: Resolving deltas: 100% (1/1), completed with 1 local object.
  To https://github.com/OlyaChernyavskaya/testOlyaChe.git
  0626f1a..46a8570  main -> main


  $ vim README.md

  $ git add README.md

  $ git commit -m "contact inforamtion update"
  [main fcd737a] contact inforamtion update
  1 file changed, 1 insertion(+), 1 deletion(-)

  $ git push
  Enumerating objects: 5, done.
  Counting objects: 100% (5/5), done.
  Delta compression using up to 4 threads
  Compressing objects: 100% (2/2), done.
  Writing objects: 100% (3/3), 368 bytes | 368.00 KiB/s, done.
  Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
  remote: Resolving deltas: 100% (1/1), completed with 1 local object.
  To https://github.com/OlyaChernyavskaya/testOlyaChe.git
  46a8570..fcd737a  main -> main

  $ vim README.md

  $ git add README.md

  $ git commit -m "social media update"
  [main a6d0436] social media update
   1 file changed, 3 insertions(+), 3 deletions(-)

    (failed reverse-i-search)`psh': git clone htt^C://github.com/OlyaChernyavskaya/testOlyaChe.git

    $ git push
    Enumerating objects: 5, done.
    Counting objects: 100% (5/5), done.
    Delta compression using up to 4 threads
    Compressing objects: 100% (2/2), done.
    Writing objects: 100% (3/3), 341 bytes | 341.00 KiB/s, done.
    Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
    remote: Resolving deltas: 100% (1/1), completed with 1 local object.
    To https://github.com/OlyaChernyavskaya/testOlyaChe.git
    fcd737a..a6d0436  main -> main01

