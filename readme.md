#Git Exercise

This project will be used for Git exercise & practice.

#TerminalLogs BUNDLE2 Exercise 1

```bash
DOLPHIX ELECTRONICS@DESKTOP-TJ49EDU MINGW64 ~/git-exercise (dev)
$ git checkout ft/bundle-2
Switched to branch 'ft/bundle-2'

DOLPHIX ELECTRONICS@DESKTOP-TJ49EDU MINGW64 ~/git-exercise (ft/bundle-2)
$ git status
On branch ft/bundle-2
nothing to commit, working tree clean

DOLPHIX ELECTRONICS@DESKTOP-TJ49EDU MINGW64 ~/git-exercise (ft/bundle-2)
$ git status
On branch ft/bundle-2
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        services.html

nothing added to commit but untracked files present (use "git add" to track)

DOLPHIX ELECTRONICS@DESKTOP-TJ49EDU MINGW64 ~/git-exercise (ft/bundle-2)
$ git add .

DOLPHIX ELECTRONICS@DESKTOP-TJ49EDU MINGW64 ~/git-exercise (ft/bundle-2)
$ git commit -m "create a services page"
[ft/bundle-2 5ee3938] create a services page
 1 file changed, 14 insertions(+)
 create mode 100644 services.html

DOLPHIX ELECTRONICS@DESKTOP-TJ49EDU MINGW64 ~/git-exercise (ft/bundle-2)
$ git push
fatal: The current branch ft/bundle-2 has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin ft/bundle-2

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.


DOLPHIX ELECTRONICS@DESKTOP-TJ49EDU MINGW64 ~/git-exercise (ft/bundle-2)
$     git push --set-upstream origin ft/bundle-2
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 551 bytes | 551.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote:
remote: Create a pull request for 'ft/bundle-2' on GitHub by visiting:
remote:      https://github.com/Algor-Fernand/git-exercise/pull/new/ft/bundle-2
remote:
To https://github.com/Algor-Fernand/git-exercise.git
 * [new branch]      ft/bundle-2 -> ft/bundle-2
branch 'ft/bundle-2' set up to track 'origin/ft/bundle-2'.

DOLPHIX ELECTRONICS@DESKTOP-TJ49EDU MINGW64 ~/git-exercise (ft/bundle-2)
```

#TerminalLogs BUNDLE 3 Exercise 1

