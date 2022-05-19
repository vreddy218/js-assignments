# js-assignments
vredd218@LIN33003674 MINGW64 ~ (master)
$ mkdir js-assignment

vredd218@LIN33003674 MINGW64 ~ (master)
$ cd js-assignment

vredd218@LIN33003674 MINGW64 ~/js-assignment (master)
$ git init
Initialized empty Git repository in C:/Users/VREDD218/js-assignment/.git/

vredd218@LIN33003674 MINGW64 ~/js-assignment (master)
$ git add README.txt

vredd218@LIN33003674 MINGW64 ~/js-assignment (master)
$ git add READE.txt
fatal: pathspec 'READE.txt' did not match any files

vredd218@LIN33003674 MINGW64 ~/js-assignment (master)
$ git add README.txt

vredd218@LIN33003674 MINGW64 ~/js-assignment (master)
$ touch READE.txt

vredd218@LIN33003674 MINGW64 ~/js-assignment (master)
$ touch README.txt

vredd218@LIN33003674 MINGW64 ~/js-assignment (master)
$ git add README.txt

vredd218@LIN33003674 MINGW64 ~/js-assignment (master)
$ git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   README.txt

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        READE.txt


vredd218@LIN33003674 MINGW64 ~/js-assignment (master)
$ git commit -m 'README.txt file comited'
[master (root-commit) 53d5aff] README.txt file comited
 Committer: Reddy Muppana <venkata-sataya-sai-ram.reddy@capgemini.com>
Your name and email address were configured automatically based
on your username and hostname. Please check that they are accurate.
You can suppress this message by setting them explicitly. Run the
following command and follow the instructions in your editor to edit
your configuration file:

    git config --global --edit

After doing this, you may fix the identity used for this commit with:

    git commit --amend --reset-author

 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 README.txt

vredd218@LIN33003674 MINGW64 ~/js-assignment (master)
$ git status
On branch master
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        READE.txt

nothing added to commit but untracked files present (use "git add" to track)

vredd218@LIN33003674 MINGW64 ~/js-assignment (master)
$ touch js-assignments

vredd218@LIN33003674 MINGW64 ~/js-assignment (master)
$ git pull
There is no tracking information for the current branch.
Please specify which branch you want to merge with.
See git-pull(1) for details.

    git pull <remote> <branch>

If you wish to set tracking information for this branch you can do so with:

    git branch --set-upstream-to=<remote>/<branch> master


vredd218@LIN33003674 MINGW64 ~/js-assignment (master)
$ git branch js-assignments

vredd218@LIN33003674 MINGW64 ~/js-assignment (master)
$ git switch js-assignments
Switched to branch 'js-assignments'

vredd218@LIN33003674 MINGW64 ~/js-assignment (js-assignments)
$ git checkout master README.txt
Updated 0 paths from 62e47c7

vredd218@LIN33003674 MINGW64 ~/js-assignment (js-assignments)
$ git status
On branch js-assignments
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        READE.txt
        js-assignments

nothing added to commit but untracked files present (use "git add" to track)

vredd218@LIN33003674 MINGW64 ~/js-assignment (js-assignments)
$ touch file.txt

vredd218@LIN33003674 MINGW64 ~/js-assignment (js-assignments)
$ git add -A
vredd218@LIN33003674 MINGW64 ~/js-assignment (js-assignments)
$ git status
On branch js-assignments
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   READE.txt
        new file:   file.txt
        new file:   js-assignments


vredd218@LIN33003674 MINGW64 ~/js-assignment (js-assignments)
$ git switch master
Switched to branch 'master'
A       READE.txt
A       file.txt
A       js-assignments

vredd218@LIN33003674 MINGW64 ~/js-assignment (master)
$ touch file.js

vredd218@LIN33003674 MINGW64 ~/js-assignment (master)
$ git add -A

vredd218@LIN33003674 MINGW64 ~/js-assignment (master)
$ git status
On branch master
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   READE.txt
        new file:   file.js
        new file:   file.txt
        new file:   js-assignments


vredd218@LIN33003674 MINGW64 ~/js-assignment (master)
$ git stash
Saved working directory and index state WIP on master: 53d5aff README.txt file comited

vredd218@LIN33003674 MINGW64 ~/js-assignment (master)
$ git switch master
Already on 'master'

vredd218@LIN33003674 MINGW64 ~/js-assignment (master)
$ git merge js-assignments
Already up to date.

