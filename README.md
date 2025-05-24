# git-cafe-exercise
## Bundle 6
### Exercise 1
```
brian@AlianeI23 MINGW64 ~/git-cafe-exercise (main)
$ git checkout -b ft/menu
Switched to a new branch 'ft/menu'
brian@AlianeI23 MINGW64 ~/git-cafe-exercise (ft/menu)
$ git add .

brian@AlianeI23 MINGW64 ~/git-cafe-exercise (ft/menu)
$ git commit -m "Added the menu page"
[ft/menu 7f7bc4e] Added the menu page
 2 files changed, 24 insertions(+)
 create mode 100644 menu.html

brian@AlianeI23 MINGW64 ~/git-cafe-exercise (ft/menu)
$ git push
fatal: The current branch ft/menu has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin ft/menu

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.


brian@AlianeI23 MINGW64 ~/git-cafe-exercise (ft/menu)
$ git push --set-upstream origin ft/menu
Enumerating objects: 6, done.
Counting objects: 100% (6/6), done.
Delta compression using up to 12 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (4/4), 650 bytes | 130.00 KiB/s, done.
Total 4 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote:
remote: Create a pull request for 'ft/menu' on GitHub by visiting:
remote:      https://github.com/AlianeIsimbi/git-cafe-exercise/pull/new/ft/menu
remote:
To https://github.com/AlianeIsimbi/git-cafe-exercise.git
 * [new branch]      ft/menu -> ft/menu
branch 'ft/menu' set up to track 'origin/ft/menu'.

```