# git-cafe-exercise
## Exercise 1
```bash
MUGABE@DESKTOP-JNTT3PG MINGW64 ~/Desktop/git-cafe-exercise (main)
$ git checkout -b feature
Switched to a new branch 'feature'

MUGABE@DESKTOP-JNTT3PG MINGW64 ~/Desktop/git-cafe-exercise (feature)
$ touch Menu.html

MUGABE@DESKTOP-JNTT3PG MINGW64 ~/Desktop/git-cafe-exercise (feature)
$ git commit -am "added some text in menu"
On branch feature
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        Menu.html

nothing added to commit but untracked files present (use "git add" to track)

MUGABE@DESKTOP-JNTT3PG MINGW64 ~/Desktop/git-cafe-exercise (feature)
$ git add .

MUGABE@DESKTOP-JNTT3PG MINGW64 ~/Desktop/git-cafe-exercise (feature)
$ git commit -m "added some text in the menu"
[feature dca1eb1] added some text in the menu
 1 file changed, 16 insertions(+)
 create mode 100644 Menu.html

MUGABE@DESKTOP-JNTT3PG MINGW64 ~/Desktop/git-cafe-exercise (feature)
$ git push origin feature
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 470 bytes | 470.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote:
remote: Create a pull request for 'feature' on GitHub by visiting:
remote:      https://github.com/ben-toussaint/git-cafe-exercise/pull/new/featur
remote:
To https://github.com/ben-toussaint/git-cafe-exercise.git
 * [new branch]      feature -> feature

MUGABE@DESKTOP-JNTT3PG MINGW64 ~/Desktop/git-cafe-exercise (feature)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.
```
## exercise 2
```bash

MUGABE@DESKTOP-JNTT3PG MINGW64 ~/Desktop/git-cafe-exercise (feature)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

MUGABE@DESKTOP-JNTT3PG MINGW64 ~/Desktop/git-cafe-exercise (main)
$ git checkout -b bug-fix
Switched to a new branch 'bug-fix'

MUGABE@DESKTOP-JNTT3PG MINGW64 ~/Desktop/git-cafe-exercise (bug-fix)
$ ls
README.md  css/     index-1.html  index-3.html  index.html
bat/       images/  index-2.html  index-4.html  js/

MUGABE@DESKTOP-JNTT3PG MINGW64 ~/Desktop/git-cafe-exercise (bug-fix)
$ git status -s
 M index-4.html

MUGABE@DESKTOP-JNTT3PG MINGW64 ~/Desktop/git-cafe-exercise (bug-fix)
$ git commit -am "changed the title to Contact"
[bug-fix 0c66583] changed the title to Contact
 1 file changed, 1 insertion(+), 1 deletion(-)

MUGABE@DESKTOP-JNTT3PG MINGW64 ~/Desktop/git-cafe-exercise (bug-fix)
$ git push origin bug-fix
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 315 bytes | 315.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
remote:
remote: Create a pull request for 'bug-fix' on GitHub by visiting:
remote:      https://github.com/ben-toussaint/git-cafe-exercise/pull/new/bug-fi
remote:
To https://github.com/ben-toussaint/git-cafe-exercise.git
 * [new branch]      bug-fix -> bug-fix
```