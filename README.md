# tester
cause i'm dumb


this is change #1

Last login: Mon Oct  5 15:53:18 on ttys000
anthonys-mbp-3:~ AESteppe$ pwd
/Users/AESteppe
anthonys-mbp-3:~ AESteppe$ cd /Desktop
-bash: cd: /Desktop: No such file or directory
anthonys-mbp-3:~ AESteppe$ cd /Desktop/
-bash: cd: /Desktop/: No such file or directory
anthonys-mbp-3:~ AESteppe$ cd ~/
.CFUserTextEncoding  .cups/               Desktop/
.DS_Store            .dvdcss/             Documents/
.RData               .git/                Downloads/
.Rapp.history        .gitconfig           Library/
.Rhistory            .rstudio-desktop/    Movies/
.Trash/              .ssh/                Music/
.bash_history        .subversion/         Pictures/
.config/             Applications/        Public/
anthonys-mbp-3:~ AESteppe$ cd ~/
.CFUserTextEncoding  .cups/               Desktop/
.DS_Store            .dvdcss/             Documents/
.RData               .git/                Downloads/
.Rapp.history        .gitconfig           Library/
.Rhistory            .rstudio-desktop/    Movies/
.Trash/              .ssh/                Music/
.bash_history        .subversion/         Pictures/
.config/             Applications/        Public/
anthonys-mbp-3:~ AESteppe$ cd ~/D
Desktop/   Documents/ Downloads/ 
anthonys-mbp-3:~ AESteppe$ cd ~/D
Desktop/   Documents/ Downloads/ 
anthonys-mbp-3:~ AESteppe$ cd ~/Desktop/
anthonys-mbp-3:Desktop AESteppe$ git clone https://github.com/aesteppe/tester.git
Cloning into 'tester'...
remote: Counting objects: 3, done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (3/3), done.
Checking connectivity... done.
anthonys-mbp-3:Desktop AESteppe$ ls
Books		Documents	Movies		TV
Coding		Drivers		Music		tester
Coursera SWF	GitHubUDAClass	Pictures
anthonys-mbp-3:Desktop AESteppe$ cd tester
anthonys-mbp-3:tester AESteppe$ 
Display all 1441 possibilities? (y or n)
anthonys-mbp-3:tester AESteppe$ git status
On branch master
Your branch is up-to-date with 'origin/master'.

nothing to commit, working directory clean
anthonys-mbp-3:tester AESteppe$ git status
On branch master
Your branch is up-to-date with 'origin/master'.

Changes not staged for commit:
(use "git add <file>..." to update what will be committed)
(use "git checkout -- <file>..." to discard changes in working directory)

modified:   README.md

no changes added to commit (use "git add" and/or "git commit -a")
anthonys-mbp-3:tester AESteppe$ git add README.md 
anthonys-mbp-3:tester AESteppe$ git status
On branch master
Your branch is up-to-date with 'origin/master'.

Changes to be committed:
(use "git reset HEAD <file>..." to unstage)

modified:   README.md

anthonys-mbp-3:tester AESteppe$ git commit
Aborting commit due to empty commit message.
anthonys-mbp-3:tester AESteppe$ git commit -m "first commit"
[master 3e4a5b2] first commit
1 file changed, 3 insertions(+)
anthonys-mbp-3:tester AESteppe$ git status
On branch master
Your branch is ahead of 'origin/master' by 1 commit.
(use "git push" to publish your local commits)

nothing to commit, working directory clean
anthonys-mbp-3:tester AESteppe$ git push
warning: push.default is unset; its implicit value is changing in
Git 2.0 from 'matching' to 'simple'. To squelch this message
and maintain the current behavior after the default changes, use:

git config --global push.default matching

To squelch this message and adopt the new behavior now, use:

git config --global push.default simple

When push.default is set to 'matching', git will push local branches
to the remote branches that already exist with the same name.

In Git 2.0, Git will default to the more conservative 'simple'
behavior, which only pushes the current branch to the corresponding
remote branch that 'git pull' uses to update the current branch.

See 'git help config' and search for 'push.default' for further information.
(the 'simple' mode was introduced in Git 1.7.11. Use the similar mode
'current' instead of 'simple' if you sometimes use older versions of Git)

Counting objects: 5, done.
Writing objects: 100% (3/3), 274 bytes | 0 bytes/s, done.
Total 3 (delta 0), reused 0 (delta 0)
To https://github.com/aesteppe/tester.git
157c510..3e4a5b2  master -> master
anthonys-mbp-3:tester AESteppe$ 
