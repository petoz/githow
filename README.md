# githow
created new on github without readme

cmds on linux:

mkdir githow
cd githow/
echo "# githow" >> README.md
- git init
- git add README.md
- git commit -m "first commit"
-  git remote add origin git@github.com:petoz/githow.git
 - git push -u origin master
- end on cmds

git pull to synch changes on other comp
[root@localhost githow]# git pull
remote: Counting objects: 3, done.
remote: Compressing objects: 100% (2/2), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (3/3), done.
From github.com:petoz/githow
   c88a1ca..00f2091  master     -> origin/master
Updating c88a1ca..00f2091
Fast-forward
 README.md |   14 ++++++++++++++
 1 files changed, 14 insertions(+), 0 deletions(-)


