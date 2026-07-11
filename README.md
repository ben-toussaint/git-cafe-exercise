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