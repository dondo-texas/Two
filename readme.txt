Microsoft Windows [Version 10.0.18363.1256]
(c) 2019 Microsoft Corporation. All rights reserved.

C:\Users\Don-Desktop>cd git
The system cannot find the path specified.

C:\Users\Don-Desktop>cd\

C:\>cd git

C:\Git>mkdir
The syntax of the command is incorrect.

C:\Git>mkdir test_repo

C:\Git>cd test_repo

C:\Git\test_repo>git init
Initialized empty Git repository in C:/Git/test_repo/.git/

C:\Git\test_repo>git commit
On branch master

Initial commit

nothing to commit (create/copy files and use "git add" to track)

C:\Git\test_repo>git add readme.txt

C:\Git\test_repo>


C:\Git\test_repo>git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   readme.txt


C:\Git\test_repo>git commit -m "added readme.txt"
[master (root-commit) 5ba5912] added readme.txt
 1 file changed, 1 insertion(+)
 create mode 100644 readme.txt

C:\Git\test_repo>git status
On branch master
nothing to commit, working tree clean
------------------------------------------------------------------
made some changes                                                                
------------------------------------------------------------------
C:\Git\test_repo>git status
On branch master
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   readme.txt

no changes added to commit (use "git add" and/or "git commit -a")

C:\Git\test_repo>git add .

C:\Git\test_repo>git status
On branch master
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   readme.txt


C:\Git\test_repo>git commit -m "2. made changes"
[master 939d4cb] 2. made changes
 1 file changed, 2 insertions(+), 1 deletion(-)

C:\Git\test_repo>