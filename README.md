C:\Users\maram>cd C:\Users\maram\OneDrive\Bureau\learn_git

C:\Users\maram\OneDrive\Bureau\learn_git>git init
Initialized empty Git repository in C:/Users/maram/OneDrive/Bureau/learn_git/.git/

C:\Users\maram\OneDrive\Bureau\learn_git>git add third.txt
fatal: pathspec 'third.txt' did not match any files

C:\Users\maram\OneDrive\Bureau\learn_git>git add third.docx

C:\Users\maram\OneDrive\Bureau\learn_git>git commit -m "adding third.docx"
[master (root-commit) 1a8e661] adding third.docx
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 third.docx

C:\Users\maram\OneDrive\Bureau\learn_git>git log
commit 1a8e661aff10ffe41659b15cf7b5a0b1d0b8e459 (HEAD -> master)
Author: maram <hmedamaram@gmail.com>
Date:   Sun Jul 14 19:09:44 2024 +0100

    adding third.docx

C:\Users\maram\OneDrive\Bureau\learn_git>git add fourth.docx

C:\Users\maram\OneDrive\Bureau\learn_git>git commit -m  "adding fourth.docx"
[master 5b46d08] adding fourth.docx
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 fourth.docx

C:\Users\maram\OneDrive\Bureau\learn_git>git rm third.docx
rm 'third.docx'

C:\Users\maram\OneDrive\Bureau\learn_git>git add .

C:\Users\maram\OneDrive\Bureau\learn_git>git commit -m "removing third.docx"
[master 235e829] removing third.docx
 1 file changed, 0 insertions(+), 0 deletions(-)
 delete mode 100644 third.docx

C:\Users\maram\OneDrive\Bureau\learn_git>git log
commit 235e829677f29f7f904a2835a674db1819cdffd7 (HEAD -> master)
Author: maram <hmedamaram@gmail.com>
Date:   Sun Jul 14 19:15:08 2024 +0100

    removing third.docx

commit 5b46d08ca0f4d2483b96c8e96b09e65306d9d985
Author: maram <hmedamaram@gmail.com>
Date:   Sun Jul 14 19:13:13 2024 +0100

    adding fourth.docx

commit 1a8e661aff10ffe41659b15cf7b5a0b1d0b8e459
Author: maram <hmedamaram@gmail.com>
Date:   Sun Jul 14 19:09:44 2024 +0100

    adding third.docx

C:\Users\maram\OneDrive\Bureau\learn_git>git config --global core.pager=cat
error: invalid key: core.pager=cat

C:\Users\maram\OneDrive\Bureau\learn_git>git config --global core.pager = cat

C:\Users\maram\OneDrive\Bureau\learn_git>git config --global core.pager =cat

C:\Users\maram\OneDrive\Bureau\learn_git>git config --global core.pager =cat-

C:\Users\maram\OneDrive\Bureau\learn_git>git config --global core.pager 'cat'

C:\Users\maram\OneDrive\Bureau\learn_git>git config --global core.pager '=cat'

C:\Users\maram\OneDrive\Bureau\learn_git>git config --global cat
error: key does not contain a section: cat

C:\Users\maram\OneDrive\Bureau\learn_git>git config --global core.pager
'=cat'

C:\Users\maram\OneDrive\Bureau\learn_git>git config --global core.pager '=cat'

C:\Users\maram\OneDrive\Bureau\learn_git>git config --global core.pager cat

C:\Users\maram\OneDrive\Bureau\learn_git>git config --global --list
user.email=hmedamaram@gmail.com
user.name=maram
core.pager=cat

C:\Users\maram\OneDrive\Bureau\learn_git>git remote add origin  https://github.com/Maram141120/maram--hmida

C:\Users\maram\OneDrive\Bureau\learn_git>git push origin master
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 12 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (7/7), 627 bytes | 209.00 KiB/s, done.
Total 7 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/Maram141120/maram--hmida
 * [new branch]      master -> master

C:\Users\maram\OneDrive\Bureau\learn_git>git clone https://github.com/Maram141120/maram--hmida
Cloning into 'maram--hmida'...
remote: Enumerating objects: 7, done.
remote: Counting objects: 100% (7/7), done.
remote: Compressing objects: 100% (4/4), done.
remote: Total 7 (delta 0), reused 7 (delta 0), pack-reused 0
Receiving objects: 100% (7/7), done.

C:\Users\maram\OneDrive\Bureau\learn_git>git remote add origin https://github.com/Maram141120/maram--hmida.git
error: remote origin already exists.
