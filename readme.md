Sprint 3
The project is created on an iterative basis - adding functionality little by little, creating a commit - used GitBash.
The project goal is to create a web application frond end using css framework.

Author:
Project made by Valdemaras Macevičius


https://github.com/Vizijant/Sprint3


User@User-PC MINGW64 ~/Desktop/sprint 3 (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   css/grid.css
        modified:   css/stayle.css
        modified:   house.html
        modified:   index.html

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        .gitignore
        apartment.html
        img/3butas.jpg
        img/butas.jpg
        readme.md

no changes added to commit (use "git add" and/or "git commit -a")

User@User-PC MINGW64 ~/Desktop/sprint 3 (main)
$ git add .

User@User-PC MINGW64 ~/Desktop/sprint 3 (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   .gitignore
        new file:   apartment.html
        modified:   css/grid.css
        modified:   css/stayle.css
        modified:   house.html
        new file:   img/3butas.jpg
        new file:   img/butas.jpg
        modified:   index.html
        new file:   readme.md


User@User-PC MINGW64 ~/Desktop/sprint 3 (main)
$ git commit -m "Corrections. And gitignore, and readme files are attached"
[main ef95380] Corrections. And gitignore, and readme files are attached
 9 files changed, 344 insertions(+), 70 deletions(-)
 create mode 100644 .gitignore
 create mode 100644 apartment.html
 create mode 100644 img/3butas.jpg
 create mode 100644 img/butas.jpg
 create mode 100644 readme.md

User@User-PC MINGW64 ~/Desktop/sprint 3 (main)
$ git push -u origin main