```bash
DOLPHIX ELECTRONICS@DESKTOP-TJ49EDU MINGW64 ~/git-exercise (main)
$ git checkout ft/team-page 
Switched to branch 'ft/team-page'

DOLPHIX ELECTRONICS@DESKTOP-TJ49EDU MINGW64 ~/git-exercise (ft/team-page)
$ git status
On branch ft/team-page
nothing to commit, working tree clean

DOLPHIX ELECTRONICS@DESKTOP-TJ49EDU MINGW64 ~/git-exercise (ft/team-page)
$ git commit -m "add team page"
[ft/team-page 17e8268] add team page
 2 files changed, 12 insertions(+)
 create mode 100644 team.html

DOLPHIX ELECTRONICS@DESKTOP-TJ49EDU MINGW64 ~/git-exercise (ft/team-page)
$ git push
fatal: The current branch ft/team-page has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin ft/team-page

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.


DOLPHIX ELECTRONICS@DESKTOP-TJ49EDU MINGW64 ~/git-exercise (ft/team-page)
$     git push --set-upstream origin ft/team-page
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 437 bytes | 218.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote:
remote: Create a pull request for 'ft/team-page' on GitHub by visiting:
remote:      https://github.com/Algor-Fernand/git-exercise/pull/new/ft/team-page
remote:
To https://github.com/Algor-Fernand/git-exercise.git
 * [new branch]      ft/team-page -> ft/team-page
branch 'ft/team-page' set up to track 'origin/ft/team-page'.

DOLPHIX ELECTRONICS@DESKTOP-TJ49EDU MINGW64 ~/git-exercise (ft/team-page)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

DOLPHIX ELECTRONICS@DESKTOP-TJ49EDU MINGW64 ~/git-exercise (main)
$ git checkout -b ft/contact-page
Switched to a new branch 'ft/contact-page'

DOLPHIX ELECTRONICS@DESKTOP-TJ49EDU MINGW64 ~/git-exercise (ft/contact-page)
$ git checkout ft/team-page 
Switched to branch 'ft/team-page'
Your branch is up to date with 'origin/ft/team-page'.

DOLPHIX ELECTRONICS@DESKTOP-TJ49EDU MINGW64 ~/git-exercise (ft/team-page)
$ git log
commit 17e82682f64c51bffe86aa1c3a88110581460d88 (HEAD -> ft/team-page, origin/ft/team-page)
Author: Algor Fernand <algorfernand014@gmail.com>
Date:   Wed Jul 26 11:32:27 2023 +0200
commit 17e82682f64c51bffe86aa1c3a88110581460d88 (HEAD -> ft/team-page, origin/ft/team-page)
Author: Algor Fernand <algorfernand014@gmail.com>
Date:   Wed Jul 26 11:32:27 2023 +0200

    add team page

commit e13215b04d94ec36fbcf03bfc0ab2faaec7a5130 (origin/ft/bundle-2, ft/service-redesign, ft/bundle-2)
Author: Algor Fernand <algorfernand014@gmail.com>
Date:   Thu Jul 13 11:38:43 2023 +0200

    Terminal logs added in the readme

commit 5ee393858e4f849d98c63f924a0c42eeac53c00c
Author: Algor Fernand <algorfernand014@gmail.com>

DOLPHIX ELECTRONICS@DESKTOP-TJ49EDU MINGW64 ~/git-exercise (ft/team-page)
$ git checkout ft/contact-page 
Switched to branch 'ft/contact-page'

DOLPHIX ELECTRONICS@DESKTOP-TJ49EDU MINGW64 ~/git-exercise (ft/contact-page)
$ git cherry-pick  17e82682f64c51bffe86aa1c3a88110581460d8801~
fatal: bad revision '17e82682f64c51bffe86aa1c3a88110581460d8801~'
DOLPHIX ELECTRONICS@DESKTOP-TJ49EDU MINGW64 ~/git-exercise (ft/contact-page)
$ git checkout ft/team-page 
Switched to branch 'ft/team-page'
Your branch is up to date with 'origin/ft/team-page'.

DOLPHIX ELECTRONICS@DESKTOP-TJ49EDU MINGW64 ~/git-exercise (ft/team-page)
$ git log
commit 17e82682f64c51bffe86aa1c3a88110581460d88 (HEAD -> ft/team-page, origin/ft/team-page)
Author: Algor Fernand <algorfernand014@gmail.com>
Date:   Wed Jul 26 11:32:27 2023 +0200

    add team page

commit e13215b04d94ec36fbcf03bfc0ab2faaec7a5130 (origin/ft/bundle-2, ft/service-redesign, ft/bundle-2)
Author: Algor Fernand <algorfernand014@gmail.com>
Date:   Thu Jul 13 11:38:43 2023 +0200

    Terminal logs added in the readme

commit 5ee393858e4f849d98c63f924a0c42eeac53c00c
Author: Algor Fernand <algorfernand014@gmail.com>

DOLPHIX ELECTRONICS@DESKTOP-TJ49EDU MINGW64 ~/git-exercise (ft/team-page)
$ git checkout ft/contact-page 
Switched to branch 'ft/contact-page'

DOLPHIX ELECTRONICS@DESKTOP-TJ49EDU MINGW64 ~/git-exercise (ft/contact-page)
$ git cherry-pick 17e82682f64c51bffe86aa1c3a88110581460d881
fatal: bad revision '17e82682f64c51bffe86aa1c3a88110581460d881'

DOLPHIX ELECTRONICS@DESKTOP-TJ49EDU MINGW64 ~/git-exercise (ft/contact-page)
$ git cherry pick 17e82682f64c51bffe86aa1c3a88110581460d881
fatal: unknown commit 17e82682f64c51bffe86aa1c3a88110581460d881

DOLPHIX ELECTRONICS@DESKTOP-TJ49EDU MINGW64 ~/git-exercise (ft/contact-page)
$ git cherry pick 17e82682f64c51bffe86aa1c3a88110581460d881
fatal: unknown commit 17e82682f64c51bffe86aa1c3a88110581460d881

DOLPHIX ELECTRONICS@DESKTOP-TJ49EDU MINGW64 ~/git-exercise (ft/contact-page)
$ git cherry-pick 17e82682f64c51bffe86aa1c3a88110581460d881
fatal: bad revision '17e82682f64c51bffe86aa1c3a88110581460d881'

DOLPHIX ELECTRONICS@DESKTOP-TJ49EDU MINGW64 ~/git-exercise (ft/contact-page)
$ git checkout ft/team-page
Switched to branch 'ft/team-page'
Your branch is up to date with 'origin/ft/team-page'.

DOLPHIX ELECTRONICS@DESKTOP-TJ49EDU MINGW64 ~/git-exercise (ft/team-page)
$ git fetch remote
fatal: 'remote' does not appear to be a git repository
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.

DOLPHIX ELECTRONICS@DESKTOP-TJ49EDU MINGW64 ~/git-exercise (ft/team-page)
$ git fetch https://github.com/Algor-Fernand/git-exercise.git
remote: Enumerating objects: 1, done.
remote: Counting objects: 100% (1/1), done.
remote: Total 1 (delta 0), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (1/1), 648 bytes | 36.00 KiB/s, done.
From https://github.com/Algor-Fernand/git-exercise
 * branch            HEAD       -> FETCH_HEAD

DOLPHIX ELECTRONICS@DESKTOP-TJ49EDU MINGW64 ~/git-exercise (ft/team-page)
$ git log
commit 17e82682f64c51bffe86aa1c3a88110581460d88 (HEAD -> ft/team-page, origin/ft/team-page)
Author: Algor Fernand <algorfernand014@gmail.com>
Date:   Wed Jul 26 11:32:27 2023 +0200

    add team page

commit e13215b04d94ec36fbcf03bfc0ab2faaec7a5130 (origin/ft/bundle-2, ft/service-redesign, ft/bundle-2)
Author: Algor Fernand <algorfernand014@gmail.com>
Date:   Thu Jul 13 11:38:43 2023 +0200

    Terminal logs added in the readme

commit 5ee393858e4f849d98c63f924a0c42eeac53c00c
Author: Algor Fernand <algorfernand014@gmail.com>

DOLPHIX ELECTRONICS@DESKTOP-TJ49EDU MINGW64 ~/git-exercise (ft/team-page)
$ git checkout ft/contact-page
Switched to branch 'ft/contact-page'

DOLPHIX ELECTRONICS@DESKTOP-TJ49EDU MINGW64 ~/git-exercise (ft/contact-page)
$ git cherry-pick 17e82682f64c51bffe86aa1c3a88110581460d881
fatal: bad revision '17e82682f64c51bffe86aa1c3a88110581460d881'

DOLPHIX ELECTRONICS@DESKTOP-TJ49EDU MINGW64 ~/git-exercise (ft/contact-page)
$ git cherry-pick 17e82682f64c51bffe86aa1c3a88110581460d88
[ft/contact-page 341f8ea] add team page
 Date: Wed Jul 26 11:32:27 2023 +0200
 2 files changed, 12 insertions(+)
 delete mode 100644 index.html
 create mode 100644 team.html

DOLPHIX ELECTRONICS@DESKTOP-TJ49EDU MINGW64 ~/git-exercise (ft/contact-page)
$ git status
On branch ft/contact-page
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        contact.html

nothing added to commit but untracked files present (use "git add" to track)

DOLPHIX ELECTRONICS@DESKTOP-TJ49EDU MINGW64 ~/git-exercise (ft/contact-page)
$ git add .

DOLPHIX ELECTRONICS@DESKTOP-TJ49EDU MINGW64 ~/git-exercise (ft/contact-page)
$ git log
commit 341f8ea6971c23940fd899cacb24226db07a3a7a (HEAD -> ft/contact-page)
Author: Algor Fernand <algorfernand014@gmail.com>
Date:   Wed Jul 26 11:32:27 2023 +0200

    add team page

commit b409ad97579cbfeaaa7d5dd9d64e4f5ab01a4169 (origin/main, main)
Author: Algor Fernand <algorfernand014@gmail.com>
Date:   Tue Jul 11 11:12:09 2023 +0200

    initial commit

DOLPHIX ELECTRONICS@DESKTOP-TJ49EDU MINGW64 ~/git-exercise (ft/contact-page)
$ git commit -m "add contact page"
[ft/contact-page 32ab455] add contact page
 1 file changed, 11 insertions(+)
 create mode 100644 contact.html

DOLPHIX ELECTRONICS@DESKTOP-TJ49EDU MINGW64 ~/git-exercise (ft/contact-page)
$ git push
fatal: The current branch ft/contact-page has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin ft/contact-page

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.


DOLPHIX ELECTRONICS@DESKTOP-TJ49EDU MINGW64 ~/git-exercise (ft/contact-page)
$     git push --set-upstream origin ft/contact-page
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 4 threads
Compressing objects: 100% (6/6), done.
Writing objects: 100% (6/6), 774 bytes | 258.00 KiB/s, done.
Total 6 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), done.
remote:
remote: Create a pull request for 'ft/contact-page' on GitHub by visiting:
remote:      https://github.com/Algor-Fernand/git-exercise/pull/new/ft/contact-page
remote:
To https://github.com/Algor-Fernand/git-exercise.git
 * [new branch]      ft/contact-page -> ft/contact-page
branch 'ft/contact-page' set up to track 'origin/ft/contact-page'.

DOLPHIX ELECTRONICS@DESKTOP-TJ49EDU MINGW64 ~/git-exercise (ft/contact-page)
$ git checkout -b ft/faq-page
Switched to a new branch 'ft/faq-page'

DOLPHIX ELECTRONICS@DESKTOP-TJ49EDU MINGW64 ~/git-exercise (ft/faq-page)
$ git status
On branch ft/faq-page
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        faq.html

nothing added to commit but untracked files present (use "git add" to track)

DOLPHIX ELECTRONICS@DESKTOP-TJ49EDU MINGW64 ~/git-exercise (ft/faq-page)
$ git add .

DOLPHIX ELECTRONICS@DESKTOP-TJ49EDU MINGW64 ~/git-exercise (ft/faq-page)
$ git commit -m "faq added"
[ft/faq-page 92bfdfa] faq added
 1 file changed, 12 insertions(+)
 create mode 100644 faq.html

DOLPHIX ELECTRONICS@DESKTOP-TJ49EDU MINGW64 ~/git-exercise (ft/faq-page)
$ git push 
fatal: The current branch ft/faq-page has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin ft/faq-page

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.


DOLPHIX ELECTRONICS@DESKTOP-TJ49EDU MINGW64 ~/git-exercise (ft/faq-page)
$     git push --set-upstream origin ft/faq-page
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 496 bytes | 248.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
remote: 
remote: Create a pull request for 'ft/faq-page' on GitHub by visiting:
remote:      https://github.com/Algor-Fernand/git-exercise/pull/new/ft/faq-page
remote:
To https://github.com/Algor-Fernand/git-exercise.git
 * [new branch]      ft/faq-page -> ft/faq-page
branch 'ft/faq-page' set up to track 'origin/ft/faq-page'.

DOLPHIX ELECTRONICS@DESKTOP-TJ49EDU MINGW64 ~/git-exercise (ft/faq-page)
$ git log
commit 92bfdfaf5c7ca6452f4300c78baba50ec92c7376 (HEAD -> ft/faq-page, origin/ft/faq-page)
Author: Algor Fernand <algorfernand014@gmail.com>
Date:   Wed Jul 26 12:35:20 2023 +0200
#       new file:   index.html

    faq added

commit 32ab4555fd1a87664049e7bbccee3ce94f529414 (origin/ft/contact-page, ft/contact-page)
Author: Algor Fernand <algorfernand014@gmail.com>
Date:   Wed Jul 26 12:30:05 2023 +0200

    add contact page

commit 341f8ea6971c23940fd899cacb24226db07a3a7a
Author: Algor Fernand <algorfernand014@gmail.com>

DOLPHIX ELECTRONICS@DESKTOP-TJ49EDU MINGW64 ~/git-exercise (ft/faq-page)
$ git revert 17e82682f64c51bffe86aa1c3a88110581460d88
[ft/faq-page 4a61ca8] Revert "add team page"
 2 files changed, 12 deletions(-)
 create mode 100644 index.html
 delete mode 100644 team.html

DOLPHIX ELECTRONICS@DESKTOP-TJ49EDU MINGW64 ~/git-exercise (ft/faq-page)
$ git status
On branch ft/faq-page
Your branch is ahead of 'origin/ft/faq-page' by 1 commit.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean

DOLPHIX ELECTRONICS@DESKTOP-TJ49EDU MINGW64 ~/git-exercise (ft/faq-page)
$ git add .

DOLPHIX ELECTRONICS@DESKTOP-TJ49EDU MINGW64 ~/git-exercise (ft/faq-page)
$ git status
On branch ft/faq-page
Your branch is ahead of 'origin/ft/faq-page' by 1 commit.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean

DOLPHIX ELECTRONICS@DESKTOP-TJ49EDU MINGW64 ~/git-exercise (ft/faq-page)
$ git commit -m "reverted teampage"
On branch ft/faq-page
Your branch is ahead of 'origin/ft/faq-page' by 1 commit.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean

DOLPHIX ELECTRONICS@DESKTOP-TJ49EDU MINGW64 ~/git-exercise (ft/faq-page)
$ git push 
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 392 bytes | 196.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/Algor-Fernand/git-exercise.git
   92bfdfa..4a61ca8  ft/faq-page -> ft/faq-page

DOLPHIX ELECTRONICS@DESKTOP-TJ49EDU MINGW64 ~/git-exercise (ft/faq-page)
$
´´´
