# git-cafe-exercise
## Bundle 6
### Exercise 1

...bash

C:\Users\user\Desktop\git-cafe-exercise [main ≡]> git checkout -b ft/menu
Switched to a new branch 'ft/menu'
C:\Users\user\Desktop\git-cafe-exercise [ft/menu]>git status
On branch ft/menu
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        menu.html

nothing added to commit but untracked files present (use "git add" to track)
C:\Users\user\Desktop\git-cafe-exercise [ft/menu +1 ~0 -0 !]>git add .
C:\Users\user\Desktop\git-cafe-exercise [ft/menu +1 ~0 -0 ~]>git commit -m "Added a new file called menu.html"
[ft/menu 11f491d] Added a new file called menu.html
 1 file changed, 11 insertions(+)
 create mode 100644 menu.html
C:\Users\user\Desktop\git-cafe-exercise [ft/menu]> git push -u origin ft/menu                
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 16 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 455 bytes | 227.00 KiB/Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote:
remote: Create a pull request for 'ft/menu' on GitHub by visiting:
remote:      https://github.com/Emelyne749/git-cafe-exercise/pull/new/ft/menu
remote:
To https://github.com/Emelyne749/git-cafe-exercise.git
 * [new branch]      ft/menu -> ft/menu
branch 'ft/menu' set up to track 'origin/ft/menu'.
... 