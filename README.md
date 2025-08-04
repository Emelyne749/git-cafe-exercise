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

### Excercise 2
... bash
C:\Users\user\Desktop\git-cafe-exercise [main ≡]> git checkout -b ft/bug-fix
Switched to a new branch 'ft/bug-fix'
C:\Users\user\Desktop\git-cafe-exercise [ft/bug-fix]> git status
On branch ft/bug-fix
Changes not staged for commit:
  (use "git add/rm <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        deleted:    index-4.html

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        contact.html

no changes added to commit (use "git add" and/or "git commit -a")
C:\Users\user\Desktop\git-cafe-exercise [ft/bug-fix +1 ~0 -1 !]> git add .
C:\Users\user\Desktop\git-cafe-exercise [ft/bug-fix +0 ~1 -0 ~]> git commit -m "Renamed index-4.html to contact.html"
[ft/bug-fix eeec1c1] Renamed index-4.html to contact.html
 1 file changed, 203 insertions(+), 203 deletions(-)
 rename index-4.html => contact.html (98%)
C:\Users\user\Desktop\git-cafe-exercise [ft/bug-fix]> git push
fatal: The current branch ft/bug-fix has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin ft/bug-fix

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.

C:\Users\user\Desktop\git-cafe-exercise [ft/bug-fix]> git push --set-upstream origin ft/bug-fix
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 16 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 2.51 KiB | 1.25 MiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote:
remote: Create a pull request for 'ft/bug-fix' on GitHub by visiting:
remote:      https://github.com/Emelyne749/git-cafe-exercise/pull/new/ft/bug-fix
remote:
To https://github.com/Emelyne749/git-cafe-exercise.git
 * [new branch]      ft/bug-fix -> ft/bug-fix
branch 'ft/bug-fix' set up to track 'origin/ft/bug-fix'.

...

### Exercise 3

...bash

C:\Users\user\Desktop\git-cafe-exercise [ft/bug-fix ≡]> git checkout -b ft/hot-fix
Switched to a new branch 'ft/hot-fix'
C:\Users\user\Desktop\git-cafe-exercise [ft/hot-fix]>







C:\Users\user\Desktop\git-cafe-exercise [ft/bug-fix ≡]> git checkout -b ft/hot-fix
Switched to a new branch 'ft/hot-fix'
C:\Users\user\Desktop\git-cafe-exercise [ft/hot-fix]>






C:\Users\user\Desktop\git-cafe-exercise [ft/bug-fix ≡]> git checkout -b ft/hot-fix
Switched to a new branch 'ft/hot-fix'
C:\Users\user\Desktop\git-cafe-exercise [ft/hot-fix]>




C:\Users\user\Desktop\git-cafe-exercise [ft/bug-fix ≡]> git checkout -b ft/hot-fix
Switched to a new branch 'ft/hot-fix'
C:\Users\user\Desktop\git-cafe-exercise [ft/hot-fix]>



C:\Users\user\Desktop\git-cafe-exercise [ft/bug-fix ≡]> git checkout -b ft/hot-fix
Switched to a new branch 'ft/hot-fix'
C:\Users\user\Desktop\git-cafe-exercise [ft/hot-fix]>

C:\Users\user\Desktop\git-cafe-exercise [ft/bug-fix ≡]> git checkout -b ft/hot-fix
Switched to a new branch 'ft/hot-fix'
C:\Users\user\Desktop\git-cafe-exercise [ft/hot-fix]>
C:\Users\user\Desktop\git-cafe-exercise [ft/bug-fix ≡]> git checkout -b ft/hot-fix
Switched to a new branch 'ft/hot-fix'
C:\Users\user\Desktop\git-cafe-exercise [ft/hot-fix]>
                                                      git add .
C:\Users\user\Desktop\git-cafe-exercise [ft/hot-fix +0 ~1 -0 ~]> git commit -m "Updated the contacts"
[ft/hot-fix add3fe5] Updated the contacts
 1 file changed, 1 insertion(+), 1 deletion(-)
C:\Users\user\Desktop\git-cafe-exercise [ft/hot-fix]> git push -u origin ft/hot-fix
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 16 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 306 bytes | 306.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
remote: 
remote: Create a pull request for 'ft/hot-fix' on GitHub by visiting:
remote:      https://github.com/Emelyne749/git-cafe-exercise/pull/new/ft/hot-fix
remote:
To https://github.com/Emelyne749/git-cafe-exercise.git
 * [new branch]      ft/hot-fix -> ft/hot-fix
branch 'ft/hot-fix' set up to track 'origin/ft/hot-fix'.
C:\Users\user\Desktop\git-cafe-exercise [ft/hot-fix ≡]> git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.
...