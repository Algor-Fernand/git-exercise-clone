#Git Exercise

This project will be used for Git exercise & practice.

#TerminalLogs BUNDLE2 Exercise 1

´´´´bash
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
´´´´